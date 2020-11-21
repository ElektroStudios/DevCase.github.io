# IClrStrongName.StrongNameFreeBuffer Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult StrongNameFreeBuffer(
	IntPtr memory
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function StrongNameFreeBuffer ( 
	memory As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
Dim memory As IntPtr
Dim returnValue As HResult

returnValue = instance.StrongNameFreeBuffer(memory)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult StrongNameFreeBuffer(
	[InAttribute] IntPtr memory
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract StrongNameFreeBuffer : 
        memory : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>memory</dt><dd>Type: System.IntPtr<br />\[Missing <param name="memory"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameFreeBuffer(System.IntPtr)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IClrStrongName.StrongNameFreeBuffer(System.IntPtr)"\]

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName">IClrStrongName Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />