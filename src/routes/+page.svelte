<script>
    export let data
</script>

<style>
  :global(body) {
    margin: 0;
    font-family: Arial, sans-serif;
  }

  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #333;
    padding: 1rem;
    animation: slideDown 0.5s ease-in-out;
  }

  .navbar .logo {
    color: #fff;
    font-size: 1.5rem;
  }

  .navbar .links {
    display: flex;
    gap: 1rem;
  }

  .navbar .links a {
    color: #fff;
    text-decoration: none;
    font-size: 1rem;
  }

  .navbar .links a:hover {
    text-decoration: underline;
  }

  @keyframes slideDown {
    from {
      transform: translateY(-100%);
    }
    to {
      transform: translateY(0);
    }
  }

  .welcome-box {
    background: rgba(255, 255, 255, 0.8);
    padding: 2rem;
    margin: 2rem auto;
    max-width: 600px;
    text-align: center;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
</style>

<nav class="navbar">
  <div class="logo">Nonprofit Logo</div>
  <div class="links">
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/how-to-help">How to Help</a>
    <a href="/members">Members</a>
    <a href="/contact">Contact</a>
  </div>
</nav>

<div class="welcome-box">
  <h1>Learning is for all, coding is no exception.</h1>
</div>
