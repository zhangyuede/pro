<template>
    <div>
        <slotVue>
            <template v-slot:header>
                <h1>Here might be a page title</h1>
            </template>
            <template v-slot:default>
                <p>A paragraph for the main content.</p>
            </template>
            <template v-slot:footer>
                <p>Here's some contact info</p>
            </template>
        </slotVue>
    </div>
</template>

<script>
import slotVue from './slot.vue'
export default {
  name: 'HomeView',
  components: {
    slotVue
  }
}
</script>
