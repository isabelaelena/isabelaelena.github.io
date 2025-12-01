<script lang="ts">
  import Banner from "$lib/elena.svelte";
</script>

<!-- HERO -->
<section id="home" class="flex items-center justify-center">
  <div class="padding grid items-center md:grid-cols-2">
    <div>
      <div>
        <span>📍</span>
        <span class="text-gray-500">Toronto, Canada</span>
      </div>
      <h1 class="pt-6">
        Advocating progress through technology and innovation
      </h1>
      <body>
        <p>
          Hi, I'm Elena. Currently working as a Product Manager in the public
          sector across North America.
        </p>
      </body>
      <div class="mt-6 flex items-center">
        <a href="https://docs.google.com/document/d/1_D_RsFurP79CagVsEI5k12oEKSLORnerFzmg0Kvbyfg/edit?usp=sharing" class="hover:italic">Download my resume 〉</a>
      </div>
      <!-- <div class="mt-4 flex items-center">
        <a href="/resume.pdf" class="hover:italic">Get to know me 〉</a>
      </div> -->
    </div>
    <div class="flex justify-center pt-6 px-14">
      <Banner />
    </div>
  </div>
</section>

<!-- WORKS / PROJECTS -->
<section id="works" class="padding">
  <div class="pt-12">
    <h2>Works & Projects</h2>
      <div class="grid grid-cols-3 gap-4 pt-2 pb-12">
        <a href="/works/duanyam" class="card">Du'Anyam: Design Showcase</a>
        <a href="/works/siklus" class="card">Siklus Refill: Showcase</a>
        <a href="/works/canadagoose">Canada Goose: Case Study</a>
        <!-- <a class="card">Spotify Case: Study</a> -->
      </div>
  </div>
</section>
