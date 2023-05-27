<script>
  // import AiOutlineMessage from "@react-icons/ai";

  // import ChatBox from "./ChatBox.svelte";
  // import Havinesh from "./havinesh.svelte";
  // import Test from "./test.svelte";

  // import { FaBeer } from "react-icons/fa";
  let showComponent = false;
  function componentVisible() {
    showComponent = !showComponent;
  }
</script>

<div>
  <button on:click={componentVisible}>hi</button>
  {#if showComponent}
    <div>hi</div>
    <!-- <ChatBox /> -->
    <!-- <Test /> -->
    <!-- <Havinesh /> -->
  {/if}
</div>
