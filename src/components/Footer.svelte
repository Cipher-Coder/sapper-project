<script>
  const getYear = new Date().getFullYear();
</script>

<style>
  .footer-class {
    position: relative;
    padding: 5px 20px;
    text-align: center;
    color: rgba(255, 255, 255, 0.8);
    background-color: #111111;
  }

  .copysign {
    display: inline-block;
    margin-right: 15px;
  }

  .email-link {
    color: rgba(255, 255, 255, 0.8);
  }

  .email-link:hover {
    color: green;
  }
</style>

<footer class="footer-class">
  <p>
    <span class="copysign">
      ©
      <span class="copyYear">{getYear}</span>
      Mattaz Web Design
    </span>
    <a class="email-link" href="mailto:matthew@mattaz.com">
      matthew@mattaz.com
    </a>
  </p>
</footer>
