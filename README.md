# Easy-Debounce
Easy Debounce 
 •  دلوقت لو انطلب منك تعمل بحث بإستخدام اي كلمة يدخلها المستخدم ؟ 
ف طبعا هتروح علطول علي onChange الموجوده ف ال TextField
و مع كل تغير هتبدا تبعت request
صح؟؟
صح!
لكن حرفياً دا كارثه!
لان ممكن علي ما المستخدم يدخل الاسم او الكلمه اللي بيبحث عنها تكون انت بعت ما يقرب من 10 : 15 طلب علي السيرفر
و دا مش افضل حاجه لانك حرفياً بتستهلك السيرفر علي حاجه تكاد تكون بسيطه و مش مستهله
 • طب الحل ايه ؟
 • الحل بكل بساطه ف مكتبة easy_debounce 
 - هتساعدك المكتبه دي انك تعمل عملية البحث اللي انت محتاجها ولكن بشكل احترافي و كمان هتحافظ علي موارد السيرفر اللي انت شغال عليه

 • طب نستخدمها ازاي ؟

 1. هنبدا ننزل المكتبه عندنا ف المشروع 
flutter pub add easy_debounce
 2. هنروح علي Textfield المسؤال عن عملية البحث و اللي المستخدم هيدخل فيه الكمله اللي بيبحث عنها
و ف Method onhChange
هنبدا نستدعي ال EasyDebounce.debounce 
زي ما موجود في المثال

 • بالطريقه دي هتبقي عملت عملية البحث بشكل احترافي من ناحية ال 
 user (front)
 • و كمان حافظت علي السيرفر الخاص بالمشروع من كثرة الطلبات عليه

 •  link: https://lnkd.in/dB5uK5P6
• Example
<img src='https://github.com/Ahmedelsapagh10/Easy-Debounce-/blob/master/2.png' width="30%"/>
<img src='https://github.com/Ahmedelsapagh10/Easy-Debounce-/blob/master/11.png' width="30%"/>



#easy_debounce
#flutter
#flutter_dev
#flutter_package

