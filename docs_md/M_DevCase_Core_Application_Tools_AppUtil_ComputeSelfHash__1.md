# AppUtil.ComputeSelfHash(*T*) Method 
 

Computes a hash code for the main executable file of the running application.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ComputeSelfHash<T>()
where T : HashAlgorithm

```

**VB**<br />
``` VB
Public Shared Function ComputeSelfHash(Of T As HashAlgorithm) As String
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As String

returnValue = AppUtil.ComputeSelfHash()
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : HashAlgorithm
static String^ ComputeSelfHash()
```

**F#**<br />
``` F#
static member ComputeSelfHash : unit -> string  when 'T : HashAlgorithm

```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Application.Tools.AppUtil.ComputeSelfHash``1"\]</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting hash code.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim selfHash As String = ComputeSelfHash(Of MD5CryptoServiceProvider)()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />