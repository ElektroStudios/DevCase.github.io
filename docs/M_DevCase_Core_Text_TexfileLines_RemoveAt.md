# TexfileLines.RemoveAt Method 
 

Removes the elements at the specified indices of this <a href="T_DevCase_Core_Text_TexfileLines">TexfileLines</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void RemoveAt(
	IEnumerable<int> indices
)
```

**VB**<br />
``` VB
Public Overridable Sub RemoveAt ( 
	indices As IEnumerable(Of Integer)
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As TexfileLines
Dim indices As IEnumerable(Of Integer)

instance.RemoveAt(indices)
```

**C++**<br />
``` C++
public:
virtual void RemoveAt(
	IEnumerable<int>^ indices
)
```

**F#**<br />
``` F#
abstract RemoveAt : 
        indices : IEnumerable<int> -> unit 
override RemoveAt : 
        indices : IEnumerable<int> -> unit 
```


#### Parameters
&nbsp;<dl><dt>indices</dt><dd>Type: System.Collections.Generic.IEnumerable(Int32)<br />The zero-based indices of the elements to remove.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>indices</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TexfileLines">TexfileLines Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />