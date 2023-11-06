# drop-down
a easy drop down components
## install
main.js
```js
import Vue from 'vue'
import App from './App.vue'
import DropDown from "../drop-down";

Vue.use(DropDown);

new Vue({
  render: h => h(App),
}).$mount('#app')

```
## usage
```Vue
<DropDown>
  <h1>你好</h1>
  <div slot="overlay" class="menu"></div>
</DropDown>
```