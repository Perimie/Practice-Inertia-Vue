<template>
    <h1>
        <div>
            {{title}} 
        </div>
    </h1>
    
    </template>
    
    <script setup>
    
    defineProps({
    title: {
        type: String,
    },
    
});
    </script>