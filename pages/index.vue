<template>
  <div>
    <!-- nav and banner -->
    <div class="banner">
      <!-- nav -->
      <div class="animate__animated animate__bounceIn">
        <b-navbar class="mx-lg-5" toggleable="lg" variant="transparent">
          <b-navbar-brand href="#">
            <img src="~assets/images/logo.png" alt="" />
          </b-navbar-brand>

          <b-navbar-toggle target="nav-collapse">
            <i class="fas fa-bars text-white fs-3"></i>
          </b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="ms-auto">
              <b-nav-item class="mx-2" href="#home">Home</b-nav-item>
              <b-nav-item class="mx-2" href="#mission">Mission</b-nav-item>
              <b-nav-item class="mx-2" href="#about">About us</b-nav-item>
              <b-nav-item class="mx-2" href="#roadmap">Roadmap</b-nav-item>
              <b-nav-item class="mx-2" href="#nodes">Nodes</b-nav-item>
              <b-nav-item class="mx-2" href="#faq">FAQ</b-nav-item>
              <button class="launch_btn mx-2">Launch App</button>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>

      <!-- banner -->
      <div id="home">
        <div class="mx-3 mx-lg-5 ban_content">
          <div
            class="banner_side_img col-12 text-center animate__animated animate__pulse animate__infinite"
          >
            <img src="~assets/images/banner hero.png" class="mount_img"  alt="" />
          </div>
          <div
            class="col-12 text-center mt-3 animate__animated animate__bounceInDown"
          >
            <p class="ban_head mb-0">
              Mine at a deeper level for the most
              <br class="d-lg-block d-md-block d-none" />
              precious stones
            </p>
            <p class="text-center">
              Enjoy daily rewards and perks powered by GameFi on AVALANCHE.
            </p>
            <div class="whitepaper">
              <button class="launch_btn px-3 me-3">Download Whitepaper</button>
              <div>
                <i class="fab fa-twitter text-white fs-4 m-3"></i>
                <i class="fab fa-discord text-white fs-4 m-3"></i>
                <!-- <i class="fas fa-paper-plane text-white fs-4 m-3"></i> -->
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- coins -->
      <div class="banner_coins mx-3">
        <img width="100%" src="~assets/images/coins1.png" alt="" />
      </div>
    </div>

    <!-- mission -->
    <div class="mission py-0 py-lg-5" id="mission">
      <div class="mission_top_coins mx-3">
        <img width="100%" src="~assets/images/coins2.png" alt="" />
      </div>
      <div class="mx-3 mx-lg-5 mission_content py-5">
        <div
          class="mission_side_img text-center col-12 col-lg-5 animate__animated animate__pulse animate__infinite"
        >
          <img src="~assets/images/mission_hero.png" alt="" />
        </div>
        <div
          class="col-12 col-lg-5 text-center text-lg-start animate__animated animate__fadeInUp"
        >
          <img width="55px" src="~assets/images/blue_diamond.png" alt="" />
          <p class="fs-2 mission_head">Our Mission</p>
          <p class="mission_para">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. It was popularised in the 1960s
            with the release of Letraset sheets containing Lorem Ipsum passages,
            and more recently with desktop publishing software like Aldus
            PageMaker including versions of Lorem Ipsum.
          </p>
        </div>
      </div>
      <div
        class="mission_bottom_coins mx-3 animate__animated animate__fadeInUpBig"
      >
        <img width="100%" src="~assets/images/coins3.png" alt="" />
      </div>
    </div>

    <!-- That’s why we are -->
    <div class="reason_for_here my-5 pt-0 pt-lg-5">
      <img height="45px" src="~assets/images/red_diamond.png" alt="" />
      <p class="fs-3 reason_head">That’s why we are</p>
      <div class="mt-5 reason_cards">
        <div class="card_left_shadow">
          <img src="~assets/images/left_shadow.png" alt="" />
        </div>
        <div class="reason_torch_card animate__animated animate__flipInX">
          <div class="reason_card m-3">
            <img width="70px" src="~assets/images/transparency.png" alt="" />
            <p class="fw-bold fs-4 mb-0 mt-4 pt-2">Transparancy</p>
            <img
              src="~assets/images/border.png"
              alt=""
              style="margin-top: -20px"
            />
            <p class="reason_card_text mb-0">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy
            </p>
          </div>
          <div class="fire_torch_left">
            <img src="~assets/images/fire_torch1.png" alt="" />
          </div>
        </div>
        <div class="reason_card m-3">
          <img width="80px" src="~assets/images/decentralize.png" alt="" />
          <p class="fw-bold fs-4 mb-0 mt-4">Decentralization</p>
          <img
            src="~assets/images/border.png"
            alt=""
            style="margin-top: -20px"
          />
          <p class="reason_card_text mb-0">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy
          </p>
        </div>
        <div class="reason_torch_card">
          <div class="reason_card m-3">
            <img src="~assets/images/community.png" alt="" />
            <p class="fw-bold fs-4 mb-0 mt-5 pt-1">Community Driven</p>
            <img
              src="~assets/images/border.png"
              alt=""
              style="margin-top: -20px"
            />
            <p class="reason_card_text mb-0">
              Lorem Ipsum is simply dummy text of the printing and typesetting
              industry. Lorem Ipsum has been the industry's standard dummy
            </p>
          </div>
          <div class="fire_torch_right">
            <img src="~assets/images/fire_torch2.png" alt="" />
          </div>
        </div>
        <div class="card_right_shadow">
          <img src="~assets/images/right_shadow.png" alt="" />
        </div>
      </div>
    </div>

    <!-- about -->
    <div class="about_bg" id="about">
      <div class="mission_content mx-3 mx-lg-5 mt-5 mt-lg-0 pt-5 pt-lg-0">
        <div class="col-12 col-lg-5 text-center text-lg-start">
          <img width="55px" src="~assets/images/yellow_diamond.png" alt="" />
          <p class="fs-2 mission_head">The Minernode Financial Reward System</p>
          <p class="mission_para">
            Lorem Ipsum is simply dummy text of the printing and typesetting
            industry. Lorem Ipsum has been the industry's standard dummy text
            ever since the 1500s, when an unknown printer took a galley of type
            and scrambled it to make a type specimen book. It has survived not
            only five centuries, but also the leap into electronic typesetting,
            remaining essentially unchanged. It was popularised in the 1960s
            with the release of Letraset sheets containing Lorem Ipsum passages,
            and more recently with desktop publishing software like Aldus
            PageMaker including versions of Lorem Ipsum.
          </p>
        </div>
        <div
          class="mission_side_img text-center col-12 col-lg-5 animate__animated animate__pulse animate__infinite"
        >
          <img src="~assets/images/about_hero.png" alt="" />
        </div>
      </div>
    </div>

    <!-- roadmap -->
    <div class="roadmap mt-5 mt-lg-0" id="roadmap">
      <img width="45px" src="~assets/images/purple_diamond.png" alt="" />
      <p class="fs-3 mission_head">Roadmap</p>
      <div class="roadmap_content">
        <div class="roadmap_row my-2 road1">
          <div class="col-0 col-md-0 col-lg-6"></div>
          <div
            class="col-12 col-md-0 col-lg-6 d-flex justify-content-center align-items-center"
          >
            <div class="roadmap_card">
              <img src="~assets/images/road_head1.png" alt="" />
              <p class="fw-bolder fs-5 mb-2">Heading 1</p>
              <p class="mb-0 text-start roadmap_para">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s.
              </p>
            </div>
          </div>
        </div>
        <div class="roadmap_row my-2">
          <div
            class="col-12 col-md-0 col-lg-6 d-flex justify-content-center align-items-center"
          >
            <div class="roadmap_card">
              <img src="~assets/images/road_head2.png" alt="" />
              <p class="fw-bolder fs-5 mb-2">Heading 1</p>
              <p class="mb-0 text-start roadmap_para">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s.
              </p>
            </div>
          </div>
          <div class="col-0 col-md-0 col-lg-6"></div>
        </div>
        <div class="roadmap_row my-2">
          <div class="col-0 col-md-0 col-lg-6"></div>
          <div
            class="col-12 col-md-0 col-lg-6 d-flex justify-content-center align-items-center"
          >
            <div class="roadmap_card">
              <img src="~assets/images/road_head3.png" alt="" />
              <p class="fw-bolder fs-5 mb-2">Heading 1</p>
              <p class="mb-0 text-start roadmap_para">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s.
              </p>
            </div>
          </div>
        </div>
        <div class="roadmap_row my-2">
          <div
            class="col-12 col-md-0 col-lg-6 d-flex justify-content-center align-items-center"
          >
            <div class="roadmap_card">
              <img src="~assets/images/road_head4.png" alt="" />
              <p class="fw-bolder fs-5 mb-2">Heading 1</p>
              <p class="mb-0 text-start roadmap_para">
                Lorem Ipsum is simply dummy text of the printing and typesetting
                industry. Lorem Ipsum has been the industry's standard dummy
                text ever since the 1500s.
              </p>
            </div>
          </div>
          <div class="col-0 col-md-0 col-lg-6"></div>
        </div>
        <div class="roadmap_train d-none d-md-none d-lg-block">
          <img src="~assets/images/roadmap_hero.png" alt="" />
        </div>
        <div class="roadmap_bottom">
          <img width="100%" src="~assets/images/roadmap_bottom.png" alt="" />
        </div>
      </div>
      <img class="axe1" src="~assets/images/axe1.png" alt="" />
      <img class="axe2" src="~assets/images/axe2.png" alt="" />
      <img
        class="axe3 d-none d-md-block d-lg-block"
        src="~assets/images/axe3.png"
        alt=""
      />
      <img
        class="axe4 d-none d-md-block d-lg-block"
        src="~assets/images/axe4.png"
        alt=""
      />
    </div>

    <!-- nodes -->
    <div class="nodes mt-5 pt-5" id="nodes">
      <img width="45px" src="~assets/images/yellow_diamond2.png" alt="" />
      <p class="fs-3 mission_head">Miner Nodes</p>
      <div class="all_nodes mx-3 mx-lg-5 mt-5">
        <div class="node_card m-3">
          <img width="220px" src="~assets/images/node1.png" alt="" />
          <p class="mb-2 fw-bolder fs-5">2.5 GEM</p>
          <p class="mb-2 fw-bold text-warning">Earn 0.15 per day</p>
          <p class="mb-2 text-muted">0.6% Daily</p>
        </div>
        <div class="node_card m-3">
          <img width="220px" src="~assets/images/node2.png" alt="" />
          <p class="mb-2 fw-bolder fs-5">2.5 GEM</p>
          <p class="mb-2 fw-bold text-warning">Earn 0.15 per day</p>
          <p class="mb-2 text-muted">0.6% Daily</p>
        </div>
        <div class="node_card m-3">
          <img width="220px" src="~assets/images/node3.png" alt="" />
          <p class="mb-2 fw-bolder fs-5">2.5 GEM</p>
          <p class="mb-2 fw-bold text-warning">Earn 0.15 per day</p>
          <p class="mb-2 text-muted">0.6% Daily</p>
        </div>
        <div class="node_card m-3">
          <img width="220px" src="~assets/images/node4.png" alt="" />
          <p class="mb-2 fw-bolder fs-5">2.5 GEM</p>
          <p class="mb-2 fw-bold text-warning">Earn 0.15 per day</p>
          <p class="mb-2 text-muted">0.6% Daily</p>
        </div>
      </div>
      <div class="card_left_shadow">
        <img src="~assets/images/left_shadow.png" alt="" />
      </div>
      <div class="card_right_shadow">
        <img src="~assets/images/right_shadow.png" alt="" />
      </div>
    </div>

    <!-- lucky box -->
    <div class="lucky_box mt-5">
      <img width="50px" src="~assets/images/green_diamond.png" alt="" />
      <p class="fs-3 mission_head">Tokenomics</p>
      <div class="container">
        <div class="Tokenomics_sec p-5">
          <div class="row">
            <div class="col-12">
              <div class="p-5 text-center">
                <h5>What is the supply of Spring Game ?</h5>
                <p class="mt-3 fw-light">
                  There is a total of 2,500,000 $SPRING in circulation.
                  350,000<br class="d-lg-block d-md-block d-none" />
                  tokens are sent to the LP to provide liquidity. The other
                  are<br class="d-lg-block d-md-block d-none" />
                  held in the Game Rewards Pool wallet to be distributed to<br
                    class="d-lg-block d-md-block d-none"
                  />
                  users.
                </p>
                <h5>Where do my tokens go when a NFT is created?</h5>
                <p class="mt-3 fw-light">
                  The breakdown of the token distribution is as follows:
                </p>
              </div>
              <div class="d-flex justify-content-center">
                <div class="mx-3 text-center">
                  <h3 class="fw-bolder">8%</h3>
                  <p class="fw-light">Liquidity Pool</p>
                </div>
                <div class="mx-3 text-center">
                  <h3 class="fw-bolder">14%</h3>
                  <p class="fw-light">Treasury Wallet</p>
                </div>
                <div class="mx-3 text-center">
                  <h3 class="fw-bolder">68%</h3>
                  <p class="fw-light">Rewards Pool</p>
                </div>
                <div class="mx-3 text-center">
                  <h3 class="fw-bolder">10%</h3>
                  <p class="fw-light">Miner Team</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="boxes mx-3 mx-lg-5 w-100 mt-5">
        <img class="m-3" src="~assets/images/lucky_box1.png" alt="" />
        <img class="m-3" src="~assets/images/lucky_box2.png" alt="" />
        <img class="m-3" src="~assets/images/lucky_box3.png" alt="" />
        <img class="m-3" src="~assets/images/lucky_box4.png" alt="" />
      </div> -->
    </div>

    <!-- faqs -->
    <div class="faqs mt-5" id="faq">
      <img width="50px" src="~assets/images/light_purple_diamond.png" alt="" />
      <p class="fs-3 mission_head">FREQUENTLY ASKED QUESTIONS</p>
      <div class="accordion mx-3 mx-lg-5 mt-5" role="tablist">
        <div class="accordian_row">
          <div class="col-12 col-md-6 col-lg-6 p-3">
            <b-card no-body class="mb-1">
              <b-card-header
                header-tag="header"
                class="p-0 accordian_header"
                role="tab"
              >
                <b-button
                  block
                  v-b-toggle.accordion-1
                  class="w-100 text-start fw-bold d-flex justify-content-between align-items-center"
                  variant="transparent"
                  >Lorem Ipsum is simply dummy text?
                  <i class="fas fa-plus-circle"></i
                ></b-button>
              </b-card-header>
              <b-collapse
                id="accordion-1"
                visible
                accordion="my-accordion"
                role="tabpanel"
              >
                <b-card-body class="accordian_body">
                  <b-card-text class="accordian_text text-start">{{
                    text
                  }}</b-card-text>
                </b-card-body>
              </b-collapse>
            </b-card>
          </div>
          <div class="col-12 col-md-6 col-lg-6 p-3">
            <b-card no-body class="mb-1">
              <b-card-header
                header-tag="header"
                class="p-0 accordian_header"
                role="tab"
              >
                <b-button
                  block
                  v-b-toggle.accordion-2
                  class="w-100 text-start fw-bold d-flex justify-content-between align-items-center"
                  variant="transparent"
                  >Lorem Ipsum is simply dummy text?
                  <i class="fas fa-plus-circle"></i
                ></b-button>
              </b-card-header>
              <b-collapse
                id="accordion-2"
                visible
                accordion="my-accordion"
                role="tabpanel"
              >
                <b-card-body class="accordian_body">
                  <b-card-text class="accordian_text text-start">{{
                    text
                  }}</b-card-text>
                </b-card-body>
              </b-collapse>
            </b-card>
          </div>
        </div>
        <div class="accordian_row">
          <div class="col-12 col-md-6 col-lg-6 p-3">
            <b-card no-body class="mb-1">
              <b-card-header
                header-tag="header"
                class="p-0 accordian_header"
                role="tab"
              >
                <b-button
                  block
                  v-b-toggle.accordion-3
                  class="w-100 text-start fw-bold d-flex justify-content-between align-items-center"
                  variant="transparent"
                  >Lorem Ipsum is simply dummy text?
                  <i class="fas fa-plus-circle"></i
                ></b-button>
              </b-card-header>
              <b-collapse
                id="accordion-3"
                visible
                accordion="my-accordion"
                role="tabpanel"
              >
                <b-card-body class="accordian_body">
                  <b-card-text class="accordian_text text-start">{{
                    text
                  }}</b-card-text>
                </b-card-body>
              </b-collapse>
            </b-card>
          </div>
          <div class="col-12 col-md-6 col-lg-6 p-3">
            <b-card no-body class="mb-1">
              <b-card-header
                header-tag="header"
                class="p-0 accordian_header"
                role="tab"
              >
                <b-button
                  block
                  v-b-toggle.accordion-4
                  class="w-100 text-start fw-bold d-flex justify-content-between align-items-center"
                  variant="transparent"
                  >Lorem Ipsum is simply dummy text?
                  <i class="fas fa-plus-circle"></i
                ></b-button>
              </b-card-header>
              <b-collapse
                id="accordion-4"
                visible
                accordion="my-accordion"
                role="tabpanel"
              >
                <b-card-body class="accordian_body">
                  <b-card-text class="accordian_text text-start">{{
                    text
                  }}</b-card-text>
                </b-card-body>
              </b-collapse>
            </b-card>
          </div>
        </div>
        <div class="accordian_row">
          <div class="col-12 col-md-6 col-lg-6 p-3">
            <b-card no-body class="mb-1">
              <b-card-header
                header-tag="header"
                class="p-0 accordian_header"
                role="tab"
              >
                <b-button
                  block
                  v-b-toggle.accordion-5
                  class="w-100 text-start fw-bold d-flex justify-content-between align-items-center"
                  variant="transparent"
                  >Lorem Ipsum is simply dummy text?
                  <i class="fas fa-plus-circle"></i
                ></b-button>
              </b-card-header>
              <b-collapse
                id="accordion-5"
                visible
                accordion="my-accordion"
                role="tabpanel"
              >
                <b-card-body class="accordian_body">
                  <b-card-text class="accordian_text text-start">{{
                    text
                  }}</b-card-text>
                </b-card-body>
              </b-collapse>
            </b-card>
          </div>
          <div class="col-12 col-md-6 col-lg-6 p-3">
            <b-card no-body class="mb-1">
              <b-card-header
                header-tag="header"
                class="p-0 accordian_header"
                role="tab"
              >
                <b-button
                  block
                  v-b-toggle.accordion-6
                  class="w-100 text-start fw-bold d-flex justify-content-between align-items-center"
                  variant="transparent"
                  >Lorem Ipsum is simply dummy text?
                  <i class="fas fa-plus-circle"></i
                ></b-button>
              </b-card-header>
              <b-collapse
                id="accordion-6"
                visible
                accordion="my-accordion"
                role="tabpanel"
              >
                <b-card-body class="accordian_body">
                  <b-card-text class="accordian_text text-start">{{
                    text
                  }}</b-card-text>
                </b-card-body>
              </b-collapse>
            </b-card>
          </div>
        </div>
      </div>
    </div>

    <!-- footer -->
    <div class="footer px-3 px-lg-5">
      <img src="~assets/images/logo.png" alt="" />
      <p class="text-gray fs-5 fw-lighter mb-0 mt-2">Contact Us</p>
      <p class="">infor@minernodes.com</p>
      <div class="social_icons">
        <div class="icon m-2">
          <i class="fab fa-twitter fs-4"></i>
        </div>
        <div class="icon m-2">
          <i class="fab fa-instagram fs-4"></i>
        </div>
        <div class="icon m-2">
          <i class="fab fa-discord fs-4"></i>
        </div>
      </div>
      <div>
        <img width="100%" src="~assets/images/footer_line.png" alt="" />
      </div>
      <p class="mb-0 py-2">Copyright © 2021 . All rights reserved.</p>
    </div>
  </div>
</template>

<script>
import "animate.css";
export default {
  data() {
    return {
      text: `
          Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry
          richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor
          brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon
          tempor, sunt aliqua put a bird on it squid single-origin coffee nulla.
        `,
    };
  },
};
</script>
