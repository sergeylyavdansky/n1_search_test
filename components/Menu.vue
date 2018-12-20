<template>
  <div class="top-panel__content">
    <div class="top-panel__wrapper">
      <div class="top-panel__logo">
        <img src="/logo.png" alt="N1.RU" width="140" height="40"/>
      </div>
      <nav role="navigation" class="top-panel__menu">
        <ul class="top-panel-menu">
          <li class="top-panel-menu__item"><span class="top-panel-menu__text">Продажа</span></li>
          <li class="top-panel-menu__item"><span class="top-panel-menu__text">Аренда</span></li>
          <li class="top-panel-menu__item"><span class="top-panel-menu__text">Новостройки</span></li>
          <li class="top-panel-menu__item"><span class="top-panel-menu__text">Статьи</span></li>
          <li class="top-panel-menu__item"><span class="top-panel-menu__text">Оценка</span></li>
          <li class="top-panel-menu__item"><span class="top-panel-menu__text">Компании</span></li>
        </ul>
      </nav>
      <div class="top-panel__user">
        <ul class="user-nav-bar">
          <li class="user-nav-bar__item">
            <div class="user-nav-bar__btn">
              <div class="user-nav-bar__icon"></div>
                <div class="user-nav-bar__text">Личный кабинет</div>
              </div>
            </li>
        </ul>
      </div>
    </div>
  </div>
</template>



<style>

.top-panel__content {
  position: relative;
  background: #fff;
  height: 56px;
  width: 100%;
  outline: 2px solid red;
}

  .top-panel__wrapper {
   box-sizing: border-box;
   position: relative;
   z-index: 90;
   margin-left: auto;
   margin-right: auto;
   max-width: none;
   display: flex;
   height: 100%;
  }
    
.top-panel__logo {
    display: flex;
    flex-shrink: 0;
    flex-grow: 0;
    flex-basis: auto;
    align-items: center;
  }

.top-panel__menu {
    display: flex;
    flex-shrink: 1;
    flex-grow: 1;
    flex-basis: auto;
    min-width: 0;
}

.top-panel-menu__item {
    vertical-align: top;
    display: inline-block;
    height: 100%;
}

.top-panel-menu__text {
    position: relative;
    display: inline-block;
    box-sizing: border-box;
    padding-top: 12px;
    color: #000;
    height: 100%;
}

.top-panel__user {
    display: flex;
    flex-shrink: 0;
    flex-grow: 0;
    flex-basis: auto;
    height: 100%;
}

.user-nav-bar {
    height: 100%;
    margin-top: -2px;
}

nav ol, nav ul {
    list-style: none;
    list-style-image: none;
}

li {
    list-style: none;
    list-style-image: none;
}

.user-nav-bar__icon:before {
    content: "";
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-position: 50% 50%;
    background-size: 100% 100%;
    opacity: .5;
    background-image: src('/icon.png');
}
</style>
