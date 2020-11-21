# IClrStrongName.StrongNameGetBlobFromImage Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameGetBlobFromImage(
	IntPtr base,
	int length,
	byte[] blob,
	out int refBlob
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameGetBlobFromImage ( 
	base As IntPtr,
	length As Integer,
	<OutAttribute> blob As Byte(),
	<OutAttribute> ByRef refBlob As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim base As IntPtr
Dim length As Integer
Dim blob As Byte()
Dim refBlob As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameGetBlobFromImage(base, 
	length, blob, refBlob)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameGetBlobFromImage(
	[InAttribute] IntPtr base, 
	[InAttribute] int length, 
	[OutAttribute] array<unsigned char>^ blob, 
	[InAttribute] [OutAttribute] int% refBlob
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameGetBlobFromImage : 
        base : IntPtr * 
        length : int * 
        blob : byte[] byref * 
        refBlob : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>base</dt><dd>Type: System.IntPtr<br />\[Missing <param name="base"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlobFromImage(System.IntPtr,System.Int32,System.Byte[],System.Int32@)"\]</dd><dt>length</dt><dd>Type: System.Int32<br />\[Missing <param name="length"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlobFromImage(System.IntPtr,System.Int32,System.Byte[],System.Int32@)"\]</dd><dt>blob</dt><dd>Type: System.Byte[]<br />\[Missing <param name="blob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlobFromImage(System.IntPtr,System.Int32,System.Byte[],System.Int32@)"\]</dd><dt>refBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="refBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlobFromImage(System.IntPtr,System.Int32,System.Byte[],System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameGetBlobFromImage(System.IntPtr,System.Int32,System.Byte[],System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />