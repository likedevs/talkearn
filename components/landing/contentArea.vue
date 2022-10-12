<template>
  <div id="root">
    <div class="AppRoot">
      <div class="Home">
        <div class="space-hr"></div>

        <section class="Section-2">
          <img src="/landing/main-banner.png" class="Hero-1 image-metaverse"/>
          <div class="Section-1-main">
            <div class="logo-content">

            </div>
            <div class="Heading has-text is-white is-heading is-large">
              Monetize Your time through Video Calls and Crypto
            </div>
            <div class="Heading has-text is-white is-medium sub-heading">
              Get Paid Per Minute Or Per Session
            </div>
            <div class="Paragraph-1 has-text is-white is-paragraph-main">
              For teams and individuals: therapists, coaches, models, entertainers, psychics, astrologysts, doctors,
              after sales consultants, technical support specialists or any kind of online consultants.
            </div>
            <div class="buttons-wrapper">
              <form-area :title="'Join Us'"></form-area>

              <explainer-video></explainer-video>

            </div>
          </div>
        </section>

        <div class="space-hr" id="features"></div>
        <section class="Section-3">
          <div class="Section-3-main has-text is-centered">
            <div class="Heading-3 has-text is-white is-heading is-large" style="margin-top: 50px">
              Introducing TalkEarn App
            </div>
            <div class="Paragraph-3 has-text is-paragraph-large is-white"
                 style="padding: 0 20%; margin-bottom: 40px">
              TalkEarn enabling anyone to add a crypto paywall layer to their video calls, creating faster and easier
              continuity and scalability when providing live video services online.
            </div>
            <div class="">

              <div class="introducing-wrapp">
                <div class="introducing-item">
                  <img src="/landing/int-1.png" alt="">
                  <div class="item-inside">
                    <h5>No code require</h5>
                    <p>
                      Install our dapp on Your website/app. No plugins or downloads required
                    </p>
                  </div>
                </div>

                <div class="introducing-item">
                  <img src="/landing/int-2.png" alt="">
                  <div class="item-inside">
                    <h5>Easy setup</h5>
                    <p>
                      Easily setup the services You provide and Your price per minute/session
                    </p>
                  </div>
                </div>

                <div class="introducing-item">
                  <img src="/landing/int-3.png" alt="">
                  <div class="item-inside">
                    <h5>Instant Video Calls</h5>
                    <p>
                      Your clients can call you any time You set yourself online for calls
                    </p>
                  </div>
                </div>
              </div>

              <div class="introducing-wrapp">
                <div class="introducing-item">
                  <img src="/landing/int-4.png" alt="">
                  <div class="item-inside">
                    <h5>Instant payment</h5>
                    <p>
                      You're paid per minutes/session immediately after the call is over. To Your Crypto wallet
                    </p>
                  </div>
                </div>

                <div class="introducing-item">
                  <img src="/landing/int-5.png" alt="">
                  <div class="item-inside">
                    <h5>No registration, No bank</h5>
                    <p>
                      You don't need to register, have a bank account. All You need to make money - a Crypto wallet made
                      in seconds
                    </p>
                  </div>
                </div>

                <div class="introducing-item">
                  <img src="/landing/int-6.png" alt="">
                  <div class="item-inside">
                    <h5>Web conference</h5>
                    <p>
                      Make a conference, send the link to Your Clients. Each of them will pay You for the time spent in
                      conference
                    </p>
                  </div>
                </div>
              </div>


            </div>
          </div>
        </section>


        <!--        <div class="space-hr"></div>-->
        <!--        <section class="Section-7" style="padding-bottom: 0;">-->
        <!--          <div class="Section-7-main">-->
        <!--            <div class="Section-7-hero" v-if="!$mobileDetect.mobile()" style="text-align: center">-->
        <!--              <img :src="section2SVG" alt="">-->
        <!--            </div>-->
        <!--            <div class="Heading has-text is-white is-heading is-large">-->
        <!--              TalkEarn Platform Monetisation System-->
        <!--            </div>-->
        <!--            <div class="Section-7-hero" v-if="$mobileDetect.mobile()" style="text-align: center">-->
        <!--              <img :src="section2SVG" alt="">-->
        <!--            </div>-->
        <!--            <div class="Paragraph has-text is-white is-paragraph-main">-->
        <!--              We’re building the DAO of the future through collective intelligence,-->
        <!--              collective exchange of knowledge and experience,-->
        <!--              and meritocratic-based ecosystems that reward users based on the benefit-->
        <!--              they bring the community.-->
        <!--            </div>-->
        <!--            <div class="Section-7-accordion">-->
        <!--              <div class="Accordion">-->
        <!--                <v-expansion-panels multiple>-->
        <!--                  <v-expansion-panel>-->
        <!--                    <v-expansion-panel-header>Pay-per-minute functionality</v-expansion-panel-header>-->
        <!--                    <v-expansion-panel-content>-->
        <!--                      So many smart people spend hours each day crawling through treasure troves of information, on-->
        <!--                      Telegram,-->
        <!--                      private WhatsApp and Discord groups, subreddits, newsletters, YouTube, and more, sourcing-->
        <!--                      knowledge, tips, and trading insights.-->
        <!--                      What if there was a way to harness all this information and pay for it just as much as the number-->
        <!--                      of minutes used to get it from professional experts? Now there is.-->
        <!--                    </v-expansion-panel-content>-->
        <!--                  </v-expansion-panel>-->
        <!--                  <v-expansion-panel>-->
        <!--                    <v-expansion-panel-header>Real Estate NFT sale/rent</v-expansion-panel-header>-->
        <!--                    <v-expansion-panel-content>-->
        <!--                      Platform’s Partners, i.e. Exchanges, Crypto Projects, Blockchains, Crypto Schools and other-->
        <!--                      partners eager to grab the-->
        <!--                      attention of our impressive community will have the opportunity to rent/buy real estate in our-->
        <!--                      metaverse.-->
        <!--                      There they will be able to place the content about their ecosystem and their experts.-->
        <!--                      It is similar to their discord ecosystems but augmented with virtual reality and #talk2earn-->
        <!--                      technology.-->
        <!--                    </v-expansion-panel-content>-->
        <!--                  </v-expansion-panel>-->
        <!--                  <v-expansion-panel>-->
        <!--                    <v-expansion-panel-header>Boosted articles and Ads</v-expansion-panel-header>-->
        <!--                    <v-expansion-panel-content>-->
        <!--                      Professional experts will have the opportunity to boost their articles and profiles, to-->
        <!--                      get higher visibility in the Metaverse.-->
        <!--                      Partners (i.e. Exchanges, Crypto Projects, Blockchains, and others) will have the opportunity to-->
        <!--                      launch-->
        <!--                      promotions and display Ads in the Metaverse,-->
        <!--                      to grab the attention of our impressive community.-->
        <!--                    </v-expansion-panel-content>-->
        <!--                  </v-expansion-panel>-->
        <!--                </v-expansion-panels>-->
        <!--              </div>-->
        <!--            </div>-->
        <!--            <form-area :title="'Learn More'"></form-area>-->
        <!--          </div>-->
        <!--        </section>-->
        <!--        <div class="space-hr" id="ecosystem"></div>-->
        <!--        <section class="Section-3" style="padding-top: 20px">-->
        <!--          <div class="Section-3-main has-text is-centered">-->
        <!--            <div class="Heading-3 has-text is-white is-heading is-large" style="margin: 50px 0">-->
        <!--              The TalkEarn Ecosystem-->
        <!--            </div>-->
        <!--            <div class="introducing-wrapp">-->
        <!--              <div class="introducing-item">-->
        <!--                <img :src="eco1SVG" alt="">-->
        <!--                <div class="item-inside-view-2">-->
        <!--                  <h5>Professional Experts</h5>-->
        <!--                  <p>-->
        <!--                    Core users, who are well-versed in Crypto, and are willing to earn money for their-->
        <!--                    knowledge and experience-->
        <!--                  </p>-->
        <!--                </div>-->
        <!--              </div>-->
        <!--              <div class="introducing-item mid-item">-->
        <!--                <img :src="eco2SVG" alt="">-->
        <!--                <div class="item-inside-view-2">-->
        <!--                  <h5>Crypto Learners</h5>-->
        <!--                  <p>-->
        <!--                    Crypto Learners are users who are looking for opportunities to learn and professional-->
        <!--                    mentorship.-->
        <!--                  </p>-->
        <!--                </div>-->
        <!--              </div>-->
        <!--              <div class="introducing-item">-->
        <!--                <img :src="eco3SVG" alt="">-->
        <!--                <div class="item-inside-view-2">-->
        <!--                  <h5>Partners & Community</h5>-->
        <!--                  <p>-->
        <!--                    Platform's Partners - Exchanges, Crypto Projects, Blockchains, etc. eager to grab the-->
        <!--                    attention of our impressive community by metaverse experience.-->
        <!--                  </p>-->
        <!--                </div>-->
        <!--              </div>-->

        <!--            </div>-->
        <!--          </div>-->
        <!--        </section>-->

        <div class="space-hr" id="tokens"></div>
        <section class="Section-6">
          <div class="Section-6-hero has-text is-paragraph-main is-white">
            <div class="Heading has-text is-white is-heading is-large">
              Meet TET Tokens, <br> <p>a token for video consulting online</p>
            </div>
            <p style="margin-top: 30px; margin-right: 20%">The TET token is used as a reward for platform users, as well as payment for
              live consultancy and services and provided within the TalkEarn Platform.
            </p>
          </div>
          <div class="Section-6-main" style="text-align: right">
            <img src="/landing/tet.png" alt="">
          </div>
        </section>

        <div class="space-hr" id="use-case"></div>
        <section class="Section-3" style="padding-top: 10px !important;">
          <div class="Section-3-main has-text is-centered">
            <div class="Heading-3 has-text is-white is-heading is-large" style="margin-top: 50px">
              TalkEarn App Use Cases
            </div>

            <div class="introducing-wrapp">
              <div class="introducing-item">
                <img src="/landing/Group 100.png" style="height: 200px">
                <div class="item-inside">
                  <h4>Therapists & Psychics</h4>
                  <p>
                    Group or 1x1 sessions with the clients. Schedule individual calls or send the link to Conference
                    Call
                  </p>
                </div>
              </div>

              <div class="introducing-item">
                <img src="/landing/gr-102.png" style="height: 200px">
                <div class="item-inside">
                  <h4>Entertainers & Models</h4>
                  <p>
                    No requirement to reveal the identity. All participants in group or 1x1 call just login into App
                    with their wallets
                  </p>
                </div>
              </div>

              <div class="introducing-item">
                <img src="/landing/gr-103.png" style="height: 200px">
                <div class="item-inside">
                  <h4>Trainers & Coaches</h4>
                  <p>
                    Live demonstration of workout/exercise plans. Share screen, chat & co-browse features for additional
                    information
                  </p>
                </div>
              </div>
            </div>
          </div>
        </section>


        <div class="business-model">
          <h4>TalkEarn App Business Model</h4>

          <div class="business-model-list only-desktop">

            <div class="business-model-item">
              <p>Service provider installs TalkEarn App via copy/paste code or Google Tag Manager</p>
              <img src="/landing/bus-1.png" alt="">
              <span><img src="/landing/nr-1.png" alt=""></span>
            </div>

            <div class="business-model-item">
              <span><img src="/landing/nr-2.png" alt=""></span>
              <img src="/landing/bus-2.png" alt="">
              <p>He/she provides services to his/her clients via 1x1 or conference call</p>
            </div>

            <div class="business-model-item">
              <p>The client(s) wallet(s) are charged instantly for minutes spent in call after the call is over</p>
              <img src="/landing/bus-3.png" alt="">
              <span><img src="/landing/nr-3.png" alt=""></span>
            </div>

            <div class="business-model-item">
              <span><img src="/landing/nr-4.png" alt=""></span>
              <img src="/landing/bus-4.png" alt="">
              <p>The service provider(s) wallet receives instantly the money, except for the 5% TalkEarn App's fee</p>
            </div>

          </div>

          <div class="business-model-list only-mobile">

            <div class="business-model-item">
              <span><img src="/landing/nr-1.png" alt=""></span>
              <img src="/landing/bus-1.png" alt="">
              <p>Service provider installs TalkEarn App via copy/paste code or Google Tag Manager</p>
            </div>

            <div class="business-model-item">
              <span><img src="/landing/nr-2.png" alt=""></span>
              <img src="/landing/bus-2.png" alt="">
              <p>He/she provides services to his/her clients via 1x1 or conference call</p>
            </div>

            <div class="business-model-item">
              <span><img src="/landing/nr-3.png" alt=""></span>
              <img src="/landing/bus-3.png" alt="">
              <p>The client(s) wallet(s) are charged instantly for minutes spent in call after the call is over</p>
            </div>

            <div class="business-model-item">
              <span><img src="/landing/nr-4.png" alt=""></span>
              <img src="/landing/bus-4.png" alt="">
              <p>The service provider(s) wallet receives instantly the money, except for the 5% TalkEarn App's fee</p>
            </div>

          </div>
        </div>

        <div class="space-hr" id="team"></div>
        <section class="Section-11 Team-section">
          <div class="Header Heading has-text is-white is-centered is-heading is-large">
            Our Team
          </div>
          <div class="Section-11-main is-centered">
            <experts></experts>
          </div>
        </section>
        <div class="space-hr"></div>
        <section class="Section-4" style="overflow: hidden">
          <div class="Section-4-main">
            <div class="Heading has-text is-white is-heading is-large">Partners</div>

            <div class="partner-list">
              <div class="partner-item">
                <img :src="logo1" alt="">
              </div>

              <div class="partner-item">
                <img src="/landing/Zuckerberg.png" alt="">
              </div>

              <div class="partner-item">
                <img src="/landing/artcor.png" alt="">
              </div>

              <div class="partner-item">
                <img src="/landing/yep.png" alt="">
              </div>
            </div>

            <div class="partner-list">
              <div class="partner-item">
                <img src="/landing/mediacor.png" alt="">
              </div>

              <div class="partner-item">
                <img :src="logo2" alt="">
              </div>

              <div class="partner-item">
                <img src="/landing/hug.png" alt="">
              </div>

              <div class="partner-item">
                <img :src="logo3" alt="">
              </div>
            </div>
          </div>
        </section>


        <div class="space-hr"></div>
        <div>
          <h4 class="heading-customize">Awards</h4>

          <div class="awards-area">
            <div class="awards-area-item">
              Near Certified <br> Entrepreneur Program <br> Alumni
            </div>
            <div class="awards-area-item">
              Personal Mentorship <br> with <br>Randi Zuckerberg
            </div>
            <div class="awards-area-item">
              Web3 Hackathon <br> Moldova Winner
            </div>
            <div class="awards-area-item">
              Incubated <br> by the Hug Studio
            </div>
          </div>
        </div>

        <div class="space-hr" id="roadmap"></div>
        <section class="Section-4">
          <div class="Section-4-main">
            <div class="Heading has-text is-white is-heading is-large">Roadmap</div>

            <div class="roadmap">
              <div class="roadmap-item roadmap-item1"></div>
              <div class="roadmap-item roadmap-item2"></div>
              <div class="roadmap-item roadmap-item3"></div>
              <div class="roadmap-item roadmap-item4"></div>
            </div>
            <div class="roadmap-list">
              <div class="roadmap-list-item">
                <h5>2022 - Q4</h5>
                <ul>
                  <li>Platform launch</li>
                  <li>Smart Contract</li>
                  <li>Development (webRTC)</li>
                  <li>Develop content for the Romanian-speaking market</li>
                </ul>
              </div>
              <div class="roadmap-list-item">
                <h5>2023 - Q1</h5>
                <ul>
                  <li>Seed and Private Sale</li>
                  <li>IDO</li>
                  <li>TGE</li>
                  <li>Experts validation & integration</li>
                </ul>
              </div>
              <div class="roadmap-list-item">
                <h5>2023 - Q1</h5>
                <ul>
                  <li>Strategic Partnerships</li>
                  <li>Community Expansion</li>
                  <li>Hive mind education</li>
                  <li>Influencer Marketing</li>
                  <li>Partnerships</li>
                </ul>
              </div>
              <div class="roadmap-list-item">
                <h5>2023 - Q2</h5>
                <ul>
                  <li>Striking more partnerships with Web3 Projects</li>
                  <li>Staking program launch</li>
                  <li>Metaverse release</li>
                </ul>
              </div>
            </div>
          </div>
        </section>
      </div>

      <section class="Section-4" style="background-color: #1F2131 !important;">
        <div class="Section-4-main">
          <div class="footer-inside Home">
            <div class="footer-logo">
              <img src="/landing/logo-footer.png" alt="">
            </div>
            <div class="footer-socials">
              <p>Getting paid for Video Calls made easy</p>
              <div class="Footer-icons">

                <a class="Pollen-discord medium-icon" target="_blank" href="https://talkearn.medium.com">
                  <img src="/landing/Medium-Logo.png" alt="medium" style="height: 18px; width: auto">
                </a>

                <a class="Pollen-twitter" target="_blank" href="https://twitter.com/TalkEarn">
                  <img src="/landing/twitter.png" alt="twitter">
                </a>

                <a class="Pollen-telegram" target="_blank" href="https://t.me/talkearn_official">
                  <img src="/landing/telegram-icon-white-transparent.svg" alt="telegram">
                </a>

                <a class="Pollen-discord medium-icon" target="_blank" href="https://linkedin.com/company/talkearn">
                  <img src="/landing/linkedin.png" alt="medium" style="height: 15px; width: auto !important;">
                </a>

<!--                <a class="Pollen-discord medium-icon" target="_blank" href="https://github.com/talkearn/talkearn">-->
<!--                  <img src="/landing/youtube.png" alt="medium" style="height: 15px;">-->
<!--                </a>-->


<!--                <a class="Pollen-twitter" target="_blank" href="https://twitter.com/TalkEarn">-->
<!--                  <img src="/landing/twitter-icon-white-transparent-24.svg" alt="twitter">-->
<!--                </a>-->


<!--                <a class="Pollen-discord medium-icon" target="_blank" href="https://github.com/talkearn/talkearn">-->
<!--                  <img src="/landing/github-logo.svg" alt="medium" style="height: 15px;">-->
<!--                </a>-->
              </div>
            </div>
            <div class="footer-contacts">
              <a href="">
                <svg width="14" height="16" viewBox="0 0 14 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M1.8975 1.20594C2.70234 0.287947 4.03342 0.395844 4.71635 1.43444L5.84998 3.15843C6.40841 4.00775 6.33441 5.19622 5.67623 5.94692L4.84043 6.90021C4.92143 7.14071 5.18807 7.66836 6.00005 8.59451C6.81204 9.52066 7.27471 9.8248 7.48556 9.91718L8.32131 8.96393C8.97949 8.21321 10.0215 8.12873 10.7661 8.76574L12.2776 10.0588C13.1881 10.8377 13.2828 12.3559 12.4779 13.2739C12.2162 13.5724 12.172 13.6228 11.7353 14.1209C11.2903 14.6285 10.3454 15.103 9.3886 15.1504C7.89149 15.2246 5.85796 14.4664 3.35496 11.6115C0.851986 8.75664 0.187212 6.43717 0.252308 4.72956C0.288518 3.77965 0.553294 2.73636 1.15838 2.05692C1.59156 1.5549 1.64789 1.49064 1.8975 1.20594ZM1.49804 4.79134C1.45292 5.97501 1.89028 7.92962 4.23666 10.6059C6.58304 13.2822 8.29668 13.781 9.33449 13.7295C10.3032 13.6814 10.8229 13.1475 10.8536 13.1153L11.5962 12.2683C11.8645 11.9623 11.833 11.4562 11.5294 11.1965L10.0179 9.90352C9.76972 9.69118 9.42239 9.71934 9.203 9.96958C8.8725 10.3466 8.64681 10.6077 8.20515 11.1096C7.28768 12.1522 5.71713 10.2831 5.11836 9.60023C4.56811 8.97261 2.89123 7.12436 3.79408 6.08236C3.79587 6.08031 4.03905 5.80294 4.79452 4.94126C5.0139 4.69103 5.03859 4.29487 4.85243 4.01176L3.71882 2.28777C3.49117 1.94157 3.04748 1.9056 2.7792 2.2116C2.53228 2.49324 2.25283 2.81197 2.03735 3.05946C1.59384 3.56882 1.52178 4.16869 1.49804 4.79134Z"
                        fill="white"/>
                </svg>
                +373 79666626</a><br>
              <a href="">
                <svg width="15" height="13" viewBox="0 0 15 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M12.4687 1.48863H2.49342C2.14909 1.48863 1.86996 1.80701 1.86996 2.19974V10.7331C1.86996 11.1258 2.14909 11.4442 2.49342 11.4442H12.4687C12.8131 11.4442 13.0922 11.1258 13.0922 10.7331V2.19974C13.0922 1.80701 12.8131 1.48863 12.4687 1.48863ZM2.49342 0.0664062C1.46044 0.0664062 0.623047 1.02154 0.623047 2.19974V10.7331C0.623047 11.9113 1.46044 12.8664 2.49342 12.8664H12.4687C13.5017 12.8664 14.3391 11.9113 14.3391 10.7331V2.19974C14.3391 1.02154 13.5017 0.0664062 12.4687 0.0664062H2.49342Z"
                        fill="white"/>
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M3.26171 3.16653C3.48214 2.86482 3.87527 2.82406 4.13979 3.07548L7.08227 5.8723C7.31351 6.09203 7.6493 6.09203 7.88054 5.8723L10.823 3.07548C11.0875 2.82406 11.4807 2.86482 11.7011 3.16653C11.9215 3.46824 11.8858 3.91664 11.6213 4.16807L8.67875 6.96484C7.98516 7.62419 6.97765 7.62419 6.28399 6.96484L3.34153 4.16807C3.07701 3.91664 3.04128 3.46824 3.26171 3.16653Z"
                        fill="white"/>
                </svg>
                a.tintari@talkearn.app
              </a>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>

import VideoPlayer from 'nuxt-video-player'
import headerArea from '~/components/landing/headerArea'
import footerArea from '~/components/landing/footerArea'
import experts from '~/components/landing/expertsWidget'
import formArea from '~/components/landing/form'
import explainerVideo from '~/components/landing/explainerVideo'
import userApi from "~/api/userApi";
import {mapActions, mapGetters} from 'vuex'

require('nuxt-video-player/src/assets/css/main.css')

export default {
  components: {headerArea, footerArea, experts, formArea, explainerVideo, VideoPlayer},
  data() {
    return {
      section1SVG: require('@/static/svg/section1.svg'),
      section2SVG: require('@/static/svg/section2.svg'),

      eco1SVG: require('@/static/svg/eco1.svg'),
      eco2SVG: require('@/static/svg/eco2.svg'),
      eco3SVG: require('@/static/svg/eco3.svg'),

      tetSVG: require('@/static/svg/tet.svg'),

      metaVer1SNG: require('@/static/svg/Virtual Reality Meeting.svg'),
      metaVer2SNG: require('@/static/svg/TND_M454_010.svg'),
      metaVer3SNG: require('@/static/svg/HD_M352_04.svg'),

      logo1: require('@/static/svg/logo1.svg'),
      logo2: require('@/static/svg/logo2.svg'),
      logo3: require('@/static/svg/logo3.svg'),
      logo4: require('@/static/svg/logo4.svg'),
      video: false,
      youtubeLink: false,
      tab: false,
      success: false,
      form: {
        valid: false,
        email: 'Your email',
        name: '',
      },
      emailRules: [
        v => !!v || 'E-mail is required',
        v => /.+@.+\..+/.test(v) || 'E-mail must be valid',
      ],
    }
  },
  computed: mapGetters({
    user: 'chat/getUser',
  }),
  methods: {
    submit() {
      if (this.$refs.form.validate()) {
        this.form.guestId = this.user._id
        userApi.bookUser(this.form, async response => {
          this.success = true
        })
      }
    },
  }
}
</script>

<style>
#root {
  background-color: #000000;
}

.Section-An {
  padding-top: 130px;
  position: relative;
  min-height: 1000px;
}

.Section-An iframe {
  width: 100% !important;
  position: absolute;
  left: 0;
  top: 130px;
}

.customize_1 {
  display: block !important;
  justify-content: center;
  flex-direction: row;
  grid-column: 1 !important;
  text-align: center;
}

.video-wrapp1 {
  margin-top: 121px;
}

.video-wrapp1 video {
  width: 100%;
}

.buttons-wrapper {
  display: flex;
  align-items: center;
}

.buttons-wrapper p {
  margin: 0;
  padding: 0;
  margin-left: 20px;
}

.video-play-btn {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background-color: #FFF;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-left: 20px;
  cursor: pointer;
}

.video-play-btn svg {
  width: 20px !important;
  height: 20px !important;
}
</style>
