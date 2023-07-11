<template>
  <div class="home">
     <HeaderiStoreSaidhFJ />
      <!-- Hero Section Begin -->
    <section class="hero-section">
        <carousel  class="hero-items" :items="1" :nav="false" >
            <div  class="single-hero-items set-bg" style="background-image: url('/Item/BT21.jpg')" >
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>BT21</span>
                            <h1>BT21 series</h1>
                            <p>
                                Ayo lengkapi koleksi mu dengan merchandise karakter BT21 dimana lagi kalau bukan di BT21 Merchandise!
                            </p>
                            <a href="#" class="primary-btn">Buy Now</a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="single-hero-items set-bg"  style="background-image: url('/img/BT21.png')">
                <div class="container">
                    <div class="row">
                        <div class="col-lg-5">
                            <span>BT21</span>
                            <h1>Find Your Characters</h1>
                            <p>
                                Ayo lengkapi koleksi mu dengan merchandise karakter BT21 dimana lagi kalau bukan di BT21 Merchandise!
                            </p>
                            <a href="#" class="primary-btn">Buy Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </carousel >
    </section>
    <!-- Hero Section End -->


  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue';
import HeaderiStoreSaidhFJ from '@/components/HeaderiStoreSaidhFJ.vue';
import carousel from 'vue-owl-carousel';

export default {
  name: 'Home',
  components: {
   HeaderiStoreSaidhFJ,
   carousel 
  }
};
</script>
