# IClrStrongName.StrongNameTokenFromAssemblyEx Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameTokenFromAssemblyEx(
	string filePath,
	ref IntPtr refPpbStrongNameToken,
	ref int refPcbStrongNameToken,
	ref IntPtr refPpbPublicKeyBlob,
	ref int refPcbPublicKeyBlob
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameTokenFromAssemblyEx ( 
	filePath As String,
	ByRef refPpbStrongNameToken As IntPtr,
	ByRef refPcbStrongNameToken As Integer,
	ByRef refPpbPublicKeyBlob As IntPtr,
	ByRef refPcbPublicKeyBlob As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim filePath As String
Dim refPpbStrongNameToken As IntPtr
Dim refPcbStrongNameToken As Integer
Dim refPpbPublicKeyBlob As IntPtr
Dim refPcbPublicKeyBlob As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameTokenFromAssemblyEx(filePath, 
	refPpbStrongNameToken, refPcbStrongNameToken, 
	refPpbPublicKeyBlob, refPcbPublicKeyBlob)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameTokenFromAssemblyEx(
	[InAttribute] String^ filePath, 
	IntPtr% refPpbStrongNameToken, 
	int% refPcbStrongNameToken, 
	IntPtr% refPpbPublicKeyBlob, 
	int% refPcbPublicKeyBlob
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameTokenFromAssemblyEx : 
        filePath : string * 
        refPpbStrongNameToken : IntPtr byref * 
        refPcbStrongNameToken : int byref * 
        refPpbPublicKeyBlob : IntPtr byref * 
        refPcbPublicKeyBlob : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />\[Missing <param name="filePath"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssemblyEx(System.String,System.IntPtr@,System.Int32@,System.IntPtr@,System.Int32@)"\]</dd><dt>refPpbStrongNameToken</dt><dd>Type: System.IntPtr<br />\[Missing <param name="refPpbStrongNameToken"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssemblyEx(System.String,System.IntPtr@,System.Int32@,System.IntPtr@,System.Int32@)"\]</dd><dt>refPcbStrongNameToken</dt><dd>Type: System.Int32<br />\[Missing <param name="refPcbStrongNameToken"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssemblyEx(System.String,System.IntPtr@,System.Int32@,System.IntPtr@,System.Int32@)"\]</dd><dt>refPpbPublicKeyBlob</dt><dd>Type: System.IntPtr<br />\[Missing <param name="refPpbPublicKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssemblyEx(System.String,System.IntPtr@,System.Int32@,System.IntPtr@,System.Int32@)"\]</dd><dt>refPcbPublicKeyBlob</dt><dd>Type: System.Int32<br />\[Missing <param name="refPcbPublicKeyBlob"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssemblyEx(System.String,System.IntPtr@,System.Int32@,System.IntPtr@,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssemblyEx(System.String,System.IntPtr@,System.Int32@,System.IntPtr@,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />