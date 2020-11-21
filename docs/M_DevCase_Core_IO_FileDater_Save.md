# FileDater.Save Method 
 

Preserves the specified dates of the file to restore them later at any time. 

 Note: Dates can be preserved again at any time.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Save(
	DateAttribute dateAttributes
)
```

**VB**<br />
``` VB
Public Overridable Sub Save ( 
	dateAttributes As DateAttribute
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim dateAttributes As DateAttribute

instance.Save(dateAttributes)
```

**C++**<br />
``` C++
public:
virtual void Save(
	DateAttribute dateAttributes
)
```

**F#**<br />
``` F#
abstract Save : 
        dateAttributes : DateAttribute -> unit 
override Save : 
        dateAttributes : DateAttribute -> unit 
```


#### Parameters
&nbsp;<dl><dt>dateAttributes</dt><dd>Type: <a href="T_DevCase_Core_IO_DateAttribute">DevCase.Core.IO.DateAttribute</a><br />The type of date(s) to preserve.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />