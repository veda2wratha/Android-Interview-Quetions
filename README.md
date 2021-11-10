# Android-Interview-Quetions
I will upload latest android interview questions [Based on live interviews]

## Common Interview Quetions 

- Tell me about your self?
- Why you are loocking for a job change?
  > I are looking for better career prospects, professional growth and work opportunities. You want a change in career direction. You are looking for new challenges at work. You were made redundant or the company closed down.
  

## Android Interview Quetions

- What is Activity?
  > An activity represents a single screen with a user interface just like a window or frame of Java. 
Android Activity is the subclass of ContextThemeWrapper class.

- What is ContextThemeWrapper?
  > ContextThemeWrapper adds theming support to a Context, otherwise, you can't apply any theme to the Views you create. That's why Activity layouts support themes while widget layouts don't, for example. You can also create a ContextThemeWrapper yourself to override the current theme with another one.
  
- What is Context?
  > As the name suggests, it's the context of the current state of the application/object. [Learn more](https://stackoverflow.com/questions/3572463/what-is-context-on-android)

- What is a Widget?
  > A widget is a small gadget or control of your android application placed on the home screen. Widgets can be very handy as they allow you to put your favorite applications on your home screen in order to quickly access them. You have probably seen some common widgets, such as music widget, weather widget, clock widget e.t.c

- Difference Between Class and Abstract class?
  In Class, We use the class as a keyword and in the abstract class, the abstract is the keyword and in the interface, the interface is the keyword.
