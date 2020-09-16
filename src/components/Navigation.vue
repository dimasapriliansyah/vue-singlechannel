<template>
  <nav class="navigation">
    <div class="nav-group">
      <ul>
        <li>
          <a class="logo" href="#">
            <img src="img/white-logo.png" class="img_logo" />
          </a>
        </li>
        <li>
          <a data-navigation-target="chats" class="active" href="javascript:nav_chat()">
            <i class="ti-comment-alt"></i>
          </a>
        </li>
        <li>
          <a data-navigation-target="chat_agent" href="javascript:nav_agent()" id="chat_agent">
            <i class="material-icons">group</i>
          </a>
        </li>
        <li>
          <a data-navigation-target="favorites" href="#">
            <i class="fa fa-history"></i>
          </a>
        </li>
        <li data-navigation-target="#" class="brackets">
          <a href="#">
            <i class="fa fa-user"></i>
          </a>
        </li>
        <li>
          <a href="#" data-toggle="modal" data-target="#settingModal">
            <i class="ti-settings"></i>
          </a>
        </li>
        <li>
          <a href="./login.html">
            <i class="ti-power-off"></i>
          </a>
        </li>
      </ul>
    </div>
  </nav>
</template>