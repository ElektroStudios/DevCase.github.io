# NumericSequenceFormatter.DoFormat(*T*) Method 
 

Does the format.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DoFormat<T>(
	T[] obj,
	string format
)

```

**VB**<br />
``` VB
Public Function DoFormat(Of T) ( 
	obj As T(),
	format As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As NumericSequenceFormatter
Dim obj As T()
Dim format As String
Dim returnValue As String

returnValue = instance.DoFormat(obj, format)
```

**C++**<br />
``` C++
public:
generic<typename T>
String^ DoFormat(
	array<T>^ obj, 
	String^ format
)
```

**F#**<br />
``` F#
member DoFormat : 
        obj : 'T[] * 
        format : string -> string 

```


#### Parameters
&nbsp;<dl><dt>obj</dt><dd>Type: *T*[]<br />The numeric sequence to format.</dd><dt>format</dt><dd>Type: System.String<br />The format.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the numeric sequence.</dd></dl>

#### Return Value
Type: String<br />The resulting string representation of the numeric sequence passed to *obj*.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>FormatException</td><td>{format} cannot be used to format {value}.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_NumericSequenceFormatter">NumericSequenceFormatter Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />