# IShellFolder.CompareIDs Method 
 

Determines the relative order of two file objects or folders, given their item identifier lists.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult CompareIDs(
	IntPtr lParam,
	PIDL pidl1,
	PIDL pidl2
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function CompareIDs ( 
	lParam As IntPtr,
	pidl1 As PIDL,
	pidl2 As PIDL
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim lParam As IntPtr
Dim pidl1 As PIDL
Dim pidl2 As PIDL
Dim returnValue As HResult

returnValue = instance.CompareIDs(lParam, 
	pidl1, pidl2)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult CompareIDs(
	IntPtr lParam, 
	[InAttribute] PIDL^ pidl1, 
	[InAttribute] PIDL^ pidl2
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract CompareIDs : 
        lParam : IntPtr * 
        pidl1 : PIDL * 
        pidl2 : PIDL -> HResult 

```


#### Parameters
&nbsp;<dl><dt>lParam</dt><dd>Type: System.IntPtr<br />A value that specifies how the comparison should be performed. 

 The lower sixteen bits of *lParam* define the sorting rule. 

 Most applications set the sorting rule to the default value of zero, indicating that the two items should be compared by name. The system does not define any other sorting rules. 

 Some folder objects might allow calling applications to use the lower sixteen bits of *lParam* to specify folder-specific sorting rules. The rules and their associated *lParam* values are defined by the folder. 

 When the system folder view object calls CompareIDs(IntPtr, PIDL, PIDL), the lower sixteen bits of lParam are used to specify the column to be used for the comparison. 

 The upper sixteen bits of lParam are used for flags that modify the sorting rule. The system currently defines these modifier flags.</dd><dt>pidl1</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A pointer to the first item's ITEMIDLIST structure. It will be relative to the folder. 

 This ITEMIDLIST structure can contain more than one element; therefore, the entire structure must be compared, not just the first element.</dd><dt>pidl2</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />A pointer to the second item's ITEMIDLIST structure. It will be relative to the folder. 

 This ITEMIDLIST structure can contain more than one element; therefore, the entire structure must be compared, not just the first element.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this method is successful, the CODE field of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> contains one of the following values. 

 If this method is unsuccessful, it returns a COM error code.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />