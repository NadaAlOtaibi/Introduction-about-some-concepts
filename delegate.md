 
<div dir = "rtl">


# :delegate 



 :عبارة عن كائن يقوم بمهمة المؤشر  فهو نوع بيانات ذات القيمة المرجعية يشير الى دالة .و هو مفوض للدالة فبدلا من أن يقوم البرنامج مناداة الدالة فإن delegate هو من يقوم بمناداة الدالة بطريقة غير مباشرة.يستخدم delegate مع الاحداث والدوال التي يتم استدعاءها عكسيا اي الى الوراء call-back  methods.

ويجب أن تكون عدد البارمتر في الداله مشابة لعدد البارمتر في الداله التي سنقوم بتطبيق **delegate**  عليها**.**
</div>

```c#
 <نوع البيانات> <delegate> < اسمdelegate > <الباراميترات>

public  delegate  void printString(string s);

printString ps1 =  new printString(WriteToScreen);

printString ps2 =  new printString(WriteToFile);

  public  static  int  AddNum(int p) {

 num += p;

  return num;  }

  public  static  int  MultNum(int q) {

 num *= q;

  return num;
  ```


