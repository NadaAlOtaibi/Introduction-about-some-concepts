<div dir = "rtl">

 

# this

كلمة محجوزة في اللغة وتعتبر مؤشر يشير إلى الكلاس  أو الخصائص الحالية وتستخدم كـمتغير في أول مدخل في الدوال الممتدة (extension method).

مثال:

</div>

```c#
class ClassicCar{

public string m_Make;

public string m_Model;

public int m_Year;

public int m_Value;

public ClassicCar(string m_Mak, string m_Model, int _Year, int m_Value){

m_Make = this.make;

m_Model = this.model;

m_Year = this.year;

m_Value = this. val;

}  }
```
