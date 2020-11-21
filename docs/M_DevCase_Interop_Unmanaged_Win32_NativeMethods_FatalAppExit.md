# NativeMethods.FatalAppExit Method 
 

Displays a message box and terminates the application when the message box is closed. 

 If the system is running with a debug version of Kernel32.dll, the message box gives the user the opportunity to terminate the application or to cancel the message box and return to the application that called FatalAppExit(UInt32, String).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static void FatalAppExit(
	uint action,
	string messageText
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Sub FatalAppExit ( 
	action As UInteger,
	messageText As String
)
```

**VB Usage**<br />
``` VB Usage
Dim action As UInteger
Dim messageText As StringNativeMethods.FatalAppExit(action, messageText)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static void FatalAppExit(
	unsigned int action, 
	String^ messageText
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member FatalAppExit : 
        action : uint32 * 
        messageText : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>action</dt><dd>Type: System.UInt32<br />This parameter must be zero</dd><dt>messageText</dt><dd>Type: System.String<br />The null-terminated string that is displayed in the message box.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679336(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679336(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />