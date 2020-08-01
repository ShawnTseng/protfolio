<template>
  <v-container>
    <h1>Version:v1.0.1</h1>    
    <br />

    <h1>Category</h1>
    <a href="https://shawntseng.github.io/vue-protfolio/" target="_blank">Vue Related</a>    
    <a href="https://shawntseng.github.io/react-protfolio/" target="_blank">React Related</a>    
    <br />

    <h1>Keyword memo</h1>
    <ul>
        <li>NestJs(server-side)</li>
        <li>Angular+NestJs</li>
    </ul>
    <br />
    <h1>Library</h1>
    <ul>
        <li>bulma(UI framework)</li>
        <li>date-fns(data handle)</li>
        <li>axios(http)</li>
        <li>json-server(simple db)</li>
        <li>mocha(unit test)</li>
    </ul>
  </v-container>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({
      ecosystem: [
        {
          text: 'vuetify-loader',
          href: 'https://github.com/vuetifyjs/vuetify-loader',
        },
        {
          text: 'github',
          href: 'https://github.com/vuetifyjs/vuetify',
        },
        {
          text: 'awesome-vuetify',
          href: 'https://github.com/vuetifyjs/awesome-vuetify',
        },
      ],
      importantLinks: [
        {
          text: 'Documentation',
          href: 'https://vuetifyjs.com',
        },
        {
          text: 'Chat',
          href: 'https://community.vuetifyjs.com',
        },
        {
          text: 'Made with Vuetify',
          href: 'https://madewithvuejs.com/vuetify',
        },
        {
          text: 'Twitter',
          href: 'https://twitter.com/vuetifyjs',
        },
        {
          text: 'Articles',
          href: 'https://medium.com/vuetify',
        },
      ],
      whatsNext: [
        {
          text: 'Explore components',
          href: 'https://vuetifyjs.com/components/api-explorer',
        },
        {
          text: 'Select a layout',
          href: 'https://vuetifyjs.com/getting-started/pre-made-layouts',
        },
        {
          text: 'Frequently Asked Questions',
          href: 'https://vuetifyjs.com/getting-started/frequently-asked-questions',
        },
      ],
    }),
  }
</script>
