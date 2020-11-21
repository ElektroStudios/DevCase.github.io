# FileDater.Truncate Method 
 

Truncates the specified date(s) of the file to "01/01/1800 00:00:00". 

 Note: Calling this method does not cause the removal of any saved date. 

 After setting a date, must call once the <a href="M_DevCase_Core_IO_FileDater_Save">Save(DateAttribute)</a> method if want to save any date established.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Truncate(
	DateAttribute dateAttributes
)
```

**VB**<br />
``` VB
Public Overridable Sub Truncate ( 
	dateAttributes As DateAttribute
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim dateAttributes As DateAttribute

instance.Truncate(dateAttributes)
```

**C++**<br />
``` C++
public:
virtual void Truncate(
	DateAttribute dateAttributes
)
```

**F#**<br />
``` F#
abstract Truncate : 
        dateAttributes : DateAttribute -> unit 
override Truncate : 
        dateAttributes : DateAttribute -> unit 
```


#### Parameters
&nbsp;<dl><dt>dateAttributes</dt><dd>Type: <a href="T_DevCase_Core_IO_DateAttribute">DevCase.Core.IO.DateAttribute</a><br />The type of date(s) to truncate.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />