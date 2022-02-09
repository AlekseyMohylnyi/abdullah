<template>
<section class="reviews">
  <div class="reviews__inner">
    <!-- <img class="reviews__img" src="../assets/images/footer-bg.png" alt="footer"> -->
    <p class="reviews__text">Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem.</p>
    <div class="reviews__name">Ahmed Hasan</div>
    <div class="reviews__job">Carsive Studio</div>
  </div>  
</section>
</template>


<style lang="scss" scoped>
.reviews {    
  margin-top: 200px;   
  position: relative;
  background-image: url(../assets/images/footer-bg.png);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  text-align: center; 
  padding: 135px 85px;     
  z-index: 100;    
  color: #fff;
      
   
    &:after {
        content: '';
        width: 100%;
        height: 100%;
        position: absolute;
        left: 10rem;
        top: -6rem;
        border: 5px solid #cccccc;    
        z-index: -100;    
      }
    &:before {
        content: '';
        width: 100%;
        height: 100%;
        position: absolute;
        left: 0;
        top: 0;         
        background-color: #000; 
        opacity: .3;
      }   
    &__text {
      font-family: 'NightStillComes_mine';
      font-size: 1.5rem;
      margin-bottom: 4rem;
    }
    &__name {
      font-family: 'NightStillComes_mine';
      font-size: 3rem;
    }
}

</style>
