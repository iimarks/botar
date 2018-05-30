## Botar
> بوت حماية

## المخطط
> مخطط يبين طريقة عمل البوت 

 البوت يعمل ب `/, !, #` 

> --

🌐 اللغات 
--- |
عربي
انجليزي
لغات اخرى

> --

👥 المتحكمين بالبوت
--- |
المطور : يملك الصلاحية التحكم بجميع اوامر البوت
مساعد المطور : يقوم المطور بإضافته لتفعيل البوت في المجموعات
المدير : منشئ المجموعة
المشرف : مشرف المجموعة

> --

🗂 تخزين البيانات بإستخدام
--- |
JSON

> --

-  رسالة الترحيب في الخاص
```bash
# عند دخول اي عضو - مشرف - مدير للمجموعة يقوم البوت بحفظ معلومات العضو وبعدها تظهر له رسالة الترحيب مع زرين , الازرار :
- طلب البوت : عند الضغط عليه البوت يرسل رسالة للعضو يطلب فيها رابط المجموعة 
يقوم العضو بإرسال الرابط وبعدها يقوم البوت بتحويل الرابط للمطور مع معلومات العضو الذي ارسله

- الدعم : زر للتواصل مع المطورين 
```

- حماية البوت :
```bash
# عندما يقوم اي عضو ليس مطور او مساعد مطور بإضافة البوت للمجموعة يخرج البوت تلقائياً مع ارسال رسالة للمطور بمعلومات المجموعة التي قام العضو بإضافته اليها 
```

- لوحة تحكم للمطور :
```bash
# لوحة تحكم خاصة بالمطور يستطيع من خلالها التحكم بالبوت 
تحتوي اللوحة على ازرار :

▪️ احصائيات البوت : 
عند الضغط على الزر  تظهر رسالة تحتوي على احصائيات البوت

مثال :
⭐️ مجموعات vip : 5
📣 مجموعات free : 20
💬 الاعضاء في الخاص : 60
♦️ المجموع : 85

مع زرين : 
🔹 مجموعات vip : عند الضغط عليها يظهر لك مجموعة ازرار شفافة يحتوي كل زر على اسم مجموعة
عند الضغط على اسم المجموعة تظهر لك 4 ازرار :
🔸 معلومات المجموعة : تظهر لك معلومات المجموعة الايدي والاسم والمنشئ وعدد ايام التفعيل 
🔸 شحن المجموعة : عند الضغط عليه يظهر عدد ايام التفعيل بزر شفاف مع خيار اضافة ايام تفعيل للبوت
اسبوع : اضافة اسبوع تفعيل
شهر : اضافة شهر تفعيل
ستة شهور : اضافة 6 شهور تفعيل
سنة : اضافة تفعيل سنة

"عند الشحن تصل رسالة للمجموعة بأيام الشحن التي تم اضافتها"

🔸 رسالة للمجموعة : ارسال رسالة للمجموعة
🔸 مغاردة المجموعة : البوت يقوم بمغادرة المجموعة و مسحها من قائمة الازرار الشفافة


🔹 مجموعات free : 
عند الضغط عليه يظهر لك قائمة المجموعات الغير مدفوعة ويحتوي على نفس الازرار في قسم ال vip
🔸 معلومات المجموعة : تظهر لك معلومات المجموعة الايدي والاسم والمنشئ وعدد ايام التفعيل 
🔸 شحن المجموعة : عند الضغط عليه يظهر عدد ايام التفعيل بزر شفاف مع خيار اضافة ايام تفعيل للبوت
اسبوع : اضافة اسبوع تفعيل
شهر : اضافة شهر تفعيل
ستة شهور : اضافة 6 شهور تفعيل
سنة : اضافة تفعيل سنة

"عند الشحن تصل رسالة للمجموعة بأيام الشحن التي تم اضافتها"

🔸 رسالة للمجموعة : ارسال رسالة للمجموعة
🔸 مغاردة المجموعة : البوت يقوم بمغادرة المجموعة و مسحها من قائمة الازرار الشفافة



▪️ رسالة جماعية :
عند الضغط على الزر يظهر لك 4 ازرار 

🔹 مجموعات vip :
عند الضغط عليه يظهر لك زرين :
🔸 اعادة توجيه :  اعادة توجيه رسالة للمجموعات المدفوعة فقط
🔸 ارسال : ارسال رسالة للمجموعات المدفوعة فقط

🔹 مجموعات free : 
عند الضغط عليه يظهر لك زرين :
🔸 اعادة توجيه :  اعادة توجيه رسالة للمجموعات المجانية فقط
🔸 ارسال : ارسال رسالة للمجموعات المجانية فقط

🔹 الاعضاء : 
عند الضغط عليه يظهر لك زرين :
🔸 اعادة توجيه :  اعادة توجيه رسالة للاعضاء فقط
🔸 ارسال : ارسال رسالة للاعضاء فقط

🔹 الجميع : 
عند الضغط عليه يظهر لك زرين :
🔸 اعادة توجيه :  اعادة توجيه رسالة للجميع
🔸 ارسال : ارسال رسالة للجميع



▪️ مساعدين المطور :
عند الضغط عليه يظهر لك زرين :
🔹 اضافة مساعد مطور : لاضافة مساعد مطور عن طريق الايدي - المعرف
🔹 قائمة مساعدين المطور :
عند الضغط عليه يظهر لك قائمة مساعدين المطور كل عضو بزر
عند الضغط على زر يظهر لك معلومات العضو مع زر لازالته من قائمة مساعدين المطور



▪️ اعدادات البوت :
عند الضغط على الزر يظهر قائمة ازرار :

🔹 رسالة الترحيب : تغيير رسالة الترحيب في الخاص
🔹 حماية :
عند الضغط عليه يضغط زرين :
🔸 حماية من السبام : 
زر لتفعيل و تعطيل حماية البوت من تكرار الاعضاء في الخاص
🔸 تعيين التكرار : 
تعيين الحد الاقصى للتكرار في الخاص

🔹 استقبال الطلبات : 
تفعيل وتعطيل استقبال طلبات التفعيل من الاعضاء
 
```
