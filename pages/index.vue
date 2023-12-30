<template>
    <MainLayout>
      <div d="IndexPage" class="mt-4 max-w-[1200px] mx-auto px-2"></div>
        <div class = "grid xl:grid-cols-5 md:grid-cols-4 sm:grid-cols-3 grid-cols-2 gap-4">
            <div v-if ="products" v-for="product in products" :key:string="product">
              
              <ProductComponent :product ="product"/>
            </div>
        </div>
    </MainLayout>
</template>

<script lang="ts" setup>
import MainLayout from '~/layouts/MainLayout.vue';

const products:object = [
  {
    id:1,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:1,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:2,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:3,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:4,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:5,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:1,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:1,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:1,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
  {
    id:1,
    title:"Title 1",
    description: "This is a description",
    url: "https://picsum.photos/id/7/800/800",
    price: 1000,
  },
]
</script>

