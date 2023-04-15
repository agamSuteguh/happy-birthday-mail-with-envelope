<template>
 <div v-show="letter" :class="{ open: isOpen }" @click="toggleOpen(); letterClose(); start()">
    <p class="sender">from: Ur Boyfriend</p>
    <div class="carda">
      <div class="heart">
        <div class="break">
        </div>
      </div>
    </div>
  </div>
 
</template>

<script>

</script>
