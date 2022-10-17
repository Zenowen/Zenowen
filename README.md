<style>
    .css-typing h1,h2,h3,h4,h5,h6,p {
  border-right: .15em solid orange;
  font-family:monospace;
  white-space: nowrap;
  overflow: hidden;
}
.css-typing h1:nth-child(1) {
  width: 29vw;
  animation: type 2s steps(40, end);
  animation-fill-mode: forwards;
}

.css-typing .second {
  opacity: 0;
  width: 13vw;
  animation: type2 2s steps(40, end);
  font-size: 1.35em;
  animation-fill-mode: forwards;
  animation-delay: 2s;
  
}

.css-typing .third {
  opacity: 0;
  width: 36vw;
  animation: type2 2s steps(40, end);
  font-size: 1.35em;
  animation-fill-mode: forwards;
  animation-delay: 4s;
  
}

.css-typing .fourth {
  opacity: 0;
  width: 13vw;
  animation: type2 2s steps(40, end);
  font-size: 1.35em;
  animation-fill-mode: forwards;
  animation-delay: 6s;
  
}

@keyframes type {
  0% {
    width: 0;
  }
  99.9% {
    border-right: .15em solid orange;
  }
  100% {
    border: none;
  }
}

@keyframes type2 {
  0% {
    width: 0;
  }
  1%{
    opacity: 1;
  }
  99.9% {
    border-right: .15em solid orange;
  }
  100% {
    opacity: 1;
    border: none;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}
  </style>
  <div class="css-typing">
    <h1>
      Hey, you. You're finally awake.
    </h1>

    <p class="second">
      Welcome to my page!.
    </p>

    <p class="third">
      <br>
      I'm Abraham, Fullstack developer from Seville, Spain <img src="https://cdn-icons-png.flaticon.com/512/197/197593.png" width="13"/> .
    </p>

    <h4 class="fourth">
      Things I code with
    </h4>
  </div>
