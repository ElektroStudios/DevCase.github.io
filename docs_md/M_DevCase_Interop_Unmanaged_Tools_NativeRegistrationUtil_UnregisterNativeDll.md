# NativeRegistrationUtil.UnregisterNativeDll Method (FileInfo)
 

Unregisters the classes in a native dll. 

 This is the equivalent for calling `RegSvr32.exe` to unregister a native dll.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool UnregisterNativeDll(
	FileInfo file
)
```

**VB**<br />
``` VB
Public Shared Function UnregisterNativeDll ( 
	file As FileInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim returnValue As Boolean

returnValue = NativeRegistrationUtil.UnregisterNativeDll(file)
```

**C++**<br />
``` C++
public:
static bool UnregisterNativeDll(
	FileInfo^ file
)
```

**F#**<br />
``` F#
static member UnregisterNativeDll : 
        file : FileInfo -> bool 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The native dll to be unregistered.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the native dll contains types that were successfully unregistered; otherwise `false` (`False` in Visual Basic) if the native dll contains no eligible types.

## Remarks


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil">NativeRegistrationUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeRegistrationUtil_UnregisterNativeDll">UnregisterNativeDll Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />

#### Other Resources
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms691457(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms691457(v=vs.85).aspx</a><br />