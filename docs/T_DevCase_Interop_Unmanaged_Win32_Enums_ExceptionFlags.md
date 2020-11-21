# ExceptionFlags Enumeration
 

Specifies flags for a exception that occured in the calling thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ExceptionFlags
```

**VB**<br />
``` VB
Public Enumeration ExceptionFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ExceptionFlags
```

**C++**<br />
``` C++
public enum class ExceptionFlags
```

**F#**<br />
``` F#
type ExceptionFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.Continuable">**Continuable**</td><td>0</td><td>Proceed with normal execution of UnhandledExceptionFilter. 

 That means obeying the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetErrorMode">SetErrorMode(ProcessErrorMode)</a> flags, or invoking the Application Error pop-up message box.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.NonContinuable">**NonContinuable**</td><td>1</td><td>Indicates a noncontinuable exception.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.ExecuteHandler">**ExecuteHandler**</td><td>1</td><td>Return from UnhandledExceptionFilter and execute the associated exception handler. 

 This usually results in process termination.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.Unwinding">**Unwinding**</td><td>2</td><td>( Not documented )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.ExitUnwind">**ExitUnwind**</td><td>4</td><td>( Not documented )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.StackInvalid">**StackInvalid**</td><td>8</td><td>( Not documented )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.NestedCall">**NestedCall**</td><td>16</td><td>( Not documented )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.TargetUnwind">**TargetUnwind**</td><td>32</td><td>( Not documented )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.CollidedUnwind">**CollidedUnwind**</td><td>64</td><td>( Not documented )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.Unwind">**Unwind**</td><td>102</td><td>( Not documented )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.ContinueExecution">**ContinueExecution**</td><td>4294967295</td><td>Return from UnhandledExceptionFilter and continue execution from the point of the exception. 

 Note that the filter function is free to modify the continuation state by modifying the exception information supplied through its LPPOINTERS parameter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags.ChainEnd">**ChainEnd**</td><td>4294967295</td><td>( Not documented )</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms680552(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms680552(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />