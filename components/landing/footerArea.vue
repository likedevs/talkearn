<template>
  <footer class="Footer">
    <div class="Nav Footer-links">
      <a href="#">Top</a>
      <a target="_blank" href="https://docs.talkearn.crypto">Docs</a>
      <policies></policies>
      <terms></terms>
    </div>
    <div class="Footer-icons">
      <a class="Pollen-twitter" target="_blank" href="#">
        <img src="https://pollen.id/static/media/twitter.a6815caa.svg" alt="twitter">
      </a>
      <a class="Pollen-telegram" target="_blank" href="#">
        <img src="https://pollen.id/static/media/telegram.451c86f3.svg" alt="telegram">
      </a>
      <a class="Pollen-discord medium-icon" target="_blank" href="#">
        <img src="/Medium-Logo.svg" alt="medium" style="height: 15px;">
      </a>
    </div>
    <div class="Footer-copyright mobile">© Copyright 2021 — TalkEarn</div>
  </footer>
</template>


<script>

import policies from "~/components/landing/policies";
import terms from "~/components/landing/terms";

export default {
  name: "footer-area",
  components: {policies, terms}
}
</script>