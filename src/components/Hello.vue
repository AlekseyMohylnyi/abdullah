<template>
  <section class="hello">
    <div class="hello__inner">
     <h3 class="hello__subtitle">Hello</h3>
     <h2 class="hello__title">I'm Abdullah Noman</h2>
     <p class="hello__text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Maiores at voluptatum aut rerum veritatis, velit consequatur repellat ipsam nostrum, accusantium commodi inventore recusandae beatae dolorem, ex debitis atque tempore eum. Velit consequatur repellat ipsam nostrum, accusantium commodi inventore recusandae beatae dolorem, ex debitis atque tempore eum.</p>
     <a href="#" class="hello__btn">
      <span>View Works</span>
      <img src="../assets/images/arrow_down_icon.svg" alt="arrow">
     </a>
    </div>
    <div class="hello__img">
      <img src="../assets/images/lamp.png" alt="">
    </div>
  </section>
</template>


<style lang="scss" scoped>
.hello {
    background-color: var(--grey);
    color: var(--black);
    padding: 10rem 0 11.5rem 12.5rem;
    display: grid;
    grid-template-columns: 1fr 1fr;
    margin-left: 9rem;
  &__inner {
    padding-top: 12%;
  }
  &__subtitle {
    font-family: 'Stackyard_PERSONAL_USE';
    font-size: 3rem;
    color: var(--black);
  }
  &__title {
    font-family: 'NightStillComes_mine';
    font-size: 3rem;
    color: var(--black);
  }
  &__text {
    font-family: 'NightStillComes_mine';
    font-size: 1.5rem;
    color: #969696;
    margin: 2.5rem 0 4rem 0;
    z-index: 100;
  }
  &__btn {
    border: 1px solid var(--black);
    border-radius: 40px;
    padding: 1rem 1.5rem;
    text-align: center;
    font-size: 1.5rem;
      span {
          margin-right: 1.5rem;
        }
      img {
          width: 24px;
          height: 24px;
          margin-bottom: -5px;
      }
      transition: all .3s ease;
       &:hover {
          background-color: #c0c0c0;
        }
  }
    &__img {
     padding-left: 15%;
     position: relative;
     z-index: 100;
    }
    &__img:after {
     content: '';
     width: 312px;
     height: 468px;
     position: absolute;
     left: -10%;
     bottom: -10%;
     border: 3px solid #cccccc;
     z-index: -100;
    }
}
</style>
