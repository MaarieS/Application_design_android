# Welcome to my new project : Application design
This is an application design project aimed at remaking a design from Figma on Android Studio. 
(https://www.figma.com/file/6Y0MqDlAYqppkI1uefrnE1/TP-Application-design?type=design&node-id=0-1&mode=design&t=KDAnj893i8dwsRCH-0)

The design I choose is an Android application that displays a catalogue of smartwatches, allowing users to find their suitable watch. It contains 2 pages: one with all the watches you can choose from and another with only the watch you have clicked on.
These pages are adapted for Android and use the XML markup language. The main page is composed of 4 cards with 4 different watches. To made it I used 4 CardView with different margins, depending on their position. I use a ConstraintLayout because I want to add constraints such as app:layout_constraintTop_toTopOf and app:layout_constraintStart_toStartOf and these don't work with a GridLayout or LinearLayout. Moreover, ConstraintLayout is more efficient for creating complex interfaces with greater freedom. Then, the use of guidelines in ConstraintLayout gives a grid effect. 
Finally, to have the same spacing between the texts describing the watches, I used a LinearLayout.
