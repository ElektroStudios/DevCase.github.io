# Delegates.MiniDumpCallbackRoutine Delegate
 

An application-defined callback function used with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MiniDumpWriteDump">MiniDumpWriteDump(IntPtr, Int32, SafeHandle, MiniDumpType, MiniDumpExceptionInformation, IntPtr, IntPtr)</a>. It receives extended minidump information.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool MiniDumpCallbackRoutine(
	IntPtr callbackParam,
	IntPtr callbackInput,
	IntPtr callbackOutput
)
```

**VB**<br />
``` VB
Public Delegate Function MiniDumpCallbackRoutine ( 
	callbackParam As IntPtr,
	callbackInput As IntPtr,
	<OutAttribute> callbackOutput As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New MiniDumpCallbackRoutine(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool MiniDumpCallbackRoutine(
	[InAttribute] IntPtr callbackParam, 
	[InAttribute] IntPtr callbackInput, 
	[InAttribute] [OutAttribute] IntPtr callbackOutput
)
```

**F#**<br />
``` F#
type MiniDumpCallbackRoutine = 
    delegate of 
        callbackParam : IntPtr * 
        callbackInput : IntPtr * 
        callbackOutput : IntPtr byref -> bool
```


#### Parameters
&nbsp;<dl><dt>callbackParam</dt><dd>Type: System.IntPtr<br />An application-defined parameter value.</dd><dt>callbackInput</dt><dd>Type: System.IntPtr<br />A pointer to a `MINIDUMP_CALLBACK_INPUT` structure that specifies extended minidump information.</dd><dt>callbackOutput</dt><dd>Type: System.IntPtr<br />A pointer to a `MINIDUMP_CALLBACK_OUTPUT` structure that receives application-defined information from the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, return `true` (`True` in Visual Basic); otherwise, return `false` (`False` in Visual Basic)

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680358%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680358%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />