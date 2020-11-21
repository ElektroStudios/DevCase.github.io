# NativeMethods.RaiseException Method 
 

Raises an exception in the calling thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static void RaiseException(
	uint exceptionCode,
	ExceptionFlags exceptionFlags,
	uint numberOfArguments,
	IntPtr arguments
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Sub RaiseException ( 
	exceptionCode As UInteger,
	exceptionFlags As ExceptionFlags,
	numberOfArguments As UInteger,
	arguments As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim exceptionCode As UInteger
Dim exceptionFlags As ExceptionFlags
Dim numberOfArguments As UInteger
Dim arguments As IntPtrNativeMethods.RaiseException(exceptionCode, 
	exceptionFlags, numberOfArguments, 
	arguments)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static void RaiseException(
	unsigned int exceptionCode, 
	ExceptionFlags exceptionFlags, 
	unsigned int numberOfArguments, 
	[InAttribute] IntPtr arguments
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member RaiseException : 
        exceptionCode : uint32 * 
        exceptionFlags : ExceptionFlags * 
        numberOfArguments : uint32 * 
        arguments : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>exceptionCode</dt><dd>Type: System.UInt32<br />An application-defined exception code of the exception being raised. 

 The filter expression and exception-handler block of an exception handler can use the GetExceptionCode macro (or GetExceptionCode()) to retrieve this value. 

 Note that the system will clear bit 28 of *exceptionCode* before displaying a message: "This bit is a reserved exception bit", used by the system for its own purposes.</dd><dt>exceptionFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExceptionFlags">DevCase.Interop.Unmanaged.Win32.Enums.ExceptionFlags</a><br />The exception flags. 

 This can be either <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExceptionFlags">Continuable</a> to indicate a continuable exception, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ExceptionFlags">NonContinuable</a> to indicate a noncontinuable exception. 

 Any attempt to continue execution after a noncontinuable exception causes the EXCEPTION_NONCONTINUABLE_EXCEPTION exception.</dd><dt>numberOfArguments</dt><dd>Type: System.UInt32<br />The number of arguments in the lpArguments array. This value must not exceed EXCEPTION_MAXIMUM_PARAMETERS. 

 This parameter is ignored if *arguments* is Zero.</dd><dt>arguments</dt><dd>Type: System.IntPtr<br />An array of arguments. This parameter can be Zero. 

 These arguments can contain any application-defined data that needs to be passed to the filter expression of the exception handler.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms680552(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms680552(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />