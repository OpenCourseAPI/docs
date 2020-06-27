<template>
  <div class="api">
    <p class="demo">
      <span class="api-path">{{ msg }}</span>
      <span class="description">Get a single course from the database</span>
      <span class="spacer"></span>
      <button class="action-button" v-on:click="sendRequest">Send API Request</button>
    </p>
    <pre><code class="json">{{ json }}</code></pre>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        msg: '/fh/single',
        json: '{ "message": "Nothing loaded yet... try clicking the button below!" }',
      }
    },
    methods: {
      sendRequest: async function () {
        this.json = JSON.stringify(await (await fetch('https://opencourse.dev/fh/single?dept=CS&course=2A')).json(), undefined, 2)
      }
    },
  }
</script>
