---
title: "JewelryShine: Каталог украшений"
type: "docs"
date: 2025-04-09
draft: false
---

# JewelryShine: Каталог украшений

Добро пожаловать в наш каталог ювелирных украшений! Здесь вы можете выбрать изысканные изделия и оформить заказ.

<style>
  .jewelry-catalog {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
  }
  .jewelry-item {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: center;
    width: 150px;
  }
  .jewelry-item img {
    width: 100px;
    height: 100px;
  }
  .cart-button {
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    margin: 20px 0;
  }
  .cart-button:hover {
    background-color: #0056b3;
  }
  .filters {
    margin-bottom: 20px;
  }
</style>

<div class="filters">
  <label>Фильтры: </label>
  <select>
    <option>Все категории</option>
    <option>Кольца</option>
    <option>Серьги</option>
    <option>Браслеты</option>
  </select>
  <select>
    <option>Все цены</option>
    <option>До 10 000 ₽</option>
    <option>10 000 - 50 000 ₽</option>
    <option>Свыше 50 000 ₽</option>
  </select>
</div>

<div class="jewelry-catalog">
  <div class="jewelry-item">
    <img src="https://via.placeholder.com/100?text=Кольцо" alt="Кольцо">
    <p>Золотое кольцо</p>
    <p>15 000 ₽</p>
    <button>Купить</button>
  </div>
  <div class="jewelry-item">
    <img src="https://via.placeholder.com/100?text=Серьги" alt="Серьги">
    <p>Серебряные серьги</p>
    <p>8 000 ₽</p>
    <button>Купить</button>
  </div>
  <div class="jewelry-item">
    <img src="https://via.placeholder.com/100?text=Браслет" alt="Браслет">
    <p>Браслет с бриллиантами</p>
    <p>45 000 ₽</p>
    <button>Купить</button>
  </div>
</div>

<button class="cart-button">Корзина</button>