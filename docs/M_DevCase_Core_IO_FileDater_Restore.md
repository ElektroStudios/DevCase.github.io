# FileDater.Restore Method 
 

Restores the specified saved dates on the file. 

 Note: Calling this method does not cause the removal of any saved date.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Restore(
	DateAttribute dateAttributes
)
```

**VB**<br />
``` VB
Public Overridable Sub Restore ( 
	dateAttributes As DateAttribute
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim dateAttributes As DateAttribute

instance.Restore(dateAttributes)
```

**C++**<br />
``` C++
public:
virtual void Restore(
	DateAttribute dateAttributes
)
```

**F#**<br />
``` F#
abstract Restore : 
        dateAttributes : DateAttribute -> unit 
override Restore : 
        dateAttributes : DateAttribute -> unit 
```


#### Parameters
&nbsp;<dl><dt>dateAttributes</dt><dd>Type: <a href="T_DevCase_Core_IO_DateAttribute">DevCase.Core.IO.DateAttribute</a><br />The type of date(s) to restore on the file.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>The specified date was not saved.;dateAttributes</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />