<script>
  import Modal from "./Modal.svelte";

  export let message;
</script>

<Modal title="An error occoured!" on:cancel>
  <p>{message}</p>
</Modal>
