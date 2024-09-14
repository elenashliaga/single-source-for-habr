# О сервисе

{% if  project == 'cloud' %}

**{{ product-name }}** — это универсальный инструмент для управления партнерской программой вашей компании или удобный интерфейс для работы аналитика, блогера, агента. Статистика, работа с партнерами, работа с финансами, гибкие интеграции — все это на одной платформе.

{% elsif project == 'raif' %}

**{{ product-name }}** — это универсальный инструмент для управления партнерской программой вашей компании или удобный интерфейс для работы партнеров. Статистика, работа с финансами, гибкие интеграции — все это на одной платформе.

{% endif %}

<div class="grid-container">
    <div class="grid-item">
        <h3>GoCPA: BLOGGERS</h3>
        <p>Продукт для работы с партнерскими программами для блогеров</p>
    </div>
    <div class="grid-item">
        <h3>GoCPA: PRM</h3>
        <p>Расширение функций кабинета рекламодателя</p>
    </div>
    <div class="grid-item">
        <h3>GoCPA: AGENTS/MLM</h3>
        <p>Отдельный бизнес-процесс работы для агентов</p>
    </div>
</div>
<div class="grid-container">
    <div class="grid-item">
        <h3>GoCPA: Analytics</h3>
        <p>Дополнительный инструмент для аналитики</p>
    </div>
    <div class="grid-item">
        <h3>Работа с отчетами</h3>
        <p>Просмотр и анализ отчетов</p>
    </div>
    <div class="grid-item">
        <h3>Работа с API</h3>
        <p>Доступные методы API</p>
    </div>
</div>
<div class="grid-container">
    <div class="grid-item">
        <h3>Защита от уязвимостей</h3>
        <p>Безопасность контура</p>
    </div>
    <div class="grid-item">
        <h3>Онбординг партнера</h3>
        <p>Инструкция по регистрации нового партнера</p>
    </div>
    <div class="grid-item">
        <h3>Биллинг</h3>
        <p>Взаимодействие с iContext</p>
    </div>
</div>
<div class="grid-container">
    <div class="grid-item">
        <h3>ОРД</h3>
        <p>Передача данных и организация работы с ОРД</p>
    </div>
</div>

<style>
.grid-container {
  display: flex;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  column-gap: 50px;
  row-gap: 20px;
}
.grid-container > div {
    margin: 10px;
    height: 87px;
    width: 331px;
}
h2 {
  padding-top: 32px !important;
  margin-top: 0 !important;
}
h3 {
  padding-top: 8px !important;
  margin-top: 0 !important;
}
</style>

<script>alert(document.lastModified);</script>