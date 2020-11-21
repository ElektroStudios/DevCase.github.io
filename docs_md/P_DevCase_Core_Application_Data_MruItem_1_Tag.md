# MruItem(*T*).Tag Property 
 

Gets or sets a tag for this MRU item. 

 A tag could contain any kind of additional info.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Object Tag { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property Tag As Object
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As MruItem
Dim value As Object

value = instance.Tag

instance.Tag = value
```

**C++**<br />
``` C++
public:
virtual property Object^ Tag {
	Object^ get ();
	void set (Object^ value);
}
```

**F#**<br />
``` F#
abstract Tag : Object with get, set
override Tag : Object with get, set
```


#### Property Value
Type: Object<br />The tag object.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_MruItem_1">MruItem(T) Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />