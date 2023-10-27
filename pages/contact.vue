<template>
    <section class="w-1/2">
        <h1 class="fancy-header">Get in touch.</h1>
        <div class="mb-2">
      <p>Emails are the best way to get in touch :-)</p>
      <ul>
        <li><Anchor is-external="true" href="mailto:jackwestmore@gmail.com" text="send me mail" /></li>
      </ul>
      </div>
      <div class="my-4">
      <p>If you're interested specifically in my poetry:</p>
      <ul>
        <li><Anchor is-external="true" href="https://mrmikardo.substack.com/" text="check out my newsletter" /></li>
      </ul>
      </div>
      <div class="my-4">
        <p>Other places you can find me:</p>
      <ul>
        <li><Anchor is-external="true" href="https://www.linkedin.com/in/jackwestmore/" text="linkedin" /></li>
        <li><Anchor is-external="true" href="https://github.com/mrmikardo" text="github" /></li>
        <li><Anchor is-external="true" href="https://twitter.com/93odradek" text="twitter" /></li>
      </ul>
      </div>
    </section>
  </template>

<script>
import Anchor from '~/components/shared/Anchor.vue';

export default {
  components: {
    Anchor,
  },
};
</script>