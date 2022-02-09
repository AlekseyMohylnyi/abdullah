<template>
  <section class="intro">
  <h2 class="intro__subtitle">
      The
  </h2>
  <h1 class="intro__title">
      abdullah noman
  </h1>
  <h4 class="intro__info">
      User Interface & User Experience Designer
  </h4>
  <a href="#" class="intro__btn">
      Hire Now
  </a>
  <a href="#" class="intro__arrow">
      <img src="../assets/images/bottom-arrow.svg" alt="">
  </a>
</section>
</template>

<script>
export default {
  name: 'Intro'
}
</script>

<style scoped lang="scss">
.intro {
    text-align: center;
    padding-top: 15%;
    padding-bottom: 2%;
    display: grid;
    grid-template-rows: auto;
    background-image: url(../assets/images/header-bg.png);
    background-position: center;
    background-size: cover;
    &__subtitle {
      font-family: 'Stackyard_PERSONAL_USE';
      font-size: 60px;
      color: var(--white);
      line-height: 22px;
      margin-bottom: 2rem;
    }
    &__title {
      font-family: 'Lato-Light';
      font-size: 40px;
      color: var(--white);
      text-transform: uppercase;
      letter-spacing: 2rem;
      line-height: normal;
    }
    &__info {
      font-family: 'NightStillComes_mine';
      font-size: 18px;
      color: var(--white);
      line-height: normal;
      letter-spacing: 3px;
      margin-top: 7px;
    }
    &__btn {
      border: 1px solid var(--white);
      border-radius: 40px;
      padding: 16px 40px;
      font-size: 18px;
      max-height: 55px;
      max-width: 170px;
      margin: 2rem auto 15%;
      transition: all .3s ease;
      color: var(--white);
        &:hover {
          border-color: var(--black);
          color: var(--black);
          background-color: var(--white);
        }
    }    
}
</style>
