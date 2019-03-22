اگر می خواهید این آموزش را با نوشتن کد ادامه دهید من پیشنهاد می کنم ابتدا یک تکست ادیتور دانلود کنید
[Visual Studio Code](https://code.visualstudio.com/) یا [Sublime Text](https://www.sublimetext.com/).

سپس یک فایل با نام "basics.php" بسازید و در هر مسیری از سیستم خود که ترجیح می دهید ذخیره کنید, حالا می توانیم کمی کد پی اچ پی بنویسیم.
تمام کد های پی اچ پی باید با تگ `php?>` شروع شوند مگر اینکه بخواهیم از یک تمپلیت HTML استفاده کنیم.
(در فصل های بعدی در مورد تمپلیت ها صحبت خواهیم کرد.)
```php
<?php

echo "Hello World!\n";
```

There is a lot going on in the above code so let's work through it.

First, the echo keyword tells PHP to output some text.
```php
echo "I am some text\n";
```

Second, PHP stores text in strings. To write a string, you surround letters with single or double quotes.
Double quoted strings can hold special characters like `\n` which tells PHP to start a new line.
```php
echo "I am a string on a new line\n";
```

Third, all lines of code in PHP must end in a semi-colon.
```php
echo "No semi-colon is a no-no\n";
```

Using semi-colons means we can write multiple statements on one line.
```php
echo "PHP"; echo " Apprentice\n";
```

To execute the code you have written, make sure you have [PHP installed](/installing-php.html).
Then, open a terminal app, either Terminal on MacOS or Powershell on Windows. In the terminal,
open the folder where you created the `basics.php` file using `cd`. For example, on Windows run `cd C:\%userprofile%\Documents\phpapprentice` and on Mac run `cd ~/Documents/phpapprentice`. Finally, you can execute the file by running `php basics.php`.

In your terminal, you should see:
```bash
Hello World!
I am some text
I am a string on a new line.
No semi-colon is a no-no
PHP Apprentice
```

With any code in future chapters, I recommend writing a PHP file for it.
It is a great way to get some practice with the language.
