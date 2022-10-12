<template>
  <div>
    <div class="Pollen-nav-container">
      <header class="Pollen-nav-desktop">

        <a aria-current="page" class="Pollen-logo active" href="/">
          <img src="/landing/logo.svg" class="is-static" alt="logo" width="100%">
        </a>

        <div class="Pollen-desktop-links">
          <a href="#features" class="Nav-link first">Features</a>
          <a href="#use-case" class="Nav-link second">Use case</a>
          <a href="#team" class="Nav-link third">Team</a>
          <a href="#roadmap" class="Nav-link fourth">Roadmap</a>
        </div>

        <div class="Pollen-desktop-buttons">
          <a rel="noopener noreferrer" target="_blank" class="button-gradient"
             href="https://docs.talkearn.app">
            Whitepaper
          </a>
          <a rel="noopener noreferrer" target="_blank" class="button-gradient"
             href="https://www.canva.com/design/DAFOLYUq46I/FqFG1nIf4TLoc0NCFoANqw/view?utm_content=DAFOLYUq46I&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink">
            <div class="Button-caption">Pitch Deck</div>
          </a>
        </div>
      </header>

      <header :class="['Pollen-nav-mobile', drawer, 'false', 'is-scrolled']">
        <div class="Pollen-nav-mobile-header">
          <div class="Pollen-logo">
            <img src="/landing/logo.svg" class="is-static" alt="logo" width="100%">
          </div>
          <div class="mx-4 hidden-sm-and-down"></div>
          <div :class="['App-hamburger', hamburger]"><span class="App-hamburger-inner" @click="showMenu()"></span></div>
        </div>

        <div class="Nav">
          <a href="#features" class="Nav-link" @click="showMenu()">Features</a>
          <a href="#use-case" class="Nav-link" @click="showMenu()">Use case</a>
          <a href="#team" class="Nav-link" @click="showMenu()">Team</a>
          <a href="#roadmap" class="Nav-link" @click="showMenu()">Roadmap</a>

          <div class="Nav-link button" @click="showMenu()">
            <div class="Pollen-desktop-buttons">
              <a rel="noopener noreferrer" target="_blank" class="button-gradient"
                 href="https://docs.talkearn.app">
                Whitepaper
              </a>
              <a rel="noopener noreferrer" target="_blank" class="button-gradient"
                 href="https://www.canva.com/design/DAE6CHg3TtM/wYqkGERgcbn6umLn0fkepQ/view?utm_content=DAE6CHg3TtM&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton">
                <div class="Button-caption">Pitch Deck</div>
              </a>
            </div>
          </div>
        </div>
        <div :class="['Nav-icons', hidden]"></div>
      </header>
    </div>
  </div>
</template>

<script>

import formArea from '~/components/landing/form'

export default {
  data: () => ({
    drawer: false,
    hamburger: false,
    hidden: 'is-hidden',
  }),
  name: "header-area",
  components: {formArea},
  methods: {
    showMenu() {
      if (this.drawer === false) {
        this.drawer = 'is-expanded'
        this.hamburger = 'is-active'
        this.hidden = false
      } else {
        this.drawer = false
        this.hamburger = false
        this.hidden = 'is-hidden'
      }
    }
  }
}
</script>
