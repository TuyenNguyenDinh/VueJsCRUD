<template>
  <div class="header">
    <header>
    <div id="header">
      <nav id="navbar-header">
        <div class="header">
          <div class="hidden-sm hidden-xs header">
            <div class="head-main backgound-primary">
              <div class="container">
                <div class="row">
                  <div class="col-md-4">
                    <div class="line">
                      <div class="logo col-logo">
                        <a href="#">
                          <img
                            src="../assets/image/logo.png"
                            alt="shopA_Z"
                            height="38px"
                            width="144px"
                          />
                        </a>
                      </div>
                      <div class="col-nav nav-menu">
                        <button class="dropbtn btn btn-secondary" type="buttom">
                          <i class="fas fa-bars"></i>
                          Danh mục
                        </button>
                        <div class="dropdown-content">
                          <a href="#">TV</a>
                          <a href="#">Loa Karaoke</a>
                          <a href="#">Tủ lạnh</a>
                          <a href="#">Điều hòa</a>
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="col-md-4">
                    <div class="search">
                      <form
                        action="#"
                        role="search"
                        method="GET"
                        class="full-width"
                      >
                        <!-- Search form -->
                        <input
                          class="form-control"
                          type="text"
                          name="result"
                          placeholder="Nhập từ khóa..."
                          aria-label="Search"
                        />
                        <button type="submit" class="color-b9 font-size-18">
                          <i class="fa fa-search"></i>
                        </button>
                      </form>
                    </div>
                  </div>
                  <div class="col-md-4">
                    <!-- cart -->
                    <a class="display" href="#">
                      <img
                        src="../assets/image/icon-cart.png"
                        height="38px"
                        width="38px"
                        style="margin-left: 40px"
                      />
                      <a style="color: white">0</a>
                    </a>
                    <!-- cart -->
                    <div class="header-account main_account pull-right">
                      <a href="#" class="btn-sign">Đăng nhập</a>
                      <a href="#" class="btn btn-login btn-secondary"
                        >Đăng ký</a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </nav>
      <!-- Mobile -->
    
    </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >
</style>