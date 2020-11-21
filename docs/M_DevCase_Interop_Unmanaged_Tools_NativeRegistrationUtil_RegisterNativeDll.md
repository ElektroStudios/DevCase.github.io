# NativeRegistrationUtil.RegisterNativeDll Method (FileInfo)
 

Registers the classes in a native dll to enable creation from COM. 

 This is the equivalent for calling `RegSvr32.exe` to register a native dll.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool RegisterNativeDll(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function RegisterNativeDll ( 
	file As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As Boolean

returnValue = NativeRegistrationUtil.RegisterNativeDll(file)
```

**C++**<br />
``` C++
public:
static bool RegisterNativeDll(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member RegisterNativeDll : 
        file : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The native dll to be registered.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the native dll contains types that were successfully registered; otherwise `false` (`False` in Visual Basic) if the native dll contains no eligible types.

## Remarks


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil">NativeRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil_RegisterNativeDll">RegisterNativeDll Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />

#### Other Resources
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms682162.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms682162.aspx</a><br />