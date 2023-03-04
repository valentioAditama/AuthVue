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
          <img src="logo" alt="" srcset="" />
        </a>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo03">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0"></ul>
          <div class="d-block">
            <button class="btn rounded-pill text-light greenColor m-2">
              Contact Us
            </button>
            <button class="btn greenColor text-light m-2">Login</button>
          </div>
        </div>
      </div>
    </nav>

    <div class="background">
      <div
        class="row d-flex justify-content-center align-items-center textBackground"
      >
        <div class="col-md-9 text-light">
          <h1>FLOU Cloud Product</h1>
          <div class="mt-3">
            <h5>
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
          <div class="mt-4">Floud Cloud Products</div>
        </div>
        <div class="col-md-8 text-dark">
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
                Search
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
                infrastructure for unlimited customer experience.
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
              <div class="col-md-6">
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
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
