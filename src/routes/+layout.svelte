<script>
  import "../app.css";
  import { goto } from "$app/navigation";
</script>

<div class="bg-base-100 fixed top-0 left-0 right-0 bg-slate-700">
  <div class="navbar flex justify-between max-w-3xl mx-auto">
    <div>
      <a href="/" class="btn btn-ghost text-xl">Linkje</a>
      <a href="/user" class="btn btn-ghost">My Page</a>
    </div>
    <div>
      <button on:click={() => goto("/login")}>Login</button>
      <span>user@domain.com</span>
      <button on:click={() => console.log("logging out")}>Log out</button>
    </div>
  </div>
</div>

<slot />
