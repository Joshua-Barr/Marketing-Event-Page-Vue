<template>
  <div class="copyright-copyright" v-bind:class="rootClassName">
    <div class="copyright-max-width">
      <span class="copyright-text">
        <span class="copyright-text01">
          <span>
            © All rights reserved
            <span v-html="raws9tl"></span>
          </span>
          <span><span v-html="rawbg24"></span></span>
        </span>
        <a
          href="https://www.teleporthq.io"
          target="_blank"
          rel="noreferrer noopener"
        >
          <span class="copyright-text04">@TeleportHQ.</span>
        </a>
        <span class="copyright-text05">
          <span>
            Powered by
            <span v-html="rawsiwt"></span>
          </span>
          <span><span v-html="rawvmta"></span></span>
        </span>
        <a
          href="https://www.vercel.com"
          target="_blank"
          rel="noreferrer noopener"
        >
          <span class="copyright-text08">Vercel</span>
        </a>
        <span class="copyright-text09">
          <span>
            . Image source:
            <span v-html="rawkjq7"></span>
          </span>
          <span><span v-html="raw14y7"></span></span>
        </span>
        <a
          href="https://www.unsplash.com"
          target="_blank"
          rel="noreferrer noopener"
        >
          <span class="copyright-text12">Unsplash</span>
        </a>
        <span class="copyright-text13">.</span>
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Copyright',
  props: {
    rootClassName: String,
  },
  data() {
    return {
      raws9tl: ' ',
      rawbg24: ' ',
      rawsiwt: ' ',
      rawvmta: ' ',
      rawkjq7: ' ',
      raw14y7: ' ',
    }
  },
}
</script>

<style scoped>
.copyright-copyright {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-twounits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-twounits);
}
.copyright-max-width {
  align-items: stretch;
}
.copyright-text {
  font-size: 14px;
  font-style: normal;
  font-weight: 300;
  line-height: 1.5;
}
.copyright-text01 {
  font-style: normal;
  font-weight: 300;
}
.copyright-text04 {
  font-style: normal;
  font-weight: 300;
  text-decoration: underline;
}
.copyright-text05 {
  font-style: normal;
  font-weight: 300;
}
.copyright-text08 {
  font-style: normal;
  font-weight: 300;
  text-decoration: underline;
}
.copyright-text09 {
  font-style: normal;
  font-weight: 300;
}
.copyright-text12 {
  font-style: normal;
  font-weight: 300;
  text-decoration: underline;
}
.copyright-text13 {
  font-style: normal;
  font-weight: 300;
}
@media(max-width: 991px) {
  .copyright-max-width {
    flex-direction: column;
  }
}
</style>
