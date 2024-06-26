<script>
  import { page } from "$app/stores";

  $: email = $page.params.email;
</script>

<div class="hero min-h-screen bg-base-300">
  <div class="hero-content">
    <div class="max-w-2xl text-center">
      <h1>{email}</h1>
      <p>User description</p>
      <div class="grid grid-cols-3">
        <div class="card bg-slate-700 m-4 shadow-lg shadow-blue-200">
          <div class="card-body">
            <div class="text-center">
              <!-- svelte-ignore a11y-img-redundant-alt -->
              <img
                src={"soon.png"}
                alt="image"
                class="w-32 h-32 mx-auto bg-gray-500"
              />
              <h2 class="text-white text-2xl font-bolf">Name</h2>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
