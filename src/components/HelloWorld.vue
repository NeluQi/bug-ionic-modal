<!-- eslint-disable vue/no-unused-components -->
<!-- eslint-disable vue/no-deprecated-slot-attribute -->
<template>
  <div class="hello">
    <ion-button  fill="outline" id="click-trigger">Open</ion-button>
    <ion-button  >NORMAL TEXT</ion-button>
    <p>{{ message }}</p>
    <small class="text-muted mb-2 mt-4"> GOOD GOOD</small>
    <small class="text-muted mb-2 mt-4"> GOOD GOOD</small>
    BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD
 <ion-modal

                        :initial-breakpoint="0.5"
                        :breakpoints="[0, 0.25, 0.5]"
                        trigger="click-trigger"
                        trigger-action="click"
                      >
                        <ion-content class="ion-padding">
                          <div class="text-center d-flex flex-column mt-3">
                            <small class="text-muted mt-2">dfsdfssdfdsfdfs</small>
                            <ion-button  fill="outline" id="click-trigger">fdggfdsfgdsgsdrfsdfgdfg</ion-button>
                            <ion-button  >BAD TEXT</ion-button>
                            <small class="text-muted mb-2 mt-4"> BAD BAD</small>
                            BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD BAD 
                          </div>
                        </ion-content>
                      </ion-modal>

    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul>
  </div>
</template>

<script>
  import {
    IonButtons,
    IonButton,
    IonModal,
    IonHeader,
    IonContent,
    IonToolbar,
    IonTitle,
    IonItem,
    IonInput,
    IonLabel,
  } from '@ionic/vue';

export default {
  name: 'HelloWorld',
  components: {
      // eslint-disable-next-line vue/no-unused-components
      IonButtons,
      IonButton,
      IonModal,
      // eslint-disable-next-line vue/no-unused-components
      IonHeader,
      IonContent,
      // eslint-disable-next-line vue/no-unused-components
      IonToolbar,
      // eslint-disable-next-line vue/no-unused-components
      IonTitle,
      // eslint-disable-next-line vue/no-unused-components
      IonItem,
      // eslint-disable-next-line vue/no-unused-components
      IonInput,
      // eslint-disable-next-line vue/no-unused-components
      IonLabel,
    },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
