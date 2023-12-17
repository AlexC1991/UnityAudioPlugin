# UnityAudioPlugin


This is a Tutorial Of How to Use It.

How to use Audio Plugin within Unity


Step One - import the folder from the github repo.




Step Two - Insert the downloaded github repo folder in your Assets Folder of your project.




Step Three - In the Menu Options in the top toolbar you should see Audio Plugin. Go into that Window and click the first option.




Step Four - Create a new folder or put the new ScriptableAudioFile into an existing file and give the file you are saving a name.




Step Five - There will be an error in the console window but it can be ignored or cleared. 




Step Six - In the Inspector there should be the scriptable audio file options. Please drag an audio clip into the section at the top and customize your sound and play it over and over until you get the right sound profile you are looking for and make sure you give it a loop or not for the final sound and press stop when finished.



Step Seven - In any script you wish to use this new audio file write the line 
[Serializefield] private ScriptableAudioFile variableA. Variable A is just your variable for it in the script to reference it.

Step Eight - Choose where you want the Audio to play in your script and say VariableA.PlayAudio() when you want to stop it say VariableA.StopAudio(). 

If you wish to control it like your normal Audio Source it does use an Audio Source still so most functions like finding how long the duration is of the audio clip and other variables that you might not be able to use in the inspector you can use by just saying this line of code.

“VariableA.audioSource.Function”

Function being replaced with any normal Unity Audio Source code lines. By using just audioSource you're talking directly to the Unity AudioSource function for that audio variable.


Once you have finished implementing the sound all you have to do is play the game and enjoy your sound. If you wish to change the sound profile in future just navigate to the folder where the scriptableaudiofile that you saved to is located in your assets folder and click on it to change its properties once again.
