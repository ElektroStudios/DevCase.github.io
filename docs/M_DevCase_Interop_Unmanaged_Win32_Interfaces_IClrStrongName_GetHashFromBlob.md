# IClrStrongName.GetHashFromBlob Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetHashFromBlob(
	IntPtr pbBlob,
	int blob,
	out int refHashAlg,
	byte[] pbHash,
	int cchHash,
	ref int refHash
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetHashFromBlob ( 
	pbBlob As IntPtr,
	blob As Integer,
	<OutAttribute> ByRef refHashAlg As Integer,
	<OutAttribute> pbHash As Byte(),
	cchHash As Integer,
	ByRef refHash As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim pbBlob As IntPtr
Dim blob As Integer
Dim refHashAlg As Integer
Dim pbHash As Byte()
Dim cchHash As Integer
Dim refHash As Integer
Dim returnValue As HResult

returnValue = instance.GetHashFromBlob(pbBlob, 
	blob, refHashAlg, pbHash, cchHash, 
	refHash)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetHashFromBlob(
	[InAttribute] IntPtr pbBlob, 
	[InAttribute] int blob, 
	[InAttribute] [OutAttribute] int% refHashAlg, 
	[OutAttribute] array<unsigned char>^ pbHash, 
	[InAttribute] int cchHash, 
	int% refHash
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetHashFromBlob : 
        pbBlob : IntPtr * 
        blob : int * 
        refHashAlg : int byref * 
        pbHash : byte[] byref * 
        cchHash : int * 
        refHash : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pbBlob</dt><dd>Type: System.IntPtr<br />\[Missing <param name="pbBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromBlob(System.IntPtr,System.Int32,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>blob</dt><dd>Type: System.Int32<br />\[Missing <param name="blob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromBlob(System.IntPtr,System.Int32,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>refHashAlg</dt><dd>Type: System.Int32<br />\[Missing <param name="refHashAlg"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromBlob(System.IntPtr,System.Int32,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>pbHash</dt><dd>Type: System.Byte[]<br />\[Missing <param name="pbHash"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromBlob(System.IntPtr,System.Int32,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>cchHash</dt><dd>Type: System.Int32<br />\[Missing <param name="cchHash"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromBlob(System.IntPtr,System.Int32,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>refHash</dt><dd>Type: System.Int32<br />\[Missing <param name="refHash"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromBlob(System.IntPtr,System.Int32,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromBlob(System.IntPtr,System.Int32,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />