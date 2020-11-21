# IMMDevice.OpenPropertyStore Method 
 

Retrieves an interface to the device's property store.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult OpenPropertyStore(
	EStgmAccess stgmAccess,
	ref IPropertyStore refPropertyStore
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function OpenPropertyStore ( 
	stgmAccess As EStgmAccess,
	ByRef refPropertyStore As IPropertyStore
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDevice
Dim stgmAccess As EStgmAccess
Dim refPropertyStore As IPropertyStore
Dim returnValue As HResult

returnValue = instance.OpenPropertyStore(stgmAccess, 
	refPropertyStore)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult OpenPropertyStore(
	EStgmAccess stgmAccess, 
	IPropertyStore^% refPropertyStore
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract OpenPropertyStore : 
        stgmAccess : EStgmAccess * 
        refPropertyStore : IPropertyStore byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>stgmAccess</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EStgmAccess">DevCase.Interop.Unmanaged.Win32.Enums.EStgmAccess</a><br />The storage-access mode. This parameter specifies whether to open the property store in read mode, write mode, or read/write mode.</dd><dt>refPropertyStore</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore">DevCase.Interop.Unmanaged.Win32.Interfaces.IPropertyStore</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore">IPropertyStore</a> variable into which the method writes the address of the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore">IPropertyStore</a> interface of the device's property store. 

 Through this method, the caller obtains a counted reference to the interface. 

 The caller is responsible for releasing the interface, when it is no longer needed, by calling the interface's Release method. 

 If the OpenPropertyStore(EStgmAccess, IPropertyStore) call fails, *refPropertyStore* is a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />