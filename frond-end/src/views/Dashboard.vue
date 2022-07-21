<!-- This example requires Tailwind CSS v2.0+ -->
<template>
  <!--
    This example requires updating your template:

    ```
    <html class="h-full bg-gray-100">
    <body class="h-full">
    ```
  -->
  <div class="min-h-full">
    <Navbar />
    <Header>Dashboard</Header>
    <main>
      <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
        <!-- Replace with your content -->
        <DashboardContent />
        <!-- /End replace -->
      </div>
    </main>
  </div>
</template>

<script setup>
import Navbar from '../components/layout/Navbar.vue';
import DashboardContent from '../components/dashboard/DashboardContent.vue';
import Header from '../components/layout/Header.vue';
</script>
