# IClrStrongName.StrongNameSignatureGeneration Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameSignatureGeneration(
	string filePath,
	string keyContainer,
	byte[] pbKeyBlob,
	int cbKeyBlob,
	IntPtr signatureBlob,
	ref int refSignatureBlob
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameSignatureGeneration ( 
	filePath As String,
	keyContainer As String,
	pbKeyBlob As Byte(),
	cbKeyBlob As Integer,
	<OutAttribute> signatureBlob As IntPtr,
	ByRef refSignatureBlob As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim filePath As String
Dim keyContainer As String
Dim pbKeyBlob As Byte()
Dim cbKeyBlob As Integer
Dim signatureBlob As IntPtr
Dim refSignatureBlob As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameSignatureGeneration(filePath, 
	keyContainer, pbKeyBlob, cbKeyBlob, 
	signatureBlob, refSignatureBlob)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameSignatureGeneration(
	[InAttribute] String^ filePath, 
	[InAttribute] String^ keyContainer, 
	[InAttribute] array<unsigned char>^ pbKeyBlob, 
	[InAttribute] int cbKeyBlob, 
	[InAttribute] [OutAttribute] IntPtr signatureBlob, 
	int% refSignatureBlob
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameSignatureGeneration : 
        filePath : string * 
        keyContainer : string * 
        pbKeyBlob : byte[] * 
        cbKeyBlob : int * 
        signatureBlob : IntPtr byref * 
        refSignatureBlob : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />\[Missing <param name="filePath"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureGeneration(System.String,System.String,System.Byte[],System.Int32,System.IntPtr,System.Int32@)"\]</dd><dt>keyContainer</dt><dd>Type: System.String<br />\[Missing <param name="keyContainer"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureGeneration(System.String,System.String,System.Byte[],System.Int32,System.IntPtr,System.Int32@)"\]</dd><dt>pbKeyBlob</dt><dd>Type: System.Byte[]<br />\[Missing <param name="pbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureGeneration(System.String,System.String,System.Byte[],System.Int32,System.IntPtr,System.Int32@)"\]</dd><dt>cbKeyBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="cbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureGeneration(System.String,System.String,System.Byte[],System.Int32,System.IntPtr,System.Int32@)"\]</dd><dt>signatureBlob</dt><dd>Type: System.IntPtr<br />\[Missing <param name="signatureBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureGeneration(System.String,System.String,System.Byte[],System.Int32,System.IntPtr,System.Int32@)"\]</dd><dt>refSignatureBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="refSignatureBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureGeneration(System.String,System.String,System.Byte[],System.Int32,System.IntPtr,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureGeneration(System.String,System.String,System.Byte[],System.Int32,System.IntPtr,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />