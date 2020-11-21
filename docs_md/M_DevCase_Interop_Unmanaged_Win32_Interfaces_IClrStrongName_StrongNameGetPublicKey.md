# IClrStrongName.StrongNameGetPublicKey Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameGetPublicKey(
	string keyContainer,
	byte[] pbKeyBlob,
	int cbKeyBlob,
	ref IntPtr refPpbPublicKeyBlob,
	ref int refPcbPublicKeyBlob
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameGetPublicKey ( 
	keyContainer As String,
	pbKeyBlob As Byte(),
	cbKeyBlob As Integer,
	ByRef refPpbPublicKeyBlob As IntPtr,
	ByRef refPcbPublicKeyBlob As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim keyContainer As String
Dim pbKeyBlob As Byte()
Dim cbKeyBlob As Integer
Dim refPpbPublicKeyBlob As IntPtr
Dim refPcbPublicKeyBlob As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameGetPublicKey(keyContainer, 
	pbKeyBlob, cbKeyBlob, refPpbPublicKeyBlob, 
	refPcbPublicKeyBlob)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameGetPublicKey(
	[InAttribute] String^ keyContainer, 
	[InAttribute] array<unsigned char>^ pbKeyBlob, 
	[InAttribute] int cbKeyBlob, 
	IntPtr% refPpbPublicKeyBlob, 
	int% refPcbPublicKeyBlob
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameGetPublicKey : 
        keyContainer : string * 
        pbKeyBlob : byte[] * 
        cbKeyBlob : int * 
        refPpbPublicKeyBlob : IntPtr byref * 
        refPcbPublicKeyBlob : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>keyContainer</dt><dd>Type: System.String<br />\[Missing <param name="keyContainer"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetPublicKey(System.String,System.Byte[],System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>pbKeyBlob</dt><dd>Type: System.Byte[]<br />\[Missing <param name="pbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetPublicKey(System.String,System.Byte[],System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>cbKeyBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="cbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetPublicKey(System.String,System.Byte[],System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>refPpbPublicKeyBlob</dt><dd>Type: System.IntPtr<br />\[Missing <param name="refPpbPublicKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetPublicKey(System.String,System.Byte[],System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>refPcbPublicKeyBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="refPcbPublicKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetPublicKey(System.String,System.Byte[],System.Int32,System.IntPtr@,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetPublicKey(System.String,System.Byte[],System.Int32,System.IntPtr@,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />