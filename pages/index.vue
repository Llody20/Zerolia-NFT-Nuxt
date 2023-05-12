<template>
  <div class="home-container">
    <header data-thq="thq-navbar" class="home-navbar">
      <span class="home-logo">Character</span>
      <div data-thq="thq-navbar-nav" data-role="Nav" class="home-desktop-menu">
        <nav data-thq="thq-navbar-nav-links" data-role="Nav" class="home-nav">
          <button class="home-button button-clean button">About</button>
          <button class="home-button1 button-clean button">Features</button>
          <button class="home-button2 button-clean button">Pricing</button>
          <button class="home-button3 button-clean button">Team</button>
          <button class="home-button4 button-clean button">Blog</button>
        </nav>
      </div>
      <div data-thq="thq-navbar-btn-group" class="home-btn-group">
        <div class="home-socials">
          <button class="social button">
            <img
              alt="image"
              src="/playground_assets/twitter.svg"
              class="home-image"
            />
          </button>
          <button class="social button">
            <img
              alt="image"
              src="/playground_assets/discord.svg"
              class="home-image01"
            />
          </button>
        </div>
        <button class="button">View on Opensea</button>
      </div>
      <div data-thq="thq-burger-menu" class="home-burger-menu">
        <button class="button home-button5">
          <svg viewBox="0 0 1024 1024" class="home-icon">
            <path
              d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
            ></path>
          </svg>
        </button>
      </div>
      <div data-thq="thq-mobile-menu" class="home-mobile-menu">
        <div data-thq="thq-mobile-menu-nav" data-role="Nav" class="home-nav1">
          <div class="home-container1">
            <span class="home-logo1">Character</span>
            <div data-thq="thq-close-menu" class="home-menu-close">
              <svg viewBox="0 0 1024 1024" class="home-icon02">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <nav
            data-thq="thq-mobile-menu-nav-links"
            data-role="Nav"
            class="home-nav2"
          >
            <span class="home-text">About</span>
            <span class="home-text01">Features</span>
            <span class="home-text02">Pricing</span>
            <span class="home-text03">Team</span>
            <span class="home-text04">Blog</span>
          </nav>
          <div class="home-container2">
            <button class="home-login button">Login</button>
            <button class="button">Register</button>
          </div>
        </div>
        <div class="home-icon-group">
          <svg viewBox="0 0 950.8571428571428 1024" class="home-icon04">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon06">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon08">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </header>
    <section class="home-hero">
      <div class="home-heading">
        <h1 class="home-header">Create yourself for the metaverse</h1>
        <footer class="home-footer">
          <div class="home-main">
            <div class="home-branding">
              <div class="home-heading01">
                <h2 class="home-logo2">Character</h2>
                <p class="home-caption">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                  eiusmod tempor incididunt ut labore et dolore.
                </p>
              </div>
              <div class="home-socials1">
                <a
                  href="https://twitter.com"
                  target="_blank"
                  rel="noreferrer noopener"
                  class="home-twitter1 social button"
                >
                  <img
                    alt="image"
                    src="/playground_assets/twitter.svg"
                    class="home-image02"
                  />
                </a>
                <a
                  href="https://discord.com"
                  target="_blank"
                  rel="noreferrer noopener"
                  class="home-discord1 social button"
                >
                  <img
                    alt="image"
                    src="/playground_assets/discord.svg"
                    class="home-image03"
                  />
                </a>
              </div>
            </div>
            <div class="home-links">
              <div class="home-list">
                <h3 class="home-heading02">Site</h3>
                <div class="home-items">
                  <button class="home-link button-clean button">About</button>
                  <button class="home-link01 button-clean button">
                    Collection
                  </button>
                  <button class="home-link02 button-clean button">Roadmap</button>
                  <button class="home-link03 button-clean button">
                    Features
                  </button>
                </div>
              </div>
              <div class="home-list1">
                <h3 class="home-heading03">Company</h3>
                <div class="home-items1">
                  <button class="home-link04 button-clean button">Team</button>
                  <button class="home-link05 button-clean button">Press</button>
                  <button class="home-link06 button-clean button">Terms</button>
                  <button class="home-link07 button-clean button">
                    Limitations
                  </button>
                  <button class="home-link08 button-clean button">
                    Licenses
                  </button>
                </div>
              </div>
            </div>
            <div class="home-socials2">
              <a
                href="https://twitter.com"
                target="_blank"
                rel="noreferrer noopener"
                class="home-twitter2 social button"
              >
                <img
                  alt="image"
                  src="/playground_assets/twitter.svg"
                  class="home-image04"
                />
              </a>
              <a
                href="https://discord.com"
                target="_blank"
                rel="noreferrer noopener"
                class="home-discord2 social button"
              >
                <img
                  alt="image"
                  src="/playground_assets/discord.svg"
                  class="home-image05"
                />
              </a>
            </div>
          </div>
          <span class="home-copyright">
            © 2022 Character. All Rights Reserved.
          </span>
        </footer>
        <p class="home-caption01">
          A character custom collection is joining the NFT space on Opensea.
        </p>
      </div>
      <div class="home-buttons">
        <button class="button">View on Opensea</button>
        <button class="home-learn button-clean button">Learn more</button>
      </div>
    </section>
    <section class="home-description">
      <img
        alt="image"
        src="/playground_assets/hero-divider-1500w.png"
        class="home-divider-image"
      />
      <div class="home-container3">
        <div class="home-description01">
          <div class="home-content">
            <p class="home-paragraph">
              We are a team of digital aute irure dolor in reprehenderit in
              voluptate velit esse cillum dolore eu fugiat.
            </p>
            <p class="home-paragraph1">
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui
              officia deserunt mollit anim id est laborum. Nemo enim ipsam
              voluptatem quia voluptas sit aspernatur aut odit aut fugit.
            </p>
          </div>
          <div class="home-links1">
            <a
              href="https://twitter.com"
              target="_blank"
              rel="noreferrer noopener"
              class="button-link button"
            >
              <span>Follow us on Twitter</span>
              <img
                alt="image"
                src="/playground_assets/arrow.svg"
                class="home-arrow"
              />
            </a>
            <a
              href="https://discord.com"
              target="_blank"
              rel="noreferrer noopener"
              class="home-link10 button-link button"
            >
              <span>Join us on Discord</span>
              <img
                alt="image"
                src="/playground_assets/arrow.svg"
                class="home-arrow1"
              />
            </a>
          </div>
        </div>
      </div>
    </section>
    <section class="home-cards">
      <div class="home-row">
        <div class="home-card">
          <div class="home-avatar">
            <img
              alt="image"
              src="/playground_assets/avatar.svg"
              class="home-avatar1"
            />
          </div>
          <div class="home-main1">
            <div class="home-content01">
              <h2 class="home-header01">10,000+ unique characters</h2>
              <p class="home-description02">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliquat enim
                ad minim veniam, quis nostrud exercitation ullamco laboris nisi
              </p>
            </div>
            <button class="home-learn1 button">
              <span class="home-text07">Learn more</span>
              <img
                alt="image"
                src="/playground_assets/arrow.svg"
                class="home-image06"
              />
            </button>
          </div>
        </div>
        <div class="home-card01">
          <div class="home-avatar2">
            <img
              alt="image"
              src="/playground_assets/default-avatar.svg"
              class="home-avatar3"
            />
          </div>
          <div class="home-main2">
            <div class="home-content02">
              <h2 class="home-header02">Create yourself for the metaverse</h2>
              <p class="home-description03">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliquat enim
                ad minim veniam, quis nostrud exercitation ullamco laboris nisi
              </p>
            </div>
            <button class="home-learn2 button">
              <span class="home-text08">Learn more</span>
              <img
                alt="image"
                src="/playground_assets/arrow-2.svg"
                class="home-image07"
              />
            </button>
          </div>
        </div>
      </div>
      <div class="home-card02">
        <div class="home-avatar4">
          <img
            alt="image"
            src="/playground_assets/light-avatar.svg"
            class="home-avatar5"
          />
        </div>
        <div class="home-row1">
          <div class="home-main3">
            <div class="home-content03">
              <h2 class="home-header03">Create yourself for the metaverse</h2>
              <p class="home-description04">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliquat enim
                ad minim veniam, quis nostrud exercitation ullamco laboris nisi
              </p>
            </div>
            <button class="home-learn3 button">
              <span class="home-text09">Learn more</span>
              <img
                alt="image"
                src="/playground_assets/arrow-2.svg"
                class="home-image08"
              />
            </button>
          </div>
          <img
            alt="image"
            src="/playground_assets/group%202262.svg"
            class="home-image09"
          />
        </div>
      </div>
    </section>
    <section class="home-collection">
      <div class="home-content04">
        <span class="home-caption02">collection</span>
        <div class="home-heading04">
          <h2 class="home-header04">All time best collections</h2>
          <p class="home-header05">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore.
          </p>
        </div>
      </div>
      <div class="home-main4">
        <div class="home-card03">
          <div class="home-image10">
            <img
              alt="image"
              src="/playground_assets/character-1.svg"
              class="home-image11"
            />
          </div>
          <div class="home-content05">
            <span class="home-caption03">Character #1</span>
            <h3 class="home-title">0.05 ETH</h3>
          </div>
        </div>
        <div class="home-card04">
          <div class="home-image12">
            <img
              alt="image"
              src="/playground_assets/character-2.svg"
              class="home-image13"
            />
          </div>
          <div class="home-content06">
            <span class="home-caption04">Character #2</span>
            <h3 class="home-title1">0.05 ETH</h3>
          </div>
        </div>
        <div class="home-card05">
          <div class="home-image14">
            <img
              alt="image"
              src="/playground_assets/character-3.svg"
              class="home-image15"
            />
          </div>
          <div class="home-content07">
            <span class="home-caption05">Character #3</span>
            <h3 class="home-title2">0.05 ETH</h3>
          </div>
        </div>
        <div class="home-card06">
          <div class="home-image16">
            <img
              alt="image"
              src="/playground_assets/character-4.svg"
              class="home-image17"
            />
          </div>
          <div class="home-content08">
            <span class="home-caption06">
              <span>Character #4</span>
              <br />
            </span>
            <h3 class="home-title3">0.05 ETH</h3>
          </div>
        </div>
        <div class="home-card07">
          <div class="home-image18">
            <img
              alt="image"
              src="/playground_assets/character-5.svg"
              class="home-image19"
            />
          </div>
          <div class="home-content09">
            <span class="home-caption07">Character #5</span>
            <h3 class="home-title4">0.05 ETH</h3>
          </div>
        </div>
        <div class="home-card08">
          <div class="home-image20">
            <img
              alt="image"
              src="/playground_assets/character-6.svg"
              class="home-image21"
            />
          </div>
          <div class="home-content10">
            <span class="home-caption08">Character #6</span>
            <h3 class="home-title5">0.05 ETH</h3>
          </div>
        </div>
        <div class="home-card09">
          <div class="home-image22">
            <img
              alt="image"
              src="/playground_assets/character-7.svg"
              class="home-image23"
            />
          </div>
          <div class="home-content11">
            <span class="home-caption09">Character #7</span>
            <h3 class="home-title6">0.05 ETH</h3>
          </div>
        </div>
        <div class="home-card10">
          <div class="home-image24">
            <img
              alt="image"
              src="/playground_assets/character-8.svg"
              class="home-image25"
            />
          </div>
          <div class="home-content12">
            <span class="home-caption10">Character #8</span>
            <h3 class="home-title7">0.05 ETH</h3>
          </div>
        </div>
      </div>
      <button class="home-view2 button-link button">View all</button>
    </section>
    <section class="home-project">
      <div class="home-understand">
        <div class="home-content13">
          <span class="home-caption11">Project</span>
          <div class="home-heading05">
            <h2 class="home-header06">Understand the project</h2>
            <p class="home-header07">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
              ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
              aliquip ex ea commodo consequat.
            </p>
          </div>
          <button class="home-view3 button-link button">
            <span>Learn More</span>
            <img
              alt="image"
              src="/playground_assets/arrow.svg"
              class="home-image26"
            />
          </button>
        </div>
        <img
          alt="image"
          src="/playground_assets/group%202415.svg"
          class="home-image27"
        />
      </div>
      <div class="home-mining">
        <img
          alt="image"
          src="/playground_assets/group%202422.svg"
          class="home-image28"
        />
        <div class="home-content14">
          <span class="home-caption12">Project</span>
          <div class="home-heading06">
            <h2 class="home-header08">How the minting works</h2>
            <p class="home-header09">
              <span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </span>
              <br />
              <br />
              <span>
                Duis aute irure dolor in reprehenderit in voluptate velit esse
                cillum dolore eu fugiat nulla pariatur.
              </span>
              <br />
            </p>
          </div>
          <button class="home-view4 button-link button">
            <span>Learn More</span>
            <img
              alt="image"
              src="/playground_assets/arrow.svg"
              class="home-image29"
            />
          </button>
        </div>
      </div>
    </section>
    <section class="home-roadmap">
      <div class="home-heading07">
        <h2 class="home-header10">Roadmap</h2>
        <p class="home-header11">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
          tempor incididunt ut labore
        </p>
      </div>
      <div class="home-list2">
        <div class="home-step">
          <span class="home-caption13">01</span>
          <div class="home-heading08">
            <h2 class="home-header12">Project Launch</h2>
            <p class="home-header13">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
              ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
              aliquip ex ea commodo consequat.
            </p>
          </div>
          <button class="home-button6 button">View on Opensea</button>
        </div>
        <div class="home-step1">
          <span class="home-caption14">02</span>
          <div class="home-heading09">
            <h2 class="home-header14">Metadata and Character</h2>
            <p class="home-header15">
              <span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
                <span v-html="raw55y3"></span>
              </span>
              <br />
              <br />
              <span>
                Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </span>
              <br />
            </p>
          </div>
        </div>
        <div class="home-step2">
          <span class="home-caption15">03</span>
          <div class="home-heading10">
            <h2 class="home-header16">Get Physical</h2>
            <p class="home-header17">
              <span>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua.
                <span v-html="raww0x5"></span>
              </span>
              <br />
              <br />
              <span>
                Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </span>
              <br />
            </p>
          </div>
        </div>
        <div class="home-step3">
          <span class="home-caption16">04</span>
          <div class="home-heading11">
            <h2 class="home-header18">Private club community</h2>
            <p class="home-header19">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
              <span v-html="raw84us"></span>
            </p>
            <div class="home-benefits">
              <div class="home-item">
                <img
                  alt="image"
                  src="/playground_assets/people.svg"
                  class="home-image30"
                />
                <p class="home-header20">Consectetur adipiscing elit</p>
              </div>
              <div class="home-item1">
                <img
                  alt="image"
                  src="/playground_assets/paper.svg"
                  class="home-image31"
                />
                <p class="home-header21">Consectetur adipiscing elit</p>
              </div>
              <div class="home-item2">
                <img
                  alt="image"
                  src="/playground_assets/checklist.svg"
                  class="home-image32"
                />
                <p class="home-header22">Consectetur adipiscing elit</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="home-join-us">
      <div class="home-content15">
        <div class="home-main5">
          <div class="home-heading12">
            <h2 class="home-header23">Create your character now</h2>
            <p class="home-caption17">
              A character custom collection is joining the NFT space on Opensea.
            </p>
          </div>
          <button class="home-view5 button">View on Opensea</button>
        </div>
        <img
          alt="image"
          src="/playground_assets/group%202273.svg"
          class="home-image33"
        />
      </div>
    </section>
    <section class="home-faq">
      <h2 class="home-header24">We have all the answers</h2>
      <div class="home-accordion">
        <div data-role="accordion-container" class="home-element accordion">
          <div class="home-content16">
            <span class="home-header25">
              Lorem ipsum dolor sit ametetur elit?
            </span>
            <span data-role="accordion-content" class="home-description05">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
              quae ab illo inventore veritatis et quasi architecto beatae vitae
              dicta sunt explicabo.
              <span v-html="rawmzd7"></span>
            </span>
          </div>
          <div class="home-icon-container">
            <svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-closed"
              class="home-icon10"
            >
              <path
                d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path></svg
            ><svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-open"
              class="home-icon12"
            >
              <path
                d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path>
            </svg>
          </div>
        </div>
        <div data-role="accordion-container" class="home-element1 accordion">
          <div class="home-content17">
            <span class="home-header26">
              Excepteur sint occaecat cupidatat non sunt in culpa qui officia
              deserunt mollit anim id est laborum?
            </span>
            <span data-role="accordion-content" class="home-description06">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
              quae ab illo inventore veritatis et quasi architecto beatae vitae
              dicta sunt explicabo.
              <span v-html="rawh4if"></span>
            </span>
          </div>
          <div class="home-icon-container1">
            <svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-closed"
              class="home-icon14"
            >
              <path
                d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path></svg
            ><svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-open"
              class="home-icon16"
            >
              <path
                d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path>
            </svg>
          </div>
        </div>
        <div data-role="accordion-container" class="home-element2 accordion">
          <div class="home-content18">
            <span class="home-header27">
              Tempor incididunt ut labore et dolore magna aliquat enim ad minim?
            </span>
            <span data-role="accordion-content" class="home-description07">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
              quae ab illo inventore veritatis et quasi architecto beatae vitae
              dicta sunt explicabo.
              <span v-html="rawla9r"></span>
            </span>
          </div>
          <div class="home-icon-container2">
            <svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-closed"
              class="home-icon18"
            >
              <path
                d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path></svg
            ><svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-open"
              class="home-icon20"
            >
              <path
                d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path>
            </svg>
          </div>
        </div>
        <div data-role="accordion-container" class="home-element3 accordion">
          <div class="home-content19">
            <span class="home-header28">
              Lorem ipsum dolor sit ametetur elit?
            </span>
            <span data-role="accordion-content" class="home-description08">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
              quae ab illo inventore veritatis et quasi architecto beatae vitae
              dicta sunt explicabo.
              <span v-html="rawzw8n"></span>
            </span>
          </div>
          <div class="home-icon-container3">
            <svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-closed"
              class="home-icon22"
            >
              <path
                d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path></svg
            ><svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-open"
              class="home-icon24"
            >
              <path
                d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path>
            </svg>
          </div>
        </div>
        <div data-role="accordion-container" class="home-element4 accordion">
          <div class="home-content20">
            <span class="home-header29">Incididunt ut labore et dolore?</span>
            <span data-role="accordion-content" class="home-description09">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
              quae ab illo inventore veritatis et quasi architecto beatae vitae
              dicta sunt explicabo.
              <span v-html="rawz1s6"></span>
            </span>
          </div>
          <div class="home-icon-container4">
            <svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-closed"
              class="home-icon26"
            >
              <path
                d="M213.333 554.667h256v256c0 23.552 19.115 42.667 42.667 42.667s42.667-19.115 42.667-42.667v-256h256c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-256v-256c0-23.552-19.115-42.667-42.667-42.667s-42.667 19.115-42.667 42.667v256h-256c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path></svg
            ><svg
              viewBox="0 0 1024 1024"
              data-role="accordion-icon-open"
              class="home-icon28"
            >
              <path
                d="M213.333 554.667h597.333c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-597.333c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
              ></path>
            </svg>
          </div>
        </div>
      </div>
    </section>
    <section class="home-get-yours">
      <div class="home-row2">
        <div class="home-column">
          <div class="home-card11">
            <img
              alt="image"
              src="/playground_assets/character-9.svg"
              class="home-image34"
            />
          </div>
        </div>
        <div class="home-column1">
          <div class="home-card12">
            <img
              alt="image"
              src="/playground_assets/character-10.svg"
              class="home-image35"
            />
          </div>
        </div>
      </div>
      <div class="home-column2">
        <div class="home-card13">
          <div class="home-content21">
            <h2 class="home-header30">Get yours now</h2>
            <p class="home-description10">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliquat enim ad
              minim veniam.
            </p>
          </div>
          <button class="home-button7 button">View on Opensea</button>
        </div>
      </div>
    </section>
    <div>
      <DangerousHTML
        html="<script>
   /*
    Accordion - Code Embed
    */
    const accordionContainers = document.querySelectorAll('[data-role='accordion-container']'); // All accordion containers
    const accordionContents = document.querySelectorAll('[data-role='accordion-content']'); // All accordion content
    const accordionIconsClosed = document.querySelectorAll('[data-role='accordion-icon-closed']'); // All accordion closed icons
    const accordionIconsOpen = document.querySelectorAll('[data-role='accordion-icon-open']'); // All accordion open icons
  
    accordionContents.forEach((accordionContent) => {
        accordionContent.style.display = 'none'; //Hides all accordion contents
    });
  
    accordionIconsClosed.forEach((icon) => {
      icon.style.display = 'flex'
    })
  
    accordionIconsOpen.forEach((icon) => {
      icon.style.display = 'none'
    })
  
    accordionContainers.forEach((accordionContainer, index) => {
        accordionContainer.addEventListener('click', () => {
            if (accordionContents[index].style.display === 'flex') {
                // If the accordion is already open, close it
                accordionContents[index].style.display = 'none';
                accordionIconsClosed[index].style.display = 'flex';
                accordionIconsOpen[index].style.display = 'none'
            } else {
                // If the accordion is closed, open it
                accordionContents.forEach((accordionContent) => {
                    accordionContent.style.display = 'none'; //Hides all accordion contents
                });
  
                accordionIconsClosed.forEach((accordionIcon) => {
                    accordionIcon.style.display = 'flex'; // Resets all icon transforms to 0deg (default)
                });
  
                accordionIconsOpen.forEach((accordionIcon) => {
                  accordionIcon.style.display = 'none';
                })
                
                accordionContents[index].style.display = 'flex'; // Shows accordion content
                accordionIconsClosed[index].style.display = 'none'; // Rotates accordion icon 180deg
                accordionIconsOpen[index].style.display = 'flex';
            }
        });
    });
  </script>
  "
      ></DangerousHTML>
    </div>
    <div data-thq="thq-dropdown" class="home-thq-dropdown list-item">
      <div data-thq="thq-dropdown-toggle" class="home-dropdown-toggle">
        <span class="home-text29">Menu Item</span>
        <div data-thq="thq-dropdown-arrow" class="home-dropdown-arrow">
          <svg viewBox="0 0 1024 1024" class="home-icon30">
            <path d="M426 726v-428l214 214z"></path>
          </svg>
        </div>
      </div>
      <ul data-thq="thq-dropdown-list" class="home-dropdown-list">
        <li data-thq="thq-dropdown" class="home-dropdown list-item">
          <div data-thq="thq-dropdown-toggle" class="home-dropdown-toggle1">
            <span class="home-text30">Sub-menu Item</span>
          </div>
        </li>
        <li data-thq="thq-dropdown" class="home-dropdown1 list-item">
          <div data-thq="thq-dropdown-toggle" class="home-dropdown-toggle2">
            <span class="home-text31">Sub-menu Item</span>
          </div>
        </li>
        <li data-thq="thq-dropdown" class="home-dropdown2 list-item">
          <div data-thq="thq-dropdown-toggle" class="home-dropdown-toggle3">
            <span class="home-text32">Sub-menu Item</span>
          </div>
        </li>
      </ul>
    </div>
    <header data-thq="thq-navbar" class="home-navbar-interactive">
      <img
        alt="logo"
        src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
        class="home-logo3"
      />
      <div data-thq="thq-navbar-nav" data-role="Nav" class="home-desktop-menu1">
        <nav data-thq="thq-navbar-nav-links" data-role="Nav" class="home-nav3">
          <span>About</span>
          <span class="home-text34">Features</span>
          <span class="home-text35">Pricing</span>
          <span class="home-text36">Team</span>
          <span class="home-text37">Blog</span>
        </nav>
      </div>
      <div data-thq="thq-navbar-btn-group" class="home-btn-group1">
        <button class="home-login1 button">Login</button>
        <button class="button">Register</button>
      </div>
      <div data-thq="thq-burger-menu" class="home-burger-menu1">
        <svg viewBox="0 0 1024 1024" class="home-icon32">
          <path
            d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
          ></path>
        </svg>
      </div>
      <div data-thq="thq-mobile-menu" class="home-mobile-menu1">
        <div data-thq="thq-mobile-menu-nav" data-role="Nav" class="home-nav4">
          <div class="home-container4">
            <img
              alt="image"
              src="https://presentation-website-assets.teleporthq.io/logos/logo.png"
              class="home-image36"
            />
            <div data-thq="thq-close-menu" class="home-menu-close1">
              <svg viewBox="0 0 1024 1024" class="home-icon34">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path>
              </svg>
            </div>
          </div>
          <nav
            data-thq="thq-mobile-menu-nav-links"
            data-role="Nav"
            class="home-nav5"
          >
            <span class="home-text38">About</span>
            <span class="home-text39">Features</span>
            <span class="home-text40">Pricing</span>
            <span class="home-text41">Team</span>
            <span class="home-text42">Blog</span>
          </nav>
          <div class="home-container5">
            <button class="home-login2 button">Login</button>
            <button class="button">Register</button>
          </div>
        </div>
        <div class="home-icon-group1">
          <svg viewBox="0 0 950.8571428571428 1024" class="home-icon36">
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg viewBox="0 0 877.7142857142857 1024" class="home-icon38">
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg viewBox="0 0 602.2582857142856 1024" class="home-icon40">
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path>
          </svg>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.mjs'

export default {
  name: 'Home',
  components: {
    DangerousHTML,
  },
  data() {
    return {
      raw55y3: ' ',
      raww0x5: ' ',
      raw84us: ' ',
      rawmzd7: ' ',
      rawh4if: ' ',
      rawla9r: ' ',
      rawzw8n: ' ',
      rawz1s6: ' ',
    }
  },
  head: {
    title: 'Zerolia NFT',
    meta: [
      {
        name: 'description',
        content:
          'a marketplace where users can buy, sell, and trade their NFTs with other users. With the help of blockchain technology, transactions are secure and immutable, ensuring that users have full control over their digital assets.',
      },
      {
        property: 'og:title',
        content: 'Zerolia NFT',
      },
      {
        property: 'og:description',
        content:
          'a marketplace where users can buy, sell, and trade their NFTs with other users. With the help of blockchain technology, transactions are secure and immutable, ensuring that users have full control over their digital assets.',
      },
      {
        property: 'og:image',
        content:
          'https://aheioqhobo.cloudimg.io/v7/_playground-bucket-v2.teleporthq.io_/19b4f0c6-615f-4919-8802-8646743bae2c/739424bf-147d-4019-afa1-81a20a7de40f?org_if_sml=1&q=80',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  background-color: #27272D;
}
.home-navbar {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 1440px;
  align-items: center;
  padding-top: var(--dl-space-space-threeunits);
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  padding-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.home-logo {
  color: rgb(255, 255, 255);
  font-size: 32px;
  font-style: normal;
  font-weight: 600;
}
.home-desktop-menu {
  display: flex;
}
.home-nav {
  gap: var(--dl-space-space-twounits);
  flex: 0 0 auto;
  color: #ffffff;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-button {
  color: rgb(255, 255, 255);
}
.home-button1 {
  color: rgb(255, 255, 255);
}
.home-button2 {
  color: rgb(255, 255, 255);
}
.home-button3 {
  color: rgb(255, 255, 255);
}
.home-button4 {
  color: rgb(255, 255, 255);
}
.home-btn-group {
  gap: var(--dl-space-space-fourunits);
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-socials {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-image {
  width: 100px;
  object-fit: cover;
}
.home-image01 {
  width: 100px;
  object-fit: cover;
}
.home-burger-menu {
  display: none;
  align-items: center;
  justify-content: center;
}
.home-icon {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-mobile-menu {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: fixed;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff;
}
.home-nav1 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-container1 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.home-logo1 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  font-style: normal;
  font-weight: 600;
}
.home-menu-close {
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-icon02 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-nav2 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text01 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text02 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text03 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text04 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-container2 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: center;
  flex-direction: row;
}
.home-login {
  margin-right: var(--dl-space-space-twounits);
}
.home-icon-group {
  display: flex;
}
.home-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-hero {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  max-width: 1440px;
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-sixunits);
}
.home-heading {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-header {
  color: rgb(255, 255, 255);
  font-size: 90px;
  max-width: 900px;
  font-style: normal;
  text-align: center;
  font-weight: 500;
  line-height: 108px;
}
.home-footer {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  position: relative;
  max-width: 1440px;
  align-items: flex-start;
  padding-top: 120px;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-threeunits);
}
.home-main {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: space-between;
}
.home-branding {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  max-width: 600px;
  align-items: flex-start;
  flex-direction: column;
}
.home-heading01 {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-logo2 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  font-style: normal;
  font-weight: 600;
}
.home-caption {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-socials1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-twitter1 {
  text-decoration: none;
}
.home-image02 {
  width: 100px;
  object-fit: cover;
}
.home-discord1 {
  text-decoration: none;
}
.home-image03 {
  width: 100px;
  object-fit: cover;
}
.home-links {
  gap: 120px;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
}
.home-list {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-heading02 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-style: normal;
  font-weight: 600;
}
.home-items {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-link {
  color: rgb(255, 255, 255);
}
.home-link01 {
  color: rgb(255, 255, 255);
}
.home-link02 {
  color: rgb(255, 255, 255);
}
.home-link03 {
  color: rgb(255, 255, 255);
}
.home-list1 {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-heading03 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  font-style: normal;
  font-weight: 600;
}
.home-items1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-link04 {
  color: rgb(255, 255, 255);
}
.home-link05 {
  color: rgb(255, 255, 255);
}
.home-link06 {
  color: rgb(255, 255, 255);
}
.home-link07 {
  color: rgb(255, 255, 255);
}
.home-link08 {
  color: rgb(255, 255, 255);
}
.home-socials2 {
  gap: var(--dl-space-space-unit);
  display: none;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-twitter2 {
  text-decoration: none;
}
.home-image04 {
  width: 100px;
  object-fit: cover;
}
.home-discord2 {
  text-decoration: none;
}
.home-image05 {
  width: 100px;
  object-fit: cover;
}
.home-copyright {
  color: rgb(255, 255, 255);
  font-size: 12px;
}
.home-caption01 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  max-width: 800px;
  text-align: center;
  line-height: 36px;
}
.home-buttons {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-learn {
  color: rgb(255, 255, 255);
}
.home-description {
  gap: 120px;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fiveunits);
}
.home-divider-image {
  width: 100%;
  object-fit: cover;
}
.home-container3 {
  width: 100%;
  display: flex;
  max-width: 1440px;
  align-items: flex-end;
  flex-direction: column;
}
.home-description01 {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  max-width: 900px;
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
}
.home-content {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-paragraph {
  color: #ffffff;
  font-size: 40px;
  line-height: 60px;
}
.home-paragraph1 {
  color: rgb(255, 255, 255);
  font-size: 40px;
  line-height: 60px;
}
.home-links1 {
  width: 100%;
  display: flex;
  align-items: stretch;
  flex-direction: column;
}
.home-arrow {
  width: 25px;
  object-fit: cover;
}
.home-link10 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
  text-decoration: none;
  border-top-width: 0px;
}
.home-arrow1 {
  width: 25px;
  object-fit: cover;
}
.home-cards {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  max-width: 1440px;
  align-items: center;
  padding-top: var(--dl-space-space-fiveunits);
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: 120px;
}
.home-row {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-card {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  background-color: #000000;
}
.home-avatar {
  width: 60px;
  height: 60px;
  display: flex;
  overflow: hidden;
  align-items: flex-start;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  background-color: #FDEA6B;
}
.home-avatar1 {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.home-main1 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-content01 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 460px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header01 {
  color: rgb(255, 255, 255);
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
}
.home-description02 {
  color: rgba(255, 255, 255, 0.8);
  width: 100%;
  font-size: 18px;
  max-width: 400px;
  line-height: 27px;
}
.home-learn1 {
  gap: var(--dl-space-space-unit);
  color: white;
  display: flex;
  padding: 0px;
  box-shadow: none;
  align-items: center;
  padding-top: 0px;
  border-width: 0px;
  padding-left: 0px;
  padding-right: 0px;
  flex-direction: row;
  padding-bottom: 0px;
  background-color: transparent;
}
.home-text07 {
  font-style: normal;
  font-weight: 500;
}
.home-image06 {
  width: 16px;
  object-fit: cover;
}
.home-card01 {
  gap: var(--dl-space-space-twounits);
  flex: 1;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  background-color: #FFCF77;
}
.home-avatar2 {
  width: 60px;
  height: 60px;
  display: flex;
  overflow: hidden;
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  justify-content: center;
  background-color: #EC7495;
}
.home-avatar3 {
  width: 28px;
  object-fit: cover;
}
.home-main2 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-content02 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 460px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header02 {
  color: rgb(0, 0, 0);
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
}
.home-description03 {
  color: #000000;
  width: 100%;
  font-size: 18px;
  max-width: 400px;
  line-height: 27px;
}
.home-learn2 {
  gap: var(--dl-space-space-unit);
  color: #000000;
  display: flex;
  padding: 0px;
  box-shadow: none;
  align-items: center;
  padding-top: 0px;
  border-width: 0px;
  padding-left: 0px;
  padding-right: 0px;
  flex-direction: row;
  padding-bottom: 0px;
  background-color: transparent;
}
.home-text08 {
  font-style: normal;
  font-weight: 500;
}
.home-image07 {
  width: 16px;
  object-fit: cover;
}
.home-card02 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-sixunits);
  padding-left: var(--dl-space-space-fourunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  background-color: #8FA7DF;
}
.home-avatar4 {
  width: 60px;
  height: 60px;
  display: flex;
  overflow: hidden;
  align-items: center;
  border-radius: var(--dl-radius-radius-round);
  flex-direction: column;
  justify-content: center;
  background-color: #000000;
}
.home-avatar5 {
  width: 22px;
  object-fit: cover;
}
.home-row1 {
  gap: var(--dl-space-space-fourunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-main3 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 460px;
  align-items: flex-start;
  flex-direction: column;
}
.home-content03 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 460px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header03 {
  color: rgb(0, 0, 0);
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
}
.home-description04 {
  color: #000000;
  width: 100%;
  font-size: 18px;
  max-width: 400px;
  line-height: 27px;
}
.home-learn3 {
  gap: var(--dl-space-space-unit);
  color: #000000;
  display: flex;
  padding: 0px;
  box-shadow: none;
  align-items: center;
  padding-top: 0px;
  border-width: 0px;
  padding-left: 0px;
  padding-right: 0px;
  flex-direction: row;
  padding-bottom: 0px;
  background-color: transparent;
}
.home-text09 {
  font-style: normal;
  font-weight: 500;
}
.home-image08 {
  width: 16px;
  object-fit: cover;
}
.home-image09 {
  width: 100%;
  object-fit: cover;
}
.home-collection {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  max-width: 1440px;
  align-items: flex-start;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: 160px;
}
.home-content04 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-caption02 {
  color: #FFCF77;
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.home-heading04 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header04 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
}
.home-header05 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-main4 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: grid;
  align-items: flex-start;
  flex-direction: column;
  grid-template-columns: repeat(4, 1fr);
}
.home-card03 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image10 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #FDEA6B;
}
.home-image11 {
  object-fit: cover;
}
.home-content05 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption03 {
  font-style: normal;
  font-weight: 600;
}
.home-title {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-card04 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image12 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #FFCF77;
}
.home-image13 {
  object-fit: cover;
}
.home-content06 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption04 {
  font-style: normal;
  font-weight: 600;
}
.home-title1 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-card05 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image14 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #8FA7DF;
}
.home-image15 {
  object-fit: cover;
}
.home-content07 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption05 {
  font-style: normal;
  font-weight: 600;
}
.home-title2 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-card06 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image16 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #9DDADB;
}
.home-image17 {
  object-fit: cover;
}
.home-content08 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption06 {
  font-style: normal;
  font-weight: 600;
}
.home-title3 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-card07 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image18 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #9FD8E5;
}
.home-image19 {
  object-fit: cover;
}
.home-content09 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption07 {
  font-style: normal;
  font-weight: 600;
}
.home-title4 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-card08 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image20 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #EC7495;
}
.home-image21 {
  object-fit: cover;
}
.home-content10 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption08 {
  font-style: normal;
  font-weight: 600;
}
.home-title5 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-card09 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image22 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #FFCF77;
}
.home-image23 {
  object-fit: cover;
}
.home-content11 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption09 {
  font-style: normal;
  font-weight: 600;
}
.home-title6 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-card10 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  background-color: #ffffff;
}
.home-image24 {
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-left: var(--dl-space-space-oneandhalfunits);
  padding-right: var(--dl-space-space-oneandhalfunits);
  flex-direction: column;
  justify-content: center;
  background-color: #FDEA6B;
}
.home-image25 {
  object-fit: cover;
}
.home-content12 {
  gap: var(--dl-space-space-halfunit);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: flex-start;
  flex-direction: column;
}
.home-caption10 {
  font-style: normal;
  font-weight: 600;
}
.home-title7 {
  font-size: 20px;
  font-style: normal;
  font-weight: 500;
  line-height: 24px;
}
.home-view2 {
  width: 100%;
  text-align: center;
}
.home-project {
  gap: 120px;
  width: 100%;
  display: flex;
  max-width: 1440px;
  align-items: center;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: 160px;
}
.home-understand {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-content13 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-caption11 {
  color: rgb(255, 207, 119);
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.home-heading05 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header06 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
}
.home-header07 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-view3 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  margin-top: var(--dl-space-space-fourunits);
  text-align: left;
  align-items: center;
  flex-direction: row;
}
.home-image26 {
  width: 25px;
  object-fit: cover;
}
.home-image27 {
  width: 480px;
  object-fit: cover;
}
.home-mining {
  gap: 130px;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.home-image28 {
  width: 510px;
  object-fit: cover;
}
.home-content14 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-caption12 {
  color: rgb(255, 207, 119);
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.home-heading06 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header08 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
}
.home-header09 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-view4 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  text-align: left;
  align-items: center;
  flex-direction: row;
}
.home-image29 {
  width: 25px;
  object-fit: cover;
}
.home-roadmap {
  gap: var(--dl-space-space-fiveunits);
  width: 100%;
  display: flex;
  max-width: 1440px;
  align-items: center;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: 120px;
}
.home-heading07 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: center;
  flex-direction: column;
}
.home-header10 {
  color: rgb(255, 255, 255);
  font-size: 90px;
  max-width: 900px;
  font-style: normal;
  font-weight: 500;
  line-height: 108px;
}
.home-header11 {
  color: rgb(255, 255, 255);
  font-size: 24px;
  text-align: center;
  line-height: 36px;
}
.home-list2 {
  gap: 106px;
  width: 100%;
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-threeunits);
  border-color: rgba(255, 255, 255, 0.3);
  padding-left: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-threeunits);
  border-left-width: 1px;
}
.home-step {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-caption13 {
  color: rgb(255, 207, 119);
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.home-heading08 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header12 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  font-weight: 500;
}
.home-header13 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-button6 {
  margin-top: var(--dl-space-space-oneandhalfunits);
}
.home-step1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-caption14 {
  color: rgb(255, 207, 119);
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.home-heading09 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header14 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  font-weight: 500;
}
.home-header15 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-step2 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-caption15 {
  color: rgb(255, 207, 119);
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.home-heading10 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header16 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  font-weight: 500;
}
.home-header17 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-step3 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-caption16 {
  color: rgb(255, 207, 119);
  font-style: normal;
  font-weight: 500;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.home-heading11 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: 640px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header18 {
  color: rgb(255, 255, 255);
  font-size: 72px;
  font-style: normal;
  font-weight: 500;
}
.home-header19 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  line-height: 27px;
}
.home-benefits {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-item {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-image30 {
  width: 16px;
  object-fit: cover;
}
.home-header20 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: 27px;
}
.home-item1 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-image31 {
  width: 16px;
  object-fit: cover;
}
.home-header21 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: 27px;
}
.home-item2 {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-image32 {
  width: 20px;
  object-fit: cover;
}
.home-header22 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  font-style: normal;
  font-weight: 500;
  line-height: 27px;
}
.home-join-us {
  width: 100%;
  display: flex;
  max-width: 1440px;
  align-items: center;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: 160px;
}
.home-content15 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  overflow: hidden;
  align-items: center;
  padding-top: var(--dl-space-space-fiveunits);
  flex-direction: column;
  background-color: #FFCF77;
}
.home-main5 {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-heading12 {
  gap: var(--dl-space-space-twounits);
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-header23 {
  font-size: 90px;
  max-width: 900px;
  font-style: normal;
  text-align: center;
  font-weight: 500;
  line-height: 108px;
}
.home-caption17 {
  font-size: 24px;
  max-width: 800px;
  line-height: 36px;
}
.home-view5 {
  background-color: #9DDADB;
}
.home-image33 {
  width: 100%;
  object-fit: cover;
}
.home-faq {
  gap: var(--dl-space-space-fiveunits);
  display: flex;
  align-items: center;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: column;
  padding-bottom: 160px;
}
.home-header24 {
  color: rgb(255, 255, 255);
  font-size: 90px;
  max-width: 900px;
  font-style: normal;
  text-align: center;
  font-weight: 500;
  line-height: 108px;
}
.home-accordion {
  width: 100%;
  display: flex;
  position: relative;
  max-width: 900px;
  align-items: center;
  flex-direction: column;
}
.home-element {
  align-items: flex-start;
  padding-top: var(--dl-space-space-threeunits);
  border-color: rgba(255, 255, 255, 0.3);
  padding-bottom: var(--dl-space-space-threeunits);
  border-top-width: 1px;
}
.home-content16 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: 800px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header25 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  font-style: normal;
  font-weight: 500;
  padding-right: var(--dl-space-space-oneandhalfunits);
}
.home-description05 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  max-width: 800px;
  line-height: 27px;
}
.home-icon-container {
  padding-top: var(--dl-space-space-halfunit);
}
.home-icon10 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
  display: none;
}
.home-icon12 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
}
.home-element1 {
  align-items: flex-start;
  padding-top: var(--dl-space-space-threeunits);
  border-color: rgba(255, 255, 255, 0.3);
  padding-bottom: var(--dl-space-space-threeunits);
}
.home-content17 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: 800px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header26 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  padding-right: var(--dl-space-space-oneandhalfunits);
}
.home-description06 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  max-width: 800px;
  line-height: 27px;
}
.home-icon-container1 {
  padding-top: var(--dl-space-space-halfunit);
}
.home-icon14 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
  display: none;
}
.home-icon16 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
}
.home-element2 {
  align-items: flex-start;
  padding-top: var(--dl-space-space-threeunits);
  border-color: rgba(255, 255, 255, 0.3);
  padding-bottom: var(--dl-space-space-threeunits);
}
.home-content18 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: 800px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header27 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  padding-right: var(--dl-space-space-oneandhalfunits);
}
.home-description07 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  max-width: 800px;
  line-height: 27px;
}
.home-icon-container2 {
  padding-top: var(--dl-space-space-halfunit);
}
.home-icon18 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
  display: none;
}
.home-icon20 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
}
.home-element3 {
  align-items: flex-start;
  padding-top: var(--dl-space-space-threeunits);
  border-color: rgba(255, 255, 255, 0.3);
  padding-bottom: var(--dl-space-space-threeunits);
}
.home-content19 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: 800px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header28 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  padding-right: var(--dl-space-space-oneandhalfunits);
}
.home-description08 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  max-width: 800px;
  line-height: 27px;
}
.home-icon-container3 {
  padding-top: var(--dl-space-space-halfunit);
}
.home-icon22 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
  display: none;
}
.home-icon24 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
}
.home-element4 {
  align-items: flex-start;
  padding-top: var(--dl-space-space-threeunits);
  border-color: rgba(255, 255, 255, 0.3);
  padding-bottom: var(--dl-space-space-threeunits);
}
.home-content20 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  max-width: 800px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header29 {
  color: rgb(255, 255, 255);
  font-size: 32px;
  padding-right: var(--dl-space-space-oneandhalfunits);
}
.home-description09 {
  color: rgb(255, 255, 255);
  font-size: 18px;
  max-width: 800px;
  line-height: 27px;
}
.home-icon-container4 {
  padding-top: var(--dl-space-space-halfunit);
}
.home-icon26 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
  display: none;
}
.home-icon28 {
  fill: #ffffff;
  width: 16px;
  height: 16px;
}
.home-get-yours {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  height: 555px;
  display: flex;
  max-width: 1440px;
  padding-left: var(--dl-space-space-fiveunits);
  padding-right: var(--dl-space-space-fiveunits);
  flex-direction: row;
}
.home-row2 {
  gap: var(--dl-space-space-threeunits);
  height: 100%;
  display: flex;
  flex-direction: row;
}
.home-column {
  height: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.home-card11 {
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: center;
  flex-direction: column;
  background-color: #FFCF77;
}
.home-image34 {
  width: 240px;
  object-fit: cover;
}
.home-column1 {
  height: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-end;
}
.home-card12 {
  display: flex;
  padding: var(--dl-space-space-oneandhalfunits);
  align-items: center;
  flex-direction: column;
  background-color: #000000;
}
.home-image35 {
  width: 240px;
  object-fit: cover;
}
.home-column2 {
  flex: 1;
  height: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-card13 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  padding: var(--dl-space-space-fourunits);
  align-items: flex-start;
  flex-direction: column;
  background-color: #8FA7DF;
}
.home-content21 {
  gap: var(--dl-space-space-unit);
  width: 100%;
  display: flex;
  max-width: 460px;
  align-items: flex-start;
  flex-direction: column;
}
.home-header30 {
  color: rgb(0, 0, 0);
  font-size: 52px;
  font-style: normal;
  font-weight: 500;
}
.home-description10 {
  color: rgb(0, 0, 0);
  width: 100%;
  font-size: 18px;
  max-width: 500px;
  line-height: 27px;
}
.home-button7 {
  margin-top: var(--dl-space-space-oneandhalfunits);
}
.home-thq-dropdown {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.home-dropdown-toggle {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius2);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.home-text29 {
  font-size: 14px;
  font-style: normal;
  text-align: center;
  font-weight: 500;
  margin-right: 4px;
  vertical-align: middle;
}
.home-dropdown-arrow {
  transition: 0.3s;
}
.home-icon30 {
  width: 18px;
  height: 18px;
  margin-top: auto;
  transition: 0.3s;
  margin-bottom: auto;
}
.home-dropdown-list {
  left: 0%;
  width: max-content;
  display: none;
  z-index: 100;
  position: absolute;
  min-width: 100%;
  transition: 0.3s;
  align-items: stretch;
  border-color: #D9D9D9;
  border-width: 1px;
  border-radius: var(--dl-radius-radius-radius4);
  flex-direction: column;
  list-style-type: none;
  background-color: var(--dl-color-gray-white);
  list-style-position: inside;
}
.home-dropdown {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.home-dropdown-toggle1 {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.home-dropdown-toggle1:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.home-text30 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
}
.home-dropdown1 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.home-dropdown-toggle2 {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.home-dropdown-toggle2:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.home-text31 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
}
.home-dropdown2 {
  cursor: pointer;
  display: inline-block;
  position: relative;
  border-radius: var(--dl-radius-radius-radius2);
}
.home-dropdown-toggle3 {
  fill: #595959;
  color: #595959;
  width: 100%;
  display: inline-flex;
  transition: 0.3s;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  padding-left: var(--dl-space-space-unit);
  border-radius: var(--dl-radius-radius-radius4);
  padding-right: var(--dl-space-space-unit);
  padding-bottom: var(--dl-space-space-halfunit);
}
.home-dropdown-toggle3:hover {
  fill: #fff;
  color: #fff;
  background-color: #595959;
}
.home-text32 {
  width: 100%;
  cursor: pointer;
  display: flex;
  font-size: 14px;
  font-style: normal;
  font-weight: 500;
}
.home-navbar-interactive {
  width: 100%;
  display: flex;
  position: relative;
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  padding-bottom: var(--dl-space-space-twounits);
  justify-content: space-between;
}
.home-logo3 {
  height: 2rem;
}
.home-desktop-menu1 {
  display: flex;
}
.home-nav3 {
  flex: 0 0 auto;
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-text34 {
  margin-left: var(--dl-space-space-twounits);
}
.home-text35 {
  margin-left: var(--dl-space-space-twounits);
}
.home-text36 {
  margin-left: var(--dl-space-space-twounits);
}
.home-text37 {
  margin-left: var(--dl-space-space-twounits);
}
.home-btn-group1 {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.home-login1 {
  border-width: 0px;
  margin-right: var(--dl-space-space-twounits);
}
.home-burger-menu1 {
  display: none;
  align-items: center;
  justify-content: center;
}
.home-icon32 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-mobile-menu1 {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: none;
  padding: 32px;
  z-index: 100;
  position: fixed;
  flex-direction: column;
  justify-content: space-between;
  background-color: #fff;
}
.home-nav4 {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-container4 {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.home-image36 {
  height: 2rem;
}
.home-menu-close1 {
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-icon34 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
.home-nav5 {
  flex: 0 0 auto;
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.home-text38 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text39 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text40 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text41 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-text42 {
  margin-bottom: var(--dl-space-space-unit);
}
.home-container5 {
  flex: 0 0 auto;
  width: auto;
  display: flex;
  margin-top: var(--dl-space-space-unit);
  align-items: center;
  flex-direction: row;
}
.home-login2 {
  margin-right: var(--dl-space-space-twounits);
}
.home-icon-group1 {
  display: flex;
}
.home-icon36 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon38 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.home-icon40 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}
@media(max-width: 991px) {
  .home-desktop-menu {
    display: none;
  }
  .home-btn-group {
    display: none;
  }
  .home-burger-menu {
    display: flex;
  }
  .home-button5 {
    display: flex;
    padding: var(--dl-space-space-unit);
    flex-direction: row;
  }
  .home-logo1 {
    color: #000000;
  }
  .home-row {
    flex-direction: column;
  }
  .home-card {
    width: 100%;
  }
  .home-card01 {
    width: 100%;
  }
  .home-row1 {
    flex-direction: column;
  }
  .home-main4 {
    grid-template-columns: repeat(2, 1fr);
  }
  .home-project {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .home-understand {
    align-items: center;
    flex-direction: column;
  }
  .home-mining {
    flex-direction: column-reverse;
  }
  .home-heading12 {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-caption17 {
    text-align: center;
  }
  .home-get-yours {
    height: auto;
    align-items: center;
    flex-direction: column;
  }
  .home-row2 {
    gap: var(--dl-space-space-threeunits);
    width: 100%;
    height: 555px;
    align-items: center;
    justify-content: center;
  }
  .home-column {
    flex: 1;
    align-items: flex-start;
  }
  .home-card11 {
    width: 100%;
    aspect-ratio: 0.85;
    justify-content: center;
  }
  .home-column1 {
    flex: 1;
    align-items: flex-end;
  }
  .home-card12 {
    width: 100%;
    aspect-ratio: 0.85;
  }
  .home-column2 {
    width: 100%;
  }
}
@media(max-width: 767px) {
  .home-navbar {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-hero {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-heading {
    gap: var(--dl-space-space-unit);
  }
  .home-header {
    font-size: 36px;
    max-width: 70%;
    line-height: 43px;
  }
  .home-footer {
    gap: var(--dl-space-space-oneandhalfunits);
    padding-top: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-main {
    gap: var(--dl-space-space-threeunits);
    flex-direction: column;
    justify-content: flex-start;
  }
  .home-heading01 {
    gap: var(--dl-space-space-unit);
  }
  .home-logo2 {
    font-size: 20px;
    line-height: 24px;
  }
  .home-caption {
    width: 80%;
    font-size: 12px;
    line-height: 18px;
  }
  .home-socials1 {
    display: none;
  }
  .home-links {
    gap: var(--dl-space-space-fourunits);
    width: 100%;
    justify-content: flex-start;
  }
  .home-list {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-list1 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-socials2 {
    display: flex;
  }
  .home-caption01 {
    font-size: 16px;
    line-height: 24px;
  }
  .home-description {
    gap: var(--dl-space-space-threeunits);
    padding-bottom: 0px;
  }
  .home-description01 {
    gap: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-content {
    gap: var(--dl-space-space-unit);
  }
  .home-paragraph {
    font-size: 20px;
    line-height: 30px;
  }
  .home-paragraph1 {
    font-size: 20px;
    line-height: 30px;
  }
  .home-cards {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-card {
    gap: var(--dl-space-space-oneandhalfunits);
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-main1 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-header01 {
    font-size: 24px;
  }
  .home-description02 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-card01 {
    gap: var(--dl-space-space-oneandhalfunits);
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-main2 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-header02 {
    font-size: 24px;
  }
  .home-description03 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-card02 {
    gap: var(--dl-space-space-oneandhalfunits);
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-row1 {
    gap: var(--dl-space-space-twounits);
  }
  .home-main3 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-header03 {
    font-size: 24px;
  }
  .home-description04 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-collection {
    gap: var(--dl-space-space-fourunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-content04 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-heading04 {
    gap: var(--dl-space-space-unit);
  }
  .home-header04 {
    font-size: 32px;
    letter-spacing: 0;
  }
  .home-header05 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-image10 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-image12 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-image14 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-image16 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-image18 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-image20 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-image22 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-image24 {
    padding-left: 0px;
    padding-right: 0px;
  }
  .home-view2 {
    display: none;
  }
  .home-project {
    gap: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-sixunits);
  }
  .home-understand {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-content13 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-heading05 {
    gap: var(--dl-space-space-unit);
  }
  .home-header06 {
    font-size: 32px;
    letter-spacing: 0;
  }
  .home-header07 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-view3 {
    margin-top: var(--dl-space-space-unit);
  }
  .home-image27 {
    width: 100%;
  }
  .home-mining {
    gap: var(--dl-space-space-fourunits);
  }
  .home-image28 {
    width: 100%;
  }
  .home-content14 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-heading06 {
    gap: var(--dl-space-space-unit);
  }
  .home-header08 {
    font-size: 32px;
    letter-spacing: 0;
  }
  .home-header09 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-view4 {
    margin-top: var(--dl-space-space-unit);
  }
  .home-roadmap {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-heading07 {
    gap: var(--dl-space-space-unit);
  }
  .home-header10 {
    font-size: 36px;
    line-height: 43px;
  }
  .home-header11 {
    width: 80%;
    font-size: 16px;
    line-height: 24px;
  }
  .home-list2 {
    gap: var(--dl-space-space-threeunits);
    padding-top: 0px;
    padding-left: var(--dl-space-space-unit);
    padding-bottom: 0px;
  }
  .home-heading08 {
    gap: var(--dl-space-space-unit);
  }
  .home-header12 {
    font-size: 32px;
  }
  .home-header13 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-button6 {
    margin-top: 0px;
  }
  .home-heading09 {
    gap: var(--dl-space-space-unit);
  }
  .home-header14 {
    font-size: 32px;
  }
  .home-header15 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-heading10 {
    gap: var(--dl-space-space-unit);
  }
  .home-header16 {
    font-size: 32px;
  }
  .home-header17 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-heading11 {
    gap: var(--dl-space-space-oneandhalfunits);
  }
  .home-header18 {
    font-size: 32px;
  }
  .home-header19 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-header20 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-header21 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-image32 {
    width: 17px;
  }
  .home-header22 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-join-us {
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-content15 {
    padding-top: var(--dl-space-space-threeunits);
  }
  .home-main5 {
    gap: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-heading12 {
    gap: var(--dl-space-space-unit);
  }
  .home-header23 {
    font-size: 36px;
    line-height: 43px;
  }
  .home-caption17 {
    font-size: 16px;
    line-height: 24px;
  }
  .home-image33 {
    width: 150%;
  }
  .home-faq {
    gap: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-fourunits);
  }
  .home-header24 {
    font-size: 36px;
    line-height: 43px;
  }
  .home-element {
    align-items: flex-start;
    padding-top: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-header25 {
    font-size: 16px;
  }
  .home-description05 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-element1 {
    align-items: flex-start;
    padding-top: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-header26 {
    font-size: 16px;
  }
  .home-description06 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-element2 {
    align-items: flex-start;
    padding-top: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-header27 {
    font-size: 16px;
  }
  .home-description07 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-element3 {
    align-items: flex-start;
    padding-top: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-header28 {
    font-size: 16px;
  }
  .home-description08 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-element4 {
    align-items: flex-start;
    padding-top: var(--dl-space-space-oneandhalfunits);
    padding-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .home-header29 {
    font-size: 16px;
  }
  .home-description09 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-get-yours {
    gap: var(--dl-space-space-oneandhalfunits);
    padding-left: var(--dl-space-space-oneandhalfunits);
    padding-right: var(--dl-space-space-oneandhalfunits);
  }
  .home-row2 {
    gap: var(--dl-space-space-oneandhalfunits);
    height: 555px;
  }
  .home-card11 {
    padding: var(--dl-space-space-unit);
  }
  .home-image34 {
    width: 100%;
  }
  .home-card12 {
    padding: var(--dl-space-space-unit);
  }
  .home-image35 {
    width: 100%;
  }
  .home-card13 {
    gap: var(--dl-space-space-threeunits);
    align-items: center;
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-content21 {
    align-items: center;
  }
  .home-header30 {
    font-size: 32px;
    text-align: center;
  }
  .home-description10 {
    font-size: 14px;
    text-align: center;
    line-height: 21px;
  }
  .home-button7 {
    margin-top: 0px;
  }
  .home-navbar-interactive {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-desktop-menu1 {
    display: none;
  }
  .home-text34 {
    margin-left: var(--dl-space-space-unit);
  }
  .home-text35 {
    margin-left: var(--dl-space-space-unit);
  }
  .home-text36 {
    margin-left: var(--dl-space-space-unit);
  }
  .home-text37 {
    margin-left: var(--dl-space-space-unit);
  }
  .home-btn-group1 {
    display: none;
  }
  .home-burger-menu1 {
    display: flex;
  }
}
@media(max-width: 479px) {
  .home-navbar {
    padding: var(--dl-space-space-unit);
  }
  .home-mobile-menu {
    padding: 16px;
  }
  .home-main4 {
    grid-template-columns: repeat(1, 1fr);
  }
  .home-image33 {
    width: 200%;
  }
  .home-header25 {
    font-size: 16px;
  }
  .home-description05 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-header26 {
    font-size: 16px;
  }
  .home-description06 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-header27 {
    font-size: 16px;
  }
  .home-description07 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-header28 {
    font-size: 16px;
  }
  .home-description08 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-header29 {
    font-size: 16px;
  }
  .home-description09 {
    font-size: 14px;
    line-height: 21px;
  }
  .home-row2 {
    height: 350px;
  }
  .home-navbar-interactive {
    padding: var(--dl-space-space-unit);
  }
  .home-mobile-menu1 {
    padding: 16px;
  }
}
</style>
