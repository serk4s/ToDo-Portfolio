<template>
  <div class="about">
    <div class="about-header">
      <h1>О ПРОЕКТЕ</h1>
    </div>

    <div class="about-main-text">
      <p>
        Мой ToDo - это лишь демонстрация моих возможностей работы с Vue
      </p>
      <p>
        Основная цель приложения — предоставить пользователю максимально <b>Ту-Душную Ту-Душку</b>.
        Это же <b>Ту-Душка</b>, но теперь по дургому. Хоть дизайн изменился
      </p>
    </div>

    <div class="about-details">
      <h3>ОСОБЕННОСТИ</h3>
      <ul>
        <li>Асимметричный Grid Layout</li>
        <li>Строгая монохромная тема</li>
        <li>Переключение светлой/темной темы</li>
        <li>Авторизация и сохранение данных</li>
        <li>Редактирование задач</li>
      </ul>
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
ul {
  list-style: none;
  padding: 0;
}
ul li {
  padding: 5px 0;
  text-transform: uppercase;
  font-weight: 300;
}
</style>