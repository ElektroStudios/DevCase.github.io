# IMMDevice.GetId Method 
 

Retrieves an endpoint ID string that identifies the audio endpoint device

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetId(
	ref string refStrId
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetId ( 
	ByRef refStrId As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDevice
Dim refStrId As String
Dim returnValue As HResult

returnValue = instance.GetId(refStrId)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetId(
	String^% refStrId
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetId : 
        refStrId : string byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refStrId</dt><dd>Type: System.String<br />Pointer to a String variable into which the method writes the address of a null-terminated, wide-character string containing the endpoint device ID. 

 The method allocates the storage for the string. 

 The caller is responsible for freeing the storage, when it is no longer needed, by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CoTaskMemFree">CoTaskMemFree(IntPtr)</a> function. 

 If the GetId(String) call fails, *refStrId* is a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />