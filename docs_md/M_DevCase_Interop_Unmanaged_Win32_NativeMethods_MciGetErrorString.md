# NativeMethods.MciGetErrorString Method 
 

Retrieves a string that describes the specified MCI error code.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinMM.dll", EntryPoint = "mciGetErrorString", CharSet = CharSet.Auto, 
	BestFitMapping = false, ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool MciGetErrorString(
	int error,
	StringBuilder buffer,
	int length
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinMM.dll", EntryPoint := "mciGetErrorString", CharSet := CharSet.Auto, 
	BestFitMapping := false, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function MciGetErrorString ( 
	error As Integer,
	buffer As StringBuilder,
	length As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim error As Integer
Dim buffer As StringBuilder
Dim length As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.MciGetErrorString(error, 
	buffer, length)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinMM.dll", EntryPoint = L"mciGetErrorString", 
	CharSet = CharSet::Auto, BestFitMapping = false, ThrowOnUnmappableChar = true, 
	SetLastError = true)]
static bool MciGetErrorString(
	int error, 
	StringBuilder^ buffer, 
	int length
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinMM.dll", EntryPoint = "mciGetErrorString", CharSet = CharSet.Auto, 
	BestFitMapping = false, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member MciGetErrorString : 
        error : int * 
        buffer : StringBuilder * 
        length : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>error</dt><dd>Type: System.Int32<br />\[Missing <param name="error"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.MciGetErrorString(System.Int32,System.Text.StringBuilder,System.Int32)"\]</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />T Pointer to a buffer that receives a null-terminated string describing the specified error.</dd><dt>length</dt><dd>Type: System.Int32<br />T Length of the buffer, in characters, pointed to by the *buffer* parameter.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) if the error code is not known.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd757158(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd757158(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />