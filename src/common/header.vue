<template>
  <div class="header-box">
    <h1>{{ msg }}</h1>
    <ul>
      <li>
        <a
          href="http://www.baidu.com"
          target="_blank"
        >
          Core Docs
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
  import 'element-ui/lib/theme-default/index.css'
  export default {
    name: 'header-box',
    data () {
      return {
        msg: 'HEADER'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
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
