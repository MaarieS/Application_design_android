# Welcome to my new project: Application design
This is an application design project aimed at remaking a design from Figma on Android Studio. 
(https://www.figma.com/file/6Y0MqDlAYqppkI1uefrnE1/TP-Application-design?type=design&node-id=0-1&mode=design&t=KDAnj893i8dwsRCH-0)

## Design choice
The design I chose is an Android application that displays a catalog of smartwatches, allowing users to find their suitable watch. It contains 2 pages: one with all the watches you can choose from and another with only the watch you have clicked on.

## Technologie
These pages are adapted for Android and use the XML markup language. 

## Code explanation
### Mandatory part
The main page is composed of 4 cards with 4 different watches. To make it I used 4 CardView with different margins, depending on their position. I use a ConstraintLayout because I want to add constraints such as app:layout_constraintTop_toTopOf and app:layout_constraintStart_toStartOf and these don't work with a GridLayout or LinearLayout. Moreover, ConstraintLayout is more efficient for creating complex interfaces with greater freedom. Then, the use of guidelines in ConstraintLayout gives a grid effect. 
Finally, to have the same spacing between the texts describing the watches, I used a LinearLayout.

### Bonus part
The second activity is a template for the 4 smartwatches. I've decided to make a single page for the 4 watches and then use intent to modify the template content. This means I don't have to create 4 similar activities.

## Conclusion
Throughout the development of this application design project, I have gained a deeper understanding of the versatility of Android's UI framework.
