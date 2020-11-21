# IClrStrongName.StrongNameKeyGenEx Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameKeyGenEx(
	string keyContainer,
	int flags,
	int keySize,
	ref IntPtr refPpbKeyBlob,
	ref int refPcbKeyBlob
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameKeyGenEx ( 
	keyContainer As String,
	flags As Integer,
	keySize As Integer,
	ByRef refPpbKeyBlob As IntPtr,
	ByRef refPcbKeyBlob As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim keyContainer As String
Dim flags As Integer
Dim keySize As Integer
Dim refPpbKeyBlob As IntPtr
Dim refPcbKeyBlob As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameKeyGenEx(keyContainer, 
	flags, keySize, refPpbKeyBlob, refPcbKeyBlob)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameKeyGenEx(
	[InAttribute] String^ keyContainer, 
	[InAttribute] int flags, 
	[InAttribute] int keySize, 
	IntPtr% refPpbKeyBlob, 
	int% refPcbKeyBlob
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameKeyGenEx : 
        keyContainer : string * 
        flags : int * 
        keySize : int * 
        refPpbKeyBlob : IntPtr byref * 
        refPcbKeyBlob : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>keyContainer</dt><dd>Type: System.String<br />\[Missing <param name="keyContainer"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyGenEx(System.String,System.Int32,System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>flags</dt><dd>Type: System.Int32<br />\[Missing <param name="flags"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyGenEx(System.String,System.Int32,System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>keySize</dt><dd>Type: System.Int32<br />\[Missing <param name="keySize"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyGenEx(System.String,System.Int32,System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>refPpbKeyBlob</dt><dd>Type: System.IntPtr<br />\[Missing <param name="refPpbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyGenEx(System.String,System.Int32,System.Int32,System.IntPtr@,System.Int32@)"\]</dd><dt>refPcbKeyBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="refPcbKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyGenEx(System.String,System.Int32,System.Int32,System.IntPtr@,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyGenEx(System.String,System.Int32,System.Int32,System.IntPtr@,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />