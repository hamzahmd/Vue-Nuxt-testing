<!-- <template>
  <div v-if="error" style="color: red">Error :{{ error }}</div>
  <div v-else-if="isFetching" style="color: blue">loading...</div>
  <div v-else="error" style="color: green">{{ data }}</div>
  <input type="number" v-model="id" />
</template>

<script setup lang="ts">
import { ref, computed } from 'vue';
import { useFetch } from '@vueuse/core';
const id = ref(1);
const url = computed(() => {
  return `https://jsonplaceholder.typicode.com/todos/${id.value}`;
});
const { isFetching, data, error } = useFetch(url, {
  refetch: true,
});
</script> -->
