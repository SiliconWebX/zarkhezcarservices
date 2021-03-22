<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>
      ✔️ Accidental Car Work | ✔️ Car Luhari Work | ✔️ Car Painting | ✔️ Car
      Repairing
    </h3>

    <h3>
      ✔️ एक्सीडेंट कार का काम | ✔️ कार लोहारी काम | ✔️ कार कलर काम | ✔️ कार
      रिपेयरिंग काम
    </h3>

    <h3>
      ✔️ ગાડી એક્સિડન્ટ કામ | ✔️ ગાડી લુહારી કામ | ✔️ ગાડી કલર કામ | ✔️ ગાડી
      રીપેરીંગ કામ
    </h3>

    <a style="text-decoration: none" href="https://maps.google.com">
      <h4>🗺️ Near Shital Hotel, Sanand Sarkhej Road, Sarkhej</h4>
    </a>

    <h4>⌚ Monday – Saturday (10AM to 8PM)</h4>

    <a style="text-decoration: none" href="tel:+91-7383532740">
      <h4>📱 +91-8200553504 | +91-7383532740</h4>
    </a>

    <a style="text-decoration: none" href="tel:+91-8200553504">
      <h4>💬 +91-8200553504 (WhatsApp)</h4>
    </a>

    <ul>
      <li>
        <a
          style="text-decoration: none"
          href="tel:+91-9898065298"
          target="_blank"
          rel="noopener"
          >💻 Silicon WebX</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "zarkhez",
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
