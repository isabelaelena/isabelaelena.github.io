<script>
  import "../app.css";
</script>

<nav
class="sticky top-0 z-20 w-full border-b bg-white/70 backdrop-blur supports-[backdrop-filter]:bg-white/60">
  <div class="padding">
    <ul class="w-full justify-end space-x-8 md:flex">
      <li class="mr-auto"><a href="/"><strong>Elena</strong></a></li>
      <li><a href="/#works">Work</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </div>
</nav>


<div class="text-base/7 pt-10 md:pt-0">
  <slot />

  <div id="contact">
    <footer class="footer">
      <div class="padding footer-inner">
        <ul class="footer-list">
          <li class="footer-coffee">
            <h3>Let's grab coffee!<span class="coffee">☕️</span></h3>
          </li>

          <li>
            <a href="mailto:isabelaelenang@gmail.com" class="footer-link">Email</a>
          </li>

          <li>
            <a
              href="https://www.linkedin.com/in/isabelaelena/"
              class="footer-link">
              LinkedIn
            </a>
          </li>
        </ul>
      </div>
    </footer>
  </div>

</div>
