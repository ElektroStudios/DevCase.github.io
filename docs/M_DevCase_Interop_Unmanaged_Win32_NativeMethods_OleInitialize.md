# NativeMethods.OleInitialize Method 
 

Initializes the COM library on the current apartment, identifies the concurrency model as single-thread apartment (STA), and enables additional functionality. 

 Applications must initialize the COM library before they can call COM library functions other than CoGetMalloc and memory allocation functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll", ExactSpelling = true)]
public static HResult OleInitialize(
	[OptionalAttribute] IntPtr reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll", ExactSpelling := true>]
Public Shared Function OleInitialize ( 
	<OptionalAttribute> reserved As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim reserved As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.OleInitialize(reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll", ExactSpelling = true)]
static HResult OleInitialize(
	[OptionalAttribute] IntPtr reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll", ExactSpelling = true)>]
static member OleInitialize : 
        [<OptionalAttribute>] reserved : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />This parameter is reserved and must be Zero.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/ole2/nf-ole2-oleinitialize" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/ole2/nf-ole2-oleinitialize</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />