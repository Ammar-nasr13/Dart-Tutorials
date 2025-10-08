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

➡️**Data are fressed up** 

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
  
➡️**What Difference between Components of dart and Dart SDK ?**

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

➡️**outputs**

- in console applications
- using Stdout class with methods => write or writein  ( must be import dart:io)
- stdout.write => not new line  or  stdout.writein => new line
- using print function ( dart core ) to output such as stdout.writein. <br>

➡️**inputs**

- in console appliations
- using Stdin class with methods => readLine sync or readByte sync  ( must be import dart:io)
- readLine sync => accept multi line or readByte sync => accept one chat only

##  Datatypes in Dart

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


➡️ **static variables** <br>

 - static ⤵️

1- used to only certian data
   
2- immutable

1- **String**

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

➡️**Properties**

- isEmpty => return bool => بتتحقق من اذا كان النص فارغ ام لا
- isNotEmpty => return bool => بتتحقق من اذا كان النص ليس فارغا ام لا
- length => return int => بتشوف عدد حروف السلسلة النصية وبترجع العدد
- runtimetype => return datatypes => هي بتعرفنا نوع البيانات المستخدم حاليا
- codeUnits => return list<int> => ASCII هي بترجع كود كل حرف موجود في جدول
- hashcode => return int =>  هو يعطي عنوان فريد للمتغير في الذاكرة  <br>

➡️**Methods**

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


➡️**Escape Sequence** => هي تستخدم مع السلاسل النصية
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

➡️**StringBuffer**

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
sb.isEmpty
sb.isNotEmpty
sb.hashcode
sb.runtimetype
sb.length
String s = sb.toString();
sb.clear();
```

➡️**Runes**

- way to represent Unicode code points inside Strings.
- allow you to access to code points directly instad of code units.
- codeUnits()
- codeUnitAt()
- String.FromeCharCode()
- \u
- \u{}
- runes


2- **Numbers and Math**

➡️**int**

- int is class and object also is int .
- An integer number. that mean can store interger number.
- Numbers are stored in 64-bit space.
- The available integer values include all integers between -2^53 and 2^53
- Classes cannot extend, implement, or mix in int.
- If the number is greater than the range, that wrap to that range on overflow.

➡️**differance between using int and bitwise operators in Dart and Javascript**

- JavaScript does not have int, it has one type for numbers called *double-precision floating point values.*
- double-precision floating point values can represent numbers up to a certain range less than the range of vm.
- To ensure safe usage, we use:
1- Int is within the allowed range for JavaScript or using Bigint.
  
2- Use bitwise operators in ways that allow their availability in JavaScript.

➡️**Properties**

- isodd => return bool =>  هي بتتحقق من اذا كان الرقم فردي ام لا
- isEven => return bool => بتتحقق من اذا الرقم زوجي ام لا
- bitLength => return int => بترجع البت الخاص بالرقم
- sign => return int => هي تستخدم لمعرفة اذا كان الرقم صفري ام موجب ام سالب
- hashcode => return int => عنوان المتغير
- isFinite => return bool => بتتحقق من اذا كان الرقم محدود ام لا 
- isInFinate => return bool => بتتحقق من اذا كان الرقم غير محدود ام لا 
- isNaN => return bool => بتتحقق من اذا كان هذا رقم ام لا 
- isNagative => return bool => بتتحقق من اذا كان هذا الرقم سالب ام  لا 
- runtimetype =>  return type => بتتحقق من نوع المتغير


➡️**Methods**

- toStringAsFixed(number) => بتستخدم في تحديد كم رقم يكون بعد العلامة العشرية
- abs() => بتجيب القيمة المطلقة للرقم
- modPow(exponent, modulus) => ثم تقوم بارجاع ناتج باقي القسمة  modulus بتحسب الرقم الاصلي مرفوع لاس معين ثم تقوم بقسمته علي الرقم المحدد
- compareTo(number) => هي تستخدم لمقارنة العدد برقم اخري واذا كان الرقم اكبر ترجع 1 ولو كان اصغر بترجع -1 ولو كان متساوي بترجع 0

➡️**Bigint**

- Bigint y = Bigint.from(********************);
- An arbitrarily large integer value.
- accept inter , double , nagtive and postive number.
- Encryption (RSA, ECC) → Because the numbers there are very huge.
- To create a big integer from the provided number, use BigInt.from.
- To check whether a big integer can be represented as an int without losing precision, use *isValidInt.*
- To convert a big integer into an int, use toInt. To convert a big integer into an double, use toDouble.

➡️**Properties and Methods** => int هي نفس الموجود داخل 
- isValidInt => ام لا int هي تتحقق من اذا كان هذا الرقم يقبل في
- pow(exponent) => دالة تستخدم لحساب الاس

➡️**double**

- double is class and object also is double .
- A double-precision floating point number.
- It is a compile-time error for a class to attempt to extend or implement double.


➡️**Properties**

- hashCode
- isFinite
- isInfinite
- isNaN
- isNegative
- runtimeType
- sign

➡️**Methods**

- abs()
- compareTo(num other) → int 
-  ceil() → int => بتقرب الرقم لاكبر عدد صحيح 13
-  ceilToDouble() → double =>  بتقرب الرقم لاكبر عدد عشري اي يكون 13.00
-  floor() → int => بيقرب الرقم لاصغر عدد صحيح
-  floorToDouble() → double => يقرب العدد لاصغر عدد عشري
-  round() → int => بيقرب العدد لاعلي او لاصغر عدد صحيح
-  roundToDouble() → double => بيقرب العدد لاعلي او لاصغر عدد عشري
-  truncate() → int => بيزيل الجزء العشري 
-  truncateToDouble() → double => بيزيل الجزء العشري وبيكون العدد عشري

➡️**num**

- An integer or floating-point number.
- num is super class ( int - double )
- It is a compile-time error for any type other than int or double to attempt to extend or implement num.

* => int - double بنستخدم معاها الخصائص المشتركة بين 


➡️**dart math**

- first import => dart.math
- It contain Mathematical constants and functions, plus a random number generator.


➡️**Classes**

*Random*

- A generator of random bool, int, or double values.

```daer
Random r = Random();
or
var r = Random();
```

➡️**Properties**

- hashCode → int
- runtimeType → Type

➡️**Methods**

- nextInt(number) => Value is >= 0 and < number.
-  the range from 0, inclusive, to max.
-  oprators with  nextInt(number) => change start range to ... and end range to .....⤵️
```dart
nextInt(number) + 50 => change start range to 50 and end range to 60
nextInt(number) * 50 => change start range to 0 and end range to 5000
```

- nextdouble( ) => Value is >= 0 and < 1.0.
- oprators with  nextnextdouble() => change start range to ... and end range to .....⤵️

```dart
nextdouble() + 50 => change start range to 50.0 and end range to 60.0
nextdouble() * 50 => change start range to 0 and end range to 5000.0
```
*Point*

- Point is a utility class for representing two-dimensional positions.

```dart
var lefttop = const Point(x , y);
var leftbottom = const Point(x , y);
var righttop = const Point(x , y);
var rightbottom = const Point(x , y);
var centercentr = const Point(x , y);
```

*Rectangle

- Rectangle is a class for representing two-dimensional axis-aligned rectangles whose properties are immutable.
- Create a rectangle spanned by the points.
```dart

var leftTop = const Point(20, 50);
var rightBottom = const Point(300, 600);
var rectangle = Rectangle.fromPoints(leftTop, rightBottom);
print(rectangle.left); // 20
print(rectangle.top); // 50
print(rectangle.right); // 300
print(rectangle.bottom); // 600

```

- Create a rectangle spanned by (left, top , left+width, top+height).

```dart

var rectangle = const Rectangle(20, 50, 300, 600);
print(rectangle.left); // 20
print(rectangle.top); // 50
print(rectangle.right); // 320
print(rectangle.bottom); // 650

```
*MutableRectangle*

- MutableRectangle is a class for representing two-dimensional axis-aligned rectangles with mutable properties.
- Create a mutable rectangle spanned by (left, top) and (left+width, top+height).

```dart
var rectangle = MutableRectangle(20, 50, 300, 600);
print(rectangle); // Rectangle (20, 50) 300 x 600
print(rectangle.left); // 20
print(rectangle.top); // 50
print(rectangle.right); // 320
print(rectangle.bottom); // 650

// Change rectangle width and height.
rectangle.width = 200;
rectangle.height = 100;
print(rectangle); // Rectangle (20, 50) 200 x 100
print(rectangle.left); // 20
print(rectangle.top); // 50
print(rectangle.right); // 220
print(rectangle.bottom); // 150

```

➡️**Mathematical Constants**

```dart

e → const double => Base of the natural logarithms.

ln10 → const double => Natural logarithm of 10.

ln2 → const double => Natural logarithm of 2.

log10e → const double => Base-10 logarithm of e.

log2e → const double => Base-2 logarithm of e.

pi → const double => The PI constant.

sqrt1_2 → const double => Square root of 1/2.

sqrt2 → const double => Square root of 2.
```

➡️**Mathematical Function**

```dart
- acos(num x) → double => Converts x to a double and returns its arc cosine in radians

- asin(num x) → double => Converts x to a double and returns its arc sine in radians.

- atan(num x) → double => Converts x to a double and returns its arc tangent in radians.

- atan2(num a, num b) → double => A variant of atan.

- cos(num radians) → double => Converts radians to a double and returns the cosine of the value.

- exp(num x) → double => Converts x to a double and returns the natural exponent, e, to the power x. = e^num

- log(num x) → double => Converts x to a double and returns the natural logarithm of the value.

- max<T extends num>(T a, T b) → T => Returns the larger of two numbers.

- min<T extends num>(T a, T b) → T => Returns the lesser of two numbers.

- pow(num x, num exponent) → num => Returns x to the power of exponent.

- sin(num radians) → double => Converts radians to a double and returns the sine of the value.

- sqrt(num x) → double => Converts x to a double and returns the positive square root of the value.

- tan(num radians) → double => Converts radians to a double and returns the tangent of the value.

```

3- **Booleans**

- The reserved words true and false denote objects that are the only two instances of this class.
- It is a compile-time error for a class to attempt to extend or implement bool.

➡️**Properties**

- hashCode → int => The hash code for this object.
- runtimeType → Type => A representation of the runtime type of the object.


➡️ **dynamic variables**

 -  variables that are assigned any value, whether it is text, a number, or bool ز
 -  After assigning it a value :

1- Determines the type of the value => text - number - booleans

2- Determines the type of the variable => String - int or doubel - bool

➡️**var**

*initilization*
- var determines the type of the variable in compile-time.
-  var convert static variable
- you can use Properties and Methods .
- you can't change another type.

*declaration and  assignement*

-  dynamic variable
-  var determines the type of the variable in run-time.
-  you can't use Properties and Methods .
- you can change another type.

```dart

void main() {
  var name = "ammar"; // initilization  // convert to Stitic variable (String)
  // name = 10; // error you can't change another type
  print(name.isEmpty); // you can use properties and methods

  var name1; // declaration
  name1 = "Ammar"; // assignement  // dynamic
  // print(name1.) you can't use properties and methods because dynamic variable

  name1 = 10; // you can change another variable

  print(name1); //10
}

```

➡️**dynamic**

*initilizatio or declaration and assignment*

- dynamic variable
- dynamic determines the type of the variable in run-time.
- you can change another type.
- you can't use Properties and Methods .

```dart

void main() {
  
  // initilization or declaration and assignement
  
 dynamic name = "Ammar"; // dynamic variable
 name=10; // you can change another type
 // print(name.) you can't use properties and methods
 
  dynamic name1 ; // declaration 
  name1 = "Ammar"; // assignement  dynamic variable
  print(name);
}
```

➡️**object**

- The base class for all Dart objects except null.
- you can use object in many cases.

*object as a variable*

- dynamic variable
- object check the type of the variable in compile-time.
- you can change another type.
- you can't use Properties and Methods .

```dart

void main() {
  Object name = "ammar"; // initilization
  name = 10; // you can change another type
  // print(name.) // you can't use Propertis and Methods

  Object name1; // declaration
  name1 = "Ammar"; // assignement
  print(name1);
}
```

**difference between dynamiv and object

- object check the type of the variable in compile-time.
- you can use properties and methods with object => casting using as


➡️**Wildcard Variables or Ignore Variables**

- A wildcard variable with the name _ declares a local variable or parameter that is non-binding.
- Wildcard variables require a language version of at least 3.7.
- Purpose: To ignore or not use the value.
- It is unreachable, because Dart considers it just a placeholder.
- **Using**⤵️

1- Local variable declaration.
```dart
main() {
  var _ = 1;
  int _ = 2;
}

```
2- For loop variable declaration.

```dart

void main() {
  for (var _ in [1, 2, 3]) {
    print("Hello");
  }
}


```

3- Catch clause parameters.

``` dart

try {
  throw '!';
} catch (_) {
  print('oops');
}

```

4- Generic type and function type parameters.

```dart
class T<_> {}
void genericFunction<_>() {}

takeGenericCallback(<_>() => true);
```

5- Function parameters.

```dart

void logMessage(String message, [int _ = 0]) {
  print("Message: $message");
}

void main() {
  logMessage("Hi"); // هنا بنمرر رسالة بس
}


```
6- Pattern Matching
```dart
void main() {
  var list = [10, 20, 30];

  switch (list) {
    case [_, var second, _]:
      print("العنصر الثاني هو: $second");
  }
}

```

3- **Constants variables**


➡️**const**


   1- const is used to define const.

   2-  value of const is defined in compile-time so you must be intialization .

   3- value of const can't be change .

   4- The value of const store in memory only once and when you define 
   another const . it's refer in the same place in the memory .
   called (canonicalization)

   5- used to

   - Constans and exprssion math and Constans numbers .

   -  list - map - set  => content can't be change and can't be modify

   - instance variable which define with static keyword => static const

   - const object when 

   1- constructor is const 

   2- instance variables are final


➡️**final**

 1- final is used to define const.

   2- value of final is defined in run-time but you shouId give value before 
   you run-time to prevent occur error .   

   3- value of final can't be change .

   4- every final is define store in the saperted place in the memory

   5- Used to

   - instance variable ( instance variable can be final but can't be const )

   - methods which value is called during run-time 

   - list - map - set  => content can't be change but can be modify

   - dynamic object

```text
                                                                   final  بدلا من  const  هل يمكن استخدام 

             ولكن في حالات معينة وبشرط final  ايوا ينفع اني استخدمه بدال 
                  compile-time تكون معرفة اثناء  final   ان قيمة 

1- في المجموعات لتعريف مجموعة ثابة  final مع  const يمكن استخدام 
مع القيم  const لتعريف المجموعة  final  حيث نستخدم 


2- فقط لتعريفها بل فك المجموعة واعطي  const مع المجموعات المتداخل لا تستخدم 
const  وادي لكل حاجه 


```

➡️**Late**

- Late => non-nullable يستخدم مع المتغيرات التي نريد تاجيل تهيئتها وبشرط ان يكون هذه المتغير
  
```text
late variable name; // declaration
name = "Ammar"; // assignement


```
➡️**Type of Late**

1- late intialization => mean use late with variable.

2- lazy intialization => mean use late and final with variable.

-

```dart

late final String uniqueValue = _generateUniqueValue();

String _generateUniqueValue() {
  print('Function is being executed...');
  return 'The final value';
}

void main() {
  print(uniqueValue); // هنا سيتم تنفيذ الدالة للمرة الأولى فقط
  print(uniqueValue); // هنا لن يتم تنفيذ الدالة مرة أخرى
  print(uniqueValue); // وهنا أيضًا
}


```
```dart
Function is being executed...
The final value
The final value
The final value
```

4- **Null or Null Saftey**

- By defualt , Datatypes are Non-nullable.

➡️**Null**

- The reserved word null denotes an object that is the sole instance of this class.
- The Null class is the only class which does not implement Object.
- It is a compile-time error for a class to attempt to extend or implement Null.

➡️**Properties**

- hashCode → int
- runtimeType → Type

➡️**Methods**

- toString() → String


➡️**Null Safety**

-  Null Saftey is a set of operators that protect types from null values ​​and the errors they cause.
-  dynamic variables accept null except object.

```dart

void main() {
  var name;
  dynamic age ;
  print(name);
  print(age);
}

```

```text

1- ? ( Nullable Type Operator )  

- Null  تستخدم لجعل انواع البيانات تقبل قيمة          


2- ! or !. ( Null Assertion Operator )      

- تستخدم لكي نقول للبرنامج ان احنا متاكدين ان نوع البيانات المستخدم لا يكون فارغ وفي حالة اذا كان فعلا قيمتة فارغة سوف يحدث خطاا 

3- ?. ( Conditional Access Operator )         

- تستخدم مع اسماء انواع البيانات في حالة استخدام خصائص او دوال هذا النوع فهي تقوم بعملية تحقق من اذا كان نوع البيانات المستخدم قيمته Null فانه لا ينفذ هذه الخصائص والدول ويطبع Null


4- ?? " value " or expr ?? expr ( Null Coalescing Operator )

- Null تقوم باعطاء نوع البيانات قيمة افتراضية في حالة كان قيمته 

5- ??= " value "   ( Null Aware Assignment Operator )

- في حالة كان المتغير يحمل قيمة فارغة  فانها تقوم بتعيين قيمة له

6- ...? ( Null Aware Sperad Operator)

- الاستخدام الامن ل Sperad Operator في حالة كان وجود قيمة 

7- ?.. ( Null-aware Cascade Operator )

- الاستخدام الامن  Cascade Operator في حاله كان وجود قيمة Null

  8- late

- بستخدم في تاجيل تهيئة انواع البيانات 
```
```dart
import 'dart:io';

void main() {
  // nullable type operator => ?

  String? name; // null
  print(name);

  List<int>? age; // null
  print(age);

  List<int> age1 = []; // not null
  print(age1);

  // null Assertion operator => !

  print("Enter your age :");
  int? age2 = int.parse(
    stdin.readLineSync()!,
  ); // if user don't Enter input occur errrror
  print("your age is :$age2");

  // condtional Access operator => ?.

  String? operator;
  print(operator?.isEmpty);

  // Null Coalesing operator
  print(operator ?? "Ammar"); // defualt value

  // Null Aware Assignment Operator
  operator ??= "Nasr";
  print(operator);
}
```

## Operators in Dart


➡️**Arthimatic operator**

- ( + , - , * , / , ~/ , % )

```dart
void main() {
  // Arthimatic operator
  var a = 40;
  var b = 40;

  print(a + b);
  print(a - b);
  print(a / b); // convert to double
  print(a ~/ b);
  print(a % b);
}



```

➡️**Increment & Decrement**

- ( a++ , ++a , a-- , --a )

```dart
void main() {
  // Increment & Decrement
  var a = 40;
  var b = 40;

  print(a++); // frist print than add 1
  print(a); // 41
  print(++a); // add 1 then print = 42
  print(b--); // frist print than subtract 1
  print(b); // 39
  print(--b); // subtract 1 then print = 38
  print(a); // 42
  print(b); // 38
}



```


➡️**Assignment operator**

- ( += , -= , *= , /= , ~/= , %= )

```dart
void main() {
  // Assignment operator
  var a = 40;
  var b = 40;
  print(a += b); // a = a + b   a = 80
  print(a -= b); // a = a - b   a = 40
  print(a *= b); // a = a * b   a = 1600
  print(a ~/= b); // a = a ~/ b   a = 40
  print(a %= b); // a = a % b   a = 0
  
}

```
➡️**Type check oprator**

- ( is , !is ) => return bool
- Used to check species
- Type Promotion means that Dart understands the type of a variable better after you confirm its type. using is or is!

```dart
// Example

void main() {
  dynamic name = "Ammar";
  print(name is String); // true
}

// Type Promotion
void main() {
  
  // Type promotion
  dynamic name = "Ammar";
  if (name is String){
    
    print("Name is : $name");
    
  }
}

```

➡️**Bitwise Operator**

- ( & , | , ^ , ~ , << , >> )
- => before use bitwise operator you shouid first convert numbers to binary 

- &   // AND  => if two numbers contain two bits 1 result = 1  else  = 0  ( deal 8 bits and using 4 bit )
- |   // OR   => if one number contain  bit 1 result = 1  else  = 0        ( deal 8 bits and using 4 bit)
- ^   // XOR  => if two numbers contain different bits result = 1  else 0   ( deal 8 bits and using 4 bit )
- ~   // NOT  => reflects bits   (  deal 32 bit  ) 
- <<  // Left Shift => transfer bit 1 left = n
- >>  // Right Shift => transfer bit 1 right = n

```dart
void main() {
  // 4- Bitwise Operators

  int a = 5; // 0101  4 bit
  int b = 3; // 0011  4 bit

  print(a & b); // 0001 = 1   (deal 4 or 8 bits)
  print(a | b); // 0111 = 7   (deal 4 or 8 bits)
  print(a ^ b); // 0110 = 6   (deal 4 or 8 bits)
  print(~a); //  11111111 11111111 11111111 11111010 = -6     (deal 32 bits)
  print(a >> 2); // 1
  print(a << 2); //10100 =  20
}

```



➡️**Relational operator**

- ( < , > , == , != , <= , >= )

```dart
void main() {
  var age = 21;
  if (age == 21) {
    print("Age is Equel 21"); // 21
  }
  if (age < 22) {
    print("Age is Less than 22");
  }
  if (age > 20) {
    print("Age is Grater than 20");
  }

  if (age != 22) {
    print("Age is Not Equel than 22");
  }
}


```

➡️**Logic operator**

- ( && , || , ! )
- && تتطلب تحقق الشرطين
- || تتطلب تحقق اي شرط من الشروط
- ! تعكس الشرط

```dart
void main() {
  var name = "Ammar";
  var age = 21;

  if (age == 21 && name == "Ammar") {
    print("""
    Name is : $name
    Age is  : $age   
        """); // print occur becuase two condition true
  }

  if (age == 22 || name == "mahmoud") {
    print("""
    Name is : $name
    Age is  : $age   
        """); // No print occur becuase two condition false
  }

  if (!(age == 21)) {
    print("""
    Name is : $name
    Age is  : $age   
        """); // No print occur becuase  condition false
  }
}

```


➡️**Spread operator**

- ( ... )

- used to merge more list or map in new list or map but list or map don't null => هو يستخدم لعملية الدمج بين المجموعات بشرط ان تكون المجموعة المدمجة غير فارغة

```dart
// using spread operator

var fruits = ['apple', 'banana', 'orange'];
var moreFruits = ['grape', 'kiwi', ...fruits]; 

print(moreFruits); // الناتج: [grape, kiwi, apple, banana, orange]


```

```dart
// without spread operator
var fruits = ['apple', 'banana', 'orange'];
var moreFruits = ['grape', 'kiwi'];
moreFruits.addAll(fruits); 

print(moreFruits); // الناتج: [grape, kiwi, apple, banana, orange]
```
- Spread condition

```dart
void main() {
  bool showExtraItems = true;
  List<String> extraItems = ['Ammar', 'Nasr'];

  List<String> items = ['Mahmoud', if (showExtraItems) ...extraItems, 'Nasr'];
  print(items);
}
```

➡️**Cascade operator**

- ( .. )

- هي تستخدم مع الكائن عند اجراء عليه عدة خصائص بشكل متتالي .
- تستخدم مع المجموعات عند اجراء عليها عدة عمليات او خصائص متتالية .
- null لايمكن استخدمها اذا كان الكائن يحتوي علي قيمة
- لا يمكن استخدامها في حالة كانت العمليات تعيد كائنات مختلفة النوع.

```dart

// with out cascade operator 
void main() {
  
    StringBuffer buffer = StringBuffer();
    buffer.write('Hello');
    buffer.write(' ');
    buffer.write('World');
    buffer.write('!');
    print(buffer.toString()); // Hello World!
  
}

// cascade operator
void main() {
  
    StringBuffer buffer = StringBuffer()
      ..write('Hello')
      ..write(' ')
      ..write('World')
      ..write('!');
    print(buffer.toString()); // Hello World!
  
}

```
➡️**Access operator**

- ( . )

- used to access objects properties and methods.

➡️**Operator Precedence**

```text
1- () , [] , . , ?.

2- ++ , -- , ! , -

3- * , / , ~/ , %

4- + , -

5- << , >> , <<<

6- $ , | , ^

7- Relational operator with out == and != , is , !is , as

8- == , ! =

9- &&

10- ||

11- ??

12- ?:

13- Assignment operator

```


## Converting in dart

1- **Implicit Conversion**

```dart
int a = 10;
double b = a;   // Dart don't allow implicit converting

```

2- **Explicit Conversion**

➡️**Type Converting**

- *convert Strings to numbers*
- to convet string to int or double or num using static methos => parse or tyrParse.

```dart
import 'dart:io';
void main() {
  print("Enter your Name :");
  String? name = stdin.readLineSync();
  print(name);
  print("Enter your Age :");
  num? age = num.tryParse(stdin.readLineSync()!); // convert strings to num
  print(age);
}
```

- *convert numbers to Strings*
- to convert numbers toString using  => toString().

```dart

void main() {
  int age = 21;
  String adult = age.toString();
  print(adult);
  print(adult * 3); // string 21 21 21
  print(age * 3); // 63 int
}

```
- *convert int to double*
- to convert int to double using => toDouble().

- *convert double to int*
- to convert int to double using => toInt().

```dart
void main() {
  int a = 10;
  double b = a.toDouble();
  print(a); // 10
  print(b); // 10.0
}
```
- *convert num to int*

- *convert num to double*

- *convert double to num*

- *convert int to num*

```dart
void main() {
  // convert num to int
  num a = 10.00;
  int b = a.toInt();
  print(b); // 10

  // convert num to double
  num c = 10;
  double e = a.toDouble();
  print(e); // 10.0
}

```
```dart

void main() {
  int a = 10;
  num b = num.parse('$a');
  print(b); // 10
}

```

➡️**Type Casting**

- as => تقوم بتحويل الكائن من نوع الي نوع اخر بشرط ان يكون النوعين في نفس التسلسل الهرمي
```dart
void main() {

  dynamic name = "Ammar";
  print(name as String);
  print(name.runtimeType);
  if (name is int) {
    print("Name is int !!");
  }
}

```

## Control flow in dart

1- **Conditional statements**

2- **Loops**

3- **Handling Errors**

**Conditional statements**

1- **if**

```text

if (condition){
statements
}
// if condition is true the statement excute.
// if condition is false the statement don't excute.
```
```dart

void main() {
  String name = "Ammar";
  if (name == "Ammar") {
    print('Name is :$name');
  }
}
```
2- **if-else**

```text

if(condition){

statement1

}else{

statement2

}

// if conditoin is true the statement1 excute.
// if condition is false the statement2 excute.
```
```dart

void main() {
  String name = "Ammar";
  if (name == "Mahmoud") {
    print('Name is :$name');
  } else {
    print("Name don't Equel $name");
  }
}

```

3- **if-else if-else**

```text

if(condition1){

statement1

} else if(condition2){

statement2

}else{

statement3

}

// if conditoin1 is true the statement1 excute.
//  if conditoin1 is false the condition2 excute.
//if conditoin2 is true the statement2 excute.
//if conditoin2 is false the statement3 excute.
```

```dart

import 'dart:io';
void main() {
  print("Enter score your obtain :");
  int score = int.parse(stdin.readLineSync()!);
  if (score >= 90 && score <=100) {
    print("A+");
  } else if (score >= 85 && score < 90) {
    print("A");
  } else if (score >= 79 && score < 85) {
    print("B+");
  } else if (score >= 70 && score < 79) {
    print("B");
  } else if (score >= 65 && score < 70) {
    print("C+");
  } else if (score >= 60 && && score < 65) {
    print("C");
  } else if (score >= 50 && score < 60) {
    print("D");
  } else if (score < 50) {
    print("D");
  }else {
    print("Invalid Data");
  }
}



```

4- **Nested if**

```text
if(condition1){
if(condition2){

statement 1

}
statement 2
}

// if condition1 is true the if statement excute.
// if condition2 is true the statement1 excute and statement2 excute
// if condition1 is false the two if don't excute.

```

```dart
void main() {
  String name = "Ammar";
  int age = 21;
  if (name == "Ammar") {
    if (age == 21) {
      print("Name is :$name age is :$age");
    }
  }
}


```

5- **if => return - break - continue**

```text
if - return => هي تستخدم لانها الدالة وحفظ القيمة بداخلها
=> يمكن ارجاع اكثر من شي واحد داخل كلمة return عن طريق استخدام { }
if - break => هي تستخدم للخروج من الدالة عند تحقق الشرط
if - continue => هي تستخدم لتخطي المرحلة الحالية اذا تحقق الشرط
```

6- **conditonal expresions ( Ternary operator)**

- **يفضل انك تستقبل هذا التعبير في متغير ويمكن عدم استقبالها ولكن يفضل استقبالها .**
- **في الدوال يمكن استخدامها مع return ويمكن وضعها كتعبير في دالة Arrow function .**

```text

condition ? expression if true : expression if false ;

Nested conditional statement :

condition1 ?
  expression if true :
   condition2 ?
     expression if true :
       condition3 ? expression if true :
           expression if false;
```

```dart

void main() {
  String name = "Ammar";
  name == "Ammar" ? print(name) : print("Name don't Equel $name");
}
```

7- **Switch Statements**

- **تستخدم لعمل شرط لمتغير او ثابت لجميع القيم الخاصة به**
- **يمكن الاستغناء عن break ولكن يفضل استخدامها**

```dart
// used to compare object with many it's value

switch (object){
case ...: statements
break;
case .. : statements
break;
case ... : statements
break;
defualt :...
// if all case are false the defualt excute
}
```
```dart

import 'dart:io';

void main() {
  print("Enter Num1 :");
  double? num1 = double.parse(stdin.readLineSync()!);
  print("Enter Num2 :");
  double? num2 = double.parse(stdin.readLineSync()!);
  print("Enter your op => ( + , - , * , / ) :");
  String? op = stdin.readLineSync()!;
  switch (op) {
    case '+':
      print(num1 + num2);
      break;
    case '-':
      print(num1 - num2);
      break;
    case '*':
      print(num1 * num2);
      break;
    case '/':
      if (num2 != 0) {
        print(num1 / num2);
      } else {
        print("Can't Divided by Zero");
      }
      break;
  }
}

```


**Fall-through Behavior**

```dart

switch(){
case ...:
case .. : statements
break;
case ... : statements
break;
defualt :...
// if all case are false the defualt excute

}
```
```dart
import 'dart:io';

void main() {
  print("Enter your Month Season :");
  int month = int.parse(stdin.readLineSync()!);
  switch (month) {
    case 12:
    case 1:
    case 2:
      print('Month $month: Winter Season ');
      break;
    case 3:
    case 4:
    case 5:
      print('Month $month: Spring Season ');
      break;
    case 6:
    case 7:
    case 8:
      print('Month $month: Summer Season ');
      break;
    case 9:
    case 10:
    case 11:
      print('Month $month: Autumn Season ');
      break;
    default:
      print('Invalid month');
      break;
  }
}


```
**Nested Switch**

```dart

/*
A system that determines subjects based on:

Department (Engineering - Medicine - Science)

Academic year (first - second - third)
 */
void main() {
  String department = "هندسة";
  int year = 2;

  print("الطالب في قسم $department سنة $year");

  switch (department) {
    case "هندسة":
      switch (year) {
        case 1:
          print("المواد: رياضيات، فيزياء، برمجة أساسية");
          break;
        case 2:
          print("المواد: دوال تفاضلية، دوائر كهربية، برمجة متقدمة");
          break;
        case 3:
          print("المواد: تحكم آلي، إلكترونيات، تصميم أنظمة");
          break;
        default:
          print("السنة غير معروفة في قسم الهندسة");
      }
      break;

    case "طب":
      switch (year) {
        case 1:
          print("المواد: تشريح، فيسيولوجيا، كيمياء حيوية");
          break;
        case 2:
          print("المواد: أمراض، صيدلة، ميكروبيولوجيا");
          break;
        case 3:
          print("المواد: طب باطني، جراحة، أطفال");
          break;
        default:
          print("السنة غير معروفة في قسم الطب");
      }
      break;

    case "علوم":
      switch (year) {
        case 1:
          print("المواد: كيمياء عامة، فيزياء عامة، أحياء عامة");
          break;
        case 2:
          print("المواد: كيمياء عضوية، فيزياء حديثة، وراثة");
          break;
        case 3:
          print("المواد: كيمياء تحليلية، فيزياء كمومية، تكنولوجيا حيوية");
          break;
        default:
          print("السنة غير معروفة في قسم العلوم");
      }
      break;

    default:
      print("القسم غير معروف");
  }
}


```



2- **Loops**

➡️**for**

- **بنستخدمها عندما نكون علي علم بعدد التكرارات وتستخدم ك عداد .**

```dart

for(initilization ; condition ; iteration){

// statements

}

// initilization => thr first statement is excuted and excute once.
// condition => if condition is true the statements  is excuted => if condition is false the for end.
//  statements  => the three step is excuted.
// iteration ( increament or Decrement ) => the four step is excuted.
```

```dart

void main() {
  for (var i = 1; i <= 5; i++) {
    print("Ammar");
  }
}

```

➡️**Nested for**

```dart

for1(initilization1 ; condition1 ; iteration1){

for2(initilization2 ; condition2 ; iteration2){

//statements1

}
//statements2
}

// initilization1 => thr first statement1 is excuted and excute once.
// condition1 => if condition1 is true the for1  is excuted => if condition is false the for end.
// initilization2 =>  thr first statement1 is excuted and excute once.
// condition2 => if condition2 is true the statements2 is excuted => if condition2 is false the for2 end and the for 1 complite.

```
- **في كل مرة تنفذ فيها الحلقة الخارجية يتم تنفيذ الحلقة الداخلية بشكل كامل ثم تستكمل الدالة الخارجية وهكذا.**


➡️**while**

- **تستخدم مثل for كعداد عندما نكون عارفين عدد التكرارات مسبقا.**
- **تستخدم ايضا عندما نكون مش عارفين عدد التكرارات مسبقا .**

```dart
// Using while => for
initilization;
while ( condition ){

// statements
counter ++;

}

```
```dart
// using while when you don't know the number of iterations

while (condition){

// statements

}
```
➡️**do while**

- **هي تستخدم مثل while .**

```dart
// Using do while => for
initilization;
do {

// statements
counter ++;

}while ( condition )

```
```dart
// using do  while when you don't know the number of iterations

do {

// statements

}while (condition)
```

<div align="center">
   <table border="3" >
            <tr class="header-row">
                <th align = center>المعيار</th>
                <th align = center>do-while</th>
                <th align = center>while</th>
                <th align = center>for</th>
            </tr>
            <tr>
                <td align = center><strong>التحقق من الشرط</strong></td>
                <td align = center>بعد التنفيذ</td>
                <td align = center>قبل التنفيذ</td>
                <td align = center>قبل التنفيذ</td>
            </tr>
            <tr>
                <td align = center><strong>عدد التكرار</strong></td>
                <td align = center>غير معروف</td>
                <td align = center>غير معروف</td>
                <td align = center>معروف غالباً</td>
            </tr>
            <tr>
                <td align = center><strong>التنفيذ الأدنى</strong></td>
                <td align = center>1 مرة على الأقل</td>
                <td align = center>0 مرة</td>
                <td align = center>0 مرة</td>
            </tr>
            <tr>
                <td align = center><strong>المتغيرات</strong></td>
                <td align = center>منفصلة خارجية</td>
                <td align = center>منفصلة خارجية</td>
                <td align = center>مدمجة في الصيغة</td>
            </tr>
            <tr>
                <td align = center><strong>الأداء</strong></td>
                <td align = center>متساوٍ في الغالب</td>
                <td align = center>متساوٍ في الغالب</td>
                <td align = center>متساوٍ في الغالب</td>
            </tr>
        </table>

</div>

➡️**break & continue**

➡️**break**

- **هي تستخدم مع حلقات التكرار للخروج منها عند تحقيق شرط معين او الخروج منها في حالات معينة .**
- **هي  تستخدم ايضا مع switch .**

```dart

for (var i = 1; i <= 10; i++) {
    if (i == 5) {
      break;
    }
    print(" i = $i");
  }


```

➡️**continue**

- **هي تستخدم مع حلقات التكرار التكرار لتخطي مرحلة معينة عند شرط معين او  في حالات معينة .** 

```dart

 for (var j = 1; j <= 10; j++) {
    if (j == 5) {
      continue;
    }
    print(" i = $j");
  }


```


➡️**Labels**

- A label is an identifier followed by a colon (labelName:)
- you can place before a statement to create a labeled statement.
- A labeled statement can be referenced later in a break or continue statement only.
- (break labelName; | continue labelName;)

- **هي تستخدم مع الحلقات المتداخلة بشكل كبير ويمكن استخدامها ايضا مع switch .**

```dart

void main() {
  outerLoop:
  for (var i = 1; i <= 3; i++) {
    for (var j = 1; j <= 3; j++) {
      print('i = $i, j = $j');
      if (i == 2 && j == 2) {
        break outerLoop;
      }
    }
  }
  print('outerLoop exited');
}



```

## Handling Errors

➡️ **During you coding you show**⤵️

➡️ **Hints** => هي التلميحات التي تظهر اثناء التطوير ولا تؤثر علي البرنامج

➡️ **warnings** => هي التحذيرات التي تظهر اثناء التطوير ولا تؤثر علي البرنامج


➡️ **Errors**

- **هي الاخطاء او المشاكل التي تحدث في البرنامج اما اثناء التطوير او في البرنامج النهائي وقت تسبب مشاكل كبيرة ونفاذ الذاكرة.**

 ➡️ **Types of Errors**

 - Compile-time Errors => اخطاء وقت الترجمة وهي تحدث قبل تنفيذ البرنامج وتمنع تنفيذه
 - Runtime Errors => اخطاء وقت التنفيذ وهي تحدث اثناء تنفيذ البرنامج
 ↪️ - Exceptions => الاستثناءات هي اخطاء تحدث اثناء التنفيذ ويمكن توقعها والتعافي منها
 ↪️ - Errors  => الاخطاء الجسيمة وهي التي تحدث اثناء التنفيذ ولا يصعب التعافي منها

 - Logical Errors => الاخطاء المنطقية وهي الاخطاء التي تحدث بعد تنفيذ البرنامج ويكون النتيجة غير منطقية وصحيحة وصعب في الاكتشاف

 ➡️ **Bugs**

 - **البق (Bug) هو أي خطأ أو عيب أو خلل في البرنامج يؤدي إلى سلوك غير متوقع أو نتائج خاطئة.**
- **البق Bugs هو نوع من أنواع الأخطاء Errors  ولكن ليس كل خطأ هو بق!**
- Syntax Bugs => اخطاء في بناء الجمل

```dart

