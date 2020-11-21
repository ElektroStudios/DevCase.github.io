# SMART.Attributes Property 
 

Gets the S.M.A.R.T. attributes of the hard drive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[TypeConverterAttribute(typeof(CollectionConverter))]
[EditorAttribute(typeof(UnwrappedCollectionEditor<SmartAttribute>), typeof(UITypeEditor))]
public ReadOnlyCollection<SmartAttribute> Attributes { get; }
```

**VB**<br />
``` VB
<TypeConverterAttribute(GetType(CollectionConverter))>
<EditorAttribute(GetType(UnwrappedCollectionEditor(Of SmartAttribute)), GetType(UITypeEditor))>
Public ReadOnly Property Attributes As ReadOnlyCollection(Of SmartAttribute)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SMART
Dim value As ReadOnlyCollection(Of SmartAttribute)

value = instance.Attributes

```

**C++**<br />
``` C++
public:
[TypeConverterAttribute(typeof(CollectionConverter))]
[EditorAttribute(typeof(UnwrappedCollectionEditor<SmartAttribute^>), typeof(UITypeEditor))]
property ReadOnlyCollection<SmartAttribute^>^ Attributes {
	ReadOnlyCollection<SmartAttribute^>^ get ();
}
```

**F#**<br />
``` F#
[<TypeConverterAttribute(typeof(CollectionConverter))>]
[<EditorAttribute(typeof(UnwrappedCollectionEditor<SmartAttribute>), typeof(UITypeEditor))>]
member Attributes : ReadOnlyCollection<SmartAttribute> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Core_IO_SmartAttribute">SmartAttribute</a>)<br />\[Missing <value> documentation for "P:DevCase.Core.IO.SMART.Attributes"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_SMART">SMART Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />