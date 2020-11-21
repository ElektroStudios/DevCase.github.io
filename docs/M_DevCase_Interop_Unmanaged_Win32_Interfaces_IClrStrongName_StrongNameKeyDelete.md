# IClrStrongName.StrongNameKeyDelete Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameKeyDelete(
	string keyContainer
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameKeyDelete ( 
	keyContainer As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim keyContainer As String
Dim returnValue As HResult

returnValue = instance.StrongNameKeyDelete(keyContainer)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameKeyDelete(
	[InAttribute] String^ keyContainer
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameKeyDelete : 
        keyContainer : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>keyContainer</dt><dd>Type: System.String<br />\[Missing <param name="keyContainer"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyDelete(System.String)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameKeyDelete(System.String)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />