say 18

Wednesday

Today there were 2 sessions, one was about programming and the other was html based. The next 4 days are holidays. 

The morning, i was busy with flutter basics, were i dwelled deeper into how to use firebase and inculcate firebase into flutter. The process was previously very hectic but now it is really convenient. So what is firebase? 
Firebase is a Backend-as-a-Service (Baas). It provides developers with a variety of tools and services to help them develop quality apps, grow their user base, and earn profit. It is built on Google’s infrastructure.  Key Features
1. Authentication
It supports authentication using passwords, phone numbers, Google, Facebook, Twitter, and more. The Firebase Authentication (SDK) can be used to manually integrate one or more sign-in methods into an app.
2. Realtime database
Data is synced across all clients in realtime and remains available even when an app goes offline.
3. Hosting
Firebase Hosting provides fast hosting for a web app; content is cached into content delivery networks worldwide.
4. Test lab
The application is tested on virtual and physical devices located in Google’s data centers.
5. Notifications
Notifications can be sent with firebase with no additional coding.

SDK stands for “Software Development Kit”, which is a great way to think about it — a kit. Think about putting together a model car or plane. When constructing this model, a whole kit of items is needed, including the kit pieces themselves, the tools needed to put them together, assembly instructions, and so forth.
An SDK or devkit functions in much the same way, providing a set of tools, libraries, relevant documentation, code samples, processes, and or guides that allow developers to create software applications on a specific platform. If an API is a set of building blocks that allow for the creation of something, an SDK is a full-fledged workshop, facilitating creation far outside the scopes of what an API would allow.
SDKs are the origination sources for almost every program a modern user would interact with. From the web browser you work on all the way to the video games you play at the end of the day, many were first built with an SDK, even before an API was used to communicate with other applications.
Now coming to how we can configure firebase into flutter, all the necessary documentations are provided in the firebase flutterfire docs website. So after creating the project, we need to add certain dependencies to the pubspec.yaml file using flutter pub add firebase_core etc. After that we need to install the flutterfire CLI(command line interface) and then firebase login in to the console where we can create the project directly from the terminal using flutterfire configure. 
After that, the programming session started where i learned about how functions work in dart or any programming, each function can be considered as a stack which a new one is stacked on top of the other and after a function is exited all its stack including the variables created inside the function disappears. 

whenever a function is called a new stack frame is created with all the function’s data and this stack frame is pushed in the program stack, and the stack pointer that always points the top of the program stack points the stack frame pushed as it is on the top of the program stack.
So from examples of certain functions i could understand how the stack works with the function. 
Then there was a class on HTML, where we were introduced to form tag. The <form> tag is used to create an HTML form for user input. The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc. I created a login page with email and password and a submit button. We also learned about script tag in html, The <script> tag is used to embed a client-side script (JavaScript).
The <script> element either contains scripting statements, or it points to an external script file through the src attribute. Common uses for JavaScript are image manipulation, form validation, and dynamic changes of content. We then created a separate main.js file where we copied the function we created in the html, this js file is then linked to the same html file using script tag. The function accepted email and password from the user. 



