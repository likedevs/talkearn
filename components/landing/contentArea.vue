<template>
  <div id="root">
    <div class="AppRoot">
      <div class="Home">
        <section v-if="!$mobileDetect.mobile()" class="Section-An" style="background-image:url('/landing/Banner-Main-Backgroud.png')">
          <iframe  height="1080" style="margin: 0 auto 50px; border: none"
                   v-if="!$mobileDetect.mobile()"
                   src="https://www.youtube.com/embed/SqhFCr4VZFs"
                   allow='autoplay'
                   allowfullscreen>
          </iframe>
        </section>
        <section v-if="$mobileDetect.mobile()" class="Section-An" style="background-image:url('/landing/Banner-Main-Backgroud.png'); min-height: 500px">
          <iframe  height="400" style="margin: 0 auto 50px; border: none"
                   v-if="$mobileDetect.mobile()"
                   src="https://www.youtube.com/embed/SqhFCr4VZFs"
                   allow='autoplay'
                   allowfullscreen>
          </iframe>
        </section>
        <section class="Section-1" style="background-image:url('/landing/Banner-Main-Backgroud.png')">
          <img class="Hero-1" src="/landing/Banner-Main-Right.png" alt="TalkEarn Metaverse">
          <div class="Section-1-main">
            <div class="Heading has-text is-white is-heading is-large">
              A Crypto Experts Metaverse. Built on Blockchain.
            </div>
            <div class="Paragraph-1 has-text is-white is-paragraph-main">
              A decentralized metaverse, where crypto enthusiasts can find professional content on any
              crypto topic and connect with verified crypto experts instantly through VR experience.
            </div>
            <form-area :title="'Join Us'"></form-area>
            <div class="Sidenote">*Get whitelisted to get TET tokens on launch day.</div>
          </div>
        </section>

        <section class="Section-1 is-centered customize_1"
                 style="background-image:url('/landing/Banner-Main-Backgroud.png'); display: flex; ">
          <div class="Heading-3 has-text is-white is-heading is-large">Our 2D platform explainer video</div>

          <div>
            <iframe width="860" height="480" style="margin: 0 auto 50px; border: none"
                    v-if="!$mobileDetect.mobile()"
                    src="https://www.youtube.com/embed/8YvKF1_UqzA?autoplay=1"
                    allow='autoplay'
                    allowfullscreen>
            </iframe>

            <iframe width="320" height="330" style="margin: 0 auto 50px; border: none"
                    v-if="$mobileDetect.mobile()"
                    src="https://www.youtube.com/embed/8YvKF1_UqzA?autoplay=1"
                    allow='autoplay; encrypted-media'
                    allowfullscreen>
            </iframe>
          </div>

        </section>

        <section class="Section-2" id="join"
                 style="background-image:url('/landing/Banner_TalkEarn_background_Desktop.png')">
          <div class="Hero-2">
            <img alt="laptop hero" src="/landing/Banner_TalkEarn_laptopImage_Desktop&Mobile.png">
          </div>
          <div class="Section-2-main">
            <div class="Heading has-text is-white is-heading is-large">
              Introducing TalkEarn Metaverse
            </div>
            <div class="Paragraph-2 has-text is-paragraph-main is-white">
              TALKEARN Metaverse is a virtual city with 3D office buildings. Each office building will be dedicated to a crypto topic (i.e. NFT, payments, etc.).
              A place where crypto enthusiasts will find professional content and verified experts on that specific topic.
              Inside the building, there will be workspaces (floors, rooms) with professional content and verified experts.
              Experts are those users that passed our certification program and proved their knowledge and skills in a specific crypto topic.
              The users will be able to read the experts’ profiles (with information about them, videos, courses, posted articles, ratings, reviews, etc.).
              Those who are online can be contacted instantly through VR experience, video call, or/and chat.
              Those who are offline can be scheduled an appointment.
              <br><br>
              Our whitepaper is now released, take a look!
            </div>
            <a rel="noopener noreferrer" target="_blank" class="Button Button--white  button"
               href="https://docs.talkearn.app">
              <div class="Button-caption">Read Documentation</div>
            </a>
          </div>
        </section>
        <section class="Section-3">
          <div class="Breaker"></div>
          <div class="Hero-3">
            <img alt="checkmark" src="/landing/whitelist-section-checkmark.svg">
          </div>
          <div class="Section-3-main has-text is-centered">
            <div class="Heading-3 has-text is-white is-heading is-large">Get Whitelisted</div>
            <div class="Paragraph-3 has-text is-paragraph-large is-white">
              We’re working around the clock to get ready for our TalkEarn Metaverse launch in the next few months. Be
              one of the first to access the TalkEarn Metaverse and get exclusive access to our Community Release.
            </div>
            <form-area :title="'Join The Whitelist'"></form-area>
          </div>
        </section>
        <section class="Section-11" id="team">
          <div class="Header Heading has-text is-grey is-centered is-heading is-large">
            Our Team
          </div>
          <div class="Section-11-main is-centered">
            <experts></experts>
          </div>
        </section>
        <section class="Section-4" id="ecosystem">
          <div class="Section-4-main">
            <div class="Heading has-text is-white is-heading is-large">The TalkEarn Ecosystem</div>
            <div class="Section-4-1 has-text is-centered">
              <div class="Hero-4">
                <img alt="traders hero" src="/landing/Ecosystem-section-1st-icon.svg">
              </div>
              <div class="Subheading-4 has-text is-white">Professional Experts</div>
              <div class="Paragraph-4 has-text is-paragraph-main is-white">
                Core users, who are well-versed in Crypto, and are willing to earn money for their knowledge and
                experience.
                The more knowledge and experience they have, the stronger their community standing becomes, and their
                visibility
                and influence over the community, as they earn more TET tokens, using Pay-per-minute functionality.
              </div>
            </div>
            <div class="Section-4-2 has-text is-centered">
              <div class="Hero-4">
                <v-icon aria-hidden="false">
                  mdi-progress-question
                </v-icon>
              </div>
              <div class="Subheading-4 has-text is-white">Crypto Enthusiasts</div>
              <div class="Paragraph-4 has-text is-paragraph-main is-white">
                Crypto Enthusiasts are users who are looking for opportunities to invest and professional guidance and
                consultancy services.
                They get full access to professional information about Crypto in one place, to the list of professional
                experts, VR experience,
                TALK2EARN technology, and WebRTC features, allowing them to benefit from real-time live consultancy.
              </div>
            </div>
            <div class="Section-4-3 has-text is-centered">
              <div class="Hero-4">
                <img alt="communities hero" src="/landing/Ecosystem-section-3rd-icon.svg">
              </div>
              <div class="Subheading-4 has-text is-white">Partners & Community</div>
              <div class="Paragraph-4 has-text is-paragraph-main is-white">
                Soon after the TalkEarn Metaverse goes live, we’ll expose it to our Platform's Partners (i.e., Exchanges,
                Crypto Projects, Blockchains, etc.),
                eager to grab the attention of our impressive community by renting/buying real estate in our metaverse.
                There they will be able to place the content about their ecosystems and their experts.
                It is similar to their discord ecosystems but augmented with virtual reality and #talk2earn technology.
              </div>
            </div>
          </div>
        </section>
        <section class="Section-6" id="tokens">
          <div class="Heading has-text is-white is-heading is-large">Meet The Tokens</div>
          <div class="Section-6-hero has-text is-paragraph-main is-white">
            <div class="image" style="background-image:url('/landing/Banner_MeetTaken_squareImage_Desktop.png')"
                 v-if="!$mobileDetect.mobile()"></div>
            <div class="image" style="background-image:url('/landing/Banner_MeetTaken_squareImage_Mobile.png')"
                 v-if="$mobileDetect.mobile()"></div>

          </div>
          <div class="Section-6-main">
            <div class="Section-6-tabs has-text is-paragraph-main is-white">
              <div class="Tabs">
                <div class="Tabs-content">
                  <v-tabs
                      v-model="tab"
                      background-color="transparent"
                      centered
                      dark
                      icons-and-text
                  >
                    <v-tabs-slider></v-tabs-slider>
                    <v-tab href="#tab-1">Metaverse Components</v-tab>
                    <v-tab href="#tab-2">Utility Token</v-tab>
                  </v-tabs>
                  <v-tabs-items v-model="tab">
                    <v-tab-item :value="'tab-' + 1">
                      <v-card flat>
                        <v-card-text>
                          <b>A virtual city with 3D office buildings</b>: Each office building will be dedicated to a crypto topic (i.e. NFT, payments in Crypto, Play2Earn, etc.)
                          <br/>
                          <b>Workspaces inside the buildings</b>: floors/rooms with professional content and verified experts. For example: inside the building "Blockchain",
                          on the first floor shall be placed rooms with experts and content related to "About blockchain". On the second floor - rooms with content and experts
                          related to "Building on blockchain" (for developers). The third floor can be filled in by content and experts, related to a specific blockchain
                          (Near, Binance or Polygon). And so on.
                          <br/>
                          <b>Users & Experts</b>: Experts are those users that passed our certification program and proved their knowledge and skills in a specific crypto topic.
                          The users will be able to read the experts’ profiles (with information about them, videos, courses, posted articles, ratings, reviews, etc.).
                          Those who are online can be contacted instantly through VR experience, video call, or/and chat. First call is free. Next ones will be paid by the users,
                          depending on the amount of call minutes and their price, defined by the experts. With the experts who are offline the users can schedule an appointment.
                          <br/>
                          <b>Real Estate</b>: Aside from built-in real estate (classic crypto topics, i.e NFT, #play2earn, payments in crypto, etc.),
                          sponsored real estate will be available. Exchanges, blockchains, and crypto projects will be able to rent/buy workspaces as NFT.
                          There they will be able to place the content about their ecosystem and their employees (experts). Their experts will be able to consult
                          the users through VR experience/video calls and present new content (webinars, AMA/Q&A sessions, etc.).
                          It is similar to their discord ecosystems but augmented with virtual reality and #talk2earn technology. The real estate owners will define
                          the cost of the time of their experts, available on their workspaces.
                        </v-card-text>
                      </v-card>
                    </v-tab-item>
                    <v-tab-item :value="'tab-' + 2">
                      <v-card flat>
                        <v-card-text>
                          <b>The TET token</b> is used as a reward for platform users, as well as payment
                          for live consultancy and services provided within the TalkEarn Metaverse.
                          <br/>
                          TET is the native token of TalkEarn. TET will be required to purchase or lease all real estate within TalkEarn Metaverse.
                          <br/>
                          <b>Stake $TET</b>. Community members holding $TET tokens will have access to stake $TET
                          tokens,
                          to get rewarded (APY 5 -15% depending on staking pool). Additionally, users who stake
                          a certain amount of $TET tokens for a certain period will be eligible to recieve additional rewards.
                          <br/>
                          <b>Community rewards</b>. Community members holding $TET tokens will be eligible to take part
                          in different contests
                          such as token airdrops and will have a priority for
                          capped events and giveaways from TALKEARN Metaverse and its partners.
                          This includes certain rewards (gifts, airdrops, prizes, etc.) and many other things.
                        </v-card-text>
                      </v-card>
                    </v-tab-item>
                  </v-tabs-items>
                </div>
              </div>
              <!--              <div class="">-->
              <!--                <form-area :title="'Join Us Now'"></form-area>-->
              <!--              </div>-->
            </div>
          </div>
        </section>
        <section class="Section-7">
          <div class="Section-7-main">
            <div class="Section-7-hero">
              <div class="image" style="background-image:url('/landing/Banner_Monetization_section.png')"
                   v-if="!$mobileDetect.mobile()"></div>
              <div class="image" style="background-image:url('/landing/Banner_Monetization_section_mobile.png')"
                   v-if="$mobileDetect.mobile()"></div>
            </div>
            <div class="Heading has-text is-white is-heading is-large">TalkEarn Platform Monetisation System</div>
            <div class="Paragraph has-text is-white is-paragraph-main">
              We’re building the DAO of the future through collective intelligence, collective exchange of knowledge and
              experience,
              and meritocratic-based ecosystems that reward users based on the benefit they bring the community.
            </div>
            <div class="Section-7-accordion">
              <div class="Accordion">
                <v-expansion-panels multiple>
                  <v-expansion-panel>
                    <v-expansion-panel-header>Pay-per-minute functionality</v-expansion-panel-header>
                    <v-expansion-panel-content>
                      So many smart people spend hours each day crawling through treasure troves of information, on
                      Telegram,
                      private WhatsApp and Discord groups, subreddits, newsletters, YouTube, and more, sourcing
                      knowledge, tips, and trading insights.
                      What if there was a way to harness all this information and pay for it just as much as the number
                      of minutes used to get it from professional experts? Now there is.
                    </v-expansion-panel-content>
                  </v-expansion-panel>
                  <v-expansion-panel>
                    <v-expansion-panel-header>Real Estate NFT sale/rent</v-expansion-panel-header>
                    <v-expansion-panel-content>
                      Platform’s Partners, i.e. Exchanges, Crypto Projects, Blockchains, Crypto Schools and other partners eager to grab the
                      attention of our impressive community will have the opportunity to rent/buy real estate in our metaverse.
                      There they will be able to place the content about their ecosystem and their experts.
                      It is similar to their discord ecosystems but augmented with virtual reality and #talk2earn technology.
                    </v-expansion-panel-content>
                  </v-expansion-panel>
                  <v-expansion-panel>
                    <v-expansion-panel-header>Boosted articles and Ads</v-expansion-panel-header>
                    <v-expansion-panel-content>
                      Professional experts will have the opportunity to boost their articles and profiles, to
                      get higher visibility in the Metaverse.
                      Partners (i.e. Exchanges, Crypto Projects, Blockchains, and others) will have the opportunity to launch
                      promotions and display Ads in the Metaverse,
                      to grab the attention of our impressive community.
                    </v-expansion-panel-content>
                  </v-expansion-panel>
                </v-expansion-panels>
              </div>
            </div>
            <form-area :title="'Learn More'"></form-area>
          </div>
        </section>
        <section class="Section-8" id="about">
          <div class="Section-8-hero">
            <div class="image" style="background-image:url('/landing/Banner_ShareKnowledge_section.png')"
                 v-if="!$mobileDetect.mobile()"></div>
            <div class="image" style="background-image:url('/landing/Banner_ShareKnowledge_section_mobile.png')"
                 v-if="$mobileDetect.mobile()"></div>
          </div>
          <div class="Section-8-main">
            <div class="Heading has-text is-white is-heading is-large">Share Your Knowledge</div>
            <div class="Section-8-tabs has-text is-paragraph-main is-white">
              Less barriers to share Your Knowledge and Experience. Create Your own workspace in Our Metaverse and start
              earning by consulting crypto enthusiasts. Get paid instantly. Just talk and earn!
            </div>
          </div>
        </section>
        <section class="Section-9">
          <div class="Breaker"></div>
          <div class="Heading has-text is-white is-heading is-large">Get in Touch</div>
          <div class="Section-9-main">
            <div class="Section-9-text has-text is-paragraph-main is-white">
              Have questions? Need help using our Metaverse? Need a mentor to show You the way in Crypto? We’d love to
              talk and get you involved in what we’re building. Get in touch and help us revolutionize Crypto.
            </div>
            <div class="Section-9-icons">
              <a class="Pollen-twitter" target="_blank" href="https://twitter.com/TalkEarn">
                <img src="/landing/twitter-icon-white-transparent-24.svg" width="40px" alt="follow us on twitter">
              </a>
              <a class="Pollen-telegram" target="_blank" href="https://t.me/talkearn_official">
                <img src="/landing/telegram-icon-white-transparent.svg" width="40px" alt="join us on telegram">
              </a>
              <a class="Pollen-discord medium-icon" target="_blank" href="https://talkearn.medium.com/"
                 style="width: 52px;">
                <img src="/landing/Medium-Logo.svg" alt="medium" style="height: 27px;">
              </a>
            </div>
          </div>
        </section>
        <section class="Section-10">
          <div class="Section-10-main">
            <div class="Heading Heading--mobile has-text is-white is-heading is-medium">
              Never miss an update about TalkEarn Metaverse!
            </div>
            <div class="Heading Heading--desktop has-text is-white is-heading is-medium">
              Never miss an update about TalkEarn Metaverse!
            </div>
            <div class="Section-10-newsletter">
              <div class="mc__form">
                <v-form
                    v-if="!success"
                    ref="form"
                    lazy-validation
                >
                  <v-text-field
                      v-model="form.email"
                      :rules="emailRules"
                      required
                  ></v-text-field>
                  <v-icon aria-hidden="false" @click="submit()">
                    mdi-send
                  </v-icon>
                </v-form>
                <p v-else>Success!</p>
              </div>
            </div>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<script>

import headerArea from '~/components/landing/headerArea'
import footerArea from '~/components/landing/footerArea'
import experts from '~/components/landing/expertsWidget'
import formArea from '~/components/landing/form'
import userApi from "~/api/userApi";
import {mapActions, mapGetters} from 'vuex'

export default {
  components: {headerArea, footerArea, experts, formArea},
  data() {
    return {
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
.Section-An{
  padding-top: 130px;
  position: relative;
  min-height: 1000px;
}
.Section-An iframe{
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
</style>
