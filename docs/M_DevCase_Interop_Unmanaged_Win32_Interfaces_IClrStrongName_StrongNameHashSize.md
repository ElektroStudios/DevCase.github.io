# IClrStrongName.StrongNameHashSize Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameHashSize(
	int hashAlg,
	ref int refSize
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameHashSize ( 
	hashAlg As Integer,
	ByRef refSize As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim hashAlg As Integer
Dim refSize As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameHashSize(hashAlg, 
	refSize)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameHashSize(
	[InAttribute] int hashAlg, 
	int% refSize
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameHashSize : 
        hashAlg : int * 
        refSize : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hashAlg</dt><dd>Type: System.Int32<br />\[Missing <param name="hashAlg"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameHashSize(System.Int32,System.Int32@)"\]</dd><dt>refSize</dt><dd>Type: System.Int32<br />\[Missing <param name="refSize"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameHashSize(System.Int32,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameHashSize(System.Int32,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />