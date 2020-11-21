# NativeMethods.SetThreadToken Method 
 

Assigns an impersonation token to a thread. The function can also cause a thread to stop using an impersonation token.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetThreadToken(
	[OptionalAttribute] IntPtr thread,
	[OptionalAttribute] IntPtr token
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetThreadToken ( 
	<OptionalAttribute> thread As IntPtr,
	<OptionalAttribute> token As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim thread As IntPtr
Dim token As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SetThreadToken(thread, 
	token)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetThreadToken(
	[OptionalAttribute] IntPtr thread, 
	[OptionalAttribute] IntPtr token
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetThreadToken : 
        [<OptionalAttribute>] thread : IntPtr * 
        [<OptionalAttribute>] token : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>thread (Optional)</dt><dd>Type: System.IntPtr<br />A pointer to a handle to the thread to which the function assigns the impersonation token. 

 If *thread* is Zero, the function assigns the impersonation token to the calling thread.</dd><dt>token (Optional)</dt><dd>Type: System.IntPtr<br />A handle to the impersonation token to assign to the thread. 

 This handle must have been opened with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TokenAccess">Impersonate</a> access rights. 

 If *token* is Zero, the function causes the thread to stop using an impersonation token.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreadtoken" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreadtoken</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />