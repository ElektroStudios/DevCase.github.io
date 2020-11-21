# NativeMethods.MciSendString Method 
 

Sends a command string to an MCI device. The device that the command is sent to is specified in the command string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinMM.dll", EntryPoint = "mciSendString", CharSet = CharSet.Auto, 
	BestFitMapping = false, ThrowOnUnmappableChar = true, SetLastError = true)]
public static int MciSendString(
	string command,
	StringBuilder buffer,
	int bufferSize,
	IntPtr hWndCallback
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinMM.dll", EntryPoint := "mciSendString", CharSet := CharSet.Auto, 
	BestFitMapping := false, ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function MciSendString ( 
	command As String,
	buffer As StringBuilder,
	bufferSize As Integer,
	hWndCallback As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim command As String
Dim buffer As StringBuilder
Dim bufferSize As Integer
Dim hWndCallback As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.MciSendString(command, 
	buffer, bufferSize, hWndCallback)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinMM.dll", EntryPoint = L"mciSendString", CharSet = CharSet::Auto, 
	BestFitMapping = false, ThrowOnUnmappableChar = true, SetLastError = true)]
static int MciSendString(
	String^ command, 
	StringBuilder^ buffer, 
	int bufferSize, 
	IntPtr hWndCallback
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinMM.dll", EntryPoint = "mciSendString", CharSet = CharSet.Auto, 
	BestFitMapping = false, ThrowOnUnmappableChar = true, SetLastError = true)>]
static member MciSendString : 
        command : string * 
        buffer : StringBuilder * 
        bufferSize : int * 
        hWndCallback : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>command</dt><dd>Type: System.String<br />Pointer to a null-terminated string that specifies an MCI command string. For a list, see <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd743572(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd743572(v=vs.85).aspx</a>.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />StringBuilder that receives return information. If no return information is needed, this parameter can be a null reference (`Nothing` in Visual Basic).</dd><dt>bufferSize</dt><dd>Type: System.Int32<br />Size, in characters, of the return buffer specified by the *buffer* parameter.</dd><dt>hWndCallback</dt><dd>Type: System.IntPtr<br />A IntPtr to a callback window if the "notify" flag was specified in the command string.</dd></dl>

#### Return Value
Type: Int32<br />Returns zero if successful or an error otherwise. The low-order word of the returned DWORD value contains the error return value. 

 If the error is device-specific, the high-order word of the return value is the driver identifier; otherwise, the high-order word is zero. For a list of possible error values, see MCIERR Return Values. 

 To retrieve a text description of return values, pass the return value to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MciGetErrorString">MciGetErrorString(Int32, StringBuilder, Int32)</a> function

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd757161%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd757161%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />