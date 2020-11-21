# CmdCommandRedirection Enumeration
 

Specifies a CMD output to redirect commands.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum CmdCommandRedirection
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration CmdCommandRedirection
```

**VB Usage**<br />
``` VB Usage
Dim instance As CmdCommandRedirection
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class CmdCommandRedirection
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type CmdCommandRedirection
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.CmdCommandRedirection.None">**None**</td><td>0</td><td>Any output.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.CmdCommandRedirection.Standard">**Standard**</td><td>1</td><td>CMD Standard Output. (`1>Nul`)</td></tr><tr><td /><td target="F:DevCase.Core.Shell.CmdCommandRedirection.Error">**Error**</td><td>2</td><td>CMD Error output. (`2>Nul`)</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />