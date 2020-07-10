---
layout: multipage
title: micro:bit
category: microbit
nav: false
permalink: /micro-bit/morse-code-translator/index
subdir: micro-bit
---

	<style type="text/css">
		body {
			display: flex;
			min-height: 100vh;
			flex-direction: column;
			width: 100%;
		}
		main {
			flex: 1 0 auto;
		}

		blockquote{
		  margin: 20px 0;
		  padding-left: 1.5rem;
		  border-left: 5px solid #b71c1c;
		}
		.input-field textarea[class=materialize-textarea]:focus {
			border-bottom: 1px solid #b71c1c;
			box-shadow: 0 1px 0 0 #b71c1c;
		}
    </style>


			<blockquote >
				Verwandle einfachen Text in Morse Code und verwandle den Morse Code in einfachen Text mit diesem einfachen Werkzeug.
			</blockquote>


			<label>Eingabe:</label>
					<textarea rows="10" cols="50" id="msgInput" oninput="MorseTranslator()" placeholder="Gib hier deinen Text oder deine Morsezeichen ein." class="materialize-textarea" style="width:95%"></textarea>

			<label>Ausgabe:</label>
					<textarea rows="10" cols="50" id="msgOutput" class="materialize-textarea" style="width:95%"></textarea> <br>

	<!-- load Javascript scrips -->
	<script type="text/javascript" src="script.js "></script>
	<script type="text/javascript" src="morse.js"></script>
</html>