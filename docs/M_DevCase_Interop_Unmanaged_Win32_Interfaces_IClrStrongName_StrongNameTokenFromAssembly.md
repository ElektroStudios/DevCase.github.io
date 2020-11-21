# IClrStrongName.StrongNameTokenFromAssembly Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameTokenFromAssembly(
	string filePath,
	ref IntPtr refPpbStrongNameToken,
	ref int refPcbStrongNameToken
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameTokenFromAssembly ( 
	filePath As String,
	ByRef refPpbStrongNameToken As IntPtr,
	ByRef refPcbStrongNameToken As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim filePath As String
Dim refPpbStrongNameToken As IntPtr
Dim refPcbStrongNameToken As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameTokenFromAssembly(filePath, 
	refPpbStrongNameToken, refPcbStrongNameToken)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameTokenFromAssembly(
	[InAttribute] String^ filePath, 
	IntPtr% refPpbStrongNameToken, 
	int% refPcbStrongNameToken
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameTokenFromAssembly : 
        filePath : string * 
        refPpbStrongNameToken : IntPtr byref * 
        refPcbStrongNameToken : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />\[Missing <param name="filePath"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssembly(System.String,System.IntPtr@,System.Int32@)"\]</dd><dt>refPpbStrongNameToken</dt><dd>Type: System.IntPtr<br />\[Missing <param name="refPpbStrongNameToken"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssembly(System.String,System.IntPtr@,System.Int32@)"\]</dd><dt>refPcbStrongNameToken</dt><dd>Type: System.Int32<br />\[Missing <param name="refPcbStrongNameToken"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssembly(System.String,System.IntPtr@,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameTokenFromAssembly(System.String,System.IntPtr@,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />