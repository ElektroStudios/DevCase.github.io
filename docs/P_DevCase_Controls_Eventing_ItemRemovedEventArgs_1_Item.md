# ItemRemovedEventArgs(*T*).Item Property 
 

Gets the removed item.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual T Item { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Item As T
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ItemRemovedEventArgs
Dim value As T

value = instance.Item

```

**C++**<br />
``` C++
public:
virtual property T Item {
	T get ();
}
```

**F#**<br />
``` F#
abstract Item : 'T with get
override Item : 'T with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_Eventing_ItemRemovedEventArgs_1">*T*</a><br />The removed item.

## See Also


#### Reference
<a href="T_DevCase_Controls_Eventing_ItemRemovedEventArgs_1">ItemRemovedEventArgs(T) Class</a><br /><a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing Namespace</a><br />