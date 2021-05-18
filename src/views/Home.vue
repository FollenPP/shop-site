<template>
  <!-- <div class="main-contener">
  	<header class="header">
  		<a href="#" class="header-logo">Elearn<span class="orange-dot">.</span></a>
      <img src="../assets/img/search.png" class="search_icon" alt="">
  		<input type="text" placeholder="Введите ваш запрос" class="header-serchbar">
  		<div class="header-profile">
  			<img src="../assets/img/avatar2.png" alt="" class="header-profile__avatar">
  			<p class="header-profile__name">Имя аккаунта</p>
  			<p class="header-profile__status">Premium account</p>
  			<button class="header-profile__notification"><img src="../assets/img/notification.png" alt=""></button>
  			<button class="shop-notification"><img src="#" alt=""><img src="../assets/img/notification.png" alt=""></button>
  		</div>

  	</header>
  </div> -->

  <div class="wrapper">
    <div class="sidebar-nav">
      <a href="#" class="sidebar-nav__logo"
        >Elearn<span class="orange-dot">.</span></a
      >
      <nav class="sidebar-nav__navigation">
        <a class="sidebar-nav__link" href="#">Главная</a>
        <a class="sidebar-nav__link" href="#">Электротехника</a>
        <a class="sidebar-nav__link" href="#">Favorite</a>
        <a class="sidebar-nav__link" href="#">Test</a>
        <a class="sidebar-nav__link" href="#">Achievments</a>
        <a class="sidebar-nav__link" href="#">Certificate</a>
        <a class="sidebar-nav__link" href="#">Settings</a>
      </nav>
    </div>
    <div class="main-content">
      <div class="main-content__searchbar">
        <img
          src="../assets/img/search.png"
          alt=""
          class="main-content__searchbar-icon"
        />
        <input
          type="text"
          placeholder="Введите ваш запрос"
          class="main-content__searchbar-field"
        />
      </div>
      <div class="main-content__slider">
        <img
          src="../assets/img/slider-img.png"
          alt=""
          class="main-content__img"
        />
        <h2 class="main-content__title">
          Artificial<br />
          Intelligence for Marketing
        </h2>
        <p class="main-content__subtitle">
          Learn how artificial intelligence is reshaping the way marketing is
          done at both large and small organizations.
        </p>
        <button class="main-content__button">Узнать больше</button>
      </div>
      <div class="main-content__example-products">
        <h2 class="main-content__title"></h2>
        <div class="main-content__cart">
          <h3 class="main-content__title-cart"></h3>
          <img src="#" alt="" class="main-content__img-cart" />
          <p class="main-content__category-cart"></p>
          <p class="main-content__comment-cart"></p>
          <img src="#" alt="" class="main-content__rating-cart" />
          <img src="#" alt="" class="main-content__lastReview-cart" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
