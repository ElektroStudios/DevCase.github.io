# IClrStrongName.StrongNameGetBlob Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameGetBlob(
	string filePath,
	byte[] blob,
	out int refBlob
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameGetBlob ( 
	filePath As String,
	<OutAttribute> blob As Byte(),
	<OutAttribute> ByRef refBlob As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim filePath As String
Dim blob As Byte()
Dim refBlob As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameGetBlob(filePath, 
	blob, refBlob)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameGetBlob(
	[InAttribute] String^ filePath, 
	[OutAttribute] array<unsigned char>^ blob, 
	[InAttribute] [OutAttribute] int% refBlob
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameGetBlob : 
        filePath : string * 
        blob : byte[] byref * 
        refBlob : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />\[Missing <param name="filePath"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlob(System.String,System.Byte[],System.Int32@)"\]</dd><dt>blob</dt><dd>Type: System.Byte[]<br />\[Missing <param name="blob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlob(System.String,System.Byte[],System.Int32@)"\]</dd><dt>refBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="refBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlob(System.String,System.Byte[],System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlob(System.String,System.Byte[],System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />