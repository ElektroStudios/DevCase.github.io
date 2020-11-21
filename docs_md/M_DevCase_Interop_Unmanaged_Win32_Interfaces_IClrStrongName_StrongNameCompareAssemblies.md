# IClrStrongName.StrongNameCompareAssemblies Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameCompareAssemblies(
	string assembly1,
	string assembly2,
	ref int refResult
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameCompareAssemblies ( 
	assembly1 As String,
	assembly2 As String,
	ByRef refResult As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim assembly1 As String
Dim assembly2 As String
Dim refResult As Integer
Dim returnValue As HResult

returnValue = instance.StrongNameCompareAssemblies(assembly1, 
	assembly2, refResult)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameCompareAssemblies(
	[InAttribute] String^ assembly1, 
	[InAttribute] String^ assembly2, 
	int% refResult
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameCompareAssemblies : 
        assembly1 : string * 
        assembly2 : string * 
        refResult : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>assembly1</dt><dd>Type: System.String<br />\[Missing <param name="assembly1"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameCompareAssemblies(System.String,System.String,System.Int32@)"\]</dd><dt>assembly2</dt><dd>Type: System.String<br />\[Missing <param name="assembly2"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameCompareAssemblies(System.String,System.String,System.Int32@)"\]</dd><dt>refResult</dt><dd>Type: System.Int32<br />\[Missing <param name="refResult"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameCompareAssemblies(System.String,System.String,System.Int32@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameCompareAssemblies(System.String,System.String,System.Int32@)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />