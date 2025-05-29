<template>
  <div class="home">
      <HeroAria/>
      <FeaturedCategories/>
      <Trending-product/>
      <BannerSection/>
      <SpecialOffer/>
      <HomeProductList/>
      <BrandList/>
      <BlogSection/>
      <ShippingInfo/>
  </div>
</template>

<script>
import HeroAria           from "@/components/home/HeroAria";
import FeaturedCategories from "@/components/home/FeaturedCategories";
import TrendingProduct    from "@/components/home/TrendingProduct";
import BannerSection      from "@/components/home/BannerSection";
import SpecialOffer       from "@/components/home/SpecialOffer";
import HomeProductList    from "@/components/home/HomeProductList";
import BrandList          from "@/components/home/BrandList";
import BlogSection        from "@/components/home/BlogSection";
import ShippingInfo       from "@/components/home/ShippingInfo";
export default {
  name: 'HomeView',
  components: {HeroAria,FeaturedCategories,TrendingProduct,BannerSection,SpecialOffer,HomeProductList,BrandList,BlogSection,ShippingInfo}
}
</script>