In class, we have only concrete methods and in the abstract class, we have both concrete and abstract methods 
The concrete method means a method that as implementation. [Learn more](https://www.youtube.com/watch?v=zb4caZzuNI8&ab_channel=DurgaSoftwareSolutions)

8. When to use Interface and Abstract Class?
9. What is the difference between public, private and protected?
10. What is Multithreading?
11. Explain OOPS concepts in java
12. What is Overloading and Overriding?
13. Difference beetween Service and IntentService?
14. Activity lifecycle methodes 
15. Fragment lifecycle methods
16. Types of servicess
17. How you handle - when the user press back while the Async task is in progress?
18. Explain launcher modes in android
19. How you maintain multi platform base URLs using gradle
20. What is mVC, MVP and MVVM and tell me the difference?
21. Why we need to use Kotlin?
22. Types of access modifiers and access specifiers
23. Diff b/w interface, marker interface & abstract class
24. Where we use LinkedList over Arraylist and vice versa?
25. How hash map works internally
26. Live Data - types - usage
27. Difference between interface and class? 
28. Split a link list in half in one itration
29. Does hash map can take null as key & value?
30. Does set store null as value
31. Activity A->B->C->D - how you go back directly to B from D
32. Difference between comparable and comparator
33. Diff b/w final, finalize and finally
34. Thread to thread communication
35. Difference b/w coordinator and constraint layout
36. Replacements of weights in constraint layout
37. How glide and picasso works internally
38. How firebase library works internally


## Interview 1
- Can I you tell me what is MVVM
- What is current project and explain it.
- Tell me about OOPS Concepts and explain each 
- What is Collections and explain it
- Explain List & Map and difference 
- For storing/ retriving the data what method will use in retrofit and when to use post and when to use get?
- What is synchronisation? 
- Explain Thread lifecycle - New-runnable-running-wait/block-terminate/stop
- Write a code to display a badge count on an app icon



## Interview 2

1. Tell me about yourself
2. What is your current project
3. What are the technical changes you faced in current project?
4. Do you know any design patters 
5. You know Any Java design patters 
6. What is singleton pattern
7. How do you make a class as single ton and how do you know the class become single ton
8. Get common elements from two lists better 
9. We have employee object having name. Id and salary, how do you sort - how do you sort by using employee id - Give Better approach
10. What is the advantage of tree set ?
11. When to use tree set?
12. Do you when to use concertante Hashmap?
13. Did you worked Multi threding ?
14. How to call two web services at a time, simultaneously?
15. How to call two web services at a time using retrofit or async task
16. What is async task is it a class or interface or abstract class?
17. Can’t we call two apis using async call same time.
18. In coordinator layout how to make an image view to be always top right.
19. When we use frame layout ? Give best example 
20. Did you worked on dagger and hilt?
21. General example how dependency injection works
22. Do you have experience in retrofit
23. What are the advantages if we use Room
24. Did you worked on RxJAvA
25. What is the advantage of MVVM



## Interview 3  [Interview Date - 25th Oct 2021] 

- What are the design patters? Have you worked on any design patterns? [Learn more](https://www.freecodecamp.org/news/the-basic-design-patterns-all-developers-need-to-know/)
 
- What is single ton class?
    > A Singleton class in Java allows only one instance to be created and provides global access to all other classes through this single object or instance. Similar to the static fields, The instance fields(if any) of a class will occur only for a single time. [Learn more](https://www.geeksforgeeks.org/singleton-class-java/)
    
- What is the difference between architectural and design patters?
    > Architecture comes in Designing phase and Design Patterns comes in Building phase. Architectural pattern is like a blue print and design pattern is actual implementation. Architecture is base which everything else adhere to and design pattern is a way to structure classes to solve common problems. [Learn more](https://singhdivesh.medium.com/according-to-wikipedia-b1afa6de08c#:~:text=Architecture%20comes%20in%20Designing%20phase,classes%20to%20solve%20common%20problems.)
     
- How to avoid dead lock situation while using the singleton / How to make a singleton class as a thred safe ? [Learn more](https://www.javatpoint.com/how-to-avoid-deadlock-in-java)

- Do you have any idea on double thread lock.

- How array List and Hashmap internally works? [Learn about Hashmap](https://www.youtube.com/watch?v=CojCE-ojdGY&ab_channel=SeleniumExpress) [Learn about ArrayList](https://www.youtube.com/watch?v=SHwVUEYcXUA&t=206s&ab_channel=SeleniumExpress)

- What is the difference between growable list and fixed list. [Learn more](https://www.baeldung.com/java-list-capacity-array-size)

- What is serialisation and parsalable [Learn more](https://proandroiddev.com/serializable-or-parcelable-why-and-which-one-17b274f3d3bb)
- Do you have any ideas on comparable and compare to.
- How comparator workes internally.
- What is the difference between extends and implementation.
- Write a programe to sort a given string without using collections sort?


## Interview 4 - [Interview Date - 1st Nov 2021] 

- What is Memory Leak and How to find Memory Leaks? 
    > A garbage collector runs periodically to check objects that are not in use and removes them. A Memory leaks will happen when there are objects that are not in use by the app but the garbage colletor connot recognize them. [Learne more](https://instabug.com/blog/how-to-fix-android-memory-leaks/)

- How to communicate between two fragments / Activity? 
    > The recommended way to communicate between fragments is to create a shared ViewModel. Both fragments can access the ViewModel through their containing Activity. [Learn more](https://developer.android.com/guide/fragments/communicate)

- How to communicate between two apps?
    - > There are two different ways for apps to interact on Android: via intents, passing data from one application to another; and through services, where one application provides functionality for others to use. [Leanr more](https://digital.ai/catalyst-blog/communicating-between-android-apps)
    - > Content providers can help an application manage access to data stored by itself, stored by other apps, and provide a way to share data with other apps. [Learn more](https://developer.android.com/guide/topics/providers/content-providers.html)

- How to integrate payment gatways in android app.[Learn more](https://www.mobindustry.net/blog/how-to-integrate-payment-gateway-in-a-mobile-app/) 

- What is Method Overloading and Method Overriding?
    > **Overloading** occurs when two or more methods in one class have the same method name but different parameters.
    **Overriding** occurs when two methods have the same method name and parameters. One of the methods is in the parent class, and the other is in the child   class. Overriding allows a child class to provide the specific implementation of a method that is already present in its parent class.[Learne more](https://www.educative.io/edpresso/overloading-vs-overriding)

- What is the difference between Hashmap and Hashtable. [Learne more](https://www.geeksforgeeks.org/differences-between-hashmap-and-hashtable-in-java/)

- What is the difference between MVC, MVP and MVVM. 
    > Both MVP and MVVM are derivatives of MVC. The key difference between MVC and its derivatives is the dependency each layer has on other layers, as well as how tightly bound they are to each other. ... MVVM attempts to avoid these issues. In MVP, the role of the controller is replaced with a Presenter. [Learne more](https://www.oreilly.com/library/view/learning-javascript-design/9781449334840/ch10s09.html)
- What is Data binding?
    > The Data Binding Library is an Android Jetpack library that allows you to bind UI components in your XML layouts to data sources in your app using a    declarative format rather than programmatically, reducing boilerplate code. [Learne more](https://developer.android.com/topic/libraries/data-binding)
- What is PendingIntent?
    > A PendingIntent is a token that you give to a foreign application (e.g. NotificationManager, AlarmManager, Home Screen AppWidgetManager, or other 3rd party applications), which allows the foreign application to use your application's permissions to execute a predefined piece of code. [Learn more](https://stackoverflow.com/questions/2808796/what-is-an-android-pendingintent)


## Interview 5 [Interview Date - 6th Nov 2021] 

- How to launch activity without using class

- What happens if we don't use run time permissions and call camera open 

- What are intents and types

- Service and intetnt service 
- Diff between MVP and MVVM 

- What is string class, data type or object 

- In Kotlin switch case is available or not 

- How to create single Tom class in kotlin
- How to load images from web 

- How to implement push notifications.. explain the process 

- Async is depcricated what is the alternative

- User of contraint layout 
- What is data binding?
- Types of services
- To load images what permissions we required 
- What is synchronised and parcelable 
- What is the difference between var and val 
- What is mutable and immutable 
- What are premitive and non data types in kotlin ? 






