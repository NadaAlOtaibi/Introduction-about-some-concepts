 
<div dir = "rtl">
# out

الـout هو parameter modifier ويشبه ref ولكن

لا يفترض أو ليس بالضرورة اسناد قيمة أولية للمتغير الذي سنمرره للدالة كــ out argument.

يجب اسناد قيمة للباراميتر المُمَرَّر للدالة كــ out parameter في الدالة الفرعية وإلا سينتج خطأ.

مثال هنا قمنا باستخدام out
</div>

```c#
string numberAsString = "1640";

if (Int32.TryParse(numberAsString, out int number))

Console.WriteLine($"Converted '{numberAsString}' to {number}");

else

Console.WriteLine($"Unable to convert '{numberAsString}'");

// The example displays the following output:

//  Converted '1640' to 1640
```
<div dir = "rtl">
وهنا يتضح من المثال أن y,c يشيرون إلى نفس الموقع بالذاكرة.
</div>
