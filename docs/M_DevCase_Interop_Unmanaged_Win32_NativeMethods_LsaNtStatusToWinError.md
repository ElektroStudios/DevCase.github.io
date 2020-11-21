# NativeMethods.LsaNtStatusToWinError Method 
 

Converts an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> value to a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll")]
public static Win32ErrorCode LsaNtStatusToWinError(
	int value
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll">]
Public Shared Function LsaNtStatusToWinError ( 
	value As Integer
) As Win32ErrorCode
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer
Dim returnValue As Win32ErrorCode

returnValue = NativeMethods.LsaNtStatusToWinError(value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll")]
static Win32ErrorCode LsaNtStatusToWinError(
	int value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll")>]
static member LsaNtStatusToWinError : 
        value : int -> Win32ErrorCode 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.Int32<br />The <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> value.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a><br />The return value is the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value that corresponds to the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NTStatus">NTStatus</a> value. 

 If there is no corresponding <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">Win32ErrorCode</a> value, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_MR_MID_NOT_FOUND</a>.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms721800(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms721800(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />