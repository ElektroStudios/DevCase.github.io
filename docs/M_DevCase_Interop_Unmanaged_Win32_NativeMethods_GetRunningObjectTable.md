# NativeMethods.GetRunningObjectTable Method 
 

Returns a pointer to the IRunningObjectTable interface on the local running object table (ROT).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll")]
public static HResult GetRunningObjectTable(
	int reserved,
	ref IRunningObjectTable refRot
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll">]
Public Shared Function GetRunningObjectTable ( 
	reserved As Integer,
	ByRef refRot As IRunningObjectTable
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim reserved As Integer
Dim refRot As IRunningObjectTable
Dim returnValue As HResult

returnValue = NativeMethods.GetRunningObjectTable(reserved, 
	refRot)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll")]
static HResult GetRunningObjectTable(
	int reserved, 
	IRunningObjectTable^% refRot
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll")>]
static member GetRunningObjectTable : 
        reserved : int * 
        refRot : IRunningObjectTable byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>reserved</dt><dd>Type: System.Int32<br />This parameter is reserved and must be 0.</dd><dt>refRot</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IRunningObjectTable<br />The address of an IRunningObjectTable pointer variable that receives the interface pointer to the local ROT. 

 When the function is successful, the caller is responsible for calling Release on the interface pointer. 

 A value of a null reference (`Nothing` in Visual Basic) for the *refRot* value indicates that an error occurred.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms684004%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms684004%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />