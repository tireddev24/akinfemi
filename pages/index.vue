<template>
  <Head>
    <Title>Akinfemi</Title>
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, maximum-scale=1"
    />
  </Head>

  <div
    class="bg-[#263238] lg:min-h-screen min-h-screen md:min-h-screen overflow-x-hidden"
  >
    <Navbar />
    <Background />
    <Heading />
    <Skills />
  </div>
</template>

<script setup>
import Background from "../components/Background.vue";
import Heading from "../components/Home/Heading.vue";
import Skills from "../components/Home/Skills.vue";

const router = useRouter();
</script>
