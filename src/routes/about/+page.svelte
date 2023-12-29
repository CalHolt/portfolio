<script>
  import NavBar from "../../lib/components/NavBar.svelte";
  import SocialBar from "../../lib/components/SocialBar.svelte";
  import DownloadButton from "../../lib/components/DownloadButton.svelte";
  import Card from "../../lib/components/Card.svelte";
  let myInfo = [
    {cardTitle: "Games I'm Playing",
    item1: "Rainbow Six Siege",
    item2: "Mortal Kombat 1",
    item3: "Chess"},
    {cardTitle: "Languages I'm Learning",
    item1: "React",
    item2: "NextJS",
    item3: "Angular"},
    {cardTitle: "Songs On Repeat",
    item1: "- Im Home by Peter Cat Recording Co.",
    item2: "- Shiela by Jamie T",
    item3: "- Dunno by Mac Miller"}]
</script>
<NavBar />
<h1 class="text-center text-5xl">-About-</h1>
<div class=" flex p-5 justify-center">
  <DownloadButton />
</div>
<div class="sm:flex-row bg-black text-white m-3 flex flex-col justify-between items-center p-5 gap-10 py-10 sm:py-20 sm:px-40 lg:px-80">
  <div>
    <img class="hero" src="../images/myimage.jpeg" alt="me">
  </div>
  <div id="card" class="w-40 lg:w-60">
    <p>Hi I am Cal, a newly graduated web developer from SAIT with a passion for front end development. On this page you can see my resume, languages / tools I know and a bit about me personally.</p>
  </div>
</div>

<div class="sm:flex-row gap-5 flex flex-col justify-between items-center p-5 sm:px-40 lg:px-80 shadow shadow-2xl">
 <div class="align-center ">
    <h2 class="text-3xl">Languages and Tools</h2>
 </div>
 <div class="flex  gap-10 text-center">
  <div>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Tailwind CSS</li>
      <li>SvelteKit</li>
      <li>SkeletonUI</li>
    </ul>
  </div>
 <div>
  <ul>  
    <li>Directus</li>
    <li>Supabase</li>
    <li>Netlify / Vercel</li>
    <li>Figma / Figjam</li>
    <li>Git</li>
    <li>NPM</li>
  </ul>
 </div>
 </div> 
</div>
<h2 class="text-3xl text-center py-5">About Me</h2>
<div class="sm:flex-row gap-5 flex flex-col justify-center items-center p-5">
  {#each myInfo as info}
  <Card {...info}/> 
 {/each}
</div>

<footer class="bg-black p-5 flex content-center items-center">
  <SocialBar />
</footer>
<style>
  h1, h2 {
    font-family: 'Fugaz One', sans-serif;
  }
  .hero {
    height: 435px;
    width: 245px;
  }
</style>