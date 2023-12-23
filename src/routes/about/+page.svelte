<script>
  import NavBar from "../../lib/components/NavBar.svelte";
  import SocialBar from "../../lib/components/SocialBar.svelte";
</script>
<NavBar />
<h1 class="text-center text-5xl">-About-</h1>
<div class="sm:flex-row  flex flex-col justify-between items-center py-40 p-5 sm:px-40 lg:px-80">
  <div>
    IMG
  </div>
  <div id="card" class="w-40">
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

<div>
  <div>
    <span>Music I Love</span>
  </div>
<div>
  <iframe title="spotify" style="border-radius:12px" src="https://open.spotify.com/embed/playlist/5GSE3gz9ZGDesTJw8hMSUw?utm_source=generator&theme=0" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
</div>
</div>
<footer class="bg-black p-5 flex content-center items-center">
  <SocialBar />
</footer>
<style>
  h1, h2 {
    font-family: 'Fugaz One', sans-serif;
  }
</style>