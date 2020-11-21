# TextComparer.Compare Method 
 

Compares two objects and returns a value indicating whether one is less than, equal to, or greater than the other.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Compare(
	Object a,
	Object b
)
```

**VB**<br />
``` VB
Public Function Compare ( 
	a As Object,
	b As Object
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextComparer
Dim a As Object
Dim b As Object
Dim returnValue As Integer

returnValue = instance.Compare(a, b)
```

**C++**<br />
``` C++
public:
int Compare(
	Object^ a, 
	Object^ b
)
```

**F#**<br />
``` F#
member Compare : 
        a : Object * 
        b : Object -> int 

```


#### Parameters
&nbsp;<dl><dt>a</dt><dd>Type: System.Object<br />The first object to compare.</dd><dt>b</dt><dd>Type: System.Object<br />The second object to compare.</dd></dl>

#### Return Value
Type: Int32<br />A signed integer that indicates the relative values of *a* and *b*. 

 0: *a* equals *b*. 

 Less than 0: *a* is less than *b*. 

 Greater than 0: *a* is greater than *b*.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_TextComparer">TextComparer Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />