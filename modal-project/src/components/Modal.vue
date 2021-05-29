<template>
  <div class='backdrop'>
    <div class="modal">
      <p>Modal Content</p>
    </div>
  </div>
</template>

<style>
.modal {
  width:400;
  padding: 20px;
  margin: 100px auto;
  background: white;
  border-radius: 10px;
}
.backdrop {
  top: 0;
  position: fixed;
  background: black;
  width: 100%;
  height: 100%;
}
</style>
