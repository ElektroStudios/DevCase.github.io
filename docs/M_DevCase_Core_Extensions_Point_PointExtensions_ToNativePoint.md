# PointExtensions.ToNativePoint Method 
 

Converts a Point to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Point">DevCase.Core.Extensions.Point</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static NativePoint ToNativePoint(
	this Point sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToNativePoint ( 
	sender As Point
) As NativePoint
```

**VB Usage**<br />
``` VB Usage
Dim sender As Point
Dim returnValue As NativePoint

returnValue = sender.ToNativePoint()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static NativePoint ToNativePoint(
	Point sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToNativePoint : 
        sender : Point -> NativePoint 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Point<br />The source Point.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Point. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Point_PointExtensions">PointExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Point">DevCase.Core.Extensions.Point Namespace</a><br />