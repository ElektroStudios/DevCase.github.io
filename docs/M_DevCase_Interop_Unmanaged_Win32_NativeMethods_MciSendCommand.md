# NativeMethods.MciSendCommand Method (Int32, MCICommands, IntPtr, MciOpenParms)
 

Sends a command message to the specified MCI device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinMM.dll", EntryPoint = "mciSendCommand", SetLastError = true)]
public static int MciSendCommand(
	int device,
	MCICommands command,
	IntPtr flags,
	ref MciOpenParms refParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinMM.dll", EntryPoint := "mciSendCommand", SetLastError := true>]
Public Shared Function MciSendCommand ( 
	device As Integer,
	command As MCICommands,
	flags As IntPtr,
	ByRef refParam As MciOpenParms
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim device As Integer
Dim command As MCICommands
Dim flags As IntPtr
Dim refParam As MciOpenParms
Dim returnValue As Integer

returnValue = NativeMethods.MciSendCommand(device, 
	command, flags, refParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinMM.dll", EntryPoint = L"mciSendCommand", SetLastError = true)]
static int MciSendCommand(
	int device, 
	MCICommands command, 
	IntPtr flags, 
	MciOpenParms% refParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinMM.dll", EntryPoint = "mciSendCommand", SetLastError = true)>]
static member MciSendCommand : 
        device : int * 
        command : MCICommands * 
        flags : IntPtr * 
        refParam : MciOpenParms byref -> int 

```


#### Parameters
&nbsp;<dl><dt>device</dt><dd>Type: System.Int32<br />Device identifier of the MCI device that is to receive the command message. 

 This parameter is not used with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MCICommands">Open</a> command message.</dd><dt>command</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MCICommands">DevCase.Interop.Unmanaged.Win32.Enums.MCICommands</a><br />The command message to send.</dd><dt>flags</dt><dd>Type: System.IntPtr<br />Flags for the command message.</dd><dt>refParam</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MciOpenParms">DevCase.Interop.Unmanaged.Win32.Structures.MciOpenParms</a><br />Pointer to a structure that contains parameters for the command message.</dd></dl>

#### Return Value
Type: Int32<br />Returns zero if successful or an error otherwise. The low-order word of the returned DWORD value contains the error return value. 

 If the error is device-specific, the high-order word of the return value is the driver identifier; otherwise, the high-order word is zero. For a list of possible return values, see MCIERR Return Values. 

 To retrieve a text description of return values, pass the return value to the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MciGetErrorString">MciGetErrorString(Int32, StringBuilder, Int32)</a> function

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd757160(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd757160(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_MciSendCommand">MciSendCommand Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />