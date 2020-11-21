# IClrStrongName.StrongNameSignatureVerification Method 
 

Gets a value that indicates whether the assembly manifest at the supplied path contains a strong name signature, which is verified according to the specified flags.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameSignatureVerification(
	string filePath,
	int inFlags,
	ref int refOutFlags
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameSignatureVerification ( 
	filePath As String,
	inFlags As Integer,
	ByRef refOutFlags As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim filePath As String
Dim inFlags As Integer
Dim refOutFlags As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameSignatureVerification(filePath, 
	inFlags, refOutFlags)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameSignatureVerification(
	[InAttribute] String^ filePath, 
	[InAttribute] int inFlags, 
	int% refOutFlags
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameSignatureVerification : 
        filePath : string * 
        inFlags : int * 
        refOutFlags : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />The path to the portable executable (.exe or .dll) file for the assembly to be verified.</dd><dt>inFlags</dt><dd>Type: System.Int32<br />Flags to modify the verification behavior.</dd><dt>refOutFlags</dt><dd>Type: System.Int32<br />Flags indicating whether the strong name signature was verified.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />