<script>
</script>

<div class="w-fit h-fit px-10 py-5 rounded border-black border-x border-y bg-white shadow-2xl grid grid-rows-6 gap-4">
  <div class="row-span-1 grid place-content-center">
    <h2 class="text-2xl font-extralight">DRES Interface</h2>
  </div>
  <div class="row-span-4 grid grid-rows-2">
    <div class="flex flex-col">
      <label class="text-lg font-extralight" for="username">Username</label>
      <input class="rounded border-black border-x border-y" type="text" name="username" id="username">
    </div>
    <div class="flex flex-col">
      <label class="text-lg font-extralight" for="password">Password</label>
      <input class="rounded border-black border-x border-y" type="password" name="password" id="password">
    </div>
  </div>
  <div class="row-span-1 grid place-content-center">
    <input class="text-lg font-extralight px-2 py-1 rounded border-black border-x border-y hover:cursor-pointer hover:shadow hover:bg-gray-300" type="button" value="Log in" on:click={()=>alert("Hellow")}>
  </div>
</div>
