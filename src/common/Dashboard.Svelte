<style type="text/scss">
  @import "../styles/global.scss";

  .sidebar {
    z-index: 100;
    min-height: 100vh;
    text-align: center;
    display: flex;
    justify-content: space-between;
    flex-direction: column;
  }
  .navbar-sticky {
    position: sticky;
  }
  .list-group-item list-group-item-action bg-light {
    color: $light;
  }

  .img {
    width: 250px;
    height: 250px;
  }

  .so-img {
    width: 100%;
  }

  .sidebar-link {
    text-transform: uppercase;
    font-weight: 600;
  }

  .text-lg {
    font-size: 22px;
  }
</style>

<main>

  <nav class="sidebar bg-light border-right">
    <div class="intro px-2 py-4">
      <img class="rounded-circle img" src="/assets/profile.jpg" />
      <h1 class="text-dark pt-2">Eduardo Vargas</h1>
      <h3 class="text-primary">Software Developer</h3>
    </div>
    <div class="list-group list-group-flush">
      <a
        href="#"
        class="text-dark list-group-item list-group-item-action bg-light
        sidebar-link border-top text-lg">
        Blog
      </a>
      <a
        href="#"
        class="text-dark list-group-item list-group-item-action bg-light
        sidebar-link border-top text-lg">
        About
      </a>
      <a
        href="#"
        class="text-dark list-group-item list-group-item-action bg-light
        sidebar-link border-top text-lg">
        Projects
      </a>

    </div>

    <a href="https://stackexchange.com/users/5023246/eduardo-vargas">
      <img
        src="https://stackexchange.com/users/flair/5023246.png"
        class="so-img"
        alt="profile for Eduardo Vargas on Stack Exchange, a network of free,
        community-driven Q&amp;A sites"
        title="profile for Eduardo Vargas on Stack Exchange, a network of free,
        community-driven Q&amp;A sites" />
    </a>
  </nav>

</main>
