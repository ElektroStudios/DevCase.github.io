# NativeMethods.LoadCursorFromFile Method 
 

Creates a cursor based on data contained in a file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr LoadCursorFromFile(
	string lpFileName
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function LoadCursorFromFile ( 
	lpFileName As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim lpFileName As String
Dim returnValue As IntPtr

returnValue = NativeMethods.LoadCursorFromFile(lpFileName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr LoadCursorFromFile(
	String^ lpFileName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member LoadCursorFromFile : 
        lpFileName : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>lpFileName</dt><dd>Type: System.String<br />The source of the file data to be used to create the cursor. 

 The data in the file must be in either .CUR or .ANI format.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is an IntPtr handle to the new cursor. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648392%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648392%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />