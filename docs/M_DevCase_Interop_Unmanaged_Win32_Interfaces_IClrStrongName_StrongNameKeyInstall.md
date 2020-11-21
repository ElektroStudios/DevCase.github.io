# IClrStrongName.StrongNameKeyInstall Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameKeyInstall(
	string keyContainer,
	byte[] pbKeyBlob,
	int cbKeyBlob
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameKeyInstall ( 
	keyContainer As String,
	pbKeyBlob As Byte(),
	cbKeyBlob As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim keyContainer As String
Dim pbKeyBlob As Byte()
Dim cbKeyBlob As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameKeyInstall(keyContainer, 
	pbKeyBlob, cbKeyBlob)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameKeyInstall(
	[InAttribute] String^ keyContainer, 
	[InAttribute] array<unsigned char>^ pbKeyBlob, 
	[InAttribute] int cbKeyBlob
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameKeyInstall : 
        keyContainer : string * 
        pbKeyBlob : byte[] * 
        cbKeyBlob : int -> HResult 

```


#### Parameters
&nbsp;<dl><dt>keyContainer</dt><dd>Type: System.String<br />\[Missing <param name="keyContainer"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyInstall(System.String,System.Byte[],System.Int32)"\]</dd><dt>pbKeyBlob</dt><dd>Type: System.Byte[]<br />\[Missing <param name="pbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyInstall(System.String,System.Byte[],System.Int32)"\]</dd><dt>cbKeyBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="cbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyInstall(System.String,System.Byte[],System.Int32)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyInstall(System.String,System.Byte[],System.Int32)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />