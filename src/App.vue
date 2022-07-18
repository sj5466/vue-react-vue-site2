<template>
  <HeaderSection/>
  <SliderSection/>
  <ImageSection/>
  <ImgTextSection/>
  <TextSection/>
  <BannerSection/>
  <CardSection/>
  <FooterSection/>
</template>
<script>
import HeaderSection from "./components/HeaderSection.vue";
import SliderSection from "./components/SliderSection.vue";
import ImageSection from "./components/ImageSection.vue";
import ImgTextSection from "./components/ImgTextSection.vue";
import TextSection from "./components/TextSection.vue";
import BannerSection from "./components/BannerSection.vue";
import CardSection from "./components/CardSection.vue";
import FooterSection from "./components/FooterSection.vue";

export default{
   name:'app',
    components:{
      HeaderSection,
      SliderSection,
      ImageSection,
      ImgTextSection,
      TextSection,
      BannerSection,
      CardSection,
      FooterSection,
    }

}
</script>
<style>
@import "./App.css";
</style>