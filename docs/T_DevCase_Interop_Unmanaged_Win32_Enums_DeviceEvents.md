# DeviceEvents Enumeration
 

Specifies a change to the hardware configuration of a device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum DeviceEvents
```

**VB**<br />
``` VB
Public Enumeration DeviceEvents
```

**VB Usage**<br />
``` VB Usage
Dim instance As DeviceEvents
```

**C++**<br />
``` C++
public enum class DeviceEvents
```

**F#**<br />
``` F#
type DeviceEvents
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents.Change">**Change**</td><td>537</td><td>The current configuration has changed, due to a dock or undock.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents.Arrival">**Arrival**</td><td>32768</td><td>A device or piece of media has been inserted and becomes available.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents.QueryRemove">**QueryRemove**</td><td>32769</td><td>Request permission to remove a device or piece of media. 

 This message is the last chance for applications and drivers to prepare for this removal. However, any application can deny this request and cancel the operation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents.QueryRemoveFailed">**QueryRemoveFailed**</td><td>32770</td><td>A request to remove a device or piece of media has been canceled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents.RemovePending">**RemovePending**</td><td>32771</td><td>A device or piece of media is being removed and is no longer available for use.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DeviceEvents.RemoveComplete">**RemoveComplete**</td><td>32772</td><td>A device or piece of media has been removed.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363480%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363480%28v=vs.85%29.aspx</a><a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363232%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363232%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />