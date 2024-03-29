# آزمایش ۶ مهندسی نرم افزار

## بازآرایی ۴ Separate Query From Modifier

<img width="1512" alt="Screenshot 1402-10-26 at 19 32 14" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/9f7667f2-27bf-4304-95e2-d281d7017fc8">

مطابق تصویر،در کلاس Memory.java تابع getDateAddress را که دو عمل افزایش متغیر و بازگرداندن آن را انجام می‌دهد را به دو تابع getDateAddress و incDateAddress می‌شکنیم و در تمامی نقاطی از کد که از این تابع استفاده شده است، دو تابع جدید را جایگزین می‌کنیم. در ادامه کد تغییر یافته و قسمت هایی که تغییر داده ایم را مشاهده می‌کنیم:


<img width="1512" alt="Screenshot 1402-10-26 at 19 36 15" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/1cdda105-c088-42f1-81f6-c1d39bb50ff3">

قسمت هایی که از تابع ()getDateAddress استفاده شده است و تغییر داده‌ایم:

<img width="1512" alt="Screenshot 1402-10-26 at 19 45 26" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/fc533dfa-b923-4a40-83d5-2a436762b008">

<img width="1512" alt="Screenshot 1402-10-26 at 19 45 36" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/98565382-c2fe-47d0-8952-d3ff34400fd2">

<img width="1512" alt="Screenshot 1402-10-26 at 19 45 48" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/e11e8136-3af7-45d7-84cc-293564ee44e2">

<img width="1512" alt="Screenshot 1402-10-26 at 19 46 12" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/cc692369-6ce1-4ecb-a82c-37cb3e6e6952">

<img width="1512" alt="Screenshot 1402-10-26 at 19 46 33" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/98aac40d-76d8-495a-adf7-3e5ebabe38c0">

## بازآرایی ۵ Extract Variable

در کلاس CodeGenerator.java، در تابع ()sub، یکی از if هایی که شرط داخل آن طولانی است را به صورت متغیرهای کوچک می‌نویسیم و در نهایت متغیرها را درون if اصلی قرار می‌دهیم. ابتدا عکس کد را قبل از تغییر مشاهده میکنیم:

<img width="1512" alt="Screenshot 1402-10-26 at 20 02 00" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/29cdbdc1-fde8-42df-9cae-7f0d54ed477a">

حال تغییر یافته آن را مشاهده می‌کنیم:

<img width="1512" alt="Screenshot 1402-10-26 at 20 07 58" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/0b63dae4-2a23-4835-a435-621ff84af439">


## بازآرایی ۶ Self Encapsulate Field

برای متغیر dataSize که private است، یک تابع getter ایجاد می‌کنیم و از این به بعد درون کلاس برای دسترسی به آن از این تابع استفاده می‌کنیم.

عکس قبل از اعمال تغییر:

<img width="1512" alt="Screenshot 1402-10-26 at 20 16 39" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/ebf58066-4841-4624-8247-63bd8508ba65">


عکس بعد از اعمال تغییر:


<img width="1512" alt="Screenshot 1402-10-26 at 20 19 26" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/0dc21262-c7f3-4e58-ae6c-b1924bd877da">


## بازآرایی ۷  Encapsulate Field

متغیر type را در کلاس Symbol.java را به حالت private تغییر داده و برایش یک getter ایجاد می‌کنیم.
قبل از تغییر:


<img width="1512" alt="Screenshot 1402-10-26 at 20 23 49" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/a5370335-ddc4-4bfc-94b4-b721458f6c85">


بعد از تغییر:


<img width="821" alt="Screenshot 1402-10-26 at 20 30 44" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/6307380e-5a54-4486-bbc8-d5a03bb7d672">

حال ارور های ایجاد شده در CodeGenerator را نیز اصلاح می‌کنیم:

<img width="821" alt="Screenshot 1402-10-26 at 20 31 46" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/e4e83084-7bc4-401f-92cd-d7670761df0e">

<img width="821" alt="Screenshot 1402-10-26 at 20 32 01" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/4d9e0fdf-8757-4ade-baab-7258944d25f7">

<img width="821" alt="Screenshot 1402-10-26 at 20 32 36" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/28a3c3ae-c9f2-4b05-8277-f133d4b55aa4">


<img width="821" alt="Screenshot 1402-10-26 at 20 32 42" src="https://github.com/dariusamiri/SE_LAB_6/assets/59167222/939bdad0-7056-4dbc-b401-dc6c15f36278">



 ## پاسخ پرسش ها

 ### سوال ۱

1. کد تمیز: کدی که به راحتی قابل درک، نگهداری است و خوانایی آن را افزایش می دهد و باعث می شود کارآمدتر و کمتر مستعد باگ باشد.
2. بدهی فنی: پیامدهای استفاده از میانبرها یا انتخاب های طراحی نامناسب در طول توسعه نرم افزار، که در طول زمان انباشته می شوند و نیاز به تلاش های آینده برای حل آن دارند.
3. بوی بد: اصطلاحی است که در مهندسی نرم افزار برای توصیف کدهایی استفاده می شود که ساختار ضعیفی دارند، درک شان دشوار است و حاوی practice های بدی هستند که حفظ و تغییر آنها را دشوارتر می کند.

 ### سوال ۲
 بر اساس وب سایت refactoring.guru، بوی بد کد به پنج دسته تقسیم می شود:

اول:	 Bloaters: Bloaters: بوهای بد کدی هستند که نشان دهنده کد یا طرحی است که بیش از حد بزرگ، پیچیده یا bloated شده است. به عنوان مثال می توان به Long Method, Large Class, و Primitive Obsession. اشاره کرد.

دوم:	 Object-Orientation Abusers :  این بوهای بد کد زمانی ایجاد می شوند که اصول و مفاهیم شی گرا مورد سوء استفاده یا نقض قرار بگیرند. مثل؛ Switch Statements, Temporary Field, و Refused Bequest.

سوم:	Change Preventers : بوهای بد کدی هستند که تغییر یا گسترش پایگاه کد را دشوار می کنند. آنها توانایی انطباق با نیازهای در حال تغییر را مختل می کنند. به عنوان مثال می توان به Shotgun Surgery, Divergent Change, و Feature Envy اشاره کرد.

چهارم:	Dispensables : به عناصر کد یا طراحی اطلاق می شوند که غیرضروری هستند و می توان آنها را با خیال راحت حذف کرد. به عنوان مثال می توان به Dead Code, Duplicate Code, و Lazy Class اشاره کرد.

پنجم:	Couplers : بوهای بد کدی هستند که نشان دهنده coupling یا وابستگی بیش از حد بین کلاس ها یا ماژول ها هستند. این بوها  انعطاف پذیری، قابلیت استفاده مجدد و قابلیت نگهداری کد را کمتر می کنند. به عنوان مثال می توان به nappropriate Intimacy, Message Chains, و Middle Man اشاره کرد.

 ### سوال ۳

1. بوی بد Lazy Class در رده Dispensables قرار می گیرد. Dispensable ها به کد یا عناصر طراحی اطلاق می شوند که غیرضروری هستند و می توان با خیال راحت آنها را حذف کرد.

2. برای حذف بوی Lazy Class، بازآرایی های توصیه شده عبارتند از:

    اول - حذف کلاس: اگر کلاس به طور فعال استفاده نشود یا عملکرد قابل توجهی نداشته باشد، می توان آن را با خیال راحت حذف کرد.
   
    دوم - Refactoring the class: اگر کلاس عملکرد مفیدی دارد اما در حال حاضر مورد استفاده قرار نمی گیرد، آن را refactoring کنید تا عملکرد آن با کلاس دیگری ادغام شود یا مسئولیت های آن بین کلاس های موجود توزیع شود.

3. بوی Lazy Class را می توان در موارد خاصی نادیده گرفت:

    - کد موقت یا آزمایشی: اگر کلاس برای استفاده موقت در حین توسعه یا آزمایش در نظر گرفته شده باشد و بعداً حذف شود، می توان بو را نادیده گرفت.
   
    - کد Placeholder: اگر کلاس یک placeholder یا stub است که به عنوان یادآوری برای implementation آینده عمل می کند، می توان آن را به طور موقت نادیده گرفت تا زمانی که پیاده سازی واقعی انجام شود.








# MiniJava
Mini-Java is a subset of Java. MiniJava compiler implement a compiler for the Mini-java
programming language.

# Rules
```
Goal --> Source EOF
Source --> ClassDeclarations MainClass
MainClass --> class Identifier { public static void main() { VarDeclarations Statements}}
ClassDeclarations --> ClassDeclaration ClassDeclarations | lambda
ClassDeclaration --> class Identifier Extension { FieldDeclarations MethodDeclarations }
Extension --> extends Identifier | lambda
FieldDeclarations --> FieldDeclaration FieldDeclarations | lambda
FieldDeclaration --> static Type Identifier ;
VarDeclarations --> VarDeclaration VarDeclarations | lambda
VarDeclaration --> Type Identifier ;
MethodDeclarations --> MethodDeclaration MethodDeclarations | lambda
MethodDeclaration --> public static Type Identifier ( Parameters ) { VarDeclarations Statements return GenExpression ; }
Parameters --> Type Identifier Parameter | lambda
Parameter --> , Type Identifier Parameter | lambda
Type --> boolean | int
Statements --> Statements Statement | lambda
Statement --> { Statements } | if ( GenExpression ) Statement else Statement | while ( GenExpression ) Statement | System.out.println ( GenExpression ) ; | Identifier = GenExpression ;
GenExpression --> Expression | RelExpression
Expression --> Expression + Term | Expression - Term | Term
Term --> Term * Factor | Factor
Factor --> ( Expression ) | Identifier | Identifier . Identifier | Identifier . Identifier ( Arguments ) | true | false | Integer
RelExpression --> RelExpression && RelTerm | RelTerm
RelTerm --> Expression == Expression | Expression < Expression
Arguments --> GenExpression Argument | lambda
Argument --> , GenExpression Argument | lambda
Identifier --> <IDENTIFIER_LITERAL>
Integer --> <INTEGER_LITERAL>
```
