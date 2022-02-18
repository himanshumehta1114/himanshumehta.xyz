<script>
  export let name;
</script>

<main>
  <div class="social-handles">
    <img src="https://placekitten.com/40/40" alt="Twitter logo" />
    <img src="https://placekitten.com/40/40" alt="Twitter logo" />
    <img src="https://placekitten.com/40/40" alt="Twitter logo" />
  </div>

  <h1>Hi, I'm {name}</h1>
  <p>
    Based in Hisar, India. I work in the UX Engineering team as a Senior
    Software Engineer in Gojek.
  </p>
  <p>
    I build tools to support design system and improve frontend development
    experience in Gojek.
  </p>
  <p>I like playing badminton 🏸 &nbsp; and building mechanical keyboads ⌨️</p>
</main>

<style>
  .social-handles {
    margin: 1rem 0;
    margin-left: 4px;
  }

  main {
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  p {
    margin: 2rem 0;
    font-size: 1.2em;
    color: navy;
  }

  h1 {
    margin-top: 3rem;
    color: #ff3e00;
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
