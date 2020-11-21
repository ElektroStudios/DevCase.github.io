# NativeMethods.FindExecutable Method 
 

Retrieves the name of and handle to the executable (.exe) file associated with a specific document file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static IntPtr FindExecutable(
	string file,
	string directory,
	StringBuilder result
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function FindExecutable ( 
	file As String,
	directory As String,
	result As StringBuilder
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim directory As String
Dim result As StringBuilder
Dim returnValue As IntPtr

returnValue = NativeMethods.FindExecutable(file, 
	directory, result)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static IntPtr FindExecutable(
	String^ file, 
	String^ directory, 
	StringBuilder^ result
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member FindExecutable : 
        file : string * 
        directory : string * 
        result : StringBuilder -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />A null-terminated string that specifies a file name. This file should be a document.</dd><dt>directory</dt><dd>Type: System.String<br />A null-terminated string that specifies the default directory. This value can be a null reference (`Nothing` in Visual Basic).</dd><dt>result</dt><dd>Type: System.Text.StringBuilder<br />The address of a buffer that receives the file name of the associated executable file. 

 This file name is a null-terminated string that specifies the executable file started when an "open" by association is run on the file specified in the lpFile parameter. 

 Put simply, this is the application that is launched when the document file is directly double-clicked or when Open is chosen from the file's shortcut menu. 

 This parameter must contain a valid non-null value and is assumed to be of length MAX_PATH. 

 Responsibility for validating the value is left to the programmer.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns a value greater than 32 if successful, or a value less than or equal to 32 representing an error.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-findexecutablea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-findexecutablea</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />