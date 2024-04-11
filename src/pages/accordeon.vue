<script 
setup lang="ts" 
>
import { ref } from 'vue'
const sectionOpen = ref(1)
</script>

<template>
  <section>
    <button class="text-xl" @pointerdown="sectionOpen=1">bouton 1</button>
    <p v-show="sectionOpen===1">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quisquam iusto facilis, unde, nostrum obcaecati explicabo enim iste corrupti, ad tempore odio velit iure est quidem voluptatem cumque molestias voluptas laudantium.</p>
  </section>
  <section>
    <button class="text-xl" @pointerdown="sectionOpen=2">bouton 2</button>
    <p v-show="sectionOpen===2">Mollitia dignissimos dolores laudantium cum excepturi odit velit commodi! Aperiam, enim tempore assumenda obcaecati repudiandae dolore perspiciatis laudantium amet praesentium est, minima officia eos vel at tenetur veritatis atque earum.</p>
  </section>
  <section>
    <button class="text-xl" @pointerdown="sectionOpen=3">bouton 3</button>
    <p v-show="sectionOpen===3">Accusantium quia odit recusandae obcaecati ipsa illo exercitationem dolorum corrupti facilis, deleniti tempore sequi dolore minima inventore ab voluptatem? Quod possimus dolore facere dignissimos! Enim ullam aliquam voluptatibus nihil eveniet?</p>
  </section>
</template>
