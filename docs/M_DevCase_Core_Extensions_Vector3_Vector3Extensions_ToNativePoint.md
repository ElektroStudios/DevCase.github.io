# Vector3Extensions.ToNativePoint Method 
 

Converts a Vector3 to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>. 

 Note that Z property is ignored.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Vector3">DevCase.Core.Extensions.Vector3</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static NativePoint ToNativePoint(
	this Vector3 vector
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToNativePoint ( 
	vector As Vector3
) As NativePoint
```

**VB Usage**<br />
``` VB Usage
Dim vector As Vector3
Dim returnValue As NativePoint

returnValue = vector.ToNativePoint()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static NativePoint ToNativePoint(
	Vector3 vector
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToNativePoint : 
        vector : Vector3 -> NativePoint 

```


#### Parameters
&nbsp;<dl><dt>vector</dt><dd>Type: System.Numerics.Vector3<br />The source Vector3.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a>.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Vector3. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Vector3_Vector3Extensions">Vector3Extensions Class</a><br /><a href="N_DevCase_Core_Extensions_Vector3">DevCase.Core.Extensions.Vector3 Namespace</a><br />