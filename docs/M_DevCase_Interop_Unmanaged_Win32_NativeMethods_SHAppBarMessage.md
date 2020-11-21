# NativeMethods.SHAppBarMessage Method 
 

Sends an `appbar` message to the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static IntPtr SHAppBarMessage(
	AppbarMessages message,
	ref AppbarData refData
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Function SHAppBarMessage ( 
	message As AppbarMessages,
	ByRef refData As AppbarData
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim message As AppbarMessages
Dim refData As AppbarData
Dim returnValue As IntPtr

returnValue = NativeMethods.SHAppBarMessage(message, 
	refData)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static IntPtr SHAppBarMessage(
	AppbarMessages message, 
	AppbarData% refData
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member SHAppBarMessage : 
        message : AppbarMessages * 
        refData : AppbarData byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_AppbarMessages">DevCase.Interop.Unmanaged.Win32.Enums.AppbarMessages</a><br />An `Appbar` message value to send.</dd><dt>refData</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData">DevCase.Interop.Unmanaged.Win32.Structures.AppbarData</a><br />A pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_AppbarData">AppbarData</a> structure. 

 The content of the structure on entry and on exit depends on the value set in the dwMessage parameter.</dd></dl>

#### Return Value
Type: IntPtr<br />This function returns a message-dependent value. 

 For more information, see the Windows SDK documentation for the specific appbar message sent. 



## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762108%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762108%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />