# FileDater.SavedDate Property 
 

Gets a saved date.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual DateTime this[
	DateAttribute dateAttributes
] { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property SavedDate ( 
	dateAttributes As DateAttribute
) As DateTime
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileDater
Dim dateAttributes As DateAttribute
Dim value As DateTime

value = instance.SavedDate(dateAttributes)

```

**C++**<br />
``` C++
public:
virtual property DateTime SavedDate[DateAttribute dateAttributes] {
	DateTime get (DateAttribute dateAttributes);
}
```

**F#**<br />
``` F#
abstract SavedDate : DateTime with get
override SavedDate : DateTime with get
```


#### Parameters
&nbsp;<dl><dt>dateAttributes</dt><dd>Type: <a href="T_DevCase_Core_IO_DateAttribute">DevCase.Core.IO.DateAttribute</a><br />The type of date to retrieve.</dd></dl>

#### Property Value
Type: DateTime<br />The date.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileDater">FileDater Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />