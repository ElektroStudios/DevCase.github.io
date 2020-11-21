# Compiler.CompilerWorkDone Event
 

Occurs when the compiler finishes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public event EventHandler<CompilerWorkDoneEventArgs> CompilerWorkDone
```

**VB**<br />
``` VB
Public Event CompilerWorkDone As EventHandler(Of CompilerWorkDoneEventArgs)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Compiler
Dim handler As EventHandler(Of CompilerWorkDoneEventArgs)

AddHandler instance.CompilerWorkDone, handler

```

**C++**<br />
``` C++
public:
 event EventHandler<CompilerWorkDoneEventArgs^>^ CompilerWorkDone {
	void add (EventHandler<CompilerWorkDoneEventArgs^>^ value);
	void remove (EventHandler<CompilerWorkDoneEventArgs^>^ value);
}
```

**F#**<br />
``` F#
member CompilerWorkDone : IEvent<EventHandler<CompilerWorkDoneEventArgs>,
    CompilerWorkDoneEventArgs>

```


#### Value
Type: System.EventHandler(<a href="T_DevCase_Interop_Managed_Eventing_CompilerWorkDoneEventArgs">CompilerWorkDoneEventArgs</a>)

## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Compiler">Compiler Class</a><br /><a href="N_DevCase_Interop_Managed">DevCase.Interop.Managed Namespace</a><br />