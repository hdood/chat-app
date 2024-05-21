<template>
  <footer
    id="footer"
    class="w-100"
  >
    <div>
      Built with ❤️ by Mahdi Bouguerzi
      <!-- <a
        href="https://github.com/maitrungduc1410/realtime-chatapp-laravelecho-socketio"
        target="_blank"
      >
        (Source code)
      </a> -->
    </div>
    <!-- <div>
      Broadcast through Presence Channel for Shared Room and Private Channel for private message
    </div> -->
  </footer>
</template>

<style>
footer {
  background: #1c5986;
  color: white;
  text-align: center;
  position: absolute;
  bottom: 0;
  font-size: 13px;
  font-weight: 300;
  z-index: 1;
}

@media only screen and (max-width: 768px) {
  footer {
    position: initial;
  }
}

footer a {
  color: #00ffe9;
}</style>
