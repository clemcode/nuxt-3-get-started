<template>
  <section>
    <h1>
      {{ $route.params.mountain }}
    </h1>
    <img
      :src="`/images/${$route.params.mountain}.png`"
      :alt="$route.params.mountain"
    />
  </section>
</template>
