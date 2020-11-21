# BufferSizes Enumeration
 

Specifies common buffer sizes to use for a disk read/write operation. 

 To calculate the optimal read/write buffer size for a determined filesize, use the <a href="M_DevCase_Core_IO_Tools_StreamUtil_GetFileStreamBufferSize">GetFileStreamBufferSize(Int64)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum BufferSizes
```

**VB**<br />
``` VB
Public Enumeration BufferSizes
```

**VB Usage**<br />
``` VB Usage
Dim instance As BufferSizes
```

**C++**<br />
``` C++
public enum class BufferSizes
```

**F#**<br />
``` F#
type BufferSizes
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb1">**Kb1**</td><td>1024</td><td>A buffer size of 1 Kilobyte (1024 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb2">**Kb2**</td><td>2048</td><td>A buffer size of 2 Kilobytes (2048 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb4">**Kb4**</td><td>4096</td><td>A buffer size of 4 Kilobytes (4096 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb8">**Kb8**</td><td>8192</td><td>A buffer size of 8 Kilobytes (8192 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb16">**Kb16**</td><td>16384</td><td>A buffer size of 16 Kilobytes (16384 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb32">**Kb32**</td><td>32768</td><td>A buffer size of 32 Kilobytes (32768 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb64">**Kb64**</td><td>65536</td><td>A buffer size of 64 Kilobytes (65536 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb128">**Kb128**</td><td>131072</td><td>A buffer size of 128 Kilobytes (131072 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb256">**Kb256**</td><td>262144</td><td>A buffer size of 256 Kilobytes (262144 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Kb512">**Kb512**</td><td>524288</td><td>A buffer size of 512 Kilobytes (524288 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.Mb1">**Mb1**</td><td>1048576</td><td>A buffer size of 1 Megabyte (1048576 bytes)</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.FileStreamDefault">**FileStreamDefault**</td><td>4096</td><td>A buffer size of 4 Kilobytes (4096 bytes) 

 This is the default buffer size of FileStream implementation.</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.BufferedStreamDefault">**BufferedStreamDefault**</td><td>4096</td><td>A buffer size of 4 Kilobytes (4096 bytes) 

 This is the default buffer size of BufferedStream implementation.</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.StreamReaderDefault">**StreamReaderDefault**</td><td>1024</td><td>A buffer size of 1 Kilobyte (1024 bytes) 

 This is the default buffer size of StreamReader implementation.</td></tr><tr><td /><td target="F:DevCase.Core.IO.BufferSizes.StreamWriterDefault">**StreamWriterDefault**</td><td>1024</td><td>A buffer size of 1 Kilobyte (1024 bytes) 

 This is the default buffer size of StreamWriter implementation.</td></tr></table>

## Remarks
Microsoft article: <a href="https://docs.microsoft.com/en-us/windows/desktop/FileIO/file-buffering" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/FileIO/file-buffering</a>

 Hans Passant comment: <a href="https://stackoverflow.com/a/3034155/1248295" target="_blank">https://stackoverflow.com/a/3034155/1248295</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />