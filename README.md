# KhuzaimahGlitcher
Class for creating a glitch animation with an image file(s).

>  glitcher.glitch( 'http://vignette2.wikia.nocookie.net/monsterspedia/images/2/28/SadakoDrapes-paper.jpg/revision/latest?cb=20140417231402', function () {<br/>
>   document.body.appendChild( glitcher.canvas );<br/>
>  });<br/>
>  function randomRange(min, max) {<br/>
>   return Math.floor(Math.random() * (max - min + 1)) + min;<br/>
>  }<br/>
>  setInterval(function () {<br/>
>   glitcher.options = {<br/>
>    color: {<br/>
>     red: 1,<br/>
>     green: 0.8,<br/>
>     blue: 0.58<br/>
>    },<br/>
>    stereoscopic: {<br/>
>     red: 10 * randomRange(1, 3),<br/>
>     green: 5 * randomRange(1, 3),<br/>
>     blue: 30 * randomRange(1, 3)<br/>
>    },<br/>
>    lineOffset: {<br/>
>     value: 5 * randomRange(1, 3),<br/>
>     lineHeight: 10 * randomRange(1, 3)<br/>
>    }<br/>
>   };<br/>
>   glitcher.process(); <br/>
>  }, 500);

![Example Image](./example-image.jpg)
