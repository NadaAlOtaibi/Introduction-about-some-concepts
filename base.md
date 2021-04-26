
<div dir = "rtl">

# base :

يستخدم للوصول للكونستركتر في الكلاس

فبدلا من أن ينشئ المستخدم فئة جديدة فيمكنه وراثة عناصر ودوال  ومتغيرات  فئة أخرى. الفئة الموروثة تسمى بالفئة الأساسية  Base Class

والفئة الوارثة تسمى بالفئة المشتقة derived Class.
</div>

مثال:
```c#
class  Tabletop  :  Rectangle {
  private  double cost;
  public Tabletop(double l,  double w)  :  base(l, w) {  }
```
