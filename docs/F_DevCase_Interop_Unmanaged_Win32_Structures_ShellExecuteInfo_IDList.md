# ShellExecuteInfo.IDList Field
 

The address of an absolute ITEMIDLIST structure (PCIDLIST_ABSOLUTE) to contain an item identifier list that uniquely identifies the file to execute. This member is ignored if the fMask member does not include SEE_MASK_IDLIST or SEE_MASK_INVOKEIDLIST.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IntPtr IDList
```

**VB**<br />
``` VB
Public IDList As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellExecuteInfo
Dim value As IntPtr

value = instance.IDList

instance.IDList = value
```

**C++**<br />
``` C++
public:
IntPtr IDList
```

**F#**<br />
``` F#
val mutable IDList: IntPtr
```


#### Field Value
Type: IntPtr

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellExecuteInfo">ShellExecuteInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />