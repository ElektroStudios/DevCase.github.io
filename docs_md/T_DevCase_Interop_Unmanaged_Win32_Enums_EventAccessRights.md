# EventAccessRights Enumeration
 

Specifies the access rights for an event object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum EventAccessRights
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration EventAccessRights
```

**VB Usage**<br />
``` VB Usage
Dim instance As EventAccessRights
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class EventAccessRights
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type EventAccessRights
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EventAccessRights.QueryState">**QueryState**</td><td>1</td><td>Query the state of the event object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EventAccessRights.ModifyState">**ModifyState**</td><td>2</td><td>Modify the state of the event object.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EventAccessRights.AllAccess">**AllAccess**</td><td>2031619</td><td>All possible access rights to the event object.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-zwopenevent" target="_blank">https://docs.microsoft.com/en-us/windows-hardware/drivers/ddi/content/wdm/nf-wdm-zwopenevent</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />