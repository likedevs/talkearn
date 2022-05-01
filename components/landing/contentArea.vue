<template>
  <div id="root">
    <div class="AppRoot">
      <div class="video-wrapp">
        <video id="video" ref="video" src="TET-metaverse-video-blockchains-fin.mp4"
               autoplay="true"
               controls
               muted
               loop>
        </video>
      </div>
      <div class="Home">
        <div class="space-hr"></div>

        <section class="Section-2">
          <img :src="section1SVG" class="Hero-1 image-metaverse"/>
          <div class="Section-1-main">
            <div class="logo-content">
              <svg width="69" height="79" viewBox="0 0 69 79" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M8.19866 40.9835C4.15989 40.9835 0.886719 38.1523 0.886719 34.6758V28.9303C0.886719 25.4434 4.15989 22.6227 8.19866 22.6227C8.87548 22.6227 9.41916 23.0911 9.41916 23.6739V39.9218C9.41916 40.5047 8.87548 40.9835 8.19866 40.9835ZM6.97815 24.8709C4.8811 25.3393 3.33883 26.9839 3.33883 28.9303V34.6758C3.33883 36.6223 4.8811 38.2668 6.97815 38.7352V24.8709Z"
                      fill="white"/>
                <path
                    d="M10.5173 39.9218V23.9342C11.7045 23.9342 12.6587 24.7669 12.6587 25.7869V38.0795C12.6587 39.0995 11.7045 39.9218 10.5173 39.9218Z"
                    fill="white"/>
                <path
                    d="M33.6769 78.4114V67.2018C20.5867 66.6558 10.1363 57.6923 10.1363 46.7713C10.1363 46.1634 10.7036 45.6689 11.4017 45.6689C12.0999 45.6689 12.6671 46.1634 12.6671 46.7713C12.6671 56.8372 22.6593 65.0279 34.9423 65.0279C47.2144 65.0279 57.2066 56.8372 57.2066 46.7713C57.2066 46.1634 57.7738 45.6689 58.472 45.6689C59.1701 45.6689 59.7483 46.1634 59.7483 46.7713C59.7483 57.6923 49.2979 66.6558 36.2077 67.2018V78.4114H33.6769ZM34.9423 60.2886C25.4083 60.2886 17.6523 53.8081 17.2705 45.5349C17.2487 44.9271 17.7832 44.4222 18.4923 44.3913C19.1795 44.2986 19.7795 44.8446 19.8013 45.4525C20.1285 52.5306 26.7718 58.0838 34.9423 58.0838C42.6546 58.0838 49.0252 53.1281 49.9633 46.5961H27.5027C26.8046 46.5961 26.2373 46.1016 26.2373 45.4937C26.2373 44.8858 26.8046 44.3913 27.5027 44.3913H51.2724C52.0905 44.4222 52.6468 44.824 52.6032 45.6998C52.1341 53.8905 44.4109 60.2886 34.9423 60.2886ZM51.3596 40.5689H18.7104C18.0123 40.5689 17.445 40.0744 17.445 39.4665C17.445 38.8587 18.0123 38.3641 18.7104 38.3641H51.3596C52.0578 38.3641 52.625 38.8587 52.625 39.4665C52.625 40.0744 52.0578 40.5689 51.3596 40.5689ZM51.3596 34.5315H18.7104C18.0123 34.5315 17.445 34.0369 17.445 33.4291C17.445 32.8212 18.0123 32.3267 18.7104 32.3267H51.3596C52.0578 32.3267 52.625 32.8212 52.625 33.4291C52.625 34.0369 52.0578 34.5315 51.3596 34.5315ZM51.3596 28.494C50.6506 28.494 50.0833 27.9995 50.0833 27.3916C50.0833 20.1384 43.2873 14.2348 34.9423 14.2348C27.0118 14.2348 20.4885 19.5511 19.8449 26.2995H42.371C43.0692 26.2995 43.6364 26.7837 43.6364 27.3916C43.6364 27.9995 43.0692 28.494 42.371 28.494H18.525C17.8268 28.494 17.2596 27.9995 17.2596 27.3916C17.2596 18.9226 25.1901 12.03 34.9423 12.03C44.6945 12.03 52.625 18.9226 52.625 27.3916C52.625 27.9995 52.0578 28.494 51.3596 28.494Z"
                    fill="white"/>
                <path
                    d="M57.2259 38.0796V25.787C57.2259 24.767 58.1912 23.9343 59.3673 23.9343V39.9219C58.1912 39.9219 57.2259 39.0996 57.2259 38.0796Z"
                    fill="white"/>
                <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M61.6976 40.9836C61.0208 40.9836 60.466 40.5048 60.466 39.9219V23.6741C60.466 23.0912 61.0208 22.6228 61.6976 22.6228C65.7253 22.6228 68.9984 25.4435 68.9984 28.9304V34.676C68.9984 38.1524 65.7253 40.9836 61.6976 40.9836ZM62.9181 24.871V38.7353C65.0041 38.2669 66.5574 36.6224 66.5574 34.676V28.9304C66.5574 26.984 65.0041 25.3394 62.9181 24.871Z"
                      fill="white"/>
                <path
                    d="M59.4264 20.5042H59.3397C58.7326 20.5042 58.234 20.0975 58.1797 19.579C57.6702 14.4751 53.0089 3.1491 35.9569 2.80342C29.4093 2.67125 23.9891 4.36914 19.8589 7.84626C15.5552 11.4759 13.7124 16.1934 13.3763 19.0503C13.3113 19.5688 12.8235 19.9653 12.2272 19.9653H12.1405C11.4684 19.9653 10.9264 19.4671 10.9806 18.8876C11.3817 15.2783 13.669 10.1745 18.1895 6.37204C22.7966 2.48824 28.7697 0.58701 36.0111 0.739515C53.1064 1.08519 59.9793 11.9639 60.5863 19.4366C60.6297 20.0162 60.0985 20.5042 59.4264 20.5042Z"
                    fill="white"/>
              </svg>
            </div>
            <div class="Heading has-text is-white is-heading is-large">
              Talkearn
            </div>
            <div class="Heading has-text is-white is-heading is-medium">
              a crypto metaverse for learning
            </div>
            <div class="Paragraph-1 has-text is-white is-paragraph-main">
              A metaverse where crypto enthusiasts can find professional learning content on any crypto topic and
              connect with verified crypto experts instantly through VR experience.
            </div>
            <div class="buttons-wrapper">
              <form-area :title="'Join Us'"></form-area>

              <explainer-video></explainer-video>


            </div>
          </div>
        </section>

        <div class="space-hr" id="about"></div>
        <section class="Section-3">
          <div class="Section-3-main has-text is-centered">
            <div class="Heading-3 has-text is-white is-heading is-large" style="margin-top: 50px">
              Introducing TalkEarn Metaverse
            </div>
            <div class="Paragraph-3 has-text is-paragraph-large is-white"
                 style="padding: 0 20%; margin-bottom: 40px">
              TALKEARN Metaverse is a virtual city with 3D office buildings. Each office building will
              be dedicated to a crypto topic (i.e. NFT, payments, etc.).
            </div>
            <div class="introducing-wrapp">
              <div class="introducing-item">
                <svg width="187" height="165" viewBox="0 0 187 165" fill="none"
                     xmlns="http://www.w3.org/2000/svg">
                  <path
                      d="M43.276 164.779H142.983C143.456 164.487 143.929 164.194 144.402 163.902C187.322
                      136.744 199.177 81.3512 170.871 40.1643C142.566 -1.02255 84.8238 -12.3813 41.9044
                      14.7688C-1.01494 41.9189 -12.8617 97.3196 15.4357 138.506C22.9272 149.403 32.48 158.215
                      43.276 164.779Z"
                      fill="#BAD4F4"/>
                </svg>
                <div class="item-inside">
                  <h5>Virtual workspaces</h5>
                  <p>
                    Inside the building, there will be workspaces (floors, rooms) with professional content
                    and verified experts.
                  </p>
                </div>
              </div>
              <div class="introducing-item mid-item">
                <svg width="187" height="165" viewBox="0 0 187 165" fill="none"
                     xmlns="http://www.w3.org/2000/svg">
                  <path
                      d="M43.276 164.779H142.983C143.456 164.487 143.929 164.194 144.402 163.902C187.322
                      136.744 199.177 81.3512 170.871 40.1643C142.566 -1.02255 84.8238 -12.3813 41.9044
                      14.7688C-1.01494 41.9189 -12.8617 97.3196 15.4357 138.506C22.9272 149.403 32.48 158.215
                      43.276 164.779Z"
                      fill="#BAD4F4"/>
                </svg>
                <div class="item-inside">
                  <h5>Experts profiles</h5>
                  <p>The users will be able to read the experts’ profiles (with information about them,
                    videos, courses, posted articles, ratings, reviews, etc.). </p>
                </div>
              </div>
              <div class="introducing-item">
                <svg width="187" height="165" viewBox="0 0 187 165" fill="none"
                     xmlns="http://www.w3.org/2000/svg">
                  <path
                      d="M43.276 164.779H142.983C143.456 164.487 143.929 164.194 144.402 163.902C187.322
                      136.744 199.177 81.3512 170.871 40.1643C142.566 -1.02255 84.8238 -12.3813 41.9044
                      14.7688C-1.01494 41.9189 -12.8617 97.3196 15.4357 138.506C22.9272 149.403 32.48 158.215
                      43.276 164.779Z"
                      fill="#BAD4F4"/>
                </svg>
                <div class="item-inside">
                  <h5>Tutoring service</h5>
                  <p>Experts who are online can be contacted instantly through VR experience. Those who are
                    offline can be scheduled an appointment.</p>
                </div>
              </div>
            </div>
          </div>
        </section>
        <div class="space-hr"></div>
        <section class="Section-7" style="padding-bottom: 0;">
          <div class="Section-7-main">
            <div class="Section-7-hero" v-if="!$mobileDetect.mobile()" style="text-align: center">
              <img :src="section2SVG" alt="">
            </div>
            <div class="Heading has-text is-white is-heading is-large">
              TalkEarn Platform Monetisation System
            </div>
            <div class="Section-7-hero" v-if="$mobileDetect.mobile()" style="text-align: center">
              <img :src="section2SVG" alt="">
            </div>
            <div class="Paragraph has-text is-white is-paragraph-main">
              We’re building the DAO of the future through collective intelligence,
              collective exchange of knowledge and experience,
              and meritocratic-based ecosystems that reward users based on the benefit
              they bring the community.
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
                      Platform’s Partners, i.e. Exchanges, Crypto Projects, Blockchains, Crypto Schools and other
                      partners eager to grab the
                      attention of our impressive community will have the opportunity to rent/buy real estate in our
                      metaverse.
                      There they will be able to place the content about their ecosystem and their experts.
                      It is similar to their discord ecosystems but augmented with virtual reality and #talk2earn
                      technology.
                    </v-expansion-panel-content>
                  </v-expansion-panel>
                  <v-expansion-panel>
                    <v-expansion-panel-header>Boosted articles and Ads</v-expansion-panel-header>
                    <v-expansion-panel-content>
                      Professional experts will have the opportunity to boost their articles and profiles, to
                      get higher visibility in the Metaverse.
                      Partners (i.e. Exchanges, Crypto Projects, Blockchains, and others) will have the opportunity to
                      launch
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
        <div class="space-hr" id="ecosystem"></div>
        <section class="Section-3"  style="padding-top: 20px">
          <div class="Section-3-main has-text is-centered">
            <div class="Heading-3 has-text is-white is-heading is-large" style="margin: 50px 0">
              The TalkEarn Ecosystem
            </div>
            <div class="introducing-wrapp">
              <div class="introducing-item">
                <img :src="eco1SVG" alt="">
                <div class="item-inside-view-2">
                  <h5>Professional Experts</h5>
                  <p>
                    Core users, who are well-versed in Crypto, and are willing to earn money for their
                    knowledge and experience
                  </p>
                </div>
              </div>
              <div class="introducing-item mid-item">
                <img :src="eco2SVG" alt="">
                <div class="item-inside-view-2">
                  <h5>Crypto Learners</h5>
                  <p>
                    Crypto Learners are users who are looking for opportunities to learn and professional
                    mentorship.
                  </p>
                </div>
              </div>
              <div class="introducing-item">
                <img :src="eco3SVG" alt="">
                <div class="item-inside-view-2">
                  <h5>Partners & Community</h5>
                  <p>
                    Platform's Partners - Exchanges, Crypto Projects, Blockchains, etc. eager to grab the
                    attention of our impressive community by metaverse experience.
                  </p>
                </div>
              </div>

            </div>
          </div>
        </section>
        <div class="space-hr" id="tokens"></div>
        <section class="Section-6">
          <div class="Section-6-hero has-text is-paragraph-main is-white">
            <div class="Heading has-text is-white is-heading is-large">
              Meet TET Tokens, <br> a token for learning
            </div>
            <p style="margin-top: 30px">The TET token is used as a reward for platform users, as well as payment for
              live consultancy
              and services and provided within the TalkEarn Metaverse.
            </p>
          </div>
          <div class="Section-6-main" style="text-align: right">
            <img :src="tetSVG" alt="">
          </div>
        </section>
        <div class="space-hr" id="team"></div>
        <section class="Section-11">
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
                <img :src="logo2" alt="">

              </div>

              <div class="partner-item">
                <img :src="logo3" alt="">

              </div>

              <div class="partner-item">
                <img :src="logo4" alt="">

              </div>
            </div>


          </div>
        </section>
        <div class="space-hr"></div>
        <section class="Section-4" >
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
                <h5>2022 - Q2</h5>
                <ul>
                  <li>Platform launch</li>
                  <li>Smart Contract</li>
                  <li>Development (webRTC on Near)</li>
                  <li>Develop content for the Romanian-speaking market</li>
                </ul>
              </div>
              <div class="roadmap-list-item">
                <h5>2022 - Q3</h5>
                <ul>
                  <li>Seed and Private Sale</li>
                  <li>IDO</li>
                  <li>TGE</li>
                  <li>Experts validation & integration</li>
                </ul>
              </div>
              <div class="roadmap-list-item">
                <h5>2022 - Q4</h5>
                <ul>
                  <li>Strategic Partnerships</li>
                  <li>Community Expansion</li>
                  <li>Hive mind education</li>
                  <li>Influencer Marketing</li>
                  <li>Partnerships</li>
                </ul>
              </div>
              <div class="roadmap-list-item">
                <h5>2022 - Q1</h5>
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

      <section class="Section-4"  style="background-color: #1F2131 !important;">
        <div class="Section-4-main">
          <div class="footer-inside Home">
            <div class="footer-logo">
              <svg width="69" height="95" viewBox="0 0 69 95" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M7.31247 49.3228C3.27341 49.3228 0 45.8679 0 41.6256V34.6143C0 30.3592 3.27341 26.9171 7.31247 26.9171C7.98934 26.9171 8.53306 27.4886 8.53306 28.1999V48.0272C8.53306 48.7385 7.98934 49.3228 7.31247 49.3228ZM6.09187 29.6606C3.99467 30.2322 2.45228 32.2391 2.45228 34.6143V41.6256C2.45228 44.0008 3.99467 46.0076 6.09187 46.5792V29.6606Z"
                      fill="white"/>
                <path
                    d="M9.63126 48.0272V28.5175C10.8186 28.5175 11.7728 29.5336 11.7728 30.7784V45.779C11.7728 47.0238 10.8186 48.0272 9.63126 48.0272Z"
                    fill="white"/>
                <path
                    d="M32.7926 94.9961V81.3171C19.7014 80.6508 9.25028 69.7126 9.25028 56.3856C9.25028 55.6439 9.81757 55.0404 10.5158 55.0404C11.214 55.0404 11.7812 55.6439 11.7812 56.3856C11.7812 68.6691 21.7742 78.6643 34.0581 78.6643C46.331 78.6643 56.324 68.6691 56.324 56.3856C56.324 55.6439 56.8912 55.0404 57.5894 55.0404C58.2876 55.0404 58.8658 55.6439 58.8658 56.3856C58.8658 69.7126 48.4147 80.6508 35.3235 81.3171V94.9961H32.7926ZM34.0581 72.8809C24.5233 72.8809 16.7668 64.9727 16.385 54.8769C16.3632 54.1351 16.8977 53.5191 17.6068 53.4814C18.2941 53.3682 18.8941 54.0346 18.9159 54.7763C19.2432 63.4137 25.887 70.1904 34.0581 70.1904C41.7709 70.1904 48.142 64.1429 49.0802 56.1719H26.6179C25.9197 56.1719 25.3524 55.5684 25.3524 54.8266C25.3524 54.0849 25.9197 53.4814 26.6179 53.4814H50.3893C51.2075 53.5191 51.7639 54.0094 51.7202 55.0781C51.2511 65.0733 43.5273 72.8809 34.0581 72.8809ZM50.4766 48.8169H17.825C17.1268 48.8169 16.5595 48.2135 16.5595 47.4717C16.5595 46.7299 17.1268 46.1264 17.825 46.1264H50.4766C51.1748 46.1264 51.7421 46.7299 51.7421 47.4717C51.7421 48.2135 51.1748 48.8169 50.4766 48.8169ZM50.4766 41.4494H17.825C17.1268 41.4494 16.5595 40.8459 16.5595 40.1041C16.5595 39.3623 17.1268 38.7589 17.825 38.7589H50.4766C51.1748 38.7589 51.7421 39.3623 51.7421 40.1041C51.7421 40.8459 51.1748 41.4494 50.4766 41.4494ZM50.4766 34.0818C49.7675 34.0818 49.2002 33.4784 49.2002 32.7366C49.2002 23.8855 42.4037 16.6814 34.0581 16.6814C26.127 16.6814 19.6032 23.1688 18.9596 31.4039H41.4873C42.1855 31.4039 42.7528 31.9948 42.7528 32.7366C42.7528 33.4784 42.1855 34.0818 41.4873 34.0818H17.6395C16.9413 34.0818 16.3741 33.4784 16.3741 32.7366C16.3741 22.4019 24.3051 13.9908 34.0581 13.9908C43.811 13.9908 51.7421 22.4019 51.7421 32.7366C51.7421 33.4784 51.1748 34.0818 50.4766 34.0818Z"
                    fill="white"/>
                <path
                    d="M56.3433 45.7792V30.7785C56.3433 29.5338 57.3087 28.5176 58.4849 28.5176V48.0274C57.3087 48.0274 56.3433 47.0239 56.3433 45.7792Z"
                    fill="white"/>
                <path fill-rule="evenodd" clip-rule="evenodd"
                      d="M60.8153 49.3229C60.1384 49.3229 59.5836 48.7386 59.5836 48.0273V28.2001C59.5836 27.4888 60.1384 26.9172 60.8153 26.9172C64.8432 26.9172 68.1167 30.3594 68.1167 34.6144V41.6257C68.1167 45.8681 64.8432 49.3229 60.8153 49.3229ZM62.0359 29.6608V46.5794C64.122 46.0078 65.6755 44.0009 65.6755 41.6257V34.6144C65.6755 32.2392 64.122 30.2323 62.0359 29.6608Z"
                      fill="white"/>
                <path
                    d="M58.5439 24.3319H58.4572C57.8501 24.3319 57.3514 23.8356 57.2972 23.2028C56.7876 16.9746 52.1259 3.15342 35.0727 2.73159C28.5246 2.5703 23.104 4.64224 18.9735 8.88537C14.6696 13.3146 12.8266 19.0714 12.4905 22.5577C12.4255 23.1904 11.9376 23.6743 11.3413 23.6743H11.2546C10.5824 23.6743 10.0404 23.0664 10.0946 22.3592C10.4957 17.9548 12.7832 11.7265 17.304 7.08638C21.9115 2.34698 27.885 0.0269035 35.1269 0.213006C52.2235 0.634838 59.0968 13.9101 59.7039 23.0292C59.7473 23.7363 59.2161 24.3319 58.5439 24.3319Z"
                    fill="white"/>
              </svg>
            </div>
            <div class="footer-socials">
              <h5>Talkearn</h5>
              <p>a crypto metaverse for learning</p>
              <div class="Footer-icons">
                <a class="Pollen-twitter" target="_blank" href="https://twitter.com/TalkEarn">
                  <img src="/landing/twitter-icon-white-transparent-24.svg" alt="twitter">
                </a>
                <a class="Pollen-telegram" target="_blank" href="https://t.me/talkearn_official">
                  <img src="/landing/telegram-icon-white-transparent.svg" alt="telegram">
                </a>
                <a class="Pollen-discord medium-icon" target="_blank" href="https://github.com/talkearn/talkearn">
                  <img src="/landing/github-logo.svg" alt="medium" style="height: 15px;">
                </a>
                <a class="Pollen-discord medium-icon" target="_blank" href="https://talkearn.medium.com/">
                  <img src="/landing/Medium-Logo.svg" alt="medium" style="height: 15px; width: auto !important;">
                </a>
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
  background-color: #121217;
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

.video-wrapp {
  margin-top: 121px;
}

.video-wrapp video {
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
