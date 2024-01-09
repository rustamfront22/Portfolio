<template>
  <div class="project">
    <div class="project-content container">
      <div class="bg-project">
        <img src="@/assets/img/bg-project.png" alt="" />
      </div>
      <h2>My Projects Highlight</h2>
      <a href="https://github.com/rustamfront22"
        ><button>
          <svg
            viewBox="0 0 24 24"
            width="24"
            height="24"
            stroke="currentColor"
            stroke-width="2"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="css-i6dzq1"
          >
            <polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"></polygon>
          </svg>
          Explore me
        </button>
      </a>
      <div class="project-content-box">
        <div class="project-content-box__info">
          <a href="https://market-olive.vercel.app/"
            ><img src="@/assets/img/project-1.png" alt=""
          /></a>
          <h3>
            Market
            <div></div>
          </h3>
          <p>
            Интернет магазин на различные товары. В проекте использовал: Vue.js
            (Composition Api), Pinia, Scss, с подключением REST API
          </p>
        </div>
        <div class="project-content-box__info">
          <a href="https://githubfinder-kohl.vercel.app/"
            ><img src="@/assets/img/project-2.png" alt=""
          /></a>
          <h3>
            GitHubFinder
            <div></div>
          </h3>
          <p>
            Проект создан для поиска профилей GitHub и их проектов. В проекте
            использовал: Vue.js (Options Api), Pinia, Scss, с подключением REST
            API
          </p>
        </div>
        <div class="project-content-box__info">
          <a href="https://todolist-olive-seven.vercel.app/"
            ><img src="@/assets/img/project-3.png" alt=""
          /></a>
          <h3>
            TodoList
            <div></div>
          </h3>
          <p>
            Это веб приложение для сохранений заметок. В проекте использовал:
            Vue.js (Options Api), Scss Для сохранений данных использовал Local
            Storage
          </p>
        </div>
        <div class="project-content-box__info">
          <a href="https://wheather-ruddy.vercel.app/"
            ><img src="@/assets/img/project-4.png" alt=""
          /></a>
          <h3>
            Wheather

            <div></div>
          </h3>
          <p>
            Проект создан чтоб ты знал какая погода в твоём городе или стране. В
            проекте использовал: Vue.js (Options Api), VueX, Axios , Scss, с
            подключением REST API
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { Icon } from "@iconify/vue";
</script>
