# NativeMethods.GetKeyboardLayout Method 
 

Retrieves the active input locale identifier (formerly called the keyboard layout).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Unicode)]
public static IntPtr GetKeyboardLayout(
	uint idThread = 0
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Unicode>]
Public Shared Function GetKeyboardLayout ( 
	Optional idThread As UInteger = 0
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim idThread As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.GetKeyboardLayout(idThread)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Unicode)]
static IntPtr GetKeyboardLayout(
	unsigned int idThread = 0
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Unicode)>]
static member GetKeyboardLayout : 
        ?idThread : uint32 
(* Defaults:
        let _idThread = defaultArg idThread 0
*)
-> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>idThread (Optional)</dt><dd>Type: System.UInt32<br />A window handle identifier of the thread to query, or `0` to query the current thread.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is the input locale identifier for the thread. 

 The low-order byte contains a Language Identifier for the input language, and the high-order byte contains a device handle to the physical layout of the keyboard.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646296%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646296%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />