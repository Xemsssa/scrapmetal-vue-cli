
<template>
  <div>
    <Header/>
    <banner-vue/>
    <our-services-vue/>
    <our-clients-vue/>
    <footer-vue/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import BannerVue from './components/Banner.vue';
import OurServicesVue from './components/OurServices.vue';
import OurClientsVue from './components/Our Clients.vue';
import FooterVue from './components/Footer.vue';

export default {
  name: "app",
  components: {
    Header,
    BannerVue,
    OurServicesVue,
    OurClientsVue,
    FooterVue
  }
};

</script>

<style>

html, body {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Open Sans', sans-serif;
}

.container {
    max-width: 1140px;
    margin: 0 auto;
}

.text_color {
    color: #f76b40; 
}


.text_align {
    /* color: #f76b40;  */
    text-align: center;
}


.font_bold {
    font-weight: bold;
}

.background_color {
    background-color: #f76b40;
}

.button_theme {
    color: #fff;
}

.icon_margin {
    margin-right: 10px;
}

.padding_zero {
    padding: 0;
}

.margin_bottom_small {
    margin-bottom: 20px !important;
}

.margin_bottom_big{
    margin-bottom: 30px !important;
}

.padding_bottom_small {
    padding: 20px 0;
}


.padding_bottom_big {
    padding: 20px 0;
}

@media (min-width: 455px) {
    
  .margin_bottom_small {
      margin-bottom: 20px !important;
  }

  .margin_bottom_big{
      margin-bottom: 70px !important;
  }

  .padding_bottom_small {
      padding: 20px 0;
  }

  .padding_bottom_big {
      padding: 50px 0;
  }
}

.header_text {
    text-align: center;
}
</style>
