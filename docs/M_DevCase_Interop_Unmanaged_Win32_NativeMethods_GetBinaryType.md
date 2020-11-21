# NativeMethods.GetBinaryType Method 
 

Determines whether a file is an executable (.exe) file, and if so, which subsystem runs the executable file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool GetBinaryType(
	string filePath,
	out BinaryType refBinaryType
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetBinaryType ( 
	filePath As String,
	<OutAttribute> ByRef refBinaryType As BinaryType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filePath As String
Dim refBinaryType As BinaryType
Dim returnValue As Boolean

returnValue = NativeMethods.GetBinaryType(filePath, 
	refBinaryType)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool GetBinaryType(
	String^ filePath, 
	[OutAttribute] BinaryType% refBinaryType
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetBinaryType : 
        filePath : string * 
        refBinaryType : BinaryType byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The full path of the file whose executable type is to be determined. 

 In the ANSI version of this function, the name is limited to `MAX_PATH` characters. To extend this limit to 32,767 wide characters, call the Unicode version of the function and prepend "\?" to the path.</dd><dt>refBinaryType</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BinaryType">DevCase.Interop.Unmanaged.Win32.Enums.BinaryType</a><br />A variable to receive information about the executable type of the file specified by *filePath*.</dd></dl>

#### Return Value
Type: Boolean<br />If the file is executable, the return value is `true` (`True` in Visual Basic). 

 The function sets the variable pointed to by *refBinaryType* to indicate the file's executable type. 

 If the file is not executable, or if the function fails, the return value is `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />