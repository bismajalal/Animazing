# Animazing

Animazing is an extension of the Colab Notebook implemented by Chervonij [1]. It implements a Deepfake Generation Model which takes a video from the user and swaps the face of the user with his/her desired character in a video clip. For our colab, we have created an Anvil web application to make the program easy to use. To run Anvil application with Google Colab, no installations are required. Only a stable internect connection and a browser is required.

The anvil app can be accessed here: https://anvil.works/build#clone:UZNAAWUAFEUHU7GT=JV74POR6A3SDRIQVZ3KLTO23

The Google Colab can be accessed here: https://colab.research.google.com/drive/1N1eQecjes-8U6FPDHs1ICjmiYDpE7D-u?usp=sharing



To run the anvil applcation:
1. Open the link and go to the settings of the web application. 
1. Open the settings from side bar and click 'Uplink'.
2. Enable the server uplink and copy the uplink key.
3. Paste this key in the Anvil Key module of the Colab Notebook.
4. Execute all of the code segments of the Colab one by one.
5. The last code waits forever for user commads from anvil frontend. As long as this code is executing, the anvil app will stay live.
6. Now run and publish the anvil app. The link can be accessed by anyone over the internet.

Refereces

[1] . https://github.com/chervonij/DFL-Colab
