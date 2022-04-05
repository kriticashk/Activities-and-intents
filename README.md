# Activities-and-intents
task challenge homework<br/>

<b> Two Activities </b><br/>

<p>Create and build an app called Two Activities that, unsurprisingly, contains two Activity implementations. You build the app in three stages.

In the first stage, you create an app whose main activity contains one button, Send. When the user clicks this button, your main activity uses an intent to start the second activity.

In the second stage, you add an EditText view to the main activity. The user enters a message and clicks Send. The main activity uses an intent to start the second activity and send the user's message to the second activity. The second activity displays the message it received.

In the final stage of creating the Two Activities app, you add an EditText and a Reply button to the second activity. The user can now type a reply message and tap Reply, and the reply is displayed on the main activity. At this point, you use an intent to pass the reply back from the second activity to the main activity.</p>

<img src="screenshots/Intent_twoactivities.gif" width="300px" height="600px">

<b>Challenges</b><br/>
<p> An app with three Button elements labeled Text One, Text Two, and Text Three. When any of these Button elements are clicked, launch a second Activity. That second Activity contain a ScrollView that displays one of three text passages. An Intent to launch the second Activity with extras to indicate which of the three passages to display.</p><br/>

<img src="screenshots/Intent_challenge.gif" width="300px" height="600px">

<b>homework</b><br/>
<p>Modify the Toast button so that it launches a new Activity to display the word "Hello!" and the current count. Change the text on the Toast button to Say Hello.</p><br/>

<img src="screenshots/Intent_homework.gif" width="300px" height="600px">

<b>Question 1</b><br/>
<p>What changes are made when you add a second Activity to your app by choosing File > New > Activity and an Activity template?<br/>
  
-> The second Activity is added as a Java class, the XML layout file is created, and the AndroidManifest.xml file is changed to declare a second Activity.</p>

<b>Question 2</b><br/>
<p>What happens if you remove the android:parentActivityName and the elements from the second Activity declaration in the AndroidManifest.xml file?<br/>

-> The Up button in the app bar no longer appears in the second Activity to send the user back to the parent Activity.</p>

<b>Question 3</b><br/>
<p>Which constructor method do you use to create a new explicit Intent?<br/>

-> new Intent(Context context, Class<?> class)</p>

<b>Question 4</b><br/>
<p>In the HelloToast app homework, how do you add the current value of the count to the Intent?<br/>

-> As an Intent extra</p>

<b>Question 5</b><br/>
<p>In the HelloToast app homework, how do you display the current count in the second "Hello" Activity?<br/>

-> All of the above.</p>
