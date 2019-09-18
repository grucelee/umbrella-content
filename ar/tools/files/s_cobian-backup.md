---
index: 2
title: النسخ الاحتياطي Cobian
---
# دليل أداة نسخ COBIAN الاحتياطي 

## كوبيان النسخ الاحتياطي
النسخ الاحتياطي لملفات الكمبيوتر الخاص بك

** درس للقراءة: [Backing Up]في (umbrella://information/backing-up) **
 ** موقع التحميل: **  [http://www.cobiansoft.com/cobianbackup.htm](http://www.cobiansoft.com/cobianbackup.htm) 
** متطلبات الكمبيوتر: **
- XP ، 2003 ، Vista ، 2008 ، Windows 7
- Windows 95 و 98 و ME متوافقان مع الإصدار 7 من Cobian.
** النسخة المستخدمة في هذا الدليل: ** Cobian 10
** الترخيص: ** مجاني
** المستوى: ** متوسط
** الوقت المطلوب: ** 30 دقيقة

### 1. أشياء يجب أن تعرفها عن هذه الأداة قبل البدء

يستخدم Cobian Backup لأرشفة (أو لعمل نسخة احتياطية) من الملفات والدلائل الخاصة بك. يمكن تخزين النسخ الاحتياطية في أدلة أو محركات أقراص أخرى على جهاز الكمبيوتر الخاص بك أو أجهزة الكمبيوتر الأخرى على شبكة المكتب أو على الأجهزة القابلة للإزالة (الأقراص المضغوطة وأقراص DVD وذاكرة USB). يتيح لك Cobian Backup إمكانية أرشفة ملفاتك وملفاتك على أساس منتظم. يعمل بصمت في الخلفية على النظام الخاص بك (أي ، في علبة النظام) ، التحقق من الجدول الزمني الخاص بك وتنفيذ عملية النسخ الاحتياطي عند الضرورة. كما يمكن لـ Cobian Backup ضغط الملفات وتشفيرها أثناء إنشاء ملف النسخ الاحتياطي.

- باستخدام Cobian سوف يعطيك:
- القدرة على عمل نسخة احتياطية من جميع المستندات والملفات والمجلدات
- القدرة على ضغط وفك ضغط ملفات النسخ الاحتياطي
- القدرة على تشفير وفك تشفير الملفات المؤرشفة

** تثبيت Cobian - في ايجاز**
- افتح www.cobiansoft.com/cobianbackup.htm
- انقر على الرابط "تنزيل نسخة Cobian Backup" على الصفحة.
- احفظ برنامج التثبيت ، ثم ابحث عنه وانقر نقرًا مزدوجًا عليه
- اقرأ "ملاحظة التثبيت" أدناه قبل المتابعة
- بعد قيامك بتثبيت Cobian بنجاح ، يمكنك حذف برنامج التثبيت من جهاز الكمبيوتر الخاص بك.

### 2.0 كيفية تثبيت نسخ  Cobian الاحتياطي

** ملاحظة التثبيت: ** قبل أن تبدأ عملية التثبيت ، تحقق من أن لديك أحدث الإصدارات من ** Microsoft Windows Installer ** و ** Microsoft.NET Framework **.

تثبيت Cobian Backup هو إجراء سهل وسريع نسبياً.

** الخطوة 1. ** انقر نقرا "cbsetup.exe" ؛ قد يظهر مربع الحوار _Open File - Security Warning_. إذا حدث ذلك ، فانقر فوق "تشغيل" لتنشيط اللون الأزرق الفاتح _استخراج شريط حالة التقدم للمورد ، متبوعًا بعد لحظات قليلة بالشاشة التالية: 
![صورة](tool_cobian1.png)

** الخطوة 2. ** انقر فوق "التالي" لتنشيط _Please قراءة وقبول اتفاقية الترخيص_ تحقق من الخيار _I accept_ ، ثم انقر فوق "التالي" مرة أخرى لتنشيط الشاشة التالية: 
![صورة](tool_cobian2.png)

** الخطوة 3. ** انقر فوق "التالي" لتنشيط الشاشة التالية:
![صورة](tool_cobian3.png)

** الخطوة 4. ** تحقق من خيار استخدم النظام المحلي _ في جزء خيارات _خدمة ، بحيث يشبه الشكل 3 الخاص بك أعلاه. يضمن هذا الخيار تشغيل نسخ Cobian الاحتياطي بصمت في الخلفية طوال الوقت ، حتى تحدث النسخ الاحتياطية وفقًا لجدول زمني.

** الخطوة 5. ** انقر فوق "التالي" لتنشيط رسالة الرسالة التالية: 
![صورة](tool_cobian4.png)

** الخطوة 6. ** انقر فوق "نعم" لتنشيط شاشة التثبيت التالية ، ثم انقر فوق "التالي" لمتابعة عملية التثبيت.

** الخطوة 7. ** انقر فوق "تم" لإكمال عملية التثبيت. بعد اكتمال عملية التثبيت ، سيظهر رمز Cobian Backup في **Windows System Tray**.

### 2.1 كيفية عمل نسخة احتياطية من الأدلة والملفات

ستتعرف في هذا القسم على كيفية إجراء نسخ احتياطي أو أرشفة بسيطة لملفات و / أو مجلدات محددة. يستخدم Cobian Backup مهمة _النشخ الاحتياطي_ التي يمكن تهيئتها لتضمين مجموعة محددة من الملفات و / أو المجلدات. يمكن ضبط مهمة النسخ الاحتياطي للتشغيل في يوم ووقت محددين.

لإنشاء مهمة نسخ احتياطي جديدة ، قم بإجراء الخطوة التالية:

** الخطوة 1. ** انقر فوق "جدول" لإنشاء مهمة نسخ احتياطي جديدة ، وتنشيط نافذة  _مهمة جديدة _ على النحو التالي:
![صورة](tool_cobian5.png)

يسرد الشريط الجانبي الأيسر عددًا من علامات التبويب ويتم عرض الشاشات المرتبطة بها - المستخدمة في تعيين خيارات ومعلمات نسخ احتياطي مختلفة - في الجزء على اليمين. جميع الخيارات في علامة التبويب _عام_ موضحة أدناه:

### 2.1.1 أوصاف الخيارات

_Task Name: _ يتيح لك حقل النص _Task Name_ هذا إدخال اسم لمهمة النسخ الاحتياطي. استخدم اسمًا يحدد طبيعة النسخ الاحتياطي. على سبيل المثال ، إذا كانت النسخة الاحتياطية ستتضمن ملفات فيديو ، فيمكنك تسميتها _Video Backup_.

_عدم تمكين _ يتم ترك هذا الخيار _must_ بدون تحديد.
 تحذير: سيؤدي تفعيل الخيار _عدم تمكين_ إلى تجاوز بقية الخيارات ومنع تشغيل مهمة النسخ الاحتياطي.

_يشمل على الدلائل الفرعية: _ يتيح لك هذا الخيار تضمين جميع الدلائل / المجلدات ضمن دليل / مجلد محدد لمهمة النسخ الاحتياطي. هذه طريقة فعالة لعمل نسخة احتياطية من عدد كبير من المجلدات و / أو الملفات. على سبيل المثال ، إذا قمت بتحديد المجلد _My Documents_ وحدد هذا الخيار ، فسيتم تضمين جميع الملفات والمجلدات الموجودة في _My Documents_ في مهمة النسخ الاحتياطي.

_إنشاء النسخ الاحتياطية المفصولة باستخدام الطوابع الزمنية: _ يتيح لك هذا الخيار تحديد أنه سيتم تضمين تاريخ ووقت مهمة النسخ الاحتياطي تلقائيًا في اسم المجلد الذي يحتوي على ملف النسخة الاحتياطية. هذه فكرة جيدة لأنها تعني أنك ستتمكن بسهولة من تحديد وقت إجراء النسخ الاحتياطي.
_استخدم  file attribute logic: _ هذا الخيار مناسب فقط عندما تختار إجراء نسخ احتياطي تزايدي أو تفاضلي (انظر أدناه). تحتوي سمات الملف على معلومات حول الملف.

** ملاحظة: ** يتوفر الخيار التالي فقط لإصدارات نظام التشغيل Windows الأحدث من _and_ بما في ذلك Windows XP.

_Use Volume Shadow Copy: _ يتيح لك هذا الخيار  نسخ الملفات الاحتياطي المؤمنة.
يتحقق Cobian Backup من هذه المعلومات لتحديد ما إذا كان هناك تغيير في الملف المصدر من آخر مرة تم فيها إجراء نسخة احتياطية. إذا قمت بتشغيل نسخة احتياطية _Differential_ أو _Incremental_ ، فسيتم تحديث الملف.

** ملاحظة: ** ستتمكن فقط من تشغيل نسخة احتياطية كاملة أو "وهمية" إذا كنت _قمت بعدم تمكين هذا الخيار_ (يتم شرح خيار النسخ الاحتياطي الوهمي أدناه).

### 2.1.2 وصف نوع النسخ الاحتياطي

_كامل: _ هذا الخيار يعني أنه سيتم نسخ كل ملف واحد في موقع المصدر إلى دليل النسخ الاحتياطي. إذا قمت بتمكين الخيار _خلق النسخ الاحتياطية باستخدام timestamp_ ، فستتوفر لديك عدة نسخ من نفس المصدر (يتم تحديدها بواسطة وقت وتاريخ النسخ الاحتياطي في عنوان المجلد). بخلاف ذلك ، ستقوم Cobian Backup بالكتابة فوق الإصدار السابق (إن وجد).

_تدريجي: _ يعني هذا الخيار أن البرنامج سيتحقق مما إذا كان قد تم تغيير الملفات المحددة للنسخ الاحتياطي منذ إجراء النسخ الاحتياطي الأخير. إذا لم يكن هناك أي تغيير ، سيتم تخطيها أثناء عملية النسخ الاحتياطي ، مما يوفر وقت النسخ الاحتياطي. يجب التحقق من الخيار _Use file attribute logic_ من أجل تنفيذ هذه النسخة الاحتياطية.

_التفاضليه: _ سيقوم البرنامج بالتحقق مما إذا كان المصدر قد تم تغييره من آخر نسخة احتياطية ** كاملة **. إذا لم تكن هناك حاجة لنسخ هذا الملف ، فسيتم تخطي ذلك ، مما يوفر وقت النسخ الاحتياطي. إذا قمت بتشغيل نسخة احتياطية كاملة من قبل على نفس مجموعة الملفات ، فيمكنك متابعة النسخ الاحتياطي ، باستخدام الطريقة التفاضلية.

_مهمة وهمية: _ يمكنك استخدام هذا الخيار للحصول على جهاز الكمبيوتر الخاص بك لتشغيل أو إيقاف تشغيل البرامج في أوقات معينة. يعد هذا خيارًا أكثر تقدمًا ولا يرتبط حقًا بإجراءات النسخ الاحتياطي الأساسية لدينا.

** الخطوة 2. ** انقر فوق "موافق" لتأكيد خيارات البحث الخاص بك والمعلمات لمهمة النسخ الاحتياطي.

### 2.2 كيفية إنشاء ملف النسخ الاحتياطي

لبدء إنشاء ملف نسخة احتياطية ، قم بإجراء الخطوات التالية:

** الخطوة 1. ** انقر فوق "ملفات" في الشريط الجانبي الأيسر من نافذة مهمة _New لعرض نسخة _blank_ من الشاشة التالية: 
![صورة](tool_cobian6.png)

** الخطوة 2. ** حدد الملفات التي تريد عمل نسخة احتياطية منها.  (In _Figure 3_ above, the _My Documents_ folder is selected.)

** الخطوة 3. ** انقر فوق "إضافة" في جزء _المصدر_ لتنشيط القائمة _Directory_.

** الخطوة 4. ** حدد _دليل_ إذا كنت تريد إجراء نسخ احتياطي لدليل بأكمله ، و _الملفات_ لعمل نسخة احتياطية من الملفات الفردية. لتحديد الملفات الفردية أو الأدلة التي سيتم نسخها احتياطيًا ، حدد _يدوياً_ ، واكتب مسار الملف أو دليله للنسخة الاحتياطية.

** ملاحظة: ** يمكنك إضافة العديد من الملفات أو الأدلة كما تريد. إذا كنت ترغب في نسخ الملفات الموجودة حاليًا على خادم FTP ، فاختر خيار موقع FTP (ستحتاج إلى الحصول على تفاصيل تسجيل الدخول إلى الخادم المناسبة).

عندما تحدد الملفات و / أو المجلدات ، فإنها ستظهر في منطقة _Source_. كما ترى في _Figure 3_ أعلاه ، يتم عرض مجلد _My Documents_ هناك ، مما يعني أن هذا المجلد سيتم تضمينه الآن في مهمة النسخ الاحتياطي.

يحدد الجزء _Destination_ موقع تخزين النسخة الاحتياطية.

** الخطوة 5. ** انقر فوق "إضافة" في الجزء _Destination_ لتنشيط قائمة الدليل.

** الخطوة 6. ** حدد _Directory_ لفتح نافذة المتصفح حيث يمكنك تحديد مجلد الوجهة لملف النسخ الاحتياطي.

** ملاحظة: ** إذا كنت ترغب في إنشاء إصدارات متعددة من ملف النسخة الاحتياطية ، فيمكنك تحديد عدة مجلدات هنا. إذا قمت بتحديد الخيار _يدوياً_ ، يجب عليك كتابة المسار الكامل للمجلد الذي تريد الاحتفاظ بالنسخة الاحتياطية فيه. لاستخدام خادم إنترنت عن بعد لتخزين الأرشيف ، حدد خيار موقع FTP (ستحتاج إلى الحصول على تفاصيل تسجيل الدخول إلى الخادم المناسبة).

يجب أن تشبه الشاشة الآن المثال أعلاه بالملف (الملفات) و / أو المجلد (المجلدات) في منطقة المصدر والمجلد (المجلدات) في منطقة الوجهة. ومع ذلك ، لا تنقر فوق _OK_ حتى الآن! ما زلت بحاجة إلى تعيين جدول للنسخ الاحتياطي الخاص بك.

### 2.3 كيفية جدولة مهمة النسخ الاحتياطي الخاص بك

لتشغيل النسخة الاحتياطية التلقائية ، تحتاج إلى ملء القسم _Schedule_. يتيح لك هذا القسم تحديد متى تريد إجراء النسخ الاحتياطي. لتعيين خيارات الجدول ، قم بتنفيذ الخطوات التالية:

** الخطوة 1. حدد "الجدول" من الشريط الجانبي الأيسر ، لتنشيط الجزء التالي:
![صورة](tool_cobian7.png)

يتم سرد خيارات _نوع الجدول الزمني_ في القائمة المنسدلة ، كما هو موضح أدناه:

_ مرة: _ سيتم إجراء النسخ الاحتياطي مرة واحدة فقط في التاريخ والوقت المحددين في منطقة _Date / Time_.

_يومياً: _ سيتم إجراء النسخ الاحتياطي كل يوم في الوقت المحدد في منطقة _Date / Time_.

_بشكل أسبوعي: _ سيتم إجراء النسخ الاحتياطي في أيام الأسبوع المحددة. في المثال أعلاه ، سيتم إجراء النسخ الاحتياطي في أيام الجمعة. يمكنك اختيار أيام أخرى أيضا. سيتم إجراء النسخ الاحتياطي في جميع الأيام المحددة في الوقت المحدد في منطقة _تاريخ/وقت_.

_ الشهر: _ ستتم عملية النسخ الاحتياطي في الأيام التي تمت كتابتها في أيام مربع الشهر في الوقت المحدد في منطقة _Date / Time_.

_سنوياً:_ سيتم إجراء النسخ الاحتياطي في الأيام التي تمت كتابتها في أيام مربع الشهر ، خلال الشهر المحدد ، وفي الوقت المحدد في منطقة _التاريخ/الوقت_.

_Timer: _ سيتم إجراء النسخ الاحتياطي بشكل متكرر على فترات زمنية محددة في مربع نص Timer في منطقة _Date / Time_.

_ بشكل يدوي:: _ سيكون عليك تشغيل النسخة الاحتياطية بنفسك من نافذة البرنامج الرئيسية.

** الخطوة 2. ** انقر فوق "موافق" لتأكيد الخيارات والإعدادات لجدول النسخ الاحتياطي على النحو التالي: 
![صورة](tool_cobian8.png)

بمجرد أن تقرر جدول النسخ الاحتياطي ، أكملت الخطوة النهائية. سيتم تشغيل النسخة الاحتياطية الآن على المجلدات المحددة وفقًا للجدول الذي اخترته.

### 3.0 كيفية ضغط ملف النسخ الاحتياطي الخاص بك

** الخطوة 1. ** قم بإنشاء مهمة نسخ احتياطي كما هو موثق في القسم 2.3 ، تحتوي على ملفات النسخ الاحتياطي التي تريد أرشفتها.

** الخطوة 2. ** حدد "أرشفة" من الشريط الجانبي الأيسر لتنشيط شاشة _مهمة جديدة_ على النحو التالي:
![صورة](tool_cobian9.png)

يتم استخدام جزء ** Compression ** لتحديد طريقة ضغط النسخة الاحتياطية.

** ملاحظة: ** يستخدم الضغط لتقليل مساحة تخزين الملفات. إذا كان لديك مجموعة من الملفات القديمة التي تستخدمها فقط من حين لآخر ، لكنك لا تزال ترغب في الاحتفاظ بها ، فمن المنطقي تخزينها بتنسيق حيث تأخذ مساحة صغيرة قدر الإمكان. يعمل الضغط عن طريق إزالة الكثير من الترميز غير الضروري من مستنداتك ، مع ترك المعلومات الهامة سليمة. لا يؤدي الضغط إلى إتلاف بياناتك الأصلية. الملفات غير قابلة للعرض عند ضغطها. يجب عكس العملية وإلغاء ضغط ملفاتك عندما تريد عرض الملفات مرة أخرى.

الخيارات الفرعية الثلاثة في القائمة المنسدلة _ نوع_الضغط _ هي:

_لا ضغط: _ لا يقوم هذا الخيار بأي ضغط ، كما هو متوقع.

ضغط _Zip: _ هذا الخيار هو تقنية ضغط قياسية لأنظمة Windows ** والأكثر ملاءمة. يمكن فتح الأرشيفات بمجرد إنشائها باستخدام أدوات Windows القياسية (أو يمكنك تنزيل برنامج [ZipGenius] في (http://www.zipgenius.it/) للوصول إليها).

يؤدي تحديد نوع ضغط مدرج تلقائيًا إلى تمكين القسم _Split_ options وقائمة المنسدلة المقابلة الخاصة به.

تنطبق خيارات _Split_ على التخزين على وسائط قابلة للإزالة ، على سبيل المثال الأقراص المضغوطة وأقراص DVD والأقراص المرنة وعصي ذاكرة USB. تقسيم الخيارات المختلفة سينقسم الأرشيف إلى أحجام تناسب جهاز التخزين الذي تختاره.

مثال: لنفترض أنك تقوم بأرشفة عدد كبير من الملفات ، وتريد نسخها على قرص مضغوط. ومع ذلك ، يتضح أن حجم الأرشيف الخاص بك أكبر من 700 ميجابايت (حجم القرص المضغوط). تقسم وظيفة التقسيم الأرشيف إلى أجزاء أصغر من أو تساوي 700 ميجابايت ،  يمكنك من نسخها بعد ذلك على الأقراص المضغوطة. إذا كنت تخطط لإجراء نسخ احتياطي على القرص الثابت للكمبيوتر الخاص بك ، أو كانت الملفات التي تريد نسخها احتياطيًا أصغر من الجهاز الذي تخطط لتخزينها عليه ، فيمكنك تخطي هذا القسم.

تتوفر الخيارات التالية لك عند النقر على القائمة المنسدلة _Split_split. يعتمد اختيارك على نوع جهاز التخزين القابل للنقل المتاح لك.
![صورة](tool_cobian10.png)

- 3،5 "- قرص مرن. هذا الخيار كبير بما يكفي لإجراء نسخ احتياطي لعدد صغير من الوثائق
- Zip - قرص مضغوط (التحقق من قدرة الشخص الذي تستخدمه). ستحتاج إلى محرك Zip خاص في جهاز الكمبيوتر الخاص بك والأقراص المصنوعة خصيصًا
- CD-R - قرص CD (تحقق من سعة السي دي الذي تستخدمه). ستحتاج إلى كاتب أقراص مضغوطة في الكمبيوتر الخاص بك وبرنامج كتابة الأقراص المضغوطة (راجع الإصدار  [DeepBurner Free] أو غيره في (http://www.deepburner.com/) من [أدوات النسخ على القرص](http://www.thefreecountry.com/utilities/dvdcdburning.shtml)).  
- DVD - قرص DVD (تحقق من سعة الجهاز الذي تستخدمه). ستحتاج إلى ناسخ أقراص DVD في جهاز الكمبيوتر الخاص بك وبرنامج كتابة DVD (راجع إصدار  [DeepBurner Free] في (http://www.deepburner.com/) أو غيرها من [أدوات النسخ على القرص]

إذا كنت تقوم بالنسخ الاحتياطي على العديد من بطاقات ذاكرة USB ، فقد ترغب في تعيين حجم مخصص.

للقيام بهذا ، نفذ الخطوات التالية:

**الخطوة 1. حدد** خيار _الحجم المخصص_ (bytes) ، ثم اكتب حجم الأرشيف بالبايت في حقل النص.

لتعطيك فكرة عن الأحجام
- 1 كيلوبايت (كيلوبايت) = 1024 بايت - يبلغ حجم المستند النصي المكون من صفحة واحدة والمصمم في Open Office حوالي 20 كيلوبايت تقريبًا
- 1 ميغابايت (ميغا بايت) = 1024 كيلوبايت - عادة ما تكون الصورة الملتقطة على كاميرا رقمية ما بين 1 و 3 ميغابايت
- 1 جيجابايت (جيجابايت) = 1024 ميجابايت - نصف ساعة تقريبًا من فيلم بجودة DVD

** ملاحظة: ** عند اختيار حجم مخصص لتقسيم النسخة الاحتياطية على قرص مضغوط أو قرص DVD ، لن يقوم Cobian Backup بنسخ النسخة الاحتياطية إلى جهازك القابل للإزالة تلقائيًا. بدلاً من ذلك ، سيقوم بإنشاء أرشيفك في هذه الملفات على الكمبيوتر وستحتاج إلى نسخها على قرص مضغوط أو قرص DVD بنفسك.

_Password Protect: _ يتيح لك هذا الخيار إدخال كلمة مرور لحماية الأرشيف. اكتب ببساطة ، ثم أعد كتابة كلمة المرور في المربعتين المقدمين. عند محاولة فك ضغط الأرشيف ، ستتم مطالبتك بكلمة المرور قبل بدء المهمة.

** ملاحظة: ** إذا كنت ترغب في تأمين الأرشيف ، فيجب التفكير في استخدام طريقة أخرى غير كلمة المرور. يتيح لك Cobian Backup تشفير الأرشيف الخاص بك. يتم تناول هذا أدناه.

_Comment: _ يتيح لك هذا الخيار أن يكتب شيئًا وصفيًا عن الأرشيف ، لكنه ليس شرطا.

### 3.1 كيفية فك ضغط ملف النسخ الاحتياطي

لإلغاء ضغط النسخة الاحتياطية ، قم بتنفيذ الخطوات التالية:

** الخطوة 1. حدد> أدوات> برنامج إلغاء ضغط. **

تظهر نافذة برنامج Decompressor على النحو التالي: 
![صورة](tool_cobian11.png)

** الخطوة 2. ** انقر على أيقونة الملف المفتوح لفتح نافذة التصفح لتمكينك من اختيار الأرشيف الذي تريد فك ضغطه.

** الخطوة 3. ** حدد الأرشيف (ملف _.zip_ أو _.7x_) ثم انقر فوق "موافق".

** الخطوة 4. ** حدد الدليل الذي سوف تفريغ (إخراج) الملف المؤرشف.

**الخطوة 5.** انقر على أيقونة الضغط لفتح نافذة أخرى تسمح لك باختيار المجلد الذي سيتم فيه فتح الأرشيف.

** الخطوة 6. ** حدد مجلد ، ثم انقر فوق "موافق".

استخدم مستكشف Windows لعرض الملفات التي تنتقل إلى هذا المجلد.

### 4.0 عن التشفير

قد يكون التشفير ضروريًا لأولئك الذين يرغبون في الاحتفاظ بنسخة احتياطية آمنة من الوصول غير المصرح به. التشفير هو عملية تشفير أو تخليط البيانات بطريقة تبدو غير واضحة لأي شخص ليس لديه المفتاح المحدد المطلوب لفك تشفير الرسالة. لمزيد من المعلومات حول التشفير ، اقرأ [درس حماية الملفات](umbrella://information/protecting-files).

### 4.1 كيفية تشفير ملف النسخ الاحتياطي الخاص بك

يستخدم جزء _التشفير القوي_ لتحديد طريقة التشفير ليتم استخدامها.

** الخطوة 1. ** انقر فوق مربع القائمة المنسدلة _Encryption_ لنشاط القائمة الخاصة بأساليب التشفير المختلفة.

للحفاظ على بساطة الأمور ، نوصي بالاختيار من بين أساليب _Blowfish_ أو _Rijndael_ (بت128) . ستوفر هذه الميزات أمانًا ممتازًا لأرشيفك ، وتسمح لك بالوصول إلى البيانات المشفرة باستخدام كلمة المرور المختارة.

** الخطوة 2. ** حدد _تشفير_ النوع الذي تريد استخدامه.

** ملاحظة: ** _Rijndael_ و _Blowfish_ كلاهما يوفران نفس المستوى تقريبًا من الأمان. _DES_ أضعف لكن عملية التشفير أسرع.

** الخطوة 3. ** اكتب وأعد كتابة كلمة المرور في المربعين الموفرين.

تتم الإشارة إلى قوة كلمة المرور بواسطة شريط يحمل علامة "جودة عبارة المرور". كلما تحرك الشريط إلى اليمين ، كلما كانت عبارة المرور أقوى. ارجع إلى ** [درس كلمات المرور]في (umbrella://information/passwords)** للحصول على معلومات حول إنشاء كلمات مرور قوية وتخزينها.

** الخطوة 4. ** انقر فوق "موافق".

### 4.2 كيفية فك تشفير ملف النسخ الاحتياطي الخاص بك

فك تشفير ملف النسخة الاحتياطية سهل وسريع. لفك تشفير ملف النسخة الاحتياطية ، قم بإجراء الخطوات التالية:

** الخطوة 1. حدد> الأدوات> ديكريبتر ومفاتيح: **

_ سيقوم هذا بتنشيط نافذة Decrypter و Keys كما يلي:
![صورة](tool_cobian12.png)

** الخطوة 2. ** انقر فوق "تحديد" لتحديد الأرشيف الذي تريد فك تشفيره.

** الخطوة 3. ** انقر فوق "وجهة" لتحديد المجلد لتخزين الأرشيف تم فك تشفيره.

** الخطوة 4. ** حدد نوع التشفير نفسه الذي حددته سابقًا ، في القسم 4.1 كيفية تشفير ملف النسخ الاحتياطي ، في القائمة المنسدلة _Methods_.

** الخطوة 4. حدد ** طريقة التشفير المناسبة (التي استخدمتها لتشفير ملف النسخ الاحتياطي).

** الخطوة 5. ** اكتب عبارة المرور الخاصة بك في حقول النص _Passphrase_.

** الخطوة 6. ** انقر فوق "فك تشفير!"

سيتم فك تشفير الملف (الملفات) إلى الموقع الذي حددته. إذا تم ضغط الملفات أيضًا ، فستحتاج إلى فك ضغطها كما هو موضح في القسم 3.1 كيفية إلغاء ضغط النسخة الاحتياطية.