<template>
  <div class="wrapper">
    <aside class="sidebar-nav">
      <a href="#" class="sidebar-nav__logo"
        >Elearn<span class="orange-dot">.</span></a>
      <nav class="sidebar-nav__navigation">
        <a class="sidebar-nav__link sidebar-nav__link_active" href="/home">Главная</a>
        <a class="sidebar-nav__link" href="/about">Электротехника</a>
        <a class="sidebar-nav__link" href="#">Favorite</a>
        <a class="sidebar-nav__link" href="#">Test</a>
        <a class="sidebar-nav__link" href="#">Achievments</a>
        <a class="sidebar-nav__link" href="#">Certificate</a>
        <a class="sidebar-nav__link" href="#">Settings</a>
      </nav>
    </aside>
    <article class="main-content">
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
          Artificial
          Intelligence for Marketing
        </h2>
        <p class="main-content__subtitle">
          Learn how artificial intelligence is reshaping the way marketing is
          done at both large and small organizations.
        </p>
        <button class="main-content__button">Узнать больше</button>
      </div>
    </article>
    <aside class="sidebar-content">
    </aside>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
