<script>
  export let name;
</script>

<main>
  <div class="social-handles">
    <a
      href="https://www.twitter.com/himanshu_1114"
      target="_blank"
      class="social-link twitter"
    >
      <svg width="32" height="32" viewBox="0 0 800 800" title="Twitter link" role="img"
        ><path
          d="M679 239s-21 34-55 57c7 156-107 329-314 329-103 0-169-50-169-50s81 17 163-45c-83-5-103-77-103-77s23 6 50-2c-93-23-89-110-89-110s23 14 50 14c-84-65-34-148-34-148s76 107 228 116c-22-121 117-177 188-101 37-6 71-27 71-27s-12 41-49 61c30-2 63-17 63-17z"
        /></svg
      >
    </a>
    <a href="https://github.com/himanshumehta1114" target="_blank" title="GitHub link" role="img">
      <svg
        height="32"
        aria-hidden="true"
        viewBox="0 0 16 16"
        version="1.1"
        width="22"
        data-view-component="true"
        class="social-link github"
      >
        <path
          fill-rule="evenodd"
          d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"
        />
      </svg>
    </a>
  </div>
  <h1>Hi, I'm {name}</h1>
  <p>
    Based in Hisar, India. I am Software Engineer (IC4) working in Risk Platform team at <a href="https://www.coinbase.com/" target="_blank" title="Coinbase">Coinbase</a>.
  </p>
  <p>
    I build exciting products to solve problems in the crypto Risk space like Credit risks, Frauds etc.
  </p>

  <h2>PAST</h2>
  <p>Design Systems at <a href="https://gojek.io" target="_blank" title="Gojek">Gojek</a>.</p>

  <h2>INTERESTS</h2>
  <p>I like to play badminton and build mechanical keyboards.</p>
  <small>
    <a href="mailto:himanshumehta1114@gmail.com">himanshumehta1114@gmail.com</a>
    | <a href="tel:+919034441114">+91-9034441114</a>
  </small>
</main>

<style>
  .social-handles {
    margin-top: 2rem;
  }

  .social-link {
    fill: rgb(0,0,0, 0.6);
    transition: 0.2s;
  }

  .twitter:hover {
    fill: rgb(29, 155, 240);
  }

  .github:hover {
    fill: #161b22;
  }

  main {
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  a {
    color: navy;
  }

  p {
    margin: 2rem 0;
    font-size: 1.2em;
  }

  h1 {
    color: #e06d10;
    font-size: 3em;
    font-weight: 200;
  }

  @media (min-width: 640px) {
    main {
      max-width: 80%;
    }

    p {
      max-width: 40%;
      letter-spacing: 2px;
      line-height: 1.5;
    }
  }
</style>