if (x > 5 { // ناقص قوس إغلاق
    print("Hello");
}


```
-  Runtime Bugs => أخطاء التنفيذ

```dart

int divide(int a, int b) {
  return a ~/ b; // إذا كانت b = 0 سيكون خطأ
}


```

- Logic Bugs => أخطاء منطقية

```dart

bool isAdult(int age) {
  return age < 18; // يجب أن يكون age >= 18
}

```
- Race Condition Bugs => أخطاء التنافس

```dart


int counter = 0;

void increment() {
  counter++; // غير آمن في البيئات المتوازية
}



```

➡️ **How to handeling error in runtime ( Exceptions )**

- **عشان نتعامل مع الاستثناءات بنستخدم القواعد التالية :**

➡️ **try**

- **هي يتم وضع بداخلها جميع الاكواد التي يتوقع انها تسبب خطا او استثناء**



```dart

try{

// all code cause Exceptions

}
```

➡️ **on**

- **هي تستخدم مع try عندما نريد التعامل مع نوع خطا معين**
- **يجب تحديد نوع الاستثناء بعدها**

```dart

try {

// all code cause Exceptions

} on Exception_type {

// Message show error

}

```

➡️ **catch**

- **هي تستخدم مع try عندما نريد التعامل مع جميع الاستثناءات اين كانت نوعها**

 ```dart
try{

// all code cause Exceptions

}catch(parameter_based, parameter_extra){

// Message show error

}

// parameter => هو عبارة عن كائن يمكن وضعه لمعرفة معلومات تفصيلية حول الخطا
// parameter_based => error or exception object => e or ex  => using e
// parameter_extra => Stack Trace or s  => توضح مسار التنفيذ الذي ادي الي الخطا
// catch (e, s) => تستخدما عندما نريد معرفة نوع الخطا وتتبع مسار الخطا
// catch (e) => تستخدم عندما نريد فقط معرفة نوع الخطا وعرض رسالة للمستخدم 
```
- **Exception: The base class for all exceptions.**
- Error objects thrown in the case of a program failure.
- **Error: The base class for all errors.**


➡️**on with catch**

- **نستخدم هذه الصيغة عندما نريد تحديد نوع الخطا مع اظهار رسالة الخطا واظهار معلومات اضافية للخطا**

```dart

try {

// all code cause Exceptions

} on Exception_type  catch(parameter){

// Message show error

}

```
➡️**on & catch**

```dart

try {

// all code cause Exceptions

} on Exception_type {

// Message show error

}catch(parameter){

// Message show error

}

```


➡️**finally**

- **يتم تنفيذ الكود بداخلها سواء تم معالجة عملية الاستثناء ام لا دائما يتم تنفيذ هذا الكود**
- **تستخدم لتنظيف الموارد مثل تنظيف الملفات انها الاتصال بقواعد البيانات**

```dart

file.close() => إغلاق الملفات
db.disconnect() => قطع الاتصالات لمنع تسريب الموارد
cache.clear() => تحرير الذاكرة لمنع استهلاك الذاكرة
lock.release() => إلغاء القفل
log.complete() => تسجيل النهاية

```

```dart

try {

// all code cause Exceptions

} catch (e){

// Message show error

} finally {

// any code

}

```


➡️ **Type of Exceptions or Error**

- **لازم تبقي عارف ان الاستثناءات موجودة بداخلة مكتبات ( dart:io - dart:core - dart:async )**

  
➡️ **dart core**

1- **FormatException**

- is a class can you use with its properties and methods .
- Exception thrown when a string or some other data does not have an expected format and cannot be parsed or processed.

➡️ **properties**

- message → String => A message describing the format error.
- offset → int? => The offset in source where the error was detected.
- source → dynamic => The actual source input which caused the error.

➡️ **Mthods**

- toString() → String => Returns a description of the format exception.

```dart

import 'dart:io';

void main() {
  try {
    print("Enter your Name :");
    String name = stdin.readLineSync()!;
    print("Enter your age :");
    int age = int.parse(stdin.readLineSync()!);
    print("""

Name is : $name
Age is : $age

""");
  } on FormatException catch (e) {
    print("Invalid Input");
    print(e.message);
    print(e.offest);
    print(e.source);
    String ex = e.toString();
    print(ex);
  }
}

```


2- **RangeError**

- is a class can you use with its properties and methods .
- Error thrown due to an argument value being outside an accepted range.
- **IndexError** => A specialized RangeError used when an index is not in the range 0..indexable.length-1.

➡️ **properties**

 - message → dynamic => Message describing the problem.
 - start → num? => The minimum value that value is allowed to assume.
 - end → num? => The maximum value that value is allowed to assume.
 - invalidValue → num? => The invalid value.
 - stackTrace → StackTrace? => The stack trace at the point where this error was first thrown.

➡️ **Mthods**

 - toString() → String => A string representation of this object.

```dart

void main() {
  try {
    List<dynamic> age = ["Ammar" , 20 , 30];
    print(age[-1]);
  } on RangeError catch (e) {
    print("NOT Allowed");
    print(e.message);
    print(e.start);
    print(e.end);
    print(e.invalidValue);
  }
}


```



3- **ArgumentError**

- is a class can you use with its properties and methods .
- Error thrown when a function is passed an unacceptable argument.

➡️ **properties**

  - message → dynamic => Message describing the problem.
  - invalidValue → dynamic => The invalid value.
  - stackTrace → StackTrace? => The stack trace at the point where this error was first thrown.


➡️ **Mthods**

 - toString() → String => A string representation of this object.


4- **StateError**

 - is a class can you use with its properties and methods .
 - The operation was not allowed by the current state of the object.
   
 - **هو استثناء يحدث عندما يتم استدعاء عملية على كائن في حالة غير صالحة لهذه العملية يعني أن الكائن ليس في الحالة المناسبة لتنفيذ العملية المطلوبة.**

➡️ **properties**

- message → String => A string representation of this object.
- stackTrace → StackTrace? => The stack trace at the point where this error was first thrown.

➡️ **Mthods**

- toString() → String => A string representation of this object.

5- **NoSuchMethodError**

- is a class can you use with its properties and methods .
- Error thrown on an invalid function or method invocation.

➡️ **properties**

- stackTrace → StackTrace? => The stack trace at the point where this error was first thrown.

6- **TypeError**

- is a class can you use with its properties and methods .
- Error thrown by the runtime system when a dynamic type error happens.
  
➡️ **properties**

- stackTrace → StackTrace? => The stack trace at the point where this error was first thrown.

7- **UnsupportedError**

- is a class can you use with its properties and methods .
- The operation was not allowed by the object.

➡️ **properties**

- message → String?
- stackTrace → StackTrace? => The stack trace at the point where this error was first thrown.

➡️ **Mthods**

- toString() → String => A string representation of this object.

=> IntegerDivisionByZeroException class => 
- UnsupportedError كنا بنستخدمها كنوع من الاستثناءات ولكن في الاصدارات الحديثة بنستخدم

8- **OutOfMemoryError**

- is a class can you use with its properties and methods .
- Error that the platform can use in case of memory shortage. => Heap Memory تستخدما عندما يطلب التطبيق ذاكرة اكبر من المتاحة في 

➡️ **properties**

- message → String?
- stackTrace → StackTrace? => The stack trace at the point where this error was first thrown.

➡️ **Mthods**

- toString() → String => A string representation of this object.

➡️ **How to create Custom Exception**

- **الطريقة الابسط والاسرع**
```dart

throw Exception (' message ');

throw constructor_typeException(' Message');

// تستخدم عندما نريد القاء استثناء بسيط 
// خطأ متكرر في المشروع	
// خطأ له معالجة خاصة
// خطأ يحمل بيانات إضافية
```

**Note** => باقي الطرق سوف نتعرف عليها في البرمجة كائنية التوجهة

➡️ **assert**

- **هي تستخدم في مرحلة التطوير فقط Debug Mode لالتقاط الاخطاء بسهولة .**
- **تساعدة في إيجاد الأخطاء مبكراً .**


**لا تستخدم في الحالات الاتية .**

 - التحقق من بيانات المستخدم => نستخدم if
- الأخطاء التي يجب معالجتها في الإنتاج
- الحالات التي تحتاج معالجة خاص
```dart

assert (condition , " message if error ");
// if condition is true the state is very good and the message don't excute.
// if condition is false the state is error and the message excute.

```
```dart

void main() {
  String name = "Ammar";
  assert(name == "M", 'error! The name equel $name');
  print(name);
}

```
## Function in dart

- **هي عبارة عن مجموعة من الاكواد البرمجية المجمعة التي تؤدي مهام معينة.**
- **تسمي الدوال داخل الكلاسات باسم Methods**
<br>

➡️**Features Using Function**
  
- orgnazing code.
- improve Readabiltiy
- Reusability
- Easy to Maintainability
- Better Testing
- Functional Programming


➡️**Types of Function**

- in generaly , the types of function
  
1- bulit in function

- **هي الدوال الموجودة في اللغة ونقوم باستخدامها**

2- user-define function

- **هي الدوال التي نقوم بعملها**

<br>

➡️**User-define function**

1- Regular Function

2- Arrow Function

3- Anonymous Function

4- Recursive Function

5- Higher-Order Functions ( Functions as first-class objects )

➡️**important**

- Lexical Scope
- Lexical Closures
- Function keyword
- Parameters

➡️**Regular Function**

1- Dynamic Function 

```dart

function_name (){

// statements

}

```

2- Void Function

```dart

void function_name (){

// statements

}

```

3- Return Function

```dart

data_type function_name (){

// statements

return ....;
}
```
➡️**call function**

```dart
void main(){

function_name ();

}

or
void main(){

var name = function_name;
name();

}
```


➡️**Arrow Function**

- **الدوال السهمية هي اختصار لصغية الدوال العادية .**
- **قيم هذه الدالة تكون عبارة عن تعبيرات فقط وسطر واحد .**


```dart

// Void Function
//  The => expr syntax is a shorthand for { expr; }.

void function_name () => ......;

// Return Function
// The => expr syntax is a shorthand for { return expr; }. The => notation is sometimes referred to as arrow syntax.
data_type function_name () => .....;

// Dynamic Function

function_name () => .....;
// The => expr syntax is a shorthand for { expr; }.
// The => expr syntax is a shorthand for { return expr; }. The => notation is sometimes referred to as arrow syntax.
```

➡️**Lexical scope**

- **يقصد بها هو مكان وجود المتغيرات فهناك نوعان من المتغيرات حسب المكان .**

1- **local variable**
- **هي المتغيرات التي توجد بداخل { }  او ( ) ولا يمكن الوصول لها الا من داخلها .**
  
2- **global variable**
- **هي المتغيرات العامة التي يمكن الوصول لها من اي مكان وغالبا توضع خارج الدالة Main .**

```dart

// Lexical Scope
int x = 10; // global variable

void main() {
  int xx = 11; // local variable for main() | global variable for foo();

  foo() {
    int xxx = 12; // local variable for foo()
    print(x);
    print(xx);
    print(xxx);
  }

  foo();
  // print(xxx); error
}

``` 

➡️**Lexical closures**

- **هي تعني وجود دالة داخل دالة اخري واستخدام الدالة الداخلية لمتغيرات الدالة الخارجية والتعديل فيها اي انهما بمثابة الاب والابن ويلزم عمل ارجاع للدرالة الداخلية في الدالة الخارجية.**

```dart

fooparent() {
  int x = 10;
  print(x);

  foochild() {
    x = x + 11;
    print(x);
  }

  return foochild();
}

void main() {
  fooparent(); // call function

  var result = fooparent; // call function متغير من نوع دالة
  result();
}

```

```dart

fooparent1() {
  int y = 20;
  print(y);

  foochild1() {
    y = y * 2;
    print(y);
  }

  return foochild1;
}

void main () {

fooparent1()();

  var result1 = fooparent1();
  result1();


}

```


➡️**Using**

-  إدارة الأحداث Event Handling
-  إدارة الذاكرة المؤقتة Caching
-  إدارة الحالة State Management
-  إعدادات التطبيق App Configuration
-   معالجة الطلبات غير المتزامنة API Rate Limiting
-   مدير المهام المجدولة Task Scheduler


➡️**Function**

- The Function class is a supertype of all function types.
- All objects that implement Function have a function type as their runtime type.
 
-  **هو عبارة عن متغير يخزن بداخلة دالة اين كان نوع هذه الدالة .**

```dart

// intilization

Function function_name = function;

// declaration then Assegnment

Function function_name;
function_name = function;

```
 ```dart

// Regular Function

Function function_name = sayHalow;

void sayHalow(){
print("Hallow World !");
}

void main (){

function_name (); // call with Function variable
sayHallow(); // call with Function_name

}

// Anonymous Function

Function function_name = (){

Statements

}

void main (){

function_name();

}
```
```dart

Function sum = foo; // function variable => initilization
void foo() {
  print("Hallow World");
}

int Function(int, int) sum2 = foo2; // secure way

int foo2(int a, int b) {
  return a + b;
}
void main() {
  sum(); // call with Function variable
  // or
  foo(); // call with Function name

  print("============================================");

  int result1 = foo2(10, 20); // call with Function name => 30
  print(result1);
}
```
**Notes**

- **الدالة المجهولة عند تخزينها بداخل متغير Function لازم نعملها initilization علي طول .**
- **لا يمكن ان يكون المتغير Function فارغة اي انه لا يحتوي علي قيمة Null .**
- **يفضل استخدام المتغير Function كالتالي :**

```dart

// استخدم أنواع محددة للأمان أكثر
int Function(int, int) calculator = (a, b) => a + b;

// بدلاً من
Function calculator = (a, b) => a + b; // أقل أماناً



```

➡️**Anonymous Function or Lambda function**

- **هي دالة لا يوجد لها اسم وتكتب بدون اسم .**
```dart

(parameters) {
  // body
  return value; // اختياري
}

// Arrow function

(parameters) => expression

```
- **هذه الدالة تستخدم فقط داخل دالة main وطريقة استدعاؤها هي ;() .**
- **اذا كنت تريد استخدام الدالة في اي مكان وخصوصا خارج دالة main لابد ان تخزن بداخل متغير Function او متغير من نوع دالة .**

```dart

void main() {
  () {
    print("أهلاً وسهلاً!");
 
  }();
}

```


```dart

var greet = () {
  print("أهلاً وسهلاً!");
  return "تم التحية";
};
void main() {
  String result = greet();
  print(result);
}

```

➡️**Recursive Function**

- **الدالة التكرارية هي دالة تعيد تعريف نفسها بداخل نفسها اي انها يمكن استدعاؤها بداخل نفسها**
- **فكرة الدالة التكرارية هي نفس فكرة حلقات التكرار بالظبط تفضل الدالة تكرر نفسها حتي تقف عند حالة معينة**

➡️**Component of this function**

```dart
// 1- Base Case - حالة التوقف (مهم جداً!)
// 2- Recursive Case - الاستدعاء المتكرر

void or return_type Function_name(parameter){

// Base Case => if statement
// Recursive Case => else or without else using => Function_name(process);

}

```

➡️**Using**

- **المشاكل الرياضية (المضروب - متسلسلة فيبوناتشي - حساب القوة - العدد التنازلي - التحويل للنظام الثنائي - الاعداد المتسلسلة)**
- **الخوارزميات وهياكل البيانات في عمليات البحث والفرز**
- **معالجة البيانات المتداخلة**
➡️**Disadvantages**

- Stack Overflow
- slow iteration

```dart
void countdown(int n) {

  // Base Case - حالة التوقف
  if (n <= 0) {
    print("🚀 انتهى!");
    return;
  }
  print("العد: $n");

  // Recursive Case 
  countdown(n - 1);
}

void main() {
  print("=== مثال العد التنازلي ===");
  countdown(5);
}


```
➡️ **Higher-Order Functions ( Functions as first-class objects )**

-  pass a function as a parameter to another function.

```dart

void printElement(int element) {
  print(element);
}

var list = [1, 2, 3];

// Pass printElement as a parameter.
list.forEach(printElement);
```

➡️**Notes**

- **pure function** => الدالة النقية هي الدالة التي لا تؤثر خارجيا وانما نفس المدخلات هي نفس المخرجات

```dart

int sum(int a, int b) {
  return a + b;
}

void main() {
  print(sum(2, 3)); // 5
  print(sum(2, 3)); // 5 - نفس المدخل → نفس المخرج
}


```
➡️**Non Pure Function**

```dart
int total = 0;

void addToTotal(int x) {
  total = total + x; // بتغير في متغير براها
  print(total); // بتطبع - تأثير جانبي
}

void main() {
  addToTotal(5); // 5
  addToTotal(5); // 10 - نفس المدخل بس مخرج مختلف!
}


```


➡️**Parameters**

➡️ **What difference between Parameters && Arguments**

- **Parameters** => It is the variable listed in the function definition. or It is the placeholder for the value that the function will use.
- **Arguments** => It is the actual value that is passed to the function when it is called.
- It is the value that the parameter will take when the function is executed.

➡️ **Types of Parameters**

1- **Requied Positonal Parameters**

- **هو ال Parameters التي  يتم اعطاؤه للدالة ويلزم تمرير له Arguments بالترتيب**

```dart
int add(int a , int b){
return a + b;
}
void main (){

int result = add(10 , 20);
print(result);
}

```

2- **Optional Positonal Parameters**

- **هو ال Parameters التي يتم اعطاؤه للدلة ويمكن تمرير له Arguments او لا يمكن**
- **يتم وضع ال Parameters بين [] لجعلها optional**

```dart
void printDetails(String name, [int? age]) {
  print('Name: $name');
  if (age != null) {
    print('Age: $age');
  }
}

void main() {
  printDetails('Alice'); // Age is omitted
  printDetails('Bob', 25);
}



```

3- **Optional Named Parameters**

- **هي ال Parameters التي يتم اعطاؤها للدالة ويمكن تمرير لها Arguments ام لا وعند تمرير قيم يلزم كتابة القيمة مع اسمها وهنا لا يفرق الترتيب**

- **يتم وضع ال Parameters بين {}**
```dart

void printPersonDetails({String? name, int? age}) {
  print('Name: $name, Age: $age');
}

void main() {
  printPersonDetails(name: 'Alice', age: 30);
  printPersonDetails(age: 25, name: 'Bob');
  printPersonDetails(name: 'Charlie'); 
  printPersonDetails(age: 40);
}


```

4- **Required Named Parameters**

- **هي Named Parameters ولكن يتم وضع كلمه Required قبل المتغيرات عشان نلزم بتمرير Arguments**

```dart

void printPersonDetails({required String name, required int age}) {
  print('Name: $name, Age: $age');
}

void main() {
  printPersonDetails(name: 'Alice', age: 30); // must provide both
  // printPersonDetails(name: 'Bob'); // Error: missing required 'age'
}


```

5- **Optional Parameters as Defulte Value**

- Both positional and named parameters can have default values.

```dart

void printMessage(String message, [String prefix = 'INFO']) {
  print('[$prefix] $message');
}

void main() {
  printMessage('Hello'); // [INFO] Hello
  printMessage('Hello', 'DEBUG'); // [DEBUG] Hello
}

```

6- **Mix Parameters**

- **You can combine Required positional parameters with**
 
2-  Optional positional parameters

or

3-  Named parameters (any required named parameters must be in the named section)

```dart

void printinfoo(String name, [int? age]) {
  print("Name is :$name , Age is :$age");
}

void main() {
  printinfoo("Ammar", 21);
  printinfoo("Ammar");
}

```

## ⤵️ قريبا سوف يتم تنزيل المحتوي التالي ⬇️
## Collection in dart


## Data Time in dart


## Pattern in Dart

----------------
## OOP in Dart
----------------

## Class && Object in OOP
