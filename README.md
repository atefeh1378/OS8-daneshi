# OS8-daneshi


به نام خدا 

تمرینات سری هشتم آزمایشگاه سیستم عامل

عاطفه دانشی کامیاب

۹۷۴۴۰۳۰۳


سوال ۱) بررسی کنید دستورات زیر چه می کنند ؟

chmod 397 :


این دستور نامعتبر است و قابل اجرا نیست چون عدد ۹ در تعیین سطح دسترسی وجود ندارد و فقط اعداد ۰ تا ۷ قابل قبول است .


chmod 440 :


این دستور به کاربر فقط دسترسی خواندن می دهد اما اجازه نوشتن یا سایر دسترسی ها را نمی دهد .


chmod a=rx file1 :


این دستور به کاربر و گروه و دیگران دسترسی خواندن فایل ۱ را می دهد اما اجازه نوشتن نمی دهد .


chmod g=w sample :


این دستور به گروه دسترسی نوشتن در فایل سمپل را می دهد ولی اجازه خواندن و اجرا کردن آن را نمی دهد .


chmod r+x sample :


این دستور نامعتبر است و قابل اجرا نیست .


chmod u+g test :


در سطح دسترسی فایل تست تغییری ایجاد نمی کند .



سوال ۲) به انتخاب خود سه مورد از آپشن های دستور سی اچ مد را مختصرا توضیح دهید .

chmod --version :

اطلاعات ورژن (نسخه) را چاپ می کند و از آن خارج می شود .


chmod -R :
   
or

chmod --recursive :

این دستور سطح دسترسی فایل ها و دایرکتوری ها را به صورت بازگشتی تغییر می دهد .


chmod -c :

or

chmod --changes :

این دستور در صورت تغییر سطح دسترسی یک فایل گزارش می دهد .





