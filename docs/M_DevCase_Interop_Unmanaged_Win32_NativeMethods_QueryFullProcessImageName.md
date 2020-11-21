# NativeMethods.QueryFullProcessImageName Method 
 

Retrieves the full name of the executable image for the specified process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool QueryFullProcessImageName(
	IntPtr hProcess,
	ProcessNameFlags flags,
	StringBuilder lpExeName,
	ref int refSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function QueryFullProcessImageName ( 
	hProcess As IntPtr,
	flags As ProcessNameFlags,
	<OutAttribute> lpExeName As StringBuilder,
	ByRef refSize As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim flags As ProcessNameFlags
Dim lpExeName As StringBuilder
Dim refSize As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.QueryFullProcessImageName(hProcess, 
	flags, lpExeName, refSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool QueryFullProcessImageName(
	[InAttribute] IntPtr hProcess, 
	[InAttribute] ProcessNameFlags flags, 
	[OutAttribute] StringBuilder^ lpExeName, 
	int% refSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member QueryFullProcessImageName : 
        hProcess : IntPtr * 
        flags : ProcessNameFlags * 
        lpExeName : StringBuilder byref * 
        refSize : int byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process. 

 This handle must be created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryInformation</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessAccessRights">QueryLimitedInformation</a> access right.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessNameFlags">DevCase.Interop.Unmanaged.Win32.Enums.ProcessNameFlags</a><br />Specifies the resulting format of the process path.</dd><dt>lpExeName</dt><dd>Type: System.Text.StringBuilder<br />The path to the executable image. 

 If the function succeeds, this string is null-terminated.</dd><dt>refSize</dt><dd>Type: System.Int32<br />On input, specifies the size of the *lpExeName* buffer, in characters. 

 On success, receives the number of characters written to the buffer, not including the null-terminating character.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error(). 



## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms684919%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms684919%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />