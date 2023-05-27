<div class="chat">
  <div class="chat_header">
    <img
      class="chat_avatar"
      src="http://www.naturaloil.ph/wp-content/uploads/2015/11/John_Doe.jpg"
      alt="avatar"
    />JOHN DOE
    <div class="chat_status">ONLINE</div>
  </div>
  <div class="chat_s">
    <div class="chat_bubble-1">Hi</div>
    <div class="chat_bubble-1">How are you?</div>
    <div class="chat_bubble-2">Fine. What about you?</div>
    <div class="chat_bubble-1">I'm great. Wanna meet?</div>
    <div class="chat_bubble-2">Sure</div>
    <div class="chat_bubble-2">I'll see you soon</div>
    <div class="chat_bubble-1">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla volutpat
      augue ac ultrices malesuada. Fusce varius urna id dignissim vestibulum.
      Integer rutrum, purus sit amet tincidunt molestie, diam dui pulvinar
      nulla, rhoncus facilisis elit mi sit amet lorem.
    </div>
    <div class="chat_bubble-2">Huh?</div>
    <div class="chat_bubble-1">Just Testing &#x1F609;</div>
  </div>
  <div class="chat_input">
    <input placeholder="Type here..." class="chat_text" /><button
      onclick="add()"
      class="chat_submit fa fa-send"
    />
  </div>
</div>

<style>
  @import "https://fonts.googleapis.com/css?family=Montserrat";
  body {
    height: 100%;
    margin: 0;
    padding: 0;
    background: url(http://kriswhitewrites.com/wp-content/uploads/2013/06/landscape-mountains-snow-sky.jpg);
    background-size: cover;
    background-position: bottom;
  }
  .chat {
    width: 400px;
    height: 80vh;
    box-shadow: 0 0 30px -5px grey;
    /* margin: 10vh calc(50vw - 200px); */
    margin-left: 20px;
    background: #fafafa;
    position: relative;
    font-family: "Montserrat", sans-serif;
  }
  .chat_header {
    padding: 15px;
    border-bottom: 4px solid teal;
    background: #f0f0f0;
    color: teal;
  }
  .chat_status {
    font-size: 11px;
    margin: 4px 0 -4px;
  }
  .chat_avatar {
    float: right;
    width: 42px;
    border-radius: 50%;
    margin-top: -3px;
  }
  .chat_input {
    position: absolute;
    bottom: 0;
    width: calc(100% - 8px);
    padding: 10px 4px 6px;
    background: #c8c8c8;
  }
  .chat_text {
    width: calc(85% - 10px);
    padding: 10px;
    box-sizing: border-box;
    margin: 0 5px 5px;
    vertical-align: top;
    font-family: "Montserrat", sans-serif;
  }
  .chat_submit {
    width: calc(15% - 5px);
    padding: 10px;
    box-sizing: border-box;
    margin: 0 5px 5px 0;
    vertical-align: top;
    border: 1px solid teal;
    cursor: pointer;
    color: teal;
    border-radius: 0 8px 8px 0;
    transition: all 0.4s;
  }
  .chat_submit:hover {
    background: teal;
    color: #fff;
  }
  .chat_bubble-1,
  .chat_bubble-2 {
    padding: 10px;
    margin: 13px 17px;
    width: 200px;
    font-size: 14px;
  }
  .chat_bubble-1 {
    border: 1px solid teal;
    border-radius: 12px 12px 12px 0;
  }
  .chat_bubble-2 {
    border: 1px solid grey;
    border-radius: 12px 12px 0 12px;
    margin-left: 160px;
  }
  .chat_s {
    max-height: calc(75vh - 86px - 29px);
    overflow-y: scroll;
    padding: 15px 0 0;
  }
  ::-webkit-scrollbar {
    width: 13px;
  }
  ::-webkit-scrollbar-thumb {
    border-radius: 10px;
    -webkit-box-shadow: inset 0 0 0 4px #fff;
    background: rgba(0, 0, 0, 0.2);
  }
</style>
