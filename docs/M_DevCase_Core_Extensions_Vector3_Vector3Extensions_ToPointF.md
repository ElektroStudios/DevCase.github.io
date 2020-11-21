# Vector3Extensions.ToPointF Method 
 

Converts a Vector3 to a PointF. 

 Note that Z property is ignored.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Vector3">DevCase.Core.Extensions.Vector3</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static PointF ToPointF(
	this Vector3 vector
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToPointF ( 
	vector As Vector3
) As PointF
```

**VB Usage**<br />
``` VB Usage
Dim vector As Vector3
Dim returnValue As PointF

returnValue = vector.ToPointF()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static PointF ToPointF(
	Vector3 vector
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToPointF : 
        vector : Vector3 -> PointF 

```


#### Parameters
&nbsp;<dl><dt>vector</dt><dd>Type: System.Numerics.Vector3<br />The source Vector3.</dd></dl>

#### Return Value
Type: PointF<br />The resulting PointF.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Vector3. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Vector3_Vector3Extensions">Vector3Extensions Class</a><br /><a href="N_DevCase_Core_Extensions_Vector3">DevCase.Core.Extensions.Vector3 Namespace</a><br />