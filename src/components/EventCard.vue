<script setup>

const event = ref(
    {
        id:1,
        category : "animal welfare",
        title : "animal",
        des : "animal welfare",
        category : "animal welfare",
        category : "animal welfare",
        category : "animal welfare",
        category : "animal welfare",
        category : "animal welfare",
    }
)
</script>

<template>
 <div class="event-card"></div>
</template>

<style scoped>
.event-card{
    padding: 20px;
    width: 250px;
    cursor: pointer;
    border: 1px solid;
    margin-bottom: 18px;
}
.event-card:hover{
    transform: scale(1.01);
    box-shadow: 0 3px 12px 0 rgba(0,0,0,0.2);
}
</style>
