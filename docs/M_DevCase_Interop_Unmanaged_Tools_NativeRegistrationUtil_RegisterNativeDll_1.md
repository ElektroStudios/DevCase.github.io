# NativeRegistrationUtil.RegisterNativeDll Method (String)
 

Registers the classes in a native dll to enable creation from COM. 

 This is the equivalent for calling `RegSvr32.exe` to register a native dll.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool RegisterNativeDll(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function RegisterNativeDll ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Boolean

returnValue = NativeRegistrationUtil.RegisterNativeDll(filepath)
```

**C++**<br />
``` C++
public:
static bool RegisterNativeDll(
	String^ filepath
)
```

**F#**<br />
``` F#
static member RegisterNativeDll : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path of the native dll to be registered.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the native dll contains types that were successfully registered; otherwise `false` (`False` in Visual Basic) if the native dll contains no eligible types.

## Remarks


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil">NativeRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil_RegisterNativeDll">RegisterNativeDll Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />

#### Other Resources
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms682162.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms682162.aspx</a><br />