# Sending-WhatsApp-Mesages-from-.NET-Applications

# Introduction 
This article will help you to learn sending  WhatsApp messages using .NET framework with C# as programming language. this article will address integration of WhatsApp with our Applications like Web Portals/Windows or Desktop Applications and Windows Phone applications,etc.

# Background
For integrating WhatsApp with applications you need to have basic understanding of application development using .NET platform. In this article i will be using C# as  programming language hence an understanding of C# language will be helpful and believe me even if you have undertsanding of any other programming language, you can understand this article in an easy manner.

# Using the code
Before we jump to into code, let me provide a brief overview of steps in achieving our motive of sending WhatsApp messages from our .NET Application. for the sake of simplicity i am dividing this tutorial into three steps: 

Step 1. Requesting code for our Phone Number from WhatsApp in  the form of an SMS or a Voice call from WhatsApp IVR.

Step 2. Confirmation of the received code to get the password from WhatsApp for sending messages, and

Step 3. Sending Messages

Create a simple UI with one textbox “txtMyPhone” for inputting Phone Number, another “txtName” for Name and third one “txtConfirmationCode” for entering confirmation code received and the fourth one “txtPassword” for displaying password received from WhatsApp API.

Now double click on the two buttons “btnRequestCode” and “btnConfirmCode” to generate the empty event in .CS file of the webpage
