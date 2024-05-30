<script>
  import { page } from "$app/stores";

  $: email = $page.params.email;
</script>

<div class="hero bg-base-300">
  <div class="hero-content">
    <div class="max-w-md text-center">
      <h1>{email}</h1>
      <p>User description here</p>
      <div class="grid grid-cols-3">
        <div class="card bg-slate-700 m-4 shadow-lg shadow-blue-900">
          <div class="card-body">
            <div class="text-center">
              <img
                src={"/"}
                alt="Linkje"
                class="w-32 h-32 mx-auto bg-gray-500"
              />
              <h2>Linkje name</h2>
              <p>Magic</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
