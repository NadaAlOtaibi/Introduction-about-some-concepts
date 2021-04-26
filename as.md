
<div dir = "rtl">

# as :

يتم استخدام **as** لإجراء التحويل بين compatible reference types أو Nullable types ويقوم بإرجاع الكائن عندما يكون متوافقًا مع النوع المحدد ويعيد القيمة فارغة إذا لم يكن التحويل ممكنًا.
```c#
expression is type ? (type)expression : (type)null
```
```c#
static  void  Main()

{

// creating and initializing object array

object[] coding = new  object[5];

obj[0] = "java";

obj[1] =  "Python";

obj[2] = "C#";

obj[3] = "C";

obj[4] = "HTML";

for  (int  i = 0; i < coding.Length; i++) {


string  str = coding[i] as  string;

Console.Write("{0}:", i);

// checking for the result

if  (str != null) {

Console.WriteLine("'"  + str + "'");

}

else  {

Console.WriteLine("Is is not a string");}}
```
</div>
