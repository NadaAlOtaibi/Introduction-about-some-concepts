 
<div dir = "rtl">



# Params

كلمة محجوزة في اللغة إذا كنا نريد إدخال عدد لامحدود من المتغيرات ولا نعرف كمية الاعداد التي نريد إدخالها وبعد الكلمة لا نستطيع وضع مدخل آخر وإن أردنا نضعه قبل Params  كي لا يصبح لانهائي ولا نستطيع الوصول للمدخل الآخر.
</div>

```c#

public void Show(params int[] val) // Params {

for (int i=0; i<val.Length; i++){

Console.WriteLine(val[i]);}}

static void Main(string[] args){

Program program = new Program(); // عمل اوبجكت

program.Show(2,4,6,8,10,12,14); // تمرير مدخلات }
```
