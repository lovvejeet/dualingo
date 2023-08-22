<template>
  <link href="https://db.onlinewebfonts.com/c/3ecce11ea34c149bb63c0c2ba1cc131d?family=DINRoundWeb+W04+Medium"
    rel="stylesheet">

   
  
    <div class="main">

      <div :class="{ 'header': true, 'fixed-header': isHeaderFixed }">
        <header class='header-main'>

          <a href="" class="header-main__logo">
            <img class="header-main__logo-duo-1"  src="../src/assets/420logo.svg" alt="logo">
            <img class="header-main__logo-duo-2" src="../src/assets/duoLOGO.svg" alt="logo">
          </a>

          <button class="header-main__light">log in</button>
          <button class="header-main__dark">sign up</button>

          <button class="header-main__humburger">
            <span class="header-main__humburger-span">
              <img src="../src/assets/humburger.svg" alt="">
            </span>

          </button>

<!-- visible after breakpints 768px X 1023px hits -->
          <div class="secondary__select-lan">
                    <span class="secondary__lan-span">
                        <button class="secondary__sel-btn">
                            Site language
                        </button>
                    </span>
                </div>
      <!-- end of this -->

        </header>
     
      </div>


<!-- visible after breakpints 768px X 1023px hits -->

<div :class="{ 'secondary': true, 'sec-fixed': isSecondaryFixed }">

  <div v-if="isSecondaryFixed" class="secondary__small-logo">
        <img src="../src/assets/420logo.svg" alt="Small Logo">
      </div>
                <nav class="secondary__lists">

                    <span class="secondary__all-lists">
                    <span class="secondary__list1">
                        Taking the Test
                    </span>
                    <span class="secondary__list2">
                        Accepting the Test
                    </span>
                    <span class="secondary__list3">
                        Test Research
                       </span>

                      </span>
                </nav>

                <div class="secondary__main-btn">
                    <a class="secondary__pri-light">log in</a>
                    <a class="secondary__pri-dark">sign up</a>
                </div>


            </div>

      <!-- end of navbar -->
      
      <div class="home">
        <div class="home__primary">
          <section class="home__section">
            <div class="home__details">
              <div class="home__details__side-img-1">
                <img class="home__details__side-1" src="../src/assets/sideImage.svg" alt="">
              </div>

              <div class="home__heading--main">
                <h1 class="home__heading--main__h1">
                  <span class="home__heading--main__span-1">
                    Certify your English proficiency
                    <span class="home__heading--main__span-2">
                      today
                    </span>
                    .
                  </span>
                </h1>


                <div class="home__lists">
                  <ul class="home__ul">
                    <li class="home__li">
                      <img src="../src/assets/check.svg" alt="" class="home__li-img">
                      <p class="home__li-p">Test online anytime, anywhere</p>
                    </li>
                    <li class="home__li">
                      <img src="../src/assets/check.svg" alt="" class="home__li-img">
                      <p class="home__li-p">Finish in 1 hour and get results in 2 days</p>
                    </li>
                    <li class="home__li">
                      <img src="../src/assets/check.svg" alt="" class="home__li-img">
                      <p class="home__li-p">Accepted by over 4000 universities</p>
                    </li>
                  </ul>

                </div>

                <div class="home__practice">
                  <button class="home__practice-btn">
                    <span class="home__practice-btn-span">
                      practice free
                    </span>
                  </button>
                </div>
              </div>

            </div>
          </section>

          <div class="universities">
            <div class="universities__main">
              <div class="universities__images">
                <div class="universities__animate">

                  <img alt="" src="../src/assets/animation/img1.svg" class="universities__animate-imgs">
                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img2.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img3.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img4.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img5.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img6.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img7.svg" class="universities__animate-imgs">
                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img8.svg" class="universities__animate-imgs">
                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img9.svg" class="universities__animate-imgs">
                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img10.svg" class="universities__animate-imgs">
                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img1.svg" class="universities__animate-imgs">
                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img2.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img3.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img4.svg" class="universities__animate-imgs">

                </div>
                <div class="universities__animate">
                  <img alt="" src="../src/assets/animation/img5.svg" class="universities__animate-imgs">

                </div>
              </div>
            </div>

            <div class="universities__main  universities__2222  ">
            <div class="universities__images-2">
              <div class="universities__animate  ">
                <img alt="" src="../src/assets/animation/img7.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img2.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img9.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img6.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img1.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img3.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img8.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img4.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img5.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img10.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img2.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img4.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img5.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img3.svg" class="universities__animate-imgs">
              </div>
              <div class="universities__animate">
                <img alt="" src="../src/assets/animation/img1.svg" class="universities__animate-imgs">
              </div>
            </div>
         </div>
          </div>
          </div>
           </div>
             


              <div class="primary">
        <div class="primary__content">
          <div></div>
          <section class="primary__section">
            <h2 class="primary__section-h2">On demand, anywhere in the world</h2>

            <div class="primary__section-boxes">

              
                <div class="primary__box1">
                  <div class="primary__box-img">
                    <img src="../src/assets/3-box-images/g1.svg" alt="" class="primary__box-image">
                  </div>
                  <div class="primary__box-details">
                    <h3 class="primary__box-details-h3">Convenient</h3>
                    <p class="primary__box-details-p">Take the test online anywhere, anytime — no traveling to a test center or appointment needed</p>
                  </div>
                 

                </div>
                <div class="primary__box1">
                  <div class="primary__box-img">
                    <img src="../src/assets/3-box-images/g2.svg" alt="" class="primary__box-image">
                  </div>
                  <div class="primary__box-details">
                    <h3 class="primary__box-details-h3">Fast</h3>
                    <p class="primary__box-details-p">Get your results within 2 days of completing the test, and share it with anyone, immediately</p>
                  </div>

              
                </div>
                <div class="primary__box1">
                  <div class="primary__box-img">
                    <img src="../src/assets/3-box-images/g3.svg" alt="" class="primary__box-image">
                  </div>
                  <div class="primary__box-details">
                    <h3 class="primary__box-details-h3">Affordable</h3>
                    <p class="primary__box-details-p">A fraction of the cost of other tests. Send your scores to an unlimited number of institutions for free!</p>
                  </div>
                </div>
             </div>
          </section>
<div></div>

<div class="result">
  <img src="../src/assets/3-box-images/flying.svg" alt="" class="result__flying-img">

  <div class="result__details" :style="{ backgroundImage: `url(${require('@/assets/send.svg')})` }">

    <h1 class="result__h1">Send results to every school on your list for free</h1>
    <div class="result__para-div">
      <p class="result__p">
        Thousands of universities around the world accept the Duolingo English Test. You can send your results to as many of them as you want, for free.
      </p>
    </div>

    <div class="result__view">
      <button class="result__button">
       <span class="result__btn_span">
           VIEW INSTITUTIONS
       </span>
      </button>
    </div>

  </div>
</div>



<section class="time">
  <div class="time__content">
    <div class="time__sideimg">
      <img src="../src/assets/clock-images/side-2.svg" alt="" class="time__side-image">
    </div>

    <div class="time__details-main">
     <h1 class="time__h1">Accurate results in minutes</h1>
     <div class="time__details-container">
      <div class="time__all">
        <div class="time__box">
          <img src="../src/assets/clock-images/time1.svg" alt="" class="time__clock">
        <div class="time__box-content">
          <h4 class="time__h4">
            Quick setup
          </h4>
          <div class="time__minutes">
            5 MINUTES
          </div>
        </div>
        <p class="time__p">
          An introduction that walks you through the test rules and requirements
        </p>
        </div>

        <div class="time__box">
          <img src="../src/assets/clock-images/time2.svg" alt="" class="time__clock">
        <div class="time__box-content">
          <h4 class="time__h4">
            Adaptive test
          </h4>
          <div class="time__minutes">
            45 MINUTES
          </div>
        </div>
        <p class="time__p">
          A series of different questions that evaluate your English skills
        </p>
        </div>
        <div class="time__box">
          <img src="../src/assets/clock-images/time3.svg" alt="" class="time__clock">
        <div class="time__box-content">
          <h4 class="time__h4">
            Writing and speaking sample
          </h4>
          <div class="time__minutes">
            10 MINUTES
           </div>
        </div>
        <p class="time__p">
          Open-ended prompts that are shared with institutions alongside your score
        </p>
        </div>
      </div>
     </div>
    
     <div class="time__watch">
   <button class="time__watch-btn">
    <div class="time__watch-div-btn">
       <img src="../src/assets/clock-images/youtube.svg" alt="" class="time__yt-logo">
    <p class="time__watch-btn-p">WATCH WALKTHROUGH VIDEO</p>
  </div></button>
     </div>


    </div>

  </div>
</section>
<div></div>

<div class="card">
  <h1 class="card__h1">Get started</h1>

  <p class="card__p">
    Sign up now and certify your English proficiency today. Test online anytime, anywhere. Finish in 1 hour and get results in 2 days. Share your results with 4,000+ institutions.
  <img src="../src/assets/card-1.svg" alt="" class="card__img-1">
  <img src="../src/assets/card-2.svg" alt="" class="card__img-2">
</p>

<div class="card__buttons">
  <button class="card__btn">
    <span class="card__btn-span">
      PRACTICE FREE
    </span>
  </button>
  <button class="card__btn">
    <span class="card__btn-span">
      PURCHASE A TEST
    </span>
  </button>
</div>
</div>






        </div>
      </div>
    </div>

</template>





<script>
export default {
  data() {
    return {
      isHeaderFixed: false,
      isSecondaryFixed: false,
      scrollThreshold: 5,
    };
  },
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
    window.addEventListener("resize", this.handleResize);
  },
  beforeUnmount() {
    window.removeEventListener("scroll", this.handleScroll);
    window.removeEventListener("resize", this.handleResize);
  },
  methods: {
    handleScroll() {
      this.isHeaderFixed = window.innerWidth < 768 && window.scrollY > this.scrollThreshold;
      this.isSecondaryFixed = window.innerWidth >= 768 && window.scrollY > this.scrollThreshold;
      this.isSmallLogoVisible = this.isSecondaryFixed;
    },
    handleResize() {
      this.isHeaderFixed = window.innerWidth < 768;
      this.isSecondaryFixed = window.innerWidth >= 768;
    },
  },
};
</script>