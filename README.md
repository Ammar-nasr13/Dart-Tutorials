## what is Dart language ?

- open source programming language => this mean you can download , use , modify and publish it.
- It developed by Google in 2011.
- It used to a client side and server side. (front-end - back-end)
- It a cross platform used to create mobile , desktop and web applications.
- Native language. => It means that the Dart language does not need an intermediary ( compiler ) to translate its code into code that a machine can understand.

## What are the components of the Dart language?

1- **Objects** => every thing in dart is object . this mean this object have classes . classes have super classes.
- The class and object have the same name. EX : int - double - string => classes , EX: num is super class => int -double class
- The class have properties and methods.
- you can use properties and methods with objects.

2- **Functions** => Dart have function and support arrow function.

3- **Asynchrony**

4- **OOP**

5- **Garbage Collection** => Dart has a built-in memory management system that automatically frees up memory that is no longer in use. <br>

- Garbage Collection frees up memory automatically during run program.

**Data are fressed up** 

- Variables or object that are stored in memory but not used in the program.
- Variables or object that have been assigned a new value will have the old value deleted.
- After executing the functions, the local variables are deleted from memory.

- *Note* => After the program ends: The operating system completely frees all the memory allocated to the program.

## How does Dart language work?

- Dart works in different ways depending on the target environment, whether it's a web or a mobile application.
- There are two main mechanisms for running Dart code.


  ### (JIT - Just-In-Time Compilation )
  
 - It used to Development stage.
- It store Dart code to VM Dart to convert Dart Code to machine code.
- Support Hot Reload.
- size of app is big and slow.
- It used keyword dart run or flutter run.



  ### (AOT - Ahead-Of-Time Compilation)
  
 - It used to production or publisher stage.
  - It convert Dart Code to Native code ( machine code ) only once.
  - Don't Support Hot Reload.
  - size of app is small and fast.
  - It used keyword flutter bulid.

## what are features of Dart language ?

- Open source.
- Easy to understand => Dart syntax similar to C# and Java Syntax.
- Browser Support => Dart code convert to Javascript code using dart2js tool.
- OOP
- Asyncronus programming
- Type Safety
- flexible compilation and Excution.

## what are versions of Dart language ?

- 2011 => It was announced as an alternative to JavaScript in browsers. 
- 2013 => release Dart 1.0 => the first use in the browser.
- 2018 => release Dart 2.0 => using Dart with Flutter Framework.
- 2023 => release Dart 3.0 => adding Features to Dart.
- **New Versions** =>  [*What's New*](https://dart.dev/resources/whats-new)

## where write Dart Code ?

- Online => compilar => DartPad
- Offline => Text eidtor => ( Vs code - Android Studio )

## Dart SDK ( Software Development Kit ) <br>

➡️ **Install Dart SDK**

- GO TO Dart Website => [*Click here to Download SDK*](https://dart.dev/get-dart/archive)
- After Download Dart SDK ⤵️
- In the Windows search box (start mune), write env and click it.
- Click Edit the system environment variables.
- Click Environment Variables....
- In the user variable section, select Path and click Edit....
- Click New, and enter the path to the dart-sdk directory.

➡️ **Create Project Dart**

- A project can be created in more than one way.
- First Create directory with project name.
- [*if you using Vs code*](#)
  
- Download Dart and Flutter Extention.
- Open directory in VS Code.
- Using terminal to Create dart project. or using command patel. => ctrl + shift + P .

- [*if you using Android Studio*](#)

- Download Dart and Flutter Extention.
- Open directory in Android Studio.
- choose flutter to create dart project.

- [*if you using CMD*](#)

- Using Command => dart create

➡️ **Explain Dart SDK**

- *Dart SDK consist of many components*.
- VM Dart
- dart2js
- Dart Compiler
- Libraries
- Comman line tools
- package manager
- Another tools => Analysis, testing, and Formatting tools. <br>

*VM Dart*

- It is a powerful engine that runs Dart code. <br>
  
*dart2js*

- Convert Dart Code to Javascript code. <br>

*Dart Compiler*

- JIT Compilation.
- AOT Compilation. <br>

*package manager*

- It manages the external packages we use. <br>

*Libraries*

- Libraries are divided by location and by target platform. <br>

➡️ **target platform** <br>

1- Native Libraries

- These are libraries dedicated to a specific operating system to access its features such as the camera, Bluetooth, files, etc.
- These libraries are written in many languages ​​depending on the operating system such as C++, Swift, and Kotlin. <br>

2- Multi Libraries

- They are libraries used with all platforms to create applications. such as dart:io - dart:core - dart:math. <br>

3- Web Libraries

- These libraries are dedicated to the web.

➡️ **Location** <br>

1- inside libaries

- These are all the built-in libraries found in the Dart language. <br>


2- outside libararies

- These are external libraries that we use to develop our own software. Called => Packages <br>

*Comman line tools*

- It is a set of commands that we use to perform many tasks.
- Divided into => Global Commands - Project Commands - Source Code Commands <br>

1-  Global Commands

- dart help or dart -h or dart --help => show all commands using in dart.
- dart --version or dart version => show Dart SDK version used.
- dart --verbose or dart -v or dart verbose => show additional information output commands.
- dart --enable-analytics => Allows Google to access anonymous data to improve the tool.
- dart  --disable-analytics => Don't Allows Google to access anonymous data to improve the tool.
- dart  --suppress-analytics => Prevent Google from accessing any anonymous data to improve the tool. <br>

2- Project Commands <br>

*dart create*

- dart create projectname
- (--template or -t ) => any project you must specific template project => defalut template is console app => web - server-shelf - package - cli - console app . <br>

*dart run*

- dart run file name.dart
- dart run :filename
- dart run => بيروح للملف اللي اسمه نفس اسم المشروع ويقوم بتشغيله
- dart run filename.dart  args <br>

*dart compile*

- dart compile
- subcommands => ( js -  aot-snapshot -  jit-snapshot -  kernel -  wasm ) <br>

*dart test*

- is used to test app. <br>

*dart pub*

- is used to file name pubspac.yaml . and you can add packages in projects. <br>
- **subcommands** ⤵️
- add
- get
- login
- publish
- logout
- outdated
- upgrade
- remove


3- source code commands

- dart analyze
- dart doc
- dart format
- dart fix
  
**What Difference between Components of dart and Dart SDK ?**

- The components of the Dart language are the rules, while the Dart SDK is the complete set of tools that implement those rules and help you build real-world       applications.
