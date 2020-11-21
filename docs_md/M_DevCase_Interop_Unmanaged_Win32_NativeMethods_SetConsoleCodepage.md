# NativeMethods.SetConsoleCodepage Method 
 

Sets the input code page used by the console associated with the calling process. 

 A console uses its input code page to translate keyboard input into the corresponding character value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "SetConsoleCP", ExactSpelling = true, 
	SetLastError = true)]
public static bool SetConsoleCodepage(
	uint codePageId
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "SetConsoleCP", ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function SetConsoleCodepage ( 
	codePageId As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim codePageId As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.SetConsoleCodepage(codePageId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"SetConsoleCP", ExactSpelling = true, 
	SetLastError = true)]
static bool SetConsoleCodepage(
	unsigned int codePageId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "SetConsoleCP", ExactSpelling = true, 
	SetLastError = true)>]
static member SetConsoleCodepage : 
        codePageId : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>codePageId</dt><dd>Type: System.UInt32<br />The identifier of the code page to be set.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/setconsolecp" target="_blank">https://docs.microsoft.com/en-us/windows/console/setconsolecp</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />