# NativeMethods.EnumThreadWindows Method 
 

Enumerates all nonchild windows associated with a thread by passing the handle to each window, in turn, to an application-defined callback function. 

EnumThreadWindows(UInt32, Delegates.EnumThreadWindowsProc, IntPtr) continues until the last window is enumerated or the callback function returns `false` (`False` in Visual Basic). 

 To enumerate child windows of a particular window, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumChildWindows">EnumChildWindows(IntPtr, Delegates.EnumChildWindowsProc, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool EnumThreadWindows(
	uint threadId,
	Delegates.EnumThreadWindowsProc lpEnumFunc,
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function EnumThreadWindows ( 
	threadId As UInteger,
	lpEnumFunc As Delegates.EnumThreadWindowsProc,
	lParam As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim threadId As UInteger
Dim lpEnumFunc As Delegates.EnumThreadWindowsProc
Dim lParam As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.EnumThreadWindows(threadId, 
	lpEnumFunc, lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool EnumThreadWindows(
	unsigned int threadId, 
	Delegates.EnumThreadWindowsProc^ lpEnumFunc, 
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member EnumThreadWindows : 
        threadId : uint32 * 
        lpEnumFunc : Delegates.EnumThreadWindowsProc * 
        lParam : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>threadId</dt><dd>Type: System.UInt32<br />The identifier of the thread whose windows are to be enumerated.</dd><dt>lpEnumFunc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumThreadWindowsProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumThreadWindowsProc</a><br />A pointer to an application-defined callback function.</dd><dt>lParam</dt><dd>Type: System.IntPtr<br />An application-defined value to be passed to the callback function.</dd></dl>

#### Return Value
Type: Boolean<br />If the callback function returns `true` (`True` in Visual Basic) for all windows in the thread specified by threadId, the return value is `true` (`True` in Visual Basic). 

 If the callback function returns `false` (`False` in Visual Basic) on any enumerated window, or if there are no windows found in the thread specified by threadId, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633495%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633495%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />