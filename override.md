 
<div dir = "rtl">

# override

توفر تمثيل للدوال الموروثة من base class

مثال: تم استخدامه لاستخدام abstract  في parent


</div>

```c#

public override void Deposit(decimal amount)

{

if (amount > Balance)

{

Console.WriteLine("Denied");

}

else

{

Balance += amount;

Console.WriteLine("accepted");

}}```

}

```c#
