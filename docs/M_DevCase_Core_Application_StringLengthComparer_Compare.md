# StringLengthComparer.Compare Method 
 

Compares two String and returns a value indicating whether one has length less than, length equal to, or length greater than the other.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Compare(
	string a,
	string b
)
```

**VB**<br />
``` VB
Public Function Compare ( 
	a As String,
	b As String
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As StringLengthComparer
Dim a As String
Dim b As String
Dim returnValue As Integer

returnValue = instance.Compare(a, b)
```

**C++**<br />
``` C++
public:
virtual int Compare(
	String^ a, 
	String^ b
) sealed
```

**F#**<br />
``` F#
abstract Compare : 
        a : string * 
        b : string -> int 
override Compare : 
        a : string * 
        b : string -> int 
```


#### Parameters
&nbsp;<dl><dt>a</dt><dd>Type: System.String<br />The first String to compare.</dd><dt>b</dt><dd>Type: System.String<br />The second String to compare.</dd></dl>

#### Return Value
Type: Int32<br />A signed integer that indicates the relative values of *a* and *b*. 

 0: *a* equals *b*. 

 Less than 0: *a* is less than *b*. 

 Greater than 0: *a* is greater than *b*.

#### Implements
IComparer(T).Compare(T, T)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Application_StringLengthComparer">StringLengthComparer Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />