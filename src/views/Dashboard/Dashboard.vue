<style>
@import "./Dashboard.css";
</style>

<template>
  <main>
    <nav class="navbar navbar-expand-lg text-light navbarColor">
      <div class="container">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarTogglerDemo03"
          aria-controls="navbarTogglerDemo03"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <a class="navbar-brand" href="#">
          <i class="fa-solid fa-cloud fa-2xl text-light"></i>
        </a>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0"></ul>
          <div class="d-block">
            <button class="btn btn-light rounded-circle">
              <i class="fa-solid fa-magnifying-glass"></i>
            </button>
            <button class="btn rounded-pill text-light greenColor m-2" style="background-color: #374e73; border: 1px solid white; width: 170px;">
              <i class="fa-regular fa-envelope"></i>
              Contact Us
            </button>
            <button class="btn rounded-pill text-light greenColor m-2" style="background-color: #374e73; border: 1px solid white; width: 170px;">
              
              English
              <i class="fa-solid fa-caret-down"></i>
            </button>
            <button class="btn rounded-pill greenColor text-light m-2">Login</button>
          </div>
        </div>
      </div>
    </nav>

    <nav
      class="navbar navbar-expand-lg navbar-expand-md navbar-expand-sm bg-body-tertiary navbarColor mt-1 subNavbar"
    >
      <div class="container">
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
          <ul class="navbar-nav">
            <li class="nav-item dropdown" style="margin-right: 20px">
              <a
                class="nav-link dropdown-toggle textGreenNav"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Why FLOU
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>

            <li class="nav-item dropdown" style="margin-right: 20px">
              <a
                class="nav-link dropdown-toggle text-light"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Products
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>

            <li class="nav-item dropdown" style="margin-right: 20px">
              <a
                class="nav-link dropdown-toggle text-light"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Solution
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>

            <li class="nav-item dropdown" style="margin-right: 20px">
              <a
                class="nav-link dropdown-toggle text-light"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Patners
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>

            <li class="nav-item dropdown" style="margin-right: 20px">
              <a
                class="nav-link dropdown-toggle text-light"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Pricing
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Action</a></li>
                <li><a class="dropdown-item" href="#">Another action</a></li>
                <li>
                  <a class="dropdown-item" href="#">Something else here</a>
                </li>
              </ul>
            </li>

            <div class="navbar-nav">
              <a
                class="nav-link text-light"
                style="margin-right: 20px"
                aria-current="page"
                href="#"
                >Resources</a
              >
              <a class="nav-link text-light" style="margin-right: 20px" href="#"
                >Support</a
              >
              <a class="nav-link text-light" style="margin-right: 20px" href="#"
                >MarketPlace</a
              >
            </div>
          </ul>
        </div>
      </div>
    </nav>

    <div class="background">
      <div
        class="row d-flex justify-content-center align-items-center textBackground"
      >
        <div class="col-md-9 text-light contentImage">
          <h1>FLOU Cloud Product</h1>
          <div class="mt-3">
            <h5 class="textImage">
              Explore FLOU Cloud's expanding range of high-performance cloud
              products <br />
              including large-scale computing, storage resources, and Big Data
              processing <br />
              capabilities for users around the world
            </h5>
          </div>
          <div class="mt-4">
            <button class="btn btn-md greenColor text-light">
              Get Started For Free
            </button>
            <button class="btn btn-md btn-light text-success m-3">
              Contact Sales
            </button>
          </div>
        </div>
      </div>
    </div>

    <div class="container mt-3">
      <div class="row">
        <div class="col-md-4 text-dark">
          <div class="mt-4">
            <h4 class="textGreen">Flou Cloud Products</h4>
          </div>
          <div class="mt-4">
            <div class="boxChoose">
              <li class="active">
                <a href="" class="text-decoration-none text-success"
                  >Infrastructure as a Service</a
                >
              </li>
              <li>
                <a href="" class="text-decoration-none text-dark"
                  >Software as a Service</a
                >
              </li>
              <li>
                <a href="" class="text-decoration-none text-dark"
                  >Platform as a Service</a
                >
              </li>
              <li>
                <a href="" class="text-decoration-none text-dark"
                  >Hybrid Multicloud</a
                >
              </li>
              <li>
                <a href="" class="text-decoration-none text-dark">Services</a>
              </li>
              <li>
                <a href="" class="text-decoration-none text-dark"
                  >Private Cloud</a
                >
              </li>
            </div>
          </div>
        </div>
        <div class="col-md-8 text-dark mt-4">
          <div class="mt-4">
            <div class="input-group mb-3">
              <input
                type="text"
                class="form-control"
                placeholder="Search Products"
                aria-label="Search Products"
                aria-describedby="button-addon2"
              />
              <button
                class="btn btn-outline-secondary"
                type="button"
                id="button-addon2"
              >
                <i class="fa-solid fa-magnifying-glass"></i>
              </button>
            </div>
            <hr />
            <div class="mt-4 mb-4">
              <a href="">
                <h5 class="textGreen">
                  Explore Infrastructure as a Service Productts (IaaS)
                </h5>
              </a>
              <small>
                Helping to accelerate the business through strong and resilient
                infrastructure for unlimited customer <br />experience.
              </small>
            </div>
            <div class="row mt-5 justify-content-between">
              <div class="col-md-6">
                <div
                  class="row d-flex justify-content-center align-items-center"
                >
                  <div class="col-md-10">
                    <h5 class="textGreen">FLOU Cloud</h5>
                  </div>
                  <div class="col-md-2">
                    <a href=""><i class="fa-solid fa-angle-right"></i></a>
                  </div>
                </div>
                <hr />
                <div class="mt-4">
                  <div
                    class="row d-flex justify-content-center align-items-center"
                  >
                    <div class="col-md-2 text-center">
                      <i class="fa-solid fa-cloud fa-2xl"></i>
                    </div>
                    <div class="col-md-9">
                      <h5 class="textGreen">FLOU Compute</h5>
                      <small
                        >Elastic Compute Service, Compute High Performance, Auto
                        Scalling, Container</small
                      >
                    </div>
                  </div>
                </div>
                <div class="mt-4">
                  <div
                    class="row d-flex justify-content-center align-items-center"
                  >
                    <div class="col-md-2 text-center">
                      <i class="fa-solid fa-cloud fa-2xl"></i>
                    </div>
                    <div class="col-md-9">
                      <h5 class="textGreen">FLOU Network</h5>
                      <small>Elastic IP, Server Load Balancer</small>
                    </div>
                  </div>
                </div>
                <div class="mt-4">
                  <div
                    class="row d-flex justify-content-center align-items-center"
                  >
                    <div class="col-md-2 text-center">
                      <i class="fa-solid fa-cloud fa-2xl"></i>
                    </div>
                    <div class="col-md-9">
                      <h5 class="textGreen">FLOU Security</h5>
                      <small
                        >Anti DDoS, Web Application Firewall WAF, Server
                        Guard</small
                      >
                    </div>
                  </div>
                </div>
                <div class="mt-4">
                  <div
                    class="row d-flex justify-content-center align-items-center"
                  >
                    <div class="col-md-2 text-center">
                      <i class="fa-solid fa-cloud fa-2xl"></i>
                    </div>
                    <div class="col-md-9">
                      <h5 class="textGreen">FLOU Compute</h5>
                      <small>Object Storage Service, Block Storage</small>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-md-6 contentTelkom">
                <div
                  class="row d-flex justify-content-center align-items-center"
                >
                  <div class="col-md-10">
                    <h5 class="textGreen">Telkom Cloud</h5>
                  </div>
                  <div class="col-md-2">
                    <a href=""><i class="fa-solid fa-angle-right"></i></a>
                  </div>
                </div>
                <hr />
                <div class="mt-4">
                  <div
                    class="row d-flex justify-content-center align-items-center"
                  >
                    <div class="col-md-2 text-center">
                      <i class="fa-solid fa-cloud fa-2xl"></i>
                    </div>
                    <div class="col-md-9">
                      <h5 class="textGreen">Telkom Cloud Compute</h5>
                      <small
                        >Virtual server service with CPU and RAM
                        resources</small
                      >
                    </div>
                  </div>
                </div>
                <div class="mt-4">
                  <div
                    class="row d-flex justify-content-center align-items-center"
                  >
                    <div class="col-md-2 text-center">
                      <i class="fa-solid fa-cloud fa-2xl"></i>
                    </div>
                    <div class="col-md-9">
                      <h5 class="textGreen">Telkom Cloud Network</h5>
                      <small
                        >Public or Private Cloud infrastructure support services
                        that enable communication</small
                      >
                    </div>
                  </div>
                </div>
                <div class="mt-5">
                  <div
                    class="row d-flex justify-content-center align-items-center"
                  >
                    <div class="col-md-12">
                      <h5 class="textGreen">BackUp Services</h5>
                    </div>
                  </div>
                  <hr />
                  <div class="mt-4">
                    <div
                      class="row d-flex justify-content-center align-items-center"
                    >
                      <div class="col-md-2 text-center">
                        <i class="fa-solid fa-cloud fa-2xl"></i>
                      </div>
                      <div class="col-md-9">
                        <h5 class="textGreen">Cloud BackUp Service Veem</h5>
                        <small
                          >Object Storage Service (OSS) is an encrypted object
                          storage service</small
                        >
                      </div>
                    </div>
                  </div>
                  <div class="mt-4 mb-5">
                    <div
                      class="row d-flex justify-content-center align-items-center"
                    >
                      <div class="col-md-2 text-center">
                        <i class="fa-solid fa-cloud fa-2xl"></i>
                      </div>
                      <div class="col-md-9">
                        <h5 class="textGreen">Cloud BackUp HBR</h5>
                        <small
                          >Object Storage Service (OSS) is an encrypted object
                          storage service</small
                        >
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="navbarColor mt-5 text-light">
      <div class="container">
        <footer class="py-5">
          <div class="row">
            <div class="col-md-9">
              <div class="row">
                <div class="col-md-2 mb-3">
                  <h5>About</h5>
                  <ul class="nav flex-column mt-4">
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">About FLOU Cloud</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Pricing Model</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Product</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Solutions</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Customer</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Partners</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Latest Update</small></a
                      >
                    </li>
                  </ul>
                </div>

                <div class="col-md-2 mb-3">
                  <h5>Promotion</h5>
                  <ul class="nav flex-column mt-4">
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Free Trial</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Refer a friend</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Starter Package</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Web Hosting</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Affiliate Program</small></a
                      >
                    </li>
                  </ul>
                </div>

                <div class="col-md-2 mb-3">
                  <h5>Explore</h5>
                  <ul class="nav flex-column mt-4">
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Indonesia Gateway</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Getting Started</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Blog</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Marketplace</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Availability Zone</small></a
                      >
                    </li>
                  </ul>
                </div>

                <div class="col-md-2 mb-3">
                  <h5>Support</h5>
                  <ul class="nav flex-column mt-4">
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Contact Sales</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light"
                          >Affter-Sales Support</small
                        ></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Pricing Calculator</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">FAQs</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">About</small></a
                      >
                    </li>
                  </ul>
                </div>

                <div class="col-md-2 mb-3">
                  <h5>Resource</h5>
                  <ul class="nav flex-column mt-4">
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Document Centre</small></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light"
                          >Security & Compliance</small
                        ></a
                      >
                    </li>
                    <li class="nav-item mb-2">
                      <a href="#" class="nav-link p-0 text-muted"
                        ><small class="text-light">Press Room</small></a
                      >
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-md-3">
              <button class="btn greenColor text-light container">
                Sign In Console
              </button>
              <div class="mt-3 text-center mt-4">
                <h5>Our Social Media</h5>
                <div class="row mt-3">
                  <div class="col-md-3">
                    <button
                      class="btn btn-light rounded-circle iconSizeFooter socialMedia"
                    >
                      <i class="fa-brands fa-instagram fa-2xl"></i>
                    </button>
                  </div>
                  <div class="col-md-3">
                    <button
                      class="btn btn-light rounded-circle iconSizeFooter socialMedia"
                    >
                      <i class="fa-brands fa-facebook fa-2xl"></i>
                    </button>
                  </div>
                  <div class="col-md-3">
                    <button
                      class="btn btn-light rounded-circle iconSizeFooter socialMedia"
                    >
                      <i class="fa-brands fa-twitter fa-2xl"></i>
                    </button>
                  </div>
                  <div class="col-md-3">
                    <button
                      class="btn btn-light rounded-circle iconSizeFooter socialMedia"
                    >
                      <i class="fa-brands fa-linkedin fa-2xl"></i>
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </footer>
      </div>
    </div>
  </main>
</template>
