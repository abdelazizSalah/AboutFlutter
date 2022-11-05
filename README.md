# FluttterQ-A.-
this is a file containning some Q&amp;A about flutter which are technical questions for interview created by me.

## questions about flutter
1. do you know what flutter is ? 
2. Do you know the difference between hot reload and hot restart? 
(Hot reload allows us to see the changes we did to UI or added features without restarting the whole app, while hot restart destroys the app state and returns it to the default)

1. have you ever made an application ?
   1. if yes then let him tells you about it. 
   2. if no then ask him about any ideas that he wish to learn.
2. okay if he know about flutter: 
3. what do you know about flutter in general? question to detect what he knows ?
4. okay what do you know about null safty? 
   > it produces an error if the variables are not initialized, to neglect it we use (?) operator.
5. what is the difference between the stateful widget and the stateless widget?
   > the stateless is a screen on which we can't update the screen unless we have restarted the app, so it does'nt change its state,
   while the stateful widget is a widget on which we can change its state in order to change its content and interact with the user actions on the same screen. 
6. do you know what are the builder functions? 
   > they are dynamic functions used as named constructor for some widgets specialy listing widgets in order to not render the whole content staticaly but dynamically so it reloads only some of the elements and keep the others in the memory till the user scroll to them, so it delets the old and add the new, to put it in a nut shell we use it to enhance the performance. 
7. do you know what is the pubspec.yaml is? 
   >yes, it is a file in which we set our dependencies and assets pathes and packages used, something like a settings file.
8.  how can we insert elements above each other (question about column)
   > using columns
9.  Have you used Firebase before?
    >to know what he knows about backend and databases. 
10. ok tb how can we insert them next to each other? (question about rows)
   > using rows
11. what is the difference between widget tree and render tree? 
   > widget tree is the tree which consists of the hirarecy of the widgets, and it is changed ocasionaly, whenever we change the widgets we use, while render tree is a almost static tree used to render the elements in element tree to be displayed on the screens. 
12. what is the diffrence between stateful widget and state widget? 
   > state widget implements stateful widgets, it is a widgets which keeps the states for the stateful widget, so when we change any thing in the state widget, we call the set state method to change it and rebuild the widget tree again, also the state element is in the state tree not in the widget tree, and it points to its corresponding widget in the widget tree. 
13. what if we want to build a text box, what is its corresponding widget?
   >we use the TextField Widget
14. how can we listen to whatever is written in this text field? 
   > using a Text editing controller
15. how to build the gridView without using the gridView widget? 
   > we can use nested rows in a column widget. 
16. how to decorate the container? 
   > using the decoration parameter inside it, then use the BoxDecoration widget in order to decorate it.
17. open messanger and let him explain for you how to make UI like it.
   > nice experience.
18. do you know anything about mockserver? 
   > it is a server which simulates your api, and we use it if we want to work on the api, but the real api is still not working, so we just simulate the get and post requests.
19. do you know how to deal with apis ?
   > using dio package.
20. what do you know about anonymous functions? 
   > ()=> what you know anout them () {}.
   he should know that they are incode functions which are excuted only once in their places, and not callable in other places, also we put the parameters in the () and if we are gonna call single code we use => or if we are gonna use multi line logic so we need to implement it inside {}
21. is it better to increase the number of widgets in the app or to decrease them? 
   > in flutter increasing number of widgets enhances the readability and maintainablity, so we target increasing the number of widgets as much as we can. 
22. how can you send http requests? 
   > using dio package by creating post and get methods, and we add the pathes of the end points after declaring our endpoints.  
23. if we want to make the screen scrollable what are our options? 
   > Listview, ListView.builder, SingleScrollableScreen any of them will fit.  
24. how to make an attribute private in dart? 
   > using _ before the name of either data member of function
25. what do you know about state management? do you know what providers are? 
   > he should know that they are used to send data between widgets without needing it to be sent through the constructor, it manages the data between the widgets.
26. how to make the circular avatars? 
   > using CircularAvatar widget. 
27. lets design an app together -> draw an application in front of him and ask him if he has any advanced ideas
   > good practice to see how he contribute in getting new ideas
28. what do you know about media query?
   > it contains all the details about the phone it self, somethings like the orientation of the device, its height, its width and textScaleFactors used ... etc. 
29. what do you know about context?
   > it is a vairable from the BuildContext class which carries all the context details about the screen, about the font, colors, and any thing related to the UI. 
30. how to make a global theme to the application?
   > using the theme parameter in the MaterialApp widget
31. can we build an app without using the MaterialApp widget? 
   > no, Material widget is the entry widget for flutter to start from, so it is something like main in the codes, so it must exits.
32. okay, can we build an app without scaffold? 
   > yes, but it will be ugly
33. what is the scaffold? 
   > it is a special widget for android shapes, it provide appBar and drawer, and a backgroud and more details, instead of creating all of them from scratch by your own, its corresponding is capertino in ios devices.
34. how can we navigate from screen to another? 
   > using Navigator widget.
35. what is the difference between Navigator .
    1.  push
      > pushes new widget in the widget stack 
    2.  pop
      > removing last widget on the top of the widget stack
    3.  pushNamed
      > pushing certain widget which has name defined in the routes list which is defined in the material app widget. 
    4.  pushReplace
      > replace the last widget of the top of the stack with new widget, so it pops then pushes
    5.  pushNamedReplace
      > replace the last widget of the top of the stack with new widget, so it pops then pushes with Named 
36. how to send data between screens? 
      > either by state management or by constructors
37. what is the difference between the screen and the widget?
      > no difference, we just call a widget as screen if it takes the whole screen or almost of it, but practically there is no differenece both are widgets.
38. can we make one file containing all the imports instead of writing import in the beginning of each separate file and just include it in all of them?  
      > no.
39. what is the modelbottomsheet? 
      > widget that looks like a card appears from the bottom of the screen and it is a callable method.
40. what is the app bar?
      > bar in the top of the widget.
