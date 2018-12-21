<template>
  <div class="search">
    <div class="search__wrapper">
      <div class="search-short__wrapper">
        <div class="search-short__section _realty-type">
          <div class="search-filter">
            <div class="search-filter__wrapper">
              <div class="search-filter__head">
                <span class="search-filter__caption">Тип недвижимости</span>
              </div>
              <div class="search-filter__body">
              </div>
            </div>
          </div>
        </div>
        <div class="search-short__section _geo">
          <div class="search-filter">
            <div class="search-filter__wrapper">
              <div class="search-filter__head">
                <span class="search-filter__caption">Новосибирск</span>
              </div>
              <div class="search-filter__body">
              </div>
            </div>
          </div>
        </div>
        <div class="search-short__section _rooms">
          <div class="search-filter">
            <div class="search-filter__wrapper">
              <div class="search-filter__head">
                <span class="search-filter__caption">Количество комнат</span>
              </div>
              <div class="search-filter__body">
              </div>
            </div>
          </div>
        </div>
        <div class="search-short__section _price">
          <div class="search-filter">
            <div class="search-filter__wrapper">
              <div class="search-filter__head">
                <span class="search-filter__caption">Цена</span>
              </div>
              <div class="search-filter__body">
              </div>
            </div>
          </div>
        </div>
        <div class="search-short__section _controls">
        </div>
      </div>
    </div>
  </div>
</template>



<style>

div {
  display: block;
}

.search {
  position: relative;
  z-index: 100;
}

.search__wrapper {
  min-width: 1000px;
  width: 906px;
  border-bottom: 1px solid #d9d9d9;
  background: #f2f2f2;
  z-index: 101;
  position: relative;
}

.search-short__wrapper {
  width: 906px;
  box-sizing: border-box;
  position: relative;
  z-index: 90;
  margin-left: auto;
  margin-right: auto;
  max-width: none;
  padding: 12px 0 18px;
}

._realty-type, ._geo, ._rooms, ._price, ._controls {
  display: inline-block;
  vertical-align: top;
}

.search-short__section._realty-type {
  width: 15.23179%;
}

.search-filter {
font-size: 15px;
line-height: 18px;
color: #000;
}

.search-filter__head {
  margin-bottom: 6px;
}

</style>
