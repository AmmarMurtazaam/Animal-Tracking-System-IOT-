This projects comprises of LORaWan module Lopi 2 and a gps module controlled by arduino uno.
In this repository there are two source codes one for receiver and one for sender.
The sender is called a node and can be many of them as required.
In the workflow diagram you can see a node sending longitude and latitude to the central node and that central node is connected to your pc which then uploads that info over the cloud.
I have used Thingspeak as a cloud platform.
Then The app i built will be using its api to upload it on the map to show the location on the app map.
