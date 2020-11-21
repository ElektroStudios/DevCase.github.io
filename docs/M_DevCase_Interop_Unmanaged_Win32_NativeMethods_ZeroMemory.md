# NativeMethods.ZeroMemory Method (IntPtr, IntPtr)
 

Fills a block of memory with zeros.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static void ZeroMemory(
	IntPtr address,
	IntPtr size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Sub ZeroMemory ( 
	address As IntPtr,
	size As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim address As IntPtr
Dim size As IntPtrNativeMethods.ZeroMemory(address, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static void ZeroMemory(
	IntPtr address, 
	IntPtr size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member ZeroMemory : 
        address : IntPtr * 
        size : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>address</dt><dd>Type: System.IntPtr<br />A pointer to the starting address of the block of memory to fill with zeros.</dd><dt>size</dt><dd>Type: System.IntPtr<br />The size of the block of memory to fill with zeros, in bytes.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366920(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366920(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_ZeroMemory">ZeroMemory Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />