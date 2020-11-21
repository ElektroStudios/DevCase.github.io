# FileDater.Set Method 
 

Sets the specified dates on the file. 

 Note: Calling this method does not cause the removal of any saved date. 

 After setting a date, must call once the <a href="M_DevCase_Core_IO_FileDater_Save">Save(DateAttribute)</a> method if want to save any date established.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Set(
	DateAttribute dateAttributes,
	DateTime date
)
```

**VB**<br />
``` VB
Public Overridable Sub Set ( 
	dateAttributes As DateAttribute,
	date As DateTime
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim dateAttributes As DateAttribute
Dim date As DateTime

instance.Set(dateAttributes, date)
```

**C++**<br />
``` C++
public:
virtual void Set(
	DateAttribute dateAttributes, 
	DateTime date
)
```

**F#**<br />
``` F#
abstract Set : 
        dateAttributes : DateAttribute * 
        date : DateTime -> unit 
override Set : 
        dateAttributes : DateAttribute * 
        date : DateTime -> unit 
```


#### Parameters
&nbsp;<dl><dt>dateAttributes</dt><dd>Type: <a href="T_DevCase_Core_IO_DateAttribute">DevCase.Core.IO.DateAttribute</a><br />The type of date(s) to set on the file.</dd><dt>date</dt><dd>Type: System.DateTime<br />The date.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />