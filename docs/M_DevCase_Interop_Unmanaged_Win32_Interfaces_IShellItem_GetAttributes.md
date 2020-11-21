# IShellItem.GetAttributes Method 
 

Gets a requested set of attributes of the <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem</a> object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
ShellItemAttributesMask GetAttributes(
	ShellItemAttributesMask sfgaoMask
)
```

**VB**<br />
``` VB
Function GetAttributes ( 
	sfgaoMask As ShellItemAttributesMask
) As ShellItemAttributesMask
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItem
Dim sfgaoMask As ShellItemAttributesMask
Dim returnValue As ShellItemAttributesMask

returnValue = instance.GetAttributes(sfgaoMask)
```

**C++**<br />
``` C++
ShellItemAttributesMask GetAttributes(
	ShellItemAttributesMask sfgaoMask
)
```

**F#**<br />
``` F#
abstract GetAttributes : 
        sfgaoMask : ShellItemAttributesMask -> ShellItemAttributesMask 

```


#### Parameters
&nbsp;<dl><dt>sfgaoMask</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask</a><br />Specifies the attributes to retrieve. One or more of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">ShellItemAttributesMask</a> values.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">ShellItemAttributesMask</a><br />A pointer to a value that, when this method returns successfully, contains the requested attributes. 

 Only those attributes specified by *sfgaoMask* are returned; other attribute values are undefined.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />