<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h1>Connect</h1>
    <ul>
      <li>
        <a
          id="lk"
          href="https://www.linkedin.com/in/clement-ng-b6b48669/"
          target="_blank"
          rel="noopener"
          ><img
            class="img-responsize img-circle logo"
            id="logos"
            src="../assets/lk.png"
          />
        </a>
      </li>
      <li>
        <a
          id="git"
          href="https://github.com/clementgng"
          target="_blank"
          rel="noopener"
          ><img
            class="img-responsize img-circle logo"
            id="logos"
            src="../assets/git.png"
        /></a>
      </li>
    </ul>

    <span>
      <form method="POST" action="http://formspree.io/cgng16@gmail.com">
        <input type="email" name="_replyto" /><textarea name="body"></textarea
        ><input type="submit" value="Send" />
      </form>
    </span>

    <span class="rights container-fluid bottom">
      <p>Copyright © 2020 ClementNg Design</p>
    </span>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
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
