<template>
  <div class="footer">
    <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 col-md-6">
            <h6>About us</h6>
            <p class="text-justify">
              Scanfcode.com <i>CODE WANTS TO BE SIMPLE </i> is an initiative to
              help the upcoming programmers with the code. Scanfcode focuses on
              providing the most efficient code or snippets as the code wants to
              be simple. We will help programmers build up concepts in different
              programming languages that include C, C++, Java, HTML, CSS,
              Bootstrap, JavaScript, PHP, Android, SQL and Algorithm.
            </p>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Categories</h6>
            <ul class="footer-links">
              <li><a href="#">TV</a></li>
              <li><a href="#">Loa Karaoke</a></li>
              <li><a href="#">Tủ lạnh</a></li>
              <li><a href="#">Điều hòa</a></li>
            </ul>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Quick Links</h6>
            <ul class="footer-links">
              <li><a href="#">About Us</a></li>
              <li><a href="#">Contact Us</a></li>
              <li><a href="#">Contribute</a></li>
              <li><a href="#">Privacy Policy</a></li>
              <li><a href="#">Sitemap</a></li>
            </ul>
          </div>
        </div>
        <hr />
      </div>
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-sm-6 col-xs-12">
            <p class="copyright-text">
              Copyright &copy; 2020 All Rights Reserved by
              <a href="#">Nguyễn Đình Tuyên</a>.
            </p>
          </div>

          <div class="col-md-4 col-sm-6 col-xs-12">
            <ul class="social-icons">
              <li>
                <a class="facebook" href="#"
                  ><i class="fab fa-facebook-square"></i
                ></a>
              </li>
              <li>
                <a class="twitter" href="#"><i class="fab fa-twitter"></i></a>
              </li>
              <li>
                <a class="dribbble" href="#"
                  ><i class="fab fa-dribbble-square"></i
                ></a>
              </li>
              <li>
                <a class="linkedin" href="#"><i class="fab fa-linkedin"></i></a>
              </li>
            </ul>
          </div>
          <button
            onclick="topFunction()"
            id="backtotop"
            title="Go to top"
            class="btn"
          >
            <i class="fa fa-arrow-up"></i>
          </button>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Footer",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
