# PermutationCollection(*T*) Class
 

Permutations defines a meta-collection, typically a list of lists, of all possible orderings of a set of values. 

 This list is enumerable and allows the scanning of all possible permutations using a simple `For Each` loop.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Collections.PermutationCollection(T)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PermutationCollection<T> : IMetaCollection<T>

```

**VB**<br />
``` VB
Public NotInheritable Class PermutationCollection(Of T)
	Implements IMetaCollection(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PermutationCollection(Of T)
```

**C++**<br />
``` C++
generic<typename T>
public ref class PermutationCollection sealed : IMetaCollection<T>
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PermutationCollection<'T> =  
    class
        interface IMetaCollection<'T>
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the values within the list.</dd></dl>&nbsp;
The PermutationCollection(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1__ctor">PermutationCollection(T)(IList(T))</a></td><td>
Initializes a new instance of the PermutationCollection(T) class. 

 Create a permutation set from the provided list of values. 

 The values `T` must implement IComparable. 

 If `T` does not implement IComparable use a constructor with an explict IComparer. 

 The repetition type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a></td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1__ctor_1">PermutationCollection(T)(IList(T), MetaCollectionType)</a></td><td>
Initializes a new instance of the PermutationCollection(T) class. 

 Create a permutation set from the provided list of values. 

 If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>, then values (`T`) must implement IComparable. 

 If T does not implement IComparable use a constructor with an explict IComparer.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1__ctor_2">PermutationCollection(T)(IList(T), IComparer(T))</a></td><td>
Initializes a new instance of the PermutationCollection(T) class. 

 Create a permutation set from the provided list of values. 

 The values will be compared using the supplied IComparer. 

 The repetition type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a></td></tr></table>&nbsp;
<a href="#permutationcollection(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_Count">Count</a></td><td>
The count of all permutations that will be returned. 

 If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a>, then this does not double count permutations with multiple identical values. 

 I.e. count of permutations of "`AAB`" will be `3` instead of `6`. If type is <a href="T_DevCase_Core_Collections_MetaCollectionType">WithRepetition</a>, then this is all combinations and is therefore `N!`, where `N` is the number of values.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_LowerIndex">LowerIndex</a></td><td>
The lower index of the meta-collection, equal to the number of items returned each iteration. 

 For Permutation, this is always equal to the <a href="P_DevCase_Core_Collections_PermutationCollection_1_UpperIndex">UpperIndex</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_Type">Type</a></td><td>
The type of Permutations set that is generated.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_PermutationCollection_1_UpperIndex">UpperIndex</a></td><td>
The upper index of the meta-collection, equal to the number of items in the initial set.</td></tr></table>&nbsp;
<a href="#permutationcollection(*t*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1_GetEnumerator">GetEnumerator</a></td><td>
Gets an enumerator for collecting the list of permutations.</td></tr></table>&nbsp;
<a href="#permutationcollection(*t*)-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#permutationcollection(*t*)-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Collections_PermutationCollection_1_System_Collections_IEnumerable_GetEnumerator">IEnumerable.GetEnumerator</a></td><td /></tr></table>&nbsp;
<a href="#permutationcollection(*t*)-class">Back to Top</a>

## Remarks
When given a input collect `{A, A, B}` and lower index of `2`, the following sets are generated: 

`MetaCollectionType.WithRepetition => {A, A, B}, {A, B, A}, {A, A, B}, {A, B, A}, {B, A, A}, {B, A, A}`

`MetaCollectionType.WithoutRepetition => {A, A, B}, {A, B, A}, {B, A, A}`



 When generating non-repetition sets, ordering is based on the lexicographic ordering of the lists based on the provided Comparer. If no comparer is provided, then `T` must be IComparable on `T`. 

 When generating repetition sets, no comparisions are performed and therefore no comparer is required and `T` does not need to be IComparable.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim permutations As New PermutationCollection(Of String)({"a", "b", "c"}, MetaCollectionType.WithoutRepetition)

For Each permutation As List(Of String) In permutations
    Console.WriteLine(String.Join(", ", permutation))
Next permutation
```


## See Also


#### Reference
<a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />