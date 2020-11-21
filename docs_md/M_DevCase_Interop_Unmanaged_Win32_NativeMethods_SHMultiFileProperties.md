# NativeMethods.SHMultiFileProperties Method 
 

Displays a merged property sheet for a set of files. 

 Property values common to all the files are shown while those that differ display the string (multiple values).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true)]
public static HResult SHMultiFileProperties(
	IDataObject dataObj,
	uint reserved = 0
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true>]
Public Shared Function SHMultiFileProperties ( 
	dataObj As IDataObject,
	Optional reserved As UInteger = 0
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim dataObj As IDataObject
Dim reserved As UInteger
Dim returnValue As HResult

returnValue = NativeMethods.SHMultiFileProperties(dataObj, 
	reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true)]
static HResult SHMultiFileProperties(
	IDataObject^ dataObj, 
	unsigned int reserved = 0
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true)>]
static member SHMultiFileProperties : 
        dataObj : IDataObject * 
        ?reserved : uint32 
(* Defaults:
        let _reserved = defaultArg reserved 0
*)
-> HResult 

```


#### Parameters
&nbsp;<dl><dt>dataObj</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IDataObject<br />A pointer to a data object that supplies the PIDLs of all of the files for which to display the merged property sheet. 

 The data object must use the CFSTR_SHELLIDLIST clipboard format. 

 The parent folder's implementation of IShellFolder.GetDisplayNameOf must return a fully qualified file system path for each item in response to the SHGDN_FORPARSING flag.</dd><dt>reserved (Optional)</dt><dd>Type: System.UInt32<br />Reserved. Must be set to 0.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj/nf-shlobj-shmultifileproperties" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj/nf-shlobj-shmultifileproperties</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />