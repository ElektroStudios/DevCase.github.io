# IClrStrongName.StrongNameSignatureVerificationFromImage Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameSignatureVerificationFromImage(
	IntPtr pbBase,
	int length,
	int inFlags,
	ref int refOutFlags
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameSignatureVerificationFromImage ( 
	pbBase As IntPtr,
	length As Integer,
	inFlags As Integer,
	ByRef refOutFlags As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim pbBase As IntPtr
Dim length As Integer
Dim inFlags As Integer
Dim refOutFlags As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameSignatureVerificationFromImage(pbBase, 
	length, inFlags, refOutFlags)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameSignatureVerificationFromImage(
	[InAttribute] IntPtr pbBase, 
	[InAttribute] int length, 
	[InAttribute] int inFlags, 
	int% refOutFlags
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameSignatureVerificationFromImage : 
        pbBase : IntPtr * 
        length : int * 
        inFlags : int * 
        refOutFlags : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>pbBase</dt><dd>Type: System.IntPtr<br />\[Missing <param name="pbBase"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureVerificationFromImage(System.IntPtr,System.Int32,System.Int32,System.Int32@)"\]</dd><dt>length</dt><dd>Type: System.Int32<br />\[Missing <param name="length"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureVerificationFromImage(System.IntPtr,System.Int32,System.Int32,System.Int32@)"\]</dd><dt>inFlags</dt><dd>Type: System.Int32<br />\[Missing <param name="inFlags"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureVerificationFromImage(System.IntPtr,System.Int32,System.Int32,System.Int32@)"\]</dd><dt>refOutFlags</dt><dd>Type: System.Int32<br />\[Missing <param name="refOutFlags"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureVerificationFromImage(System.IntPtr,System.Int32,System.Int32,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameSignatureVerificationFromImage(System.IntPtr,System.Int32,System.Int32,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />