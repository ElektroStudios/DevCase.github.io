# HardErrorResponseOption Enumeration
 

Specifies the response option when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_NtRaiseHardError">NtRaiseHardError(NTStatus, UInt32, UInt32, IntPtr, HardErrorResponseOption, HardErrorResponse)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum HardErrorResponseOption
```

**VB**<br />
``` VB
Public Enumeration HardErrorResponseOption
```

**VB Usage**<br />
``` VB Usage
Dim instance As HardErrorResponseOption
```

**C++**<br />
``` C++
public enum class HardErrorResponseOption
```

**F#**<br />
``` F#
type HardErrorResponseOption
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption.OptionAbortRetryIgnore">**OptionAbortRetryIgnore**</td><td>0</td><td>Visible buttons: ABORT, RETRY, IGNORE 

 ( like AbortRetryIgnore )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption.OptionOk">**OptionOk**</td><td>1</td><td>Visible buttons: OK 

 ( like OK )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption.OptionOkCancel">**OptionOkCancel**</td><td>2</td><td>Visible buttons: OK, CANCEL 

 ( like OKCancel )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption.OptionRetryCancel">**OptionRetryCancel**</td><td>3</td><td>Visible buttons: RETRY, CANCEL 

 ( like RetryCancel )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption.OptionYesNo">**OptionYesNo**</td><td>4</td><td>Visible buttons: YES, NO 

 ( like YesNo )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption.OptionYesNoCancel">**OptionYesNoCancel**</td><td>5</td><td>Visible buttons: YES, NO, CANCEL 

 ( like YesNoCancel )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HardErrorResponseOption.OptionShutdownSystem">**OptionShutdownSystem**</td><td>6</td><td>(Not documented)</td></tr></table>

## Remarks
<a href="https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FError%2FHARDERROR_RESPONSE_OPTION.html" target="_blank">https://undocumented.ntinternals.net/index.html?page=UserMode%2FUndocumented%20Functions%2FError%2FHARDERROR_RESPONSE_OPTION.html</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />