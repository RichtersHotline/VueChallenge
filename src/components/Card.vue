<template>
    <div class="container">
    <div class="card">
            <div class="card-header">
                <slot name="cardHeader"></slot>
        </div>
            <div class="card-body">
                <slot name="cardBody"></slot>
            </div>
          </div>
        </div>
        </template>
    
    <script>
    export default {
    name: "friendsCard",
    }
    </script>
    
    <style scoped>
    .card {
    
        width:12rem;
    
    }
    </style>