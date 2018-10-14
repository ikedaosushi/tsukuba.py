<template>
  <section class="container">
    <div>
      <h1 class="title">
        <img
          src="~/assets/logo.png"
          alt="tsukuba.py"
        >
      </h1>
      <h2 class="subtitle">
        <p>Python/機械学習のもくもく、ときどきLT会@つくば</p>
      </h2>
      <h3>
        <p>※現在準備中です。興味ある方は主催者に連絡してください</p>
      </h3>
      <div class="links">
        <a
          href="https://twitter.com/ikedaosushi"
          target="_blank"
          class="button--grey">主催者に連絡する(Twitter)
        </a>
      </div>
    </div>
  </section>
</template>

<script>

export default {
}
</script>

<style>

.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
</style>
