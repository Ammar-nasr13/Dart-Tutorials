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

- The components of the Dart language are the rules, while the Dart SDK is the complete set of tools that implement those rules and help you build real-world applications.


## Keywordes in dart

- **هي مجموعة الكلمات المفتاحية التي نستخدمها في اللغة ولا يمكن استخدامها كمحددات الا بشروط معينة** .
<img src="https://github.com/Ammar-nasr13/Files/blob/master/images/keyword1.png" height=500>
<img src="https://github.com/Ammar-nasr13/Files/blob/master/images/keywords2.png" height=500>
<br>

**الشروط**

-  1 This keyword can be used as an identifier depending on context.
-  2 This keyword can't be used as the name of a type (a class, a mixin, an enum, an extension type, or a type alias), the name of an extension, or as an import prefix. It can be used as an identifier in all    other circumstances.
-  3 This keyword can be used as an identifier without restriction.

## Comments in dart

- you can use comments to explain code or put remarkables on statements .
- there are three types of comments ( single line comments - multi line comments - decomntation comments )
- single line comments => //
- muliti line comments => /* */
-  decomntation comments => used to explain code using markdown =>  single => ///  multi => /* **/
-  when you put mouse on statements which have decomantation comments => show formatting for comments using markdown


 ## Structure in dart

 - any program file in dart must contain main function. or any code in dart must be insidet main dart.
 - main function => the entry point of dart program
 -  main function can contain arguments => list<string> only .
 -  {} => the block of code that contain all statements in program.
 -  ; => all statements must end semi colon


## outputs and inputs in dart

**outputs**

- in console applications
- using Stdout class with methods => write or writein  ( must be import dart:io)
- stdout.write => not new line  or  stdout.writein => new line
- using print function ( dart core ) to output such as stdout.writein. <br>

**inputs**

- in console appliations
- using Stdin class with methods => readLine sync or readByte sync  ( must be import dart:io)
- readLine sync => accept multi line or readByte sync => accept one chat only

##   Datatypes in Dart

- Numbers (int, double)
- Strings (String)
- Booleans (bool)
- Records ((value1, value2))
- Functions (Function)
- Lists (List, also known as arrays)
- Sets (Set)
- Maps (Map)
- Runes ( Runes ; often replaced by the characters API)
- Symbols (Symbol)
- The value null (Null)

- **Data types** => Primative data types (variables) - Non-Primative datatypes
```dart
Data Types
├── Primitive Data Types
│   ├── Static Primitive Data Types
│   │   ├── int
│   │   ├── double
│   │   ├── num
│   │   ├── bool
│   │   └── string
│   ├── Dynamic Data Types
│   │    ├── dynamic
│   │    ├── var
│   │    └── Object
│   │
│   ├── Constants Primitive Data Types
│   │      ├── const
│   │      ├── final
│   │
│   ├── Null - Null Safety
├
└── Non-Primitive Data Types
    ├── List
    ├── Map
    ├── Set
    ├── Class / Object
    └── Function
 ```
   
- **idenfiers** => هي مجموعة القواعد التي يتم مراعتها عند تسمية اي نوع من انواع البيانات
- variables or object must be start letter (a to z)
- variables or object don't start number or symbol => ( 0 , 1 , 2 .... or @ , # , $ )
- variables or objectcan be start  underscore ( _ )
- variables or object can use a keywords as a name
- variables or object use case type => ( UpperCamelCase - lowerCamelCase - lowercase_with_underscores )


##  Primative data types (variables)

- **Definations** => هي عبارة عن حجرة من الذاكرة يتم تخزين فيها البيانات ويكون لها اسم مع تحديد نوع البيانات
- Varaibles = ( Type - Name - Value )
- Structure = Varaibles name = value ;

```dart

 initialization , assignment, declaration
------------------------------------------

 - declaration = Varaibles name ;

 - assignment = name = value ;

 -  initialization = Varaibles name = value ;

 - initialization =  declaration + assignment

```

- **Types** => ( dynamic variables - static variables - constants variables - null or null Saftey ) <br>


 **static variables** <br>

 - static ⤵️

1- used to only certian data
   
2- immutable

**String**
```text
-  String is a class and object is also String. two have the same name.
-  Any class have properties and methods.
-  is a variable store texts. using UTF-16
-  String can store texts in one line with using => ' '  or " "
-  String can store texts in multi lines with using => '''  '''  or """  """
```

