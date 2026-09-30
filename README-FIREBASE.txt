رفيق الطالب - ملكية المنشورات

1) ارفع index.html وملفات المشروع كالمعتاد.
2) في Firebase Console افتح Firestore Database > Rules.
3) انسخ محتوى firestore.rules والصقه ثم اضغط Publish.
4) تأكد أن Authentication > Sign-in method > Email/Password مفعّل.

المنشورات الجديدة في summaries و deadlines و questions تحفظ ownerUid و ownerEmail.
الطالب يستطيع تعديل وحذف منشوراته فقط.
الطلاب الآخرون يستطيعون القراءة فقط.

ملاحظة: المنشورات القديمة التي أُنشئت قبل إضافة ownerUid لن تكون قابلة للتعديل أو الحذف من خلال قواعد الملكية الجديدة؛ يمكن إبقاؤها للقراءة أو إضافة ownerUid لها عبر لوحة Firebase/Admin.
