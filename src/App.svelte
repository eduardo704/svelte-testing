<script>
  import Dashboard from "./common/Dashboard.svelte";
  import Home from "./features/Home.svelte";
</script>

<style type="text/scss" global>
  @import "./styles/global.scss";
</style>

<main>
  <div class="container-fluid">
    <div class="row">
      <div class="col-sm-3 px-0">
        <Dashboard />
      </div>
      <div class="col-sm-9 bg-info">
        <Home />
      </div>
    </div>
  </div>
</main>
