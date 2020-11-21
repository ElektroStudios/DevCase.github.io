# HeapFlags Enumeration
 

Flags for Heap functions

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum HeapFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration HeapFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As HeapFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class HeapFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type HeapFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.None">**None**</td><td>0</td><td>None</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.NoSerialize">**NoSerialize**</td><td>1</td><td>Serialized access will not be used for this allocation. 

 To ensure that serialized access is disabled for all calls to this function, specify NoSerialize in the call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a>. In this case, it is not necessary to additionally specify NoSerialize in this function call. 

 This value should not be specified when accessing the process's default heap. 

 The system may create additional threads within the application's process, such as a CTRL+C handler, that simultaneously access the process's default heap.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.Growable">**Growable**</td><td>2</td><td>Specifies that the heap is growable. 

 Must be specified if HeapBase is NULL.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.GenerateExceptions">**GenerateExceptions**</td><td>4</td><td>The system will raise an exception to indicate a function failure, such as an out-of-memory condition, instead of returning NULL. 

 To ensure that exceptions are generated for all calls to this function, specify GenerateExceptions in the call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_HeapCreate">HeapCreate(HeapFlags, UInt32, UInt32)</a>. In this case, it is not necessary to additionally specify GenerateExceptions in this function call.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.ZeroMemory">**ZeroMemory**</td><td>8</td><td>The allocated memory will be initialized to zero. Otherwise, the memory is not initialized to zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.ReAllocInPlaceOnly">**ReAllocInPlaceOnly**</td><td>16</td><td>There can be no movement when reallocating a memory block. 

 If this value is not specified, the function may move the block to a new location. 

 If this value is specified and the block cannot be resized without moving, the function fails, leaving the original memory block unchanged.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.CreateEnableExecute">**CreateEnableExecute**</td><td>262144</td><td>All memory blocks that are allocated from this heap allow code execution, if the hardware enforces data execution prevention. 

 Use this flag heap in applications that run code from the heap. 

 If CreateEnableExecute is not specified and an application attempts to run code from a protected page, the application receives an exception with the status code STATUS_ACCESS_VIOLATION.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.TailCheckingEnabled">**TailCheckingEnabled**</td><td>32</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.FreeCheckingEnabled">**FreeCheckingEnabled**</td><td>64</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.DisableCoalesceOnFree">**DisableCoalesceOnFree**</td><td>128</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.CreateAlign16">**CreateAlign16**</td><td>65536</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.CreateEnableTracing">**CreateEnableTracing**</td><td>131072</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.MaximumTag">**MaximumTag**</td><td>4095</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.PseudoTagFlag">**PseudoTagFlag**</td><td>32768</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.TagShift">**TagShift**</td><td>18</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.CreateSegmentHeap">**CreateSegmentHeap**</td><td>256</td><td>( NOT DOCUMENTED )</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HeapFlags.CreateHardened">**CreateHardened**</td><td>512</td><td>( NOT DOCUMENTED )</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapcreate" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/heapapi/nf-heapapi-heapcreate</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />