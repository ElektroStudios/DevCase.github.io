# QueryUserNotificationState Enumeration
 

Specifies the state of the machine for the current user in relation to the propriety of sending a notification. 

 Used by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHQueryUserNotificationState">SHQueryUserNotificationState(QueryUserNotificationState)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum QueryUserNotificationState
```

**VB**<br />
``` VB
Public Enumeration QueryUserNotificationState
```

**VB Usage**<br />
``` VB Usage
Dim instance As QueryUserNotificationState
```

**C++**<br />
``` C++
public enum class QueryUserNotificationState
```

**F#**<br />
``` F#
type QueryUserNotificationState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState.NotPresent">**NotPresent**</td><td>1</td><td>A screen saver is displayed, the machine is locked, or a non-active Fast User Switching session is in progress.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState.Busy">**Busy**</td><td>2</td><td>A full-screen application is running or Presentation Settings are applied. 

 Presentation Settings allow a user to put their machine into a state fit for an uninterrupted presentation, such as a set of PowerPoint slides, with a single click.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState.RunningD3DFullScreen">**RunningD3DFullScreen**</td><td>3</td><td>A full-screen (exclusive mode) Direct-3D application is running.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState.PresentationMode">**PresentationMode**</td><td>4</td><td>The user has activated Windows presentation settings to block notifications and pop-up messages.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState.AcceptsNotifications">**AcceptsNotifications**</td><td>5</td><td>None of the other states are found, notifications can be freely sent.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState.QuietTime">**QuietTime**</td><td>6</td><td>The current user is in "quiet time", which is the first hour after a new user logs into his or her account for the first time. 

 During this time, most notifications should not be sent or shown. This lets a user become accustomed to a new computer system without those distractions. 

 Quiet time also occurs for each user after an operating system upgrade or clean installation. 

 Applications should set the NIIF_RESPECT_QUIET_TIME flag in their notifications or balloon tooltip, which prevents those items from being displayed while the current user is in the quiet-time state. 

 Note that during quiet time, if the user is in one of the other blocked modes (NotPresent, Busy, PresentationMode, or RunningD3DFullScreen) <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHQueryUserNotificationState">SHQueryUserNotificationState(QueryUserNotificationState)</a> returns only that value, and does not report QuietTime.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.QueryUserNotificationState.App">**App**</td><td>7</td><td>A Windows Store app is running.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/shellapi/ne-shellapi-query_user_notification_state" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/shellapi/ne-shellapi-query_user_notification_state</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />