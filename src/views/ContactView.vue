<template>
  <!-- Top Menu 1 -->
  <section class="w3l-top-menu-1">
    <div class="top-hd">
      <div class="container">
        <header class="row">
          <div class="accounts col-sm-9 col-6">
            <li class="top_li">
              <span class="fa fa-mobile"></span
              ><a href="tel:+917217764600">+917217764600</a>
            </li>
            <li class="top_li1">
              <span class="fa fa-envelope"></span>
              Fastandsafecargomoversncr@gamil.com
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
        /></a
        >

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
  <!-- inner banner -->
  <section class="w3l-inner-banner-main">
    <div class="about-inner sear-1">
      <div class="container">
        <ul class="breadcrumbs-custom-path">
          <li>
            <a
              ><router-link to="/"> Home</router-link>
              <span class="fa fa-angle-double-right" aria-hidden="true"></span
            ></a>
          </li>
          <li class="active">Contact</li>
        </ul>
      </div>
    </div>
  </section>
  <!-- //covers -->
  <!-- contact -->
  <section class="w3l-contacts-12" id="contact">
    <div class="contact-top pt-5">
      <div class="container py-md-3">
        <div class="heading text-center mx-auto">
          <h3 class="head">Have you a question?</h3>
          <p class="my-3 head">
            Vestibulum ante ipsum primis in faucibus orci luctus et ultrices
            posuere cubilia Curae; Nulla mollis dapibus nunc, ut rhoncus turpis
            sodales quis. Integer sit amet mattis quam.
          </p>
        </div>
        <div class="row cont-main-top mt-5 pt-3">
          <!-- contact address -->

          <!-- //contact address -->
          <!-- contact form -->
          <div class="contacts12-main col-lg-7 pr-lg-5 pr-3">
            <form
              action="https://formsubmit.co/Fastandsafecargomoversncr@gamil.com"
              method="POST"
              class="main-input"
            >
              <div class="top-inputs">
                <input
                  type="text"
                  placeholder="Name"
                  name="Name"
                  id="w3lName"
                  required
                />
              </div>
              <div class="top-inputs">
                <input
                  type="email"
                  name="email"
                  placeholder="Email"
                  id="w3lSender"
                  required
                />
              </div>
              <input
                type="text"
                placeholder="Phone Number"
                name="Phone Number"
                id="w3lName"
                required
              />
              <textarea
                placeholder="Message"
                name="Message"
                id="w3lMessage"
              ></textarea>
              <input type="hidden" name="_captcha" value="false">
              <div class="text-right">
                <button type="submit" class="btn btn-theme2">Submit Now</button>
              </div>
            </form>
          </div>
          <!-- //contact form -->
          <div class="contact col-lg-5 mt-lg-0 mt-5">
            <div class="cont-subs">
              <h5>Contact Info</h5>
              <p class="mt-3">
                Have any Queries? Let us know. We will clear it for you at the
                best.
              </p>
              <div class="cont-add mt-4">
                <div class="cont-add-lft">
                  <span class="fa fa-map-marker" aria-hidden="true"></span>
                </div>
                <div class="cont-add-rgt">
                  <h4>Office</h4>
                  <p class="contact-text-sub">
                    PLOT NO.860 <br />NEAR GOVERNMENT BOYS SCHOOL,BARTHAL
                    VILLAGE,DWARKA <br />
                    SEC-26,DELHI,INDIA
                  </p>
                </div>
              </div>
              <div class="cont-add my-4">
                <div class="cont-add-lft">
                  <span class="fa fa-envelope" aria-hidden="true"></span>
                </div>
                <div class="cont-add-rgt">
                  <h4>Email</h4>
                  <a href="mailto:info@example.com">
                    <p class="contact-text-sub">
                      Fastandsafecargomoversncr@gamil.com
                    </p>
                  </a>
                </div>
              </div>
              <div class="cont-add">
                <div class="cont-add-lft">
                  <span class="fa fa-phone" aria-hidden="true"></span>
                </div>
                <div class="cont-add-rgt">
                  <h4>Phone</h4>
                  <a href="tel:+917217764600">
                    <p class="contact-text-sub">+917217764600</p>
                    <p class="contact-text-sub">+91 8851055005</p>
                  </a>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- map -->
      <div class="map">
        <iframe
          style="border: 0"
          frameborder="0"
          scrolling="no"
          marginheight="0"
          marginwidth="0"
          src="https://maps.google.com/maps?width=100%25&amp;height=300&amp;hl=en&amp;q=PLOT%20NO.860%20%20NEAR%20GOVERNMENT%20BOYS%20SCHOOL%20BARTHAL%20VILLAGE%20DWARKA%20SEC-26%20DELHI%20INDIA+(My%20Business%20Name)&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
          ><a href="https://www.maps.ie/distance-area-calculator.html"
            >distance maps</a
          ></iframe
        >
      </div>
      <!-- //map -->
    </div>
  </section>
  <!-- //contact -->

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
