<template>
  <div class="container">
    <div class="row">
      <div class="col-xs-12">
        <app-header></app-header>
      </div>
    </div>
    <hr />
    <div class="row">
      <div class="col-xs-12 col-sm-6">
        <ul class="list-group">
          <li class="list-group-item" v-for="index in 5">
            Server #{{ index }}
          </li>
        </ul>
      </div>
      <div class="col-xs-12 col-sm-6">
        <p>Server Details are currently not updated</p>
      </div>
    </div>
    <hr />
    <div class="row">
      <div class="col-xs-12">
        <app-footer></app-footer>
      </div>
    </div>
  </div>
</template>

<script></script>

<style></style>