```text
   String operator => ( + )  | ( * )
- ( + ) to concatination texts .
-  concatination automaticllay => String name = 'a' 'b' 'c';
-   String operator => ( * ) to repeat texts . <br>
```

```dart
String Interpolation
--------------------
- $  => variable name only.
- ${} => function - many variables with methods
- multi String interpolation => ${} ${} ${}
```

**Properties**

- isEmpty => return bool => بتتحقق من اذا كان النص فارغ ام لا
- isNotEmpty => return bool => بتتحقق من اذا كان النص ليس فارغا ام لا
- length => return int => بتشوف عدد حروف السلسلة النصية وبترجع العدد
- runtimetype => return datatypes => هي بتعرفنا نوع البيانات المستخدم حاليا
- codeUnits => return list<int> => ASCII هي بترجع كود كل حرف موجود في جدول
- hashcode => return int =>  هو يعطي عنوان فريد للمتغير في الذاكرة  <br>

**Methods**

- toLowerCase() => return string => هي تستخدم في تحويل السلاسل النصية لحروف صغيرة
- toUpperCase() => return string => هي تستخدم في تحويل السلاسل النصية الي حروف كبيرة
- trim() => return string => هي تقوم بازالة المسافات الزائدة من ناحية اليمين واليسار
- trimLeft() => return string => هي تقوم بازالة المسافات الزائدة ناحية اليسار
- trimRight() => return string => هي تقوم بازالة المسافات الزائدة ناحية اليمين
- compareTo( pramaters ) => هي تستخدم لمقارنة سلسلة نصية بسلسلة نصية اخري  وهي تقوم بارجاع 1 او -1 او 0
- the letter of name1 grater than letter of name2 => return 1
- the letter of name1 equel letter of name2 => return 0
- the letter of name1 smaller than letter of name2 => return -1

- substring( int start , int end ) => هي تستخدم في تقسم السلسلة النصية من بداية التحديد الي النهاية
- contian("") => هي خاصية تستخدم من التاكد من محتوي السلسلة النصية ولو كانت موجود بترجع صح ولو كانت مش موجودة بترجع غلط
- contains(RegExp(r'\d+')
- startswith("") => بتستخدم للتاكد من ان السلسلة النصية تبدا ب
- endswith("") => بتستخدم للتاكد من ان السلسلة النصية تنتهي ب
- indexOf("") => هي تقوم بارجاع قيمة ترتيب السلسلة النصية المخزنة
- lastIndexOf("") => هي تقوم بارجاع اخر فهرس
- codeUnitsAt(index) => هي بترجع قيمة الحرف الموجود في النظام الثنائي
- splite("علامة التقسيم") => هي تستخدم في تقسيم السلسلة النصية بناء علي علامة معينة ويتم تخزين القيم في قائمة
- spliteMapJoin() => هي تقوم بتقسيم ومعالجة وارجاع السلاسل النصية

```dart
splitmapjoin(" " , هنا هنقوم بتقسم النص بطريقة التقسيم العادية

onMatch:(m)=> "" , هنا في مرحلة المعالجة يتم اضافة النص المراد اضافه
onNonMatch:(n)=>n.خاصية


)
``` 
- replaceAll(From , replace ) => هي تقوم باستبدال كل نص محدد ومراد استبداله بالنص التي نقوم بوضعه
- replaceFirst(From , replace) => هي تقوم باستبدال او نص محدد فقط بالنص المراد وضعه


**Escape Sequence** => هي تستخدم مع السلاسل النصية
```text
- ( \n ) => هي تقوم بعمل سطر جديد
- ( \t ) => tab هي بتقوم بعمل مسافة مثل
- (\\) => print \
- (\') => print '
- (\") => print "
- \u 4 numbers => بتستخدم لطباعة ايموجي
- \u{4 numbers or more } => تستخدم لطباعة ايموجي
- raw string => Escape Sequence قبل السلسلة النصية لابطال عمل  r هي استخدام حرف 
```

**StringBuffer**

- A class for concatenating strings efficiently.
- StringBuffer have properties and methods
- we used to StringBuffer becuase strings is immutible
- The strings are concatenated to a single string only when toString is called.
- **Uesd**
```dart
var sb = StringBuffer();
sb.wrtie("");
sb.write("");
sb.writeAll([]);
sb.clear();
String s = sb.toString();
```

**Runes**

- way to represent Unicode code points inside Strings.
- allow you to access to code points directly instad of code units.
- codeUnits()
- codeUnitAt()
- String.FromeCharCode()
- \u
- \u{}
- runes
