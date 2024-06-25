<script setup>
    import TheWelcom from '@/components/home/TheWelcom.vue';
</script>

<template>
    <main>
        <TheWelcom/>
    </main>
</template>

<style scoped>
  main {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 70%;
    margin-top: 1.5%;
    margin-left: auto;
    margin-right: auto;
    border: 1px dotted;
    background-color: #f0f8ff; /* 배경색 추가 */
    padding: 20px; /* 내용물과의 간격을 위해 패딩 추가 */
    border-radius: 10px; /* 모서리를 둥글게 */
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* 그림자 효과 추가 */
  }
</style>
