<template>
  <Head>
    <Title>Projects | Jack Westmore</Title>
  </Head>
  <section class="md:w-2/3 lg:w-1/2">
    <h1 class="fancy-header">Stuff I've made.</h1>
    <div class="mb-2">
      <p>This website!</p>
      <ul>
        <li>Nuxt + TailwindCSS</li>
        <li>Deployed to Netlify</li>
      </ul>
      <div class="my-4">
        <p>
          <Anchor
            is-external="true"
            href="https://www.kokodri.org"
            text="kokodri.org"
          />
        </p>
        <ul>
          <li>SvelteKit + TailwindCSS</li>
          <li>Python + ChatGPT API</li>
          <li>Deployed to Netlify</li>
        </ul>
      </div>
    </div>
    <div class="my-4">
      <p>
        <Anchor
          is-external="true"
          href="https://supersonic.clothing"
          text="supersonic.clothing"
        />
      </p>
      <ul>
        <li>Next.js + TailwindCSS</li>
        <li>GraphQL + Shopify API</li>
        <li>Deployed to Vercel</li>
        <li class="italic">Work in progress</li>
      </ul>
    </div>
  </section>
</template>

<script>
import Anchor from "~/components/shared/Anchor.vue";

export default {
  components: {
    Anchor,
  },
};
</script>
