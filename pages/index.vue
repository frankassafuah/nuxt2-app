<template>
  <div>
    <carousel />
    <div class="py-5 container">
      <div class="row">
        <div class="col-md-12 text-center">
          <h1 class="main-heading">About us</h1>
          <div class="underline mx-auto"></div>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sit,
            quisquam. Lorem ipsum, dolor sit amet consectetur adipisicing elit.
            Officia, excepturi voluptates! Eveniet dolore laborum id! Lorem
            ipsum, dolor sit amet consectetur adipisicing elit. Officia,
            excepturi voluptates! Eveniet dolore laborum id!
          </p>
        </div>
      </div>
    </div>
    <div class="py-5 bg-gray">
      <div class="container">
        <div class="row">
          <div class="col-md-12 text-center">
            <h1 class="main-heading">Our Services</h1>
            <div class="underline mx-auto"></div>
          </div>
          <div class="col-md-4">
            <div class="box-card">
              <img
              style="width: 350px; height: 300px;"
                src="/images/image-from-rawpixel-id-381821-jpeg.jpg"
                alt=""
              />
              <div class="box-card-body">
                <h3 class="box-card-heading">Web Designing</h3>
                <div class="underline"></div>
                <p>
                  Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet
                  consectetur adipisicing.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="box-card">
              <img
              style="width: 350px; height: 300px;"
                src="/images/image-from-rawpixel-id-381821-jpeg.jpg"
                alt=""
              />
              <div class="box-card-body">
                <h3 class="box-card-heading">Web Designing</h3>
                <div class="underline"></div>
                <p>
                  Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet
                  consectetur adipisicing.
                </p>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="box-card">
              <img
              style="width: 350px; height: 300px;"
                src="/images/image-from-rawpixel-id-381821-jpeg.jpg"
                alt=""
              />
              <div class="box-card-body">
                <h3 class="box-card-heading">Web Designing</h3>
                <div class="underline"></div>
                <p>
                  Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet
                  consectetur adipisicing.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
  head() {
    return {
      title: "Home Page",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Nuxt Js website designing from scratch",
        },
      ],
    };
  },
};
</script>
