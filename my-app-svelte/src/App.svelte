<script>
  // @ts-nocheck

  Neutralino.init();
</script>

<main>
  <!-- svelte-ignore missing-declaration -->
  <button
    on:click={async () => {
      await Neutralino.app.exit();
    }}>quit</button
  >
  <!-- svelte-ignore missing-declaration -->
  <button
    on:click={async () => {
      await Neutralino.filesystem.writeFile("./myFile.txt", "Sample content");
    }}>create file</button
  >
</main>
