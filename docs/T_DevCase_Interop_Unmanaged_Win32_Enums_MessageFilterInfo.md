# MessageFilterInfo Enumeration
 

Specifies additional information about a success call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum MessageFilterInfo
```

**VB**<br />
``` VB
Public Enumeration MessageFilterInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As MessageFilterInfo
```

**C++**<br />
``` C++
public enum class MessageFilterInfo
```

**F#**<br />
``` F#
type MessageFilterInfo
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MessageFilterInfo.None">**None**</td><td>0</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MessageFilterInfo.AlreadyAllowed">**AlreadyAllowed**</td><td>1</td><td>The message has already been allowed by this window's message filter, and the function thus succeeded with no change to the window's message filter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MessageFilterInfo.AlreadyDisAllowed">**AlreadyDisAllowed**</td><td>2</td><td>The message has already been blocked by this window's message filter, and the function thus succeeded with no change to the window's message filter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.MessageFilterInfo.AllowedHigher">**AllowedHigher**</td><td>3</td><td>The message is allowed at a scope higher than the window.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd388197%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd388197%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />