<template>
  <section class="section">
    <div class="container">
      <div class="columns">
        <div class="column mr-5 px-0 py-0 box">
          <nav class="panel is-danger">
            <p class="panel-heading">Каталог</p>
            <a class="panel-block is-active">
              <span class="panel-icon">
                <fa icon="shopping-bag" aria-hidden="true" />
              </span>
              Сумки
            </a>
            <a class="panel-block">
              <span class="panel-icon">
                <fa icon="tshirt" aria-hidden="true" />
              </span>
              Ветровки
            </a>
            <a class="panel-block">
              <span class="panel-icon">
                <fa icon="vest" aria-hidden="true" />
              </span>
              Жилеты
            </a>
            <a class="panel-block">
              <span class="panel-icon">
                <fa icon="hand-middle-finger" aria-hidden="true" />
              </span>
              Мешочки
            </a>
            <a class="panel-block">
              <span class="panel-icon">
                <fa icon="hand-middle-finger" aria-hidden="true" />
              </span>
              Пледы
            </a>
            <a class="panel-block">
              <span class="panel-icon">
                <fa icon="hand-middle-finger" aria-hidden="true" />
              </span>
              Подушки
            </a>
          </nav>
        </div>

        <div class="column is-9 box">
          <p class="title">Content</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ASidebarContent',
}
</script>

<style lang="scss" scoped>
.panel-block {
  padding: 12px;
}
</style>
