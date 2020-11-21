# Vector2Extensions.ToNativePoint Method 
 

Converts a Vector2 to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Vector2">DevCase.Core.Extensions.Vector2</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static NativePoint ToNativePoint(
	this Vector2 vector
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToNativePoint ( 
	vector As Vector2
) As NativePoint
```

**VB Usage**<br />
``` VB Usage
Dim vector As Vector2
Dim returnValue As NativePoint

returnValue = vector.ToNativePoint()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static NativePoint ToNativePoint(
	Vector2 vector
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToNativePoint : 
        vector : Vector2 -> NativePoint 

```


#### Parameters
&nbsp;<dl><dt>vector</dt><dd>Type: System.Numerics.Vector2<br />The source Vector2.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Vector2. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Vector2_Vector2Extensions">Vector2Extensions Class</a><br /><a href="N_DevCase_Core_Extensions_Vector2">DevCase.Core.Extensions.Vector2 Namespace</a><br />