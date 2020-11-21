# IClrStrongName.GetHashFromFile Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetHashFromFile(
	string filePath,
	out int refHashAlg,
	byte[] pbHash,
	int cchHash,
	ref int refHash
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetHashFromFile ( 
	filePath As String,
	<OutAttribute> ByRef refHashAlg As Integer,
	<OutAttribute> pbHash As Byte(),
	cchHash As Integer,
	ByRef refHash As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim filePath As String
Dim refHashAlg As Integer
Dim pbHash As Byte()
Dim cchHash As Integer
Dim refHash As Integer
Dim returnValue As HResult

returnValue = instance.GetHashFromFile(filePath, 
	refHashAlg, pbHash, cchHash, refHash)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetHashFromFile(
	[InAttribute] String^ filePath, 
	[InAttribute] [OutAttribute] int% refHashAlg, 
	[OutAttribute] array<unsigned char>^ pbHash, 
	[InAttribute] int cchHash, 
	int% refHash
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetHashFromFile : 
        filePath : string * 
        refHashAlg : int byref * 
        pbHash : byte[] byref * 
        cchHash : int * 
        refHash : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />\[Missing <param name="filePath"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromFile(System.String,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>refHashAlg</dt><dd>Type: System.Int32<br />\[Missing <param name="refHashAlg"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromFile(System.String,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>pbHash</dt><dd>Type: System.Byte[]<br />\[Missing <param name="pbHash"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromFile(System.String,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>cchHash</dt><dd>Type: System.Int32<br />\[Missing <param name="cchHash"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromFile(System.String,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd><dt>refHash</dt><dd>Type: System.Int32<br />\[Missing <param name="refHash"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromFile(System.String,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.GetHashFromFile(System.String,System.Int32@,System.Byte[],System.Int32,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />