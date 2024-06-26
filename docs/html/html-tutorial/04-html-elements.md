# عناصر HTML

یک عنصر HTML با یک برچسب شروع، محتوا و یک برچسب پایانی تعریف می‌شه.

## عناصر HTML

یک عنصر HTML همه چیزش از برچسب شروعش تا برچسب پایانیشه:

```html

<برچسب>محتوا</برچسب>
```

محتوای عنصر HTML همه چیز از برچسب شروع تا برچسب پایانی است:

```html
<h1> عنوان اول من </h1>

<p> پاراگراف اول من </p>
```

| برچسب شروع | محتوای عنصر | برچسب پایانی |
|--------------|---------------|----------------|
| `<h1>`       | عنوان اول من | `</h1>`        |
| `<p>`        | پاراگراف اول من. | `</p>`     |
| `<br>`       | هیچ           | هیچ           |

:::tip[توجه]
 برخی از عناصر HTML محتوایی ندارند (مانند عنصر
`<br>`
). این عناصر به عنوان عناصر خالی شناخته می‌شوند. عناصر خالی دارای برچسب پایانی نیستند!
:::

## عناصر HTML تو در تو
عناصر HTML می‌تونن به صورت درون‌یکدیگر باشن (این یعنی که عناصر می‌تونن دیگر عناصر رو شامل بشن).

تمامی اسناد HTML از عناصر HTML درون‌یکدیگر تشکیل شدن.

مثال زیر شامل چهار عنصر HTML (`<html>`، `<body>`، `<h1>` و `<p>`) است:


```html
<!DOCTYPE html>
<html>
<body>

<h1> عنوان اول من </h1>
<p> پاراگراف اول من </p>

</body>
</html>
```

### توضیح مثال
عنصر `<html>` ریشه‌ی سنده و همه‌ی اطلاعات سند HTML رو تعیین می‌کنه.

این عنصر یه برچسب شروع `<html>` و یه برچسب پایانی `</html>` داره.

بعدش، توی داخل عنصر `<html>` یه عنصر `<body>` هست:

```html
<body>

<h1>عنوان اول من</h1>
<p>پاراگراف اول من.</p>

</body>
```

عنصر `<body>` بدنه‌ی سند رو تعیین می‌کنه.

این عنصر یه برچسب شروع `<body>` و یه برچسب پایانی `</body>` داره.

بعدش، توی داخل عنصر `<body>` دو عنصر دیگه هستن: `<h1>` و `<p>`:

```html
<h1>عنوان اول من</h1>
<p>پاراگراف اول من.</p>
```
عنصر `<h1>` یه عنوان رو تعیین می‌کنه.

این عنصر یه برچسب شروع `<h1>` و یه برچسب پایانی `</h1>` داره:

```html
<h1>عنوان اول من</h1>
```
عنصر `<p>` یه پاراگراف رو تعیین می‌کنه.

این عنصر یه برچسب شروع `<p>` و یه برچسب پایانی `</p>` داره:

```html
<p>پاراگراف اول من.</p>
```

## هیچ وقت برچسب پایانی رو از فراموش نکن

برخی از عناصر HTML حتی اگه برچسب پایانی رو فراموش کنی، به درستی نمایش داده میشن:

```html title="مثال"
<html>
<body>

<p>این یه پاراگرافه
<p>این یه پاراگرافه

</body>
</html>
```

ولی هیچوقت به این اعتماد نکن! نتایج غیرمنتظره و خطاها ممکنه پیش بیاد اگه برچسب پایانی رو فراموش کنی!

## عناصر HTML خالی
عناصر HTML بدون محتوا به عنوان عناصر خالی شناخته میشن.

برچسب `<br>` یه شکست خط رو تعریف میکنه، و یه عنصر خالی بدون برچسب بسته رو نشون میده:


```html title="مثال"
<p>این یه <br> پاراگراف با یه شکست خطه.</p>
```

## HTML حساس به حروف بزرگ و کوچیک نیست
برچسب‌های HTML حساس به حروف بزرگ و کوچیک نیستن: `<P>` به معنی همون `<p>` هست.

استاندارد HTML نیازی به برچسب‌های کوچک نداره، ولی W3C تو HTML استفاده از حروف کوچک رو توصیه میکنه، و برای انواع سند محکم‌تر مثل XHTML از حروف کوچک استفاده رو می‌طلبه.

:::tip[توجه]
در مدرسه چارکد ما همیشه از نام‌های برچسب با حروف کوچک استفاده می‌کنیم.
:::

## مرجع عناصر HTML
مرجع عناصر HTML در وبسایت مدرسه چارکد اطلاعات بیشتری درباره این برچسب‌ها و ویژگی‌هایشان داره.

| برچسب HTML | توضیحات |
|---------|------------|
| `<html>` | این برچسب ریشه‌ی سند HTML رو تعریف می‌کنه |
| `<body>` | این برچسب بدنه‌ی سند رو تعریف می‌کنه |
| `<h1>` تا `<h6>` | اینا عناوین HTML رو تعریف می‌کنن |

برای دیدن یک لیست کامل از تمامی برچسب‌های HTML موجود، به [مرجع برچسب HTML](/docs/html/html-reference/html-by-alphaet) ما سر بزنید.





