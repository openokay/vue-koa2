<template>
  <div class="home">
    <shopping-mail />
  </div>
</template>

<script>
// @ is an alias to /src
import ShoppingMail from '@/components/pages/ShoppingMail.vue'

export default {
  name: 'home',
  components: {
    ShoppingMail
  }
}
</script>
