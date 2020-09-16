<template>
  <div id="chats" class="sidebar w-300 active">
    <header class="bg-green">
      <span>Chats</span>
    </header>
    <div class="sidebar-body" tabindex="2" style="overflow: hidden; outline: none;">
      <ul class="list-group list-group-flush">
        <li class="list-group-item">
          <figure class="avatar">
            <span class="avatar-title bg-green1 rounded-circle">NF</span>
          </figure>
          <div class="users-list-body">
            <h6 class="label-name">Nada Fadhilah Fitriyani</h6>
            <p class="label-date">Wed, 28 Jan 2020 at 20:32:12</p>
            <div class="users-list-action">
              <div class="new-message-count"></div>
            </div>
          </div>
        </li>
        <li class="list-group-item open-chat">
          <div>
            <figure class="avatar">
              <span class="avatar-title bg-pink rounded-circle">YH</span>
            </figure>
          </div>
          <div class="users-list-body">
            <h6 class="label-name">Yolanda Hutajulu</h6>
            <p class="label-date">Wed, 28 Jan 2020 at 20:32:12</p>
            <div class="users-list-action">
              <div class="new-message-count"></div>
            </div>
          </div>
        </li>

        <li class="list-group-item">
          <div>
            <figure class="avatar">
              <span class="avatar-title bg-purple rounded-circle">JH</span>
            </figure>
          </div>
          <div class="users-list-body">
            <h6 class="label-name">Jashinta Shanindita</h6>
            <p class="label-date">Wed, 28 Jan 2020 at 20:32:12</p>
            <div class="users-list-action">
              <div class="new-message-count"></div>
            </div>
          </div>
        </li>
        <li class="list-group-item">
          <div>
            <figure class="avatar">
              <span class="avatar-title bg-orange rounded-circle">MH</span>
            </figure>
          </div>
          <div class="users-list-body">
            <h6 class="label-name">Mumtaz Haya W</h6>
            <p class="label-date">Wed, 28 Jan 2020 at 20:32:12</p>
            <div class="users-list-action">
              <div class="new-message-count"></div>
            </div>
          </div>
        </li>
        <li class="list-group-item">
          <div>
            <figure class="avatar">
              <span class="avatar-title bg-gray1 rounded-circle">SO</span>
            </figure>
          </div>
          <div class="users-list-body">
            <h6 class="label-name">Selvie Oktaviani</h6>
            <p class="label-date">Wed, 28 Jan 2020 at 20:32:12</p>
            <div class="users-list-action">
              <div class="new-message-count"></div>
            </div>
          </div>
        </li>
        <li class="list-group-item">
          <div>
            <figure class="avatar">
              <span class="avatar-title bg-cyan rounded-circle">AA</span>
            </figure>
          </div>
          <div class="users-list-body">
            <h6 class="label-name">Annisa Aldinah</h6>
            <p class="label-date">Wed, 28 Jan 2020 at 20:32:12</p>
            <div class="users-list-action">
              <div class="new-message-count"></div>
            </div>
          </div>
        </li>
      </ul>
    </div>
    <queue></queue>
  </div>
</template>

<script>
import Queue from "./Queue.vue";

export default {
  name: "Workorder",
  components: {
    Queue,
  },
};
</script>