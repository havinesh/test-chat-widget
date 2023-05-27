<!-- <script>
  export let name;
  let count = 0;
  const clickFn = () => {
    count++;
  };

  // Get references to the chat widget and its components
  // const chatWidget = document.querySelector(".chat-widget");
  // const chatBtn = chatWidget.querySelector(".chat-btn");
  // const chatContainer = chatWidget.querySelector(".chat-container");
  // const chatForm = chatWidget.querySelector("form");
  // const chatName = chatWidget.querySelector("#name");
  // const chatMessage = chatWidget.querySelector("#message");

  // Hide the chat container by default
  // chatContainer.style.display = "none";

  // // Show/hide the chat container when the button is clicked
  // chatBtn.addEventListener("click", function () {
  //   chatContainer.style.display =
  //     chatContainer.style.display === "none" ? "block" : "none";
  // });

  // // Handle form submission
  // chatForm.addEventListener("submit", function (event) {
  //   event.preventDefault();
  //   // Send the form data to the server (replace this with your own code)
  //   const data = {
  //     name: chatName.value,
  //     message: chatMessage.value,
  //   };
  //   console.log(data);
  //   // Reset the form
  //   chatForm.reset();
  // });
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>
  <div class="chat-widget">
    <button class="chat-btn">Chat</button>
    <div class="chat-container">
      <h2>Chat with us!</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" />
        <label for="message">Message:</label>
        <textarea id="message" name="message" />
        <button type="submit">Send</button>
      </form>
    </div>
  </div>
  <button on:click={clickFn}>total number of click = {count}</button>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  .chat-widget {
    position: fixed;
    bottom: 20px;
    right: 20px;
    z-index: 9999;
  }

  .chat-btn {
    background-color: #0084ff;
    color: #fff;
    border: none;
    border-radius: 50%;
    width: 50px;
    height: 50px;
    font-size: 24px;
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.25);
    cursor: pointer;
    transition: all 0.3s ease-in-out;
  }

  .chat-btn:hover {
    background-color: #0066cc;
  }

  .chat-container {
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.25);
    padding: 20px;
  }

  .chat-container h2 {
    font-size: 18px;
    margin-top: 0;
  }

  .chat-container label {
    display: block;
    margin-bottom: 5px;
  }

  .chat-container input[type="text"],
  .chat-container textarea {
    width: 100%;
    padding: 10px;
    border-radius: 3px;
    border: 1px solid #ccc;
    margin-bottom: 10px;
    resize: none;
  }

  .chat-container button[type="submit"] {
    background-color: #0084ff;
    color: #fff;
    border: none;
    border-radius: 3px;
    padding: 10px;
    cursor: pointer;
    transition: all 0.3s ease-in-out;
  }

  .chat-container button[type="submit"]:hover {
    background-color: #0066cc;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style> -->

<script>
  // import ChatWidget from "./ChatWidget.svelte";
  // import Havinesh from "./havinesh.svelte";
</script>

<!-- <ChatWidget /> -->

<div>hi</div>
