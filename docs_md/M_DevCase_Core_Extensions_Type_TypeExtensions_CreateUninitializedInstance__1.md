# TypeExtensions.CreateUninitializedInstance(*T*) Method 
 

Creates an uninitialized instance of *T* without calling any of its constructors. 

 Note that because the returned instance of the object is initialized to zero and no constructors are run, the object might not represent a state that is regarded as valid by that object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T CreateUninitializedInstance<T>(
	this T type
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function CreateUninitializedInstance(Of T) ( 
	type As T
) As T
```

**VB Usage**<br />
``` VB Usage
Dim type As T
Dim returnValue As T

returnValue = type.CreateUninitializedInstance()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T CreateUninitializedInstance(
	T type
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member CreateUninitializedInstance : 
        type : 'T -> 'T 

```


#### Parameters
&nbsp;<dl><dt>type</dt><dd>Type: *T*<br />\[Missing <param name="type"/> documentation for "M:DevCase.Core.Extensions.Type.TypeExtensions.CreateUninitializedInstance``1(``0)"\]</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: *T*<br />An instance of type *T* with all its `non-static` fields initialized to its default value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/system.runtime.serialization.formatterservices.getuninitializedobject.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/system.runtime.serialization.formatterservices.getuninitializedobject.aspx</a>

 The current method should only be used for deserialization when the user intends to immediately populate all fields. 

 It does not create an uninitialized string, since creating an empty instance of an immutable type serves no purpose.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Type_TypeExtensions">TypeExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Type">DevCase.Core.Extensions.Type Namespace</a><br />