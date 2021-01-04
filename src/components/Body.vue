<template>
  <div class="body">
    <section id="body">
      <div class="container">
        <div class="row">
          <!-- Main -->
          <div id="main" class="col-lg-9 col-md-12 col-sm-12">
            <div
              id="carouselExampleIndicators"
              class="carousel slide"
              data-ride="carousel"
            >
              <ol class="carousel-indicators">
                <li
                  data-target="#carouselExampleIndicators"
                  data-slide-to="0"
                  class="active"
                ></li>
                <li
                  data-target="#carouselExampleIndicators"
                  data-slide-to="1"
                ></li>
                <li
                  data-target="#carouselExampleIndicators"
                  data-slide-to="2"
                ></li>
              </ol>
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img
                    class="d-block w-100"
                    src="../assets/image/slide-1.png"
                    alt="First slide"
                  />
                </div>
                <div class="carousel-item">
                  <img
                    class="d-block w-100"
                    src="../assets/image/slide-2.png"
                    alt="Second slide"
                  />
                </div>
                <div class="carousel-item">
                  <img
                    class="d-block w-100"
                    src="../assets/image/slide-3.png"
                    alt="Third slide"
                  />
                </div>
              </div>
              <a
                class="carousel-control-prev"
                href="#carouselExampleIndicators"
                role="button"
                data-slide="prev"
              >
                <!-- <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                                                <span class="sr-only">Previous</span> -->
              </a>
              <a
                class="carousel-control-next"
                href="#carouselExampleIndicators"
                role="button"
                data-slide="next"
              >
                <!-- <span class="carousel-control-next-icon" aria-hidden="true"></span>
                                                <span class="sr-only">Next</span> -->
              </a>
            </div>
          </div>
          <div class="col-lg-3 col-md-12 col-sm-12">
            <div class="product-feature">
              <div class="product-feature_item">
                <div class="item-img pull-left">
                  <a href="">
                    <img
                      src="../assets/upload/1592969208_569026_ff88983e81a92e443a413a74b6e8eb7b.jpg"
                      alt=""
                      style="height: 70px; width: 50px"
                    />
                  </a>
                </div>
                <div class="item-content pull-right">
                  <h3 class="item">
                    <a href="#">Android Tivi Sony 4K 43 inch KD-43X8000G</a>
                  </h3>
                  <div class="product-feature_price">
                    <span>9.600.000 đ</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="wrap-inner">
            <div class="products">
              <div
                class="products-tab hidden-xs display-flex-center content-space-between"
              >
                <ul class="nav nav-pills" style="padding-bottom: 12px">
                  <li class="nav-item">
                    <a
                      class="nav-link active"
                      href="#hot-products"
                      data-toggle="tab"
                      >Sản phẩm nổi bật</a
                    >
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#new-products" data-toggle="tab"
                      >Sản phẩm mới</a
                    >
                  </li>
                </ul>
              </div>
              <div class="products-tab-content">
                <div
                  id="hot-products"
                  class="tab-pane container fade active in"
                >
                  <h3>Sản phẩm nổi bật</h3>
                  <div class="product-list row">
                    <div class="product-item col-md-3 col-sm-6 col-xs-12">
                      <a href="#"
                        ><img
                          src="../assets/upload/1592969208_569026_ff88983e81a92e443a413a74b6e8eb7b.jpg"
                          style="height: 100px"
                          class="img-thumbnail"
                      /></a>
                      <p>
                        <a href="#">Android Tivi Sony 4K 43 inch KD-43X8000G</a>
                      </p>
                      <p class="price">9.600.000₫</p>
                      <div class="marsk">
                        <a href="#">Xem chi tiết</a>
                      </div>
                    </div>
                    <div class="product-item col-md-3 col-sm-6 col-xs-12">
                      <a href="#"
                        ><img
                          src="../assets/upload/1592969208_569026_ff88983e81a92e443a413a74b6e8eb7b.jpg"
                          style="height: 100px"
                          class="img-thumbnail"
                      /></a>
                      <p>
                        <a href="#">Android Tivi Sony 4K 43 inch KD-43X8000G</a>
                      </p>
                      <p class="price">9.600.000₫</p>
                      <div class="marsk">
                        <a href="#">Xem chi tiết</a>
                      </div>
                    </div>
                    <div class="product-item col-md-3 col-sm-6 col-xs-12">
                      <a href="#"
                        ><img
                          src="../assets/upload/1592969208_569026_ff88983e81a92e443a413a74b6e8eb7b.jpg"
                          style="height: 100px"
                          class="img-thumbnail"
                      /></a>
                      <p>
                        <a href="#">Android Tivi Sony 4K 43 inch KD-43X8000G</a>
                      </p>
                      <p class="price">9.600.000₫</p>
                      <div class="marsk">
                        <a href="#">Xem chi tiết</a>
                      </div>
                    </div>
                  </div>
                </div>
                <div id="new-products" class="tab-pane container fade">
                  <h3>sản phẩm mới</h3>
                  <div class="product-list row">
                    <div class="product-item col-md-3 col-sm-6 col-xs-12">
                      <a href="#"
                        ><img
                          src="../assets/upload/1592970808_4845069_027b5080e85cb94e64ff596de893a381.jpg"
                          style="height: 100px"
                          class="img-thumbnail"
                      /></a>
                      <p>
                        <a href="#">Điều hòa Toshiba Inverter 9000 BTU RAS</a>
                      </p>
                      <p class="price">9.190.000₫</p>
                      <div class="marsk">
                        <a href="#">Xem chi tiết</a>
                      </div>
                    </div>
                    <div class="product-item col-md-3 col-sm-6 col-xs-12">
                      <a href="#"
                        ><img
                          src="../assets/upload/1592970808_4845069_027b5080e85cb94e64ff596de893a381.jpg"
                          style="height: 100px"
                          class="img-thumbnail"
                      /></a>
                      <p>
                        <a href="#">Điều hòa Toshiba Inverter 9000 BTU RAS</a>
                      </p>
                      <p class="price">9.190.000₫</p>
                      <div class="marsk">
                        <a href="#">Xem chi tiết</a>
                      </div>
                    </div>
                    <div class="product-item col-md-3 col-sm-6 col-xs-12">
                      <a href="#"
                        ><img
                          src="../assets/upload/1592970808_4845069_027b5080e85cb94e64ff596de893a381.jpg"
                          style="height: 100px"
                          class="img-thumbnail"
                      /></a>
                      <p>
                        <a href="#">Điều hòa Toshiba Inverter 9000 BTU RAS</a>
                      </p>
                      <p class="price">9.190.000₫</p>
                      <div class="marsk">
                        <a href="#">Xem chi tiết</a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
            <!-- End Main -->
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "Body",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
