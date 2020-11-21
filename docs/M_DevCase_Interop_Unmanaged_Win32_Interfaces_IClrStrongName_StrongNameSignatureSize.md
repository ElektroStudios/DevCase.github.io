# IClrStrongName.StrongNameSignatureSize Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameSignatureSize(
	byte[] pbPublicKeyBlob,
	int cbPublicKeyBlob,
	ref int refSize
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameSignatureSize ( 
	pbPublicKeyBlob As Byte(),
	cbPublicKeyBlob As Integer,
	ByRef refSize As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim pbPublicKeyBlob As Byte()
Dim cbPublicKeyBlob As Integer
Dim refSize As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameSignatureSize(pbPublicKeyBlob, 
	cbPublicKeyBlob, refSize)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameSignatureSize(
	[InAttribute] array<unsigned char>^ pbPublicKeyBlob, 
	[InAttribute] int cbPublicKeyBlob, 
	int% refSize
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameSignatureSize : 
        pbPublicKeyBlob : byte[] * 
        cbPublicKeyBlob : int * 
        refSize : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pbPublicKeyBlob</dt><dd>Type: System.Byte[]<br />\[Missing <param name="pbPublicKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureSize(System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>cbPublicKeyBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="cbPublicKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureSize(System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>refSize</dt><dd>Type: System.Int32<br />\[Missing <param name="refSize"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureSize(System.Byte[],System.Int32,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureSize(System.Byte[],System.Int32,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />