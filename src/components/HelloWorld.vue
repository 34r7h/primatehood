<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Allow me to introduce a concept called <b>Proof of Primate</b>.</p>
    <p>Proof of Primate is required to interact in the Apeverse. Thanks to <img style="height: 120px" src="https://global-uploads.webflow.com/62a124d5fa609b4d1aaa0385/62e015c1253c2cc783af4ace_logo.svg">, we can now prove beyond any doubt
      that your friend is indeed the Ape they say they are!</p>
    <p>Our native tokens are bananas. You may receive 2.5 or more bananas with every click.
      <a download="mad_bananas.jpg"
        href="https://groomsfarm.co.uk/wp-content/uploads/2020/04/bunch-of-bananas-on-wooden-background-GN6YMF7-scaled.jpg">Click
        here for bananas</a>
    </p>
    <p>Besides healthy living, bananas play an essential role in the Apeverse. Money is boring and barely cleans our digestive tract so we only accept bananas as payment, gifts, and art.</p>
    <p>If you'd like to proove your primateness, find @34r7h around your favorite networks!</p>
    

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
  color: #e0e92a;
}</style>
