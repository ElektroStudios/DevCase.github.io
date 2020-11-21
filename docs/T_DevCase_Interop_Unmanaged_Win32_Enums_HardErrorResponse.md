# HardErrorResponse Enumeration
 

Specifies the response when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtRaiseHardError">NtRaiseHardError(NTStatus, UInt32, UInt32, IntPtr, HardErrorResponseOption, HardErrorResponse)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum HardErrorResponse
```

**VB**<br />
``` VB
Public Enumeration HardErrorResponse
```

**VB Usage**<br />
``` VB Usage
Dim instance As HardErrorResponse
```

**C++**<br />
``` C++
public enum class HardErrorResponse
```

**F#**<br />
``` F#
type HardErrorResponse
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseReturnToCaller">**ResponseReturnToCaller**</td><td>0</td><td>(Not documented)</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseNotHandled">**ResponseNotHandled**</td><td>1</td><td>(Not documented) 

 ( like None )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseAbort">**ResponseAbort**</td><td>2</td><td>ABORT button was pressed. 

 ( like Abort )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseCancel">**ResponseCancel**</td><td>3</td><td>CANCEL button was pressed. 

 ( like Cancel )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseIgnore">**ResponseIgnore**</td><td>4</td><td>IGNORE button was pressed. 

 ( like Ignore )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseNo">**ResponseNo**</td><td>5</td><td>NO button was pressed. 

 ( like No )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseOk">**ResponseOk**</td><td>6</td><td>OK button was pressed. 

 ( like OK )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseRetry">**ResponseRetry**</td><td>7</td><td>RETRY button was pressed. 

 ( like Retry )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponse.ResponseYes">**ResponseYes**</td><td>8</td><td>YES button was pressed. 

 ( like Yes )</td></tr></table>

## Remarks
<a href="https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FError%2FHARDERROR_RESPONSE.html" target="_blank">https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FError%2FHARDERROR_RESPONSE.html</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />