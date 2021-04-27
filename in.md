<div dir = "rtl">

# in

تستخدم لـ تمرير الـ  argumentsعن طريق الـ  referenceولكن يتم التحقق من أنه لم يتم تعديله تشبه ref أو out  لكن لا يمكن تعديلها من خلال مناداة الدالة.
هنا مثال على تمرير المدخلات:
</div>

```c#
static void Enroll(in student student){
studnet.Enrolled = true;
}
static void Main(string[]args){
var studnet = new student { 
name = "Nada ",
Enroled = false};
Enroll(student);}}
public class student{
public string Name {get; set;}
public bool Enrlled{get;set;}}
```
