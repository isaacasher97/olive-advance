<template>
  <!-- Remove the container if you want to extend the Footer to full width. -->
  <div>
    <!-- Footer -->
    <footer
      class="text-center text-lg-start text-dark"
      style="background-color: #183b54"
    >
      <!-- Section: Social media -->
      <section
        class="d-flex justify-content-between p-4 text-white"
        style="background-color: #21d192"
      >
        <!-- Left -->
        <div class="me-5"></div>
        <!-- Left -->

        <!-- Right -->
        <!-- Right -->
      </section>
      <!-- Section: Social media -->

      <!-- Section: Links  -->
      <section style="background-color: #183b54" class="footer-info">
        <div class="container text-center text-md-start mt-5">
          <!-- Grid row -->
          <div class="row mt-3">
            <!-- Grid column -->
            <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
              <!-- Content -->
              <h6 class="text-uppercase fw-bold">Olive Advance</h6>
              <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
              />
              <p>
                Olive Advance is devoted to supporting the prosperity of your
                small or mid-sized enterprise through the provision of swift and
                uncomplicated working capital loans, spanning from $3,000 to
                $500,000. Our streamlined process ensures a potential
                disbursement within as little as one business day, offering a
                reliable financial solution tailored to your business needs
              </p>
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
              <!-- Links -->
              <h6 style="color: #f7f7f7" class="text-uppercase fw-bold">
                Services
              </h6>
              <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
              />
              <p>Merchant Cash Advances</p>
              <p>Small Business Loans</p>
              <p>Collateral Loans</p>
              <p>Business Line Of Credit</p>
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
              <!-- Links -->
              <h6 class="text-uppercase fw-bold">Who We Fund</h6>
              <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
              />
              <p>Medical Practices</p>
              <p>Dental Practices</p>
              <p>Law Practices</p>
              <p>Reataraunts</p>
              <p>Retailers</p>
              <p>All Industries...</p>
            </div>
            <!-- Grid column -->

            <!-- Grid column -->
            <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
              <!-- Links -->
              <h6 class="text-uppercase fw-bold">Contact Us</h6>
              <hr
                class="mb-4 mt-0 d-inline-block mx-auto"
                style="width: 60px; background-color: #7c4dff; height: 2px"
              />
              <p><i class="fas fa-home mr-3"></i> New York, NY</p>
              <p><i class="fas fa-envelope mr-3"></i> admin@oliveadvance.com</p>
              <p><i class="fas fa-phone mr-3"></i> (123) 456 7890</p>
              <div id="apply-button">
                <button class="bn31">
                  <a href="#" role="button">Apply Now</a>
                </button>
              </div>
            </div>
            <!-- Grid column -->
          </div>
          <!-- Grid row -->
        </div>
      </section>
      <!-- Section: Links  -->

      <!-- Copyright -->
      <div class="text-center p-3" style="background-color: #133045">
        <p>© 2023 Olive Advance Inc, All Rights Reserved</p>
      </div>
      <!-- Copyright -->
    </footer>
    <!-- Footer -->
  </div>
  <!-- End of .container -->
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
p,
h6 {
  color: #f7f7f7;
  font-family: Arial, Helvetica, sans-serif;
}

a {
  text-decoration: none;
  color: #f7f7f7;
}

/* button styling  */
.bn31 {
  background-image: linear-gradient(to right, #006175 0%, #00a950 100%);
  border-radius: 40px;
  box-sizing: border-box;
  color: #00a84f;
  display: block;
  height: 50px;
  font-size: 1.4em;
  padding: 4px;
  position: relative;
  text-decoration: none;
  width: 7em;
  z-index: 2;
}

.bn31:hover {
  color: #fff;
}

.bn31 .bn31span {
  align-items: center;
  background: #0e0e10;
  border-radius: 40px;
  display: flex;
  justify-content: center;
  height: 100%;
  transition: background 0.5s ease;
  width: 100%;
}

.bn31:hover .bn31span {
  background: transparent;
}
/* button styling end  */

#apply-button {
  display: flex;
  width: 100%;
  margin: 0 auto;
}

@media screen and (max-width: 767px) {
  #apply-button {
    display: flex;
    justify-content: center;
    width: 100%;
    margin: 0 auto;
  }
}
</style>
