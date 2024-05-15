## شاخصه‌ های اصلی طراحی یه پایگاه داده

#### چهار اصل برای طراحی خوب پایگاه داده وجود دارد : درستی داده‌ها، در دسترس بودن، به حداقل رساندن redundancy و برآورده کردن انتظارات.
#### صحت اطلاعات

دقت در دریافت اطلاعات برای حفظ یکپارچگی داده‌ها بسیار مهم است. داده‌های نادرست می‌توانند به نتیجه گیری‌های نادرست و در نهایت منجر به اتلاف وقت و منابع شود. برای اطمینان از صحت، کاربران باید داده‌ها را به طور صحیح و پیوسته وارد کنند. همچنین داده‌ها باید مرتباً تأیید شوند تا خطاها به حداقل میزان ممکن برسد.
#### دسترس پذیر بودن

دسترسی‌پذیری برای اطمینان از بازیابی سریع و آسان داده‌ها ضروری است. کاربران باید بتوانند اطلاعات مورد نیاز خود را بدون مشکل پیدا کنند.

برای رسیدن به این هدف، داده‌ها باید به خوبی سازماندهی شده و به صورت منطقی ذخیره شوند. مدیران پایگاه داده می‌توانند با ایجاد نمایه‌های واضح و مختصر و مستندسازی ساختار پایگاه داده به بهبود دسترسی کمک کنند.
#### به حداقل رساندن redundancy

به حداقل رساندن افزونگی برای کاهش هزینه‌های ذخیره سازی و حذف خطاها حیاتی است. نسخه‌های تکراری و کپی داده‌ها باعث هدر رفت فضا و در صورت عدم همگام‌سازی صحیح می‌تواند inaccuracy ایجاد کند.

هنگام طراحی یک پایگاه داده، DBA ها باید از تکرار غیر ضروری داده‌ها خودداری کنند. در صورت نیاز به کپی‌های یکسان از داده‌ها، باید اطمینان حاصل شود که نسخه‌ها به روز نگه داشته می شوند.
برآورده کردن انتظارات

طراحی پایگاه داده‌ای که نیازهای کاربران را برآورده کند بسیار حیاتی است. مدیران پایگاه داده باید برای درک نیازها و انتظارات کاربران با آن‌ها مشورت کنند. سپس، پایگاه داده باید طوری طراحی شود که کاربران بتوانند داده‌های مورد نیاز خود را پیدا و بازیابی کنند.
