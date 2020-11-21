# NativeMethods.FlushConsoleInputBuffer Method 
 

Flushes the console input buffer. All input records currently in the input buffer are discarded.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool FlushConsoleInputBuffer(
	IntPtr hConsoleInput
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function FlushConsoleInputBuffer ( 
	hConsoleInput As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hConsoleInput As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.FlushConsoleInputBuffer(hConsoleInput)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool FlushConsoleInputBuffer(
	IntPtr hConsoleInput
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member FlushConsoleInputBuffer : 
        hConsoleInput : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hConsoleInput</dt><dd>Type: System.IntPtr<br />A handle to the console input buffer. 

 The handle must have the `GENERIC_WRITE` access right.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/flushconsoleinputbuffer" target="_blank">https://docs.microsoft.com/en-us/windows/console/flushconsoleinputbuffer</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />