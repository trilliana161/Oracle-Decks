<html>
    <head>
 <style>
      body {
        background-color: #ADD8E6;
      }
    </style>
    <style type="text/css">
body {
  
  margin: 0;
  padding: 1em;
}

.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: auto;
  grid-gap: 10px;
}

.item-a {
  grid-column: 2 / 3;
  grid-row: 1 / 2;
  justify-self: center;
}

.item-b {
  grid-column: 2 / 3;
  grid-row: 2 / 3;
  justify-self: center;
  text-align: center;
  font: 12px Courier, sans-serif;

}

.item-c {
  grid-column: 2 / 3;
  grid-row: 3 / 4;
  justify-self: center;

}

button {
  background-color: #F4DBED;
  border: none;
  padding: 0.7em;
  color: gray;
  display: block;
  font: 12px Courier, sans-serif;

  -webkit-transition: 0.5s;

}

button:hover {
  background-color: pink;   
  -webkit-transition: 0.5s;

}

#face {
  height: 35vw;
  -webkit-transition: 0.5s;
  

}

{card:"",
  desc:"",
  src:""}
        // CSS Content
        </style>
</head>
    <body>
<html>

<div class="container">
<div class="item-a">
  
  <img id="face" src="https://cdn.discordapp.com/emojis/863949541164974114.gif">
  
  </div>
  
<div id="card" class="item-b">
  <p></p>
  </div>

<div class="item-c">
  
    <button type="button" id="button" class="button" onclick="buttonClick()">&#9825;	
today's deck &#9825;	</button>
  
  <button onclick=location.reload();
>⁺˚*･༓☾reset☽༓･*˚⁺
</button>



  

  </div>
  
  </div>
        <script language="JavaScript"  type="text/javascript">
//an array of decks

var cards = 
[
{card: "Adorabyssal",
desc: "Truthful",
src: "https://i.imgur.com/YCgG6Gr.jpg"},
{card: "Happy Oracle",
desc: "Happy",
src: "https://i.imgur.com/4zfM66I.jpg"},
{card: "Self-Affirmation Oracle",
desc: "Positive, affirmative",
src: "https://i.imgur.com/8pswNuJ.jpg"},
{card: "Self-Love Oracle",
desc: "Loving",
src: "https://i.imgur.com/KwcCdvg.jpg"},
{card: "Shadow Work Oracle",
desc: "Deep",
src: "https://i.imgur.com/8s9G0d4.jpg"},
{card: "Faerie's Oracle",
desc: "Balanced, Avoiding Extremes, Achieving the Impossible, Being Impossible",
src: "https://i.imgur.com/a18IYyf.jpg"},
{card: "House of Night",
desc: "Needs Being Met, Close to Achieving Your Goal",
src: "https://i.imgur.com/d0E6ElI.jpg"},
{card: "Memento Mori",
desc: "Good Character, Becoming Independent",
src: "https://i.imgur.com/qXniYE0.jpg"},
{card: "Runes",
desc: "Protective, Self, Control Over Emotions",
src: "https://i.imgur.com/aiZqrKp.jpg"},
{card: "Seasons of the Witch",
desc: "Aware, Victim Mentality",
src: "https://i.imgur.com/LE6WXXF.jpg"},
{card: "Therapets",
desc: "Sweet",
src: "https://i.imgur.com/5S6eCEd.jpg"},
{card: "Threads of Fate Oracle",
desc: "Master of Their Destiny",
src: "https://i.imgur.com/RMNeVKr.jpg"},
{card: "Witches of Legend",
desc: "Strong, Unyielding",
src: "https://i.imgur.com/kV8uXjG.jpg"},

];

// The button function

function buttonClick() {
  
// Create a random number generator

var cardsNumber = cards.length;
var randomNumber = Math.random();
var chooseRange = (randomNumber * cardsNumber) + 0;
var numberGen = Math.floor(chooseRange);

// Change HTML
  
  document.getElementById('card').innerHTML = "Your deck is " + cards[numberGen].card + "." + "<br> This deck's personality is " + cards[numberGen].desc;
  document.getElementById('face').src = cards[numberGen].src;
  document.getElementById('button').visibility = 'hidden';   
  document.getElementById('button').innerHTML = "Get another deck?";

}
        </script>   
<style>
footer {
	position: fixed;
	width: 100%;
	left: 0;
	bottom: 0;
	background-color: brown;
	color: white;
	text-align: center;
}
</style>

	<script language="JavaScript">
  /**
    * Disable right-click of mouse, F12 key, and save key combinations on page
    * By Arthur Gareginyan (https://www.arthurgareginyan.com)
    * For full source code, visit https://mycyberuniverse.com
    */
  window.onload = function() {
    document.addEventListener("contextmenu", function(e){
      e.preventDefault();
    }, false);
    document.addEventListener("keydown", function(e) {
    //document.onkeydown = function(e) {
      // "I" key
      if (e.ctrlKey && e.shiftKey && e.keyCode == 73) {
        disabledEvent(e);
      }
      // "J" key
      if (e.ctrlKey && e.shiftKey && e.keyCode == 74) {
        disabledEvent(e);
      }
      // "S" key + macOS
      if (e.keyCode == 83 && (navigator.platform.match("Mac") ? e.metaKey : e.ctrlKey)) {
        disabledEvent(e);
      }
      // "U" key
      if (e.ctrlKey && e.keyCode == 85) {
        disabledEvent(e);
      }
      // "F12" key
      if (event.keyCode == 123) {
        disabledEvent(e);
      }
    }, false);
    function disabledEvent(e){
      if (e.stopPropagation){
        e.stopPropagation();
      } else if (window.event){
        window.event.cancelBubble = true;
      }
      e.preventDefault();
      return false;
    }
  };
</script>
    </body> 
    
</html>
