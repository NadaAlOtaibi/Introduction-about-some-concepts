
<div dir = "rtl">

 

# Enum

Enum كلمة محجوزة في اللغة وهي نوع بيانات قيمية لتعريف العديد من الثوابت ضمن مجموعة واحدة بشكل منطقي  وفي النهاية تعتبر هذه المجموعة كنوع جديد من البيانات وفيها عدة قيم محتملة، ولأيمكن أن توجد نفس القيمة مرتين في متغير من النوع Enum. مثال:

</div>

```c#
enum days { Sun , Mon,Tue, Wed , Thu , Fri,Sat }

foreach (days val in Enum.GetValues(typeof(days)))

{

Console.WriteLine(val);
}
```
