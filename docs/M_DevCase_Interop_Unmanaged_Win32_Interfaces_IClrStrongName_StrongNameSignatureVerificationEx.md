# IClrStrongName.StrongNameSignatureVerificationEx Method 
 

Gets a value that indicates whether the assembly manifest at the supplied path contains a strong name signature.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameSignatureVerificationEx(
	string filePath,
	bool forceVerification,
	ref bool refWasVerified
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameSignatureVerificationEx ( 
	filePath As String,
	forceVerification As Boolean,
	ByRef refWasVerified As Boolean
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim filePath As String
Dim forceVerification As Boolean
Dim refWasVerified As Boolean
Dim returnValue As HResult

returnValue = instance.StrongNameSignatureVerificationEx(filePath, 
	forceVerification, refWasVerified)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameSignatureVerificationEx(
	[InAttribute] String^ filePath, 
	[InAttribute] bool forceVerification, 
	bool% refWasVerified
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameSignatureVerificationEx : 
        filePath : string * 
        forceVerification : bool * 
        refWasVerified : bool byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The path to the portable executable (.exe or .dll) file for the assembly to be verified.</dd><dt>forceVerification</dt><dd>Type: System.Boolean<br />True to perform verification, even if it is necessary to override registry settings; otherwise, False.</dd><dt>refWasVerified</dt><dd>Type: System.Boolean<br />true if the strong name signature was verified; otherwise, false. 

 refWasVerified is also set to False if the verification was successful due to registry settings.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />