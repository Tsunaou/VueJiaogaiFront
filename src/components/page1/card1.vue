<template>
  <div>
    <div class="card">
      <div class="card__container card__container--closed">
        <svg class="card__image" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 1920 500" preserveAspectRatio="xMidYMid slice">
          <defs>
            <clipPath id="clipPath1">
              <polygon class="clip" points="0,500 0,0 1920,0 1920,500"></polygon>
            </clipPath>
          </defs>
          <image clip-path="url(#clipPath1)" width="1920" height="500" xlink:href="../../../static/img/a.jpg"></image>
        </svg>
        <div class="card__content">
          <i class="card__btn-close fa fa-arrow-left">点击此处返回</i>
          <div class="card__caption">
            <h2 class="card__title">Tristan and Isolde</h2>
            <p class="card__subtitle">A modern day love story</p>
          </div>
          <div class="card__copy">
            <div class="meta">
              <img class="meta__avatar" src="../../../static/img/authors/1.png" alt="author01" />
              <span class="meta__author">Gerry Sutherland</span>
              <span class="meta__date">06/19/2015</span>
            </div>
            <page1-card1-content></page1-card1-content>
          </div>
        </div>
      </div>
    </div><!--Card1-->
  </div>
</template>

<script>
  import Page1Card1Content from "./card1-content";
  export default {
    name: 'page1card1',
    components: {Page1Card1Content},
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

