<template>
  <!-- Top Menu 1 -->
  <section class="w3l-top-menu-1">
    <div class="top-hd">
      <div class="container">
        <header class="row">
          <div class="accounts col-sm-9 col-6">
            <li class="top_li">
              <span class="fa fa-mobile"></span
              ><a href="tel:+91 9817540044">+91 9817540044</a>
            </li>
            <li class="top_li1">
              <span class="fa fa-map-marker"></span> Gausala Road, Palam Vihar Extn., Krishna Chowk, Gurugram
            </li>
            <li class="top_li2">
              <span class="fa fa-clock-o"></span> Mon - Sun 24 hours
            </li>
          </div>
          <div class="social-top col-sm-3 col-6">
            <li>
              <a href="#"><span class="fa fa-facebook pr-2"></span></a>
            </li>
            <li>
              <a href="#"><span class="fa fa-instagram pr-2"></span></a>
            </li>
            <li>
              <a href="#"><span class="fa fa-twitter pr-2"></span></a>
            </li>
            <li>
              <a href="#"><span class="fa fa-vimeo"></span></a>
            </li>
          </div>
        </header>
      </div>
    </div>
  </section>
  <!-- //Top Menu 1 -->
  <section class="w3l-bootstrap-header">
    <nav class="navbar navbar-expand-lg navbar-light py-lg-2 py-2">
      <div class="container">
        <a class="navbar-brand" href="/"
          ><img class="navbar-logo" src="images/logo.png" alt=""
        /></a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon fa fa-bars"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mx-auto">
            <li class="nav-item">
              <a class="nav-link"
                ><router-link class="nav-link" to="/">Home</router-link></a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link"
                ><router-link class="nav-link" to="/about"
                  >About</router-link
                ></a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link"
                ><router-link class="nav-link" to="/services"
                  >Services</router-link
                ></a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link"
                ><router-link class="nav-link" to="/gallery"
                  >Gallery</router-link
                ></a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link"
                ><router-link class="nav-link" to="/contact"
                  >Contact</router-link
                ></a
              >
            </li>
          </ul>
          <form class="form-inline">
            <a class="btn btn-secondary btn-theme">
              <router-link class="text-white" to="/contact">
                Get a Quote</router-link
              >
            </a>
          </form>
        </div>
      </div>
    </nav>
  </section>
  <section class="form-12" id="home">
    <div class="form-12-content">
      <div class="container">
        <div class="grid grid-column-2">
          <div class="column2"></div>
          <div class="column1">
            <h3 class="tagline mb-3">Get a Free Moving Quote</h3>

            <form
              id="quotation-form"
              action="https://formsubmit.co/Fastandsafecargomoversncr@gamil.com"
              method="POST"
            >
              <div class="">
                <input
                  type="text"
                  name="From City"
                  class="form-input"
                  placeholder="From a City or Location"
                />
              </div>
              <div class="">
                <input
                  type="text"
                  name="To City"
                  class="form-input"
                  placeholder="To a City or Location"
                />
              </div>
              <div class="">
                <input
                  type="text"
                  name="name"
                  class="form-input"
                  placeholder="Your Name"
                  required
                />
              </div>
              <div class="">
                <input
                  type="email"
                  name="email"
                  id="form-email"
                  class="form-input"
                  placeholder="Email"
                  required
                />
              </div>
              <div class="">
                <input
                  type="tel"
                  name="phone"
                  class="form-input"
                  placeholder="Phone"
                  required
                />
              </div>
              <input type="hidden" name="_captcha" value="false" />
              <button type="submit" class="btn">Submit</button>
            </form>
            <div id="quotation-form-report"></div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <section class="w3l-features-1">
    <!-- /features -->
    <div class="features py-4">
      <div class="container">
        <div class="fea-gd-vv row">
          <div class="float-lt feature-gd col-lg-3 col-sm-6">
            <div class="icon">
              <span class="fa fa-truck" aria-hidden="true"></span>
            </div>
            <div class="icon-info">
              <h5>Free Estimate</h5>
            </div>
          </div>
          <div class="float-mid feature-gd col-lg-3 col-sm-6 mt-sm-0 mt-4">
            <div class="icon">
              <span class="fa fa-file-text-o" aria-hidden="true"></span>
            </div>
            <div class="icon-info">
              <h5>Flat Rates</h5>
            </div>
          </div>
          <div class="float-rt feature-gd col-lg-3 col-sm-6 mt-lg-0 mt-4">
            <div class="icon">
              <span class="fa fa-clone" aria-hidden="true"></span>
            </div>
            <div class="icon-info">
              <h5>Quick Delivery</h5>
            </div>
          </div>
          <div class="float-lt feature-gd col-lg-3 col-sm-6 mt-lg-0 mt-4">
            <div class="icon">
              <span class="fa fa-clock-o" aria-hidden="true"></span>
            </div>
            <div class="icon-info">
              <h5>24/7 Working Hours</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- //features -->
  </section>
  <!-- content-with-photo4 block -->
  <section class="w3l-content-with-photo-4">
    <div id="content-with-photo4-block" class="pt-5">
      <div class="container py-md-5">
        <div class="cwp4-two row">
          <div class="cwp4-text col-lg-6">
            <h3>Explore The Freight Service</h3>
            <p>
              Fast and Safe Cargo Movers is more than logistics. Look at
              moving rates and documents from three of the best and record
              checked packers and movers for safe, trouble free Household
              merchandise packing and moving administrations in India.
            </p>
            <h4>Benefits</h4>
            <ul class="cont-4">
              <li><span class="fa fa-check"></span>01. Expert Staff</li>
              <li>
                <span class="fa fa-check"></span>02. Fast Logistic Services
              </li>
              <li><span class="fa fa-check"></span>03. Ground Shipping</li>
              <li><span class="fa fa-check"></span>04. Efficient Price</li>
            </ul>
          </div>
          <div class="cwp4-image col-lg-6 pl-lg-5 mt-lg-0 mt-5">
            <img src="images/h1.jpg" class="img-fluid" alt="" />
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- content-with-photo4 block -->
  <!-- specifications -->
  <section class="w3l-specifications-9">
    <div class="main-w3 pb-5" id="stats">
      <div class="container py-md-5 mt-4">
        <div class="main-cont-wthree-fea row">
          <div class="grids-speci1 col-lg-3 col-6">
            <div class="spec-2">
              <span class="fa fa-heart"></span>
              <h3 class="title-spe">40450</h3>
              <p>Our Clients</p>
            </div>
          </div>
          <div class="grids-speci1 midd-eff-spe col-lg-3 col-6">
            <div class="spec-2">
              <span class="fa fa-thumbs-up"></span>
              <h3 class="title-spe">13500</h3>
              <p>Packages Delivered</p>
            </div>
          </div>
          <div class="grids-speci1 las-but col-lg-3 col-6 mt-lg-0 mt-4">
            <div class="spec-2">
              <span class="fa fa-address-card-o"></span>
              <h3 class="title-spe">1500</h3>
              <p>Repeat Customers</p>
            </div>
          </div>
          <div class="grids-speci1 las-t col-lg-3 col-6 mt-lg-0 mt-4">
            <div class="spec-2">
              <span class="fa fa-cog"></span>
              <h3 class="title-spe">2000</h3>
              <p>Commercial Goods</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- //specifications -->
  </section>

  <!-- skills-1 block -->
  <section class="w3l-skills-1" id="features">
    <div id="skills-1-block" class="py-5 bg bg2" data-selector=".bg.bg2">
      <div class="container py-md-5">
        <div class="team-1 row">
          <div class="right-single-team col-lg-6">
            <h6>Here are a few places to explore shipping.</h6>
            <h3 class="mb-4">Are You a Sender?</h3>
            <li><span class="fa fa-check"></span> Core freight</li>
            <li>
              <span class="fa fa-check"></span> Integrated logistics – LLP
            </li>
            <li><span class="fa fa-check"></span> Strategic-Xpert</li>
            <li><span class="fa fa-check"></span> One time solutions</li>
            <li><span class="fa fa-check"></span> Geo-Gateways</li>
          </div>
          <div class="left-single-team col-lg-6">
            <h6>Things need to know about shipping.</h6>
            <h3 class="mb-4">Are You a Shipper?</h3>
            <li>
              <span class="fa fa-check"></span> Customs & Tax Representation
            </li>
            <li><span class="fa fa-check"></span> Reusable Packaging</li>
            <li><span class="fa fa-check"></span> Warehousing</li>
            <li>
              <span class="fa fa-check"></span> Finished Vehicle Logistics
            </li>
            <li><span class="fa fa-check"></span> Control Tower</li>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Teams14 block -->

  <section class="w3l-feature-2">
    <div class="grid top-bottom py-5">
      <div class="container py-md-5">
        <div class="heading text-center mx-auto">
          <h3 class="head">How We Work</h3>
          <p class="my-3 head">
            we offer services of the highest standards, allowing you to benefit
            from seamlessly designed and customized solutions.
          </p>
        </div>
        <div class="middle-section row mt-5 pt-3">
          <div class="three-grids-columns col-lg-3 col-sm-6">
            <div class="icon">
              <span class="fa fa-arrows" aria-hidden="true"></span>
            </div>
            <h4>01. Book Us</h4>
            <p>
              Book Us through telephone medium or anyhow you want and we start
              your process instantly.
            </p>
            <a class="red mt-3"
              ><router-link to="/services">Read More</router-link>
              <span class="fa fa-angle-right pl-1"></span
            ></a>
          </div>
          <div class="three-grids-columns col-lg-3 col-sm-6 mt-sm-0 mt-5">
            <div class="icon">
              <span class="fa fa-cog" aria-hidden="true"></span>
            </div>
            <h4>02. Pack your Goods</h4>
            <p>
              We provide High Quality packaging and keeping the safety of your
              products.
            </p>
            <a class="red mt-3"
              ><router-link to="/services">Read More</router-link>
              <span class="fa fa-angle-right pl-1"></span
            ></a>
          </div>
          <div class="three-grids-columns col-lg-3 col-sm-6 mt-lg-0 mt-5">
            <div class="icon">
              <span class="fa fa-adjust" aria-hidden="true"></span>
            </div>
            <h4>03. Move your Goods</h4>
            <p>
              We take your goods from your door and move them to our basement
              for arrangements.
            </p>
            <a class="red mt-3"
              ><router-link to="/services">Read More</router-link>
              <span class="fa fa-angle-right pl-1"></span
            ></a>
          </div>
          <div class="three-grids-columns col-lg-3 col-sm-6 mt-lg-0 mt-5">
            <div class="icon">
              <span class="fa fa-anchor" aria-hidden="true"></span>
            </div>
            <h4>04. We Deliver</h4>
            <p>
              We deliver your goods at your location within time and quality
              assurance.
            </p>
            <a class="red mt-3"
              ><router-link to="/services">Read More</router-link>
              <span class="fa fa-angle-right pl-1"></span
            ></a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!--customers-7-->
  <section class="w3l-customers-8" id="testimonials">
    <div class="customers_sur py-5">
      <div class="container py-md-5">
        <div class="heading text-center mx-auto">
          <h3 class="head text-white">Words From Our Clients</h3>
          <p class="my-3 head text-white">
            In an increasingly complex world, keeping track of all your
            shipments around the world is not simple.
          </p>
        </div>
        <div class="customers-top_sur row mt-5 pt-3">
          <div class="customers-left_sur col-md-6">
            <div class="customers_grid">
              <p class="sub-test">
                <span class="fa fa-quote-left"></span> This is to formally thank
                you on the excellent services received by us from you and your
                team on our relocation to Bangalore. Things went exactly per
                plan and we were very happy with the professionalism of you and
                your team.
              </p>
            </div>
            <div class="customers-bottom_sur row">
              <div class="custo-img-res col-2">
                <img src="images/te2.jpg" alt=" " class="img-responsive" />
              </div>
              <div class="custo_grid col-10">
                <h5 class="text-white">Rashi Garg</h5>
              </div>
            </div>
          </div>
          <div class="customers-middle_sur col-md-6 mt-md-0 mt-4">
            <div class="customers_grid">
              <p class="sub-test">
                <span class="fa fa-quote-left"></span> Much obliged to you Fast
                & Safe Packers and Movers ® for the immense move and diligent
                work All of you folks made a magnificent showing with regards to
                moving my furniture and boxes and migrated us from G M paliya to
                bannerghatta street and the costs were justified regardless of
                the administration thanks.
              </p>
            </div>
            <div class="customers-bottom_sur row">
              <div class="custo-img-res col-2">
                <img src="images/te1.jpg" alt=" " class="img-responsive" />
              </div>
              <div class="custo_grid col-10">
                <h5 class="text-white">Rachna Jangra</h5>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!--//customers-7-->

  <section class="grids-4" id="news">
    <div id="grids4-block" class="py-5">
      <div class="container py-md-5">
        <div class="heading text-center mx-auto">
          <h3 class="head">Latest News</h3>
          <p class="my-3 head">
            The trucking organizations are very much positioned and clever to
            offer start to finish pressing, moving, stockpiling and vehicle
            transportation benefits securely and at the most skilled rates. We
            can also optimize your packaging, manage your materials sourcing,
            and so much more.
          </p>
        </div>
        <div class="row mt-5 pt-3">
          <div class="grids4-info col-lg-4 col-md-6">
            <div class="info-bg editContent">
              <a href="/services"
                ><img src="images/g2.jpg" class="img-fluid" alt=""
              /></a>
              <h5 class="mt-4 mb-3 editContent">
                <a class="editContent" href="/services"
                  >Waring & Packaging of Goods</a
                >
              </h5>
              <li class="pr-3">
                <span class="fa fa-calendar"></span> January 18, 2020
              </li>
              <li>
                <a
                  ><span class="fa fa-arrow-circle-right"></span
                  ><router-link to="/services">Read More</router-link></a
                >
              </li>
            </div>
          </div>
          <div class="grids4-info col-lg-4 col-md-6 mt-md-0 mt-4">
            <div class="info-bg editContent">
              <a href="/services"
                ><img src="images/g6.jpg" class="img-fluid" alt=""
              /></a>
              <h5 class="mt-4 mb-3 editContent">
                <a class="editContent" href="/services"
                  >Freight Transportation & Logistics
                </a>
              </h5>
              <li class="pr-3">
                <span class="fa fa-calendar"></span> January 18, 2020
              </li>
              <li>
                <a
                  ><span class="fa fa-arrow-circle-right"></span>
                  <router-link to="/services">Read More</router-link></a
                >
              </li>
            </div>
          </div>
          <div
            class="grids4-info col-lg-4 col-md-6 offset-lg-0 offset-md-3 mt-lg-0 mt-4"
          >
            <div class="info-bg editContent">
              <a href="/services"
                ><img src="images/g10.jpg" class="img-fluid" alt=""
              /></a>
              <h5 class="mt-4 mb-3 editContent">
                <a class="editContent" href="/services"
                  >Twist Locks Connection Devices</a
                >
              </h5>
              <li class="pr-3">
                <span class="fa fa-calendar"></span> January 18, 2020
              </li>
              <li>
                <a
                  ><span class="fa fa-arrow-circle-right"></span>
                  <router-link to="/services">Read More</router-link></a
                >
              </li>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- grids block 5 -->
  <section class="w3l-footer-29-main">
    <div class="footer-29">
      <div class="container">
        <div class="d-grid grid-col-4 footer-top-29">
          <div class="footer-list-29 footer-1">
            <h6 class="footer-title-29">
              <a href="/"><span class="fa fa-truck"></span> Packers</a>
            </h6>
            <p>
              We have our own fleet of transport to take-up the forwarding on
              top priority basis. Nevertheless to say that all the goods are
              covered with transit insurance.
            </p>
            <br />
            <p>
              Plot No. 38, Gausala Road, Palam Vihar Extn., Near Bharat Hotel, Krishna Chowk, Gurugram
            </p>
            <div class="main-social-footer-29">
              <a href="#facebook" class="facebook"
                ><span class="fa fa-facebook"></span
              ></a>
              <a href="#twitter" class="twitter"
                ><span class="fa fa-twitter"></span
              ></a>
              <a href="#instagram" class="instagram"
                ><span class="fa fa-instagram"></span
              ></a>
              <a href="#google-plus" class="google-plus"
                ><span class="fa fa-google-plus"></span
              ></a>
              <a href="#linkedin" class="linkedin"
                ><span class="fa fa-linkedin"></span
              ></a>
            </div>
          </div>
          <div class="footer-list-29 footer-2">
            <ul>
              <h6 class="footer-title-29">Categories</h6>
              <li>
                <a><router-link to="/services"> AirFreight</router-link> </a>
              </li>
              <li>
                <a><router-link to="/services"> Domestic</router-link></a>
              </li>
              <li>
                <a><router-link to="/services"> International</router-link></a>
              </li>
              <li>
                <a><router-link to="/services">Shipping</router-link></a>
              </li>
              <li>
                <a><router-link to="/services">Liquids</router-link></a>
              </li>
            </ul>
          </div>

          <div class="footer-list-29 footer-3"></div>
          <div class="footer-list-29 footer-4">
            <ul>
              <h6 class="footer-title-29">Quick Links</h6>
              <li>
                <a><router-link to="/"> Home</router-link></a>
              </li>
              <li>
                <a><router-link to="/about"> About</router-link></a>
              </li>
              <li>
                <a><router-link to="/services">Services</router-link></a>
              </li>
              <li>
                <a><router-link to="/contact">Contact</router-link></a>
              </li>
            </ul>
          </div>
        </div>
        <div class="d-grid grid-col-2 bottom-copies">
          <p class="copy-footer-29">
            © 2022 Packers. All rights reserved | Designed by
            <a href="https://jatinsoni.in">Jatin Kumar</a>
          </p>
          <ul class="list-btm-29">
            <li>
              <a
                ><router-link to="/privacyPolicy"
                  >Privacy policy</router-link
                ></a
              >
            </li>
            <li>
              <a
                ><router-link to="/termsCondition"
                  >Terms of service</router-link
                ></a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
    <!-- move top -->
    <button onclick="topFunction()" id="movetop" title="Go to top">
      <span class="fa fa-angle-up"></span>
    </button>
  </section>
</template>

<script lang="ts">
export default {
  name: "HomeView",
};
</script>

<style></style>
