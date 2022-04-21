
Monday, Tuesday & Wednesday Essay 

21-04-2022

This is a combination of daily entries from 3 days including Monday, i was on leave on Monday so I got only the summary from my colleagues. 

Monday

Today we were grouped into 2 teams consisting of 5 members each and each group was given a project to complete before 29th Friday. 

My group was told to create a memory game or a FlipCard Memory Game and we have to develop for both web and mobile, we divided the team so that each member will get a task that he is comfortable with, i took responsibility of the mobile app development, Gopi and Ram took charge of the web app and some for the design and research. We decided on a starting screen and decided we should include options like what kind of matrix you want to start with, like 2*2 or 3*3 and also an option to change the difficulty settings. I began researching on how to write the logic of the game on flutter, while it is not easy as i just started learning flutter it is a nice challenge to start with. On the 29th we have to prepare a presentation and present oru app and explain how we made it along with the obstacles and how we tackled them.

Tuesday

Today there was no session, it was just us working as a team to create the memory game app, the html team was doing good, they had already created the first page and was writing the logic, while the flutter and mobile app part was kind of difficult, i was getting a series of errors that i haven't dealt with previously. I took a good time reading documents about flutter basics and videos explaining how to start coding in flutter. Sankar and the other mentors were helpful in clearing our doubts and elaborating on new ways for logic..

I learned about basics in designing in flutter including Rows, Columns, container, Listview, etc 

Row and Column are classes that contain and lay out widgets. Widgets inside of a Row or Column are called children, and Row and Column are referred to as parents. Row lays out its widgets horizontally, and Column lays out its widgets vertically.

Row and Column occupy different main axes. A Row’s main axis is horizontal, and a Column’s main axis is vertical. The mainAxisSize property determines how much space a Row and Column can occupy on their main axes. The mainAxisSize property has two possible values:

MainAxisSize.max

Row and Column occupy all of the space on their main axes. If the combined width of their children is less than the total space on their main axes, their children are laid out with extra space.

MainAxisSize.min

Row and Column only occupy enough space on their main axes for their children. Their children are laid out without extra space and at the middle of their main axes.


I also learned about Constructors in flutter, 

Constructor is a special method of Dart class which is automatically called when the object is created. The constructor is like a function with/without parameters but it doesn’t have a return type.

Also, An abstract class, which is similar to an interface, defines a class that cannot be instantiated.

Abstract classes keep your code honest and type safe. It ensures that all implementation subclasses define all the properties and methods that abstract class defines, but leaves the implementation to each subclass.

Then I came across Future, which is data to be returned in the future, A Future addresses a computation that doesn’t finish right away. Though a typical function returns the outcome, an asynchronous function returns a Future, which will ultimately contain the outcome. The Future will reveal to you when the outcome is prepared..

Explaining about Synchronous and Asynchronous tasks, 

Asynchronous operations let your program complete work while waiting for another operation to finish. Here are some common asynchronous operations:

Fetching data over a network.

Writing to a database.

Reading data from a file.

Synchronous function

It causes the system to wait for the execution of everything that is inside it, only to then continue executing the rest of the actions.

A future represents the result of an asynchronous operation, and can have two states: uncompleted or completed.

Uncompleted

When you call an asynchronous function, it returns an incomplete future. That future is waiting for the function’s asynchronous operation to finish or to throw an error.

Completed

If the asynchronous operation succeeds, the future completes with a value. Otherwise it completes with an error.



Completing with a value

A future of type Future completes with a value of type T. For example, a future with type Future produces a string value. If a future doesn’t produce a usable value, then the future’s type is Future.



Completing with an error

If the asynchronous operation performed by the function fails for any reason, the future completes with an error.


async

Indicates that the function is asynchronous and at some point you may have to wait to get some data.

An async method is NOT executed in parallel but following the regular sequence of events, handled by the Event Loop, too.

await

Waits for the function to end. (Await basically holds the control flow, until the operation completes.)



Wednesday

Today again we started working on the project. I studied several documentations and videos to understand the flow of the app and how to implement it to flutter. The html group finished the logic and started implementing the web app. 

We also requested a session about flutter basics. The session was done by Mr Ernest, where he explained some of the core properties and basics that one must know before working with flutter. 

He started with the explanation of Rows and Columns, then he differentiated between Stateless and Stateful Widgets. 

 

After that he talked about Flexible widget 

The Flexible widget wraps a widget, so the widget becomes resizable. When the Flexible widget wraps a widget, the widget becomes the Flexible widget’s child and is considered flexible. After inflexible widgets are laid out, the widgets are resized according to their flex and fit properties.:

flex

Compares itself against other flex properties before determining what fraction of the total remaining space each Flexible widget receives.

fit

Determines whether a Flexible widget fills all of its extra space.

Then he explained the properties of different widgets: The column and row widgets accept children while the container and the rest accept child. 

The container in Flutter is a parent widget that can contain multiple child widgets and manage them efficiently through width, height, padding, background color, etc. It is a widget that combines common painting, positioning, and sizing of the child widgets.

Also talked about Scaffold and the build function, 

The Scaffold is a widget in Flutter used to implement the basic material design visual layout structure. It is quick enough to create a general-purpose mobile application and contains almost everything we need to create a functional and responsive Flutter app. This widget is able to occupy the whole device screen.

build method

Describes the part of the user interface represented by this widget.

The framework calls this method when this widget is inserted into the tree in a given BuildContext and when the dependencies of this widget change (e.g., an InheritedWidget referenced by this widget changes). This method can potentially be called in every frame and should not have any side effects beyond building a widget.

He concluded the session with that and told us to approach him or the others for doubt clarification and extra session requirements. 


