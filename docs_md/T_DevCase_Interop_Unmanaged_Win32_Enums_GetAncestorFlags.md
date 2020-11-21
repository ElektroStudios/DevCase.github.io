# GetAncestorFlags Enumeration
 

Specifies the changes to be applied for the active desktop. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetAncestor">GetAncestor(IntPtr, GetAncestorFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum GetAncestorFlags
```

**VB**<br />
``` VB
Public Enumeration GetAncestorFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As GetAncestorFlags
```

**C++**<br />
``` C++
public enum class GetAncestorFlags
```

**F#**<br />
``` F#
type GetAncestorFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetAncestorFlags.GetParent">**GetParent**</td><td>1</td><td>Retrieves the parent window. 

 This does not include the owner, as it does with the GetParent function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetAncestorFlags.GetRoot">**GetRoot**</td><td>2</td><td>Retrieves the root window by walking the chain of parent windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.GetAncestorFlags.GetRootOwner">**GetRootOwner**</td><td>3</td><td>Retrieves the owned root window by walking the chain of parent and owner windows returned by GetParent.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633502(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633502(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />