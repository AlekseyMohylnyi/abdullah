<template>
  <div class="portfolio grid-container">
  <div class="portfolio__info a">
   <h2 class="portfolio__title">Portfolio</h2>
   <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore culpa soluta doloribus cumque minus, consectetur.</p>
  </div>
  <img class="b" src="../assets/images/portfolio-1.png" alt="">
  <img class="c" src="../assets/images/portfolio-4.png" alt="">
  <img class="d" src="../assets/images/portfolio-2.png" alt="">
  <img class="e" src="../assets/images/portfolio-5.png" alt="">
<!--  <div class="f">break</div>-->
  <img class="j" src="../assets/images/portfolio-3.png" alt="">
  <img class="h" src="../assets/images/portfolio-6.png" alt="">
</div>
</template>

<style lang="scss" scoped>
.portfolio {
    margin: 9rem;
  &__title {
    font-family: 'NightStillComes_bold';
    font-size: 4rem;
    color: var(--black);
  }
  &__info {
    color: #969696;
    font-size: 1.4rem;
    align-self: center;
    margin-left: 1rem;
    padding-right: 1rem;
  }
}


.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr 1fr;
  grid-row-gap: 3rem;
  align-items: center;
  justify-items: center;
  grid-template-areas:
    "a d ."
    "a d j"
    "b d j"
    "b d j"
    "b d j"
    "b d j"
    "b e j"
    "b e h"
    "c e h"
    "c e h"
    "c e h"
    "c e h"
    "c f h"
    "c f .";
}

.a { grid-area: a; }

.b { grid-area: b; }

.c { grid-area: c; }

.d { grid-area: d; }

.e { grid-area: e; }

.f { grid-area: f; }

.j { grid-area: j; }

.h { grid-area: h; }


</style>
