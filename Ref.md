<div dir = "rtl">

# Ref

للتمرير من خلال Reference  نقوم باستخدام **Ref**
</div>

```c#
int Y = 1;  
Print (ref Y); Console.WriteLine (Y);

static void Print (ref int c) {

c = c + 1;

Console.WriteLine (c);}
```
<div dir = "rtl">
وهنا يتضح من المثال أن y,c يشيرون إلى نفس الموقع بالذاكرة.
</div>
