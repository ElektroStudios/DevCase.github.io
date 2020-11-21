# IMetaCollection(*T*) Interface
 

Interface for Permutations, Combinations and any other classes that present a collection of collections based on an input collection. 

 The enumerators that this class inherits defines the mechanism for enumerating through the collections.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public interface IMetaCollection<T> : IEnumerable<IList<T>>

```

**VB**<br />
``` VB
Public Interface IMetaCollection(Of T)
	Inherits IEnumerable(Of IList(Of T))
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMetaCollection(Of T)
```

**C++**<br />
``` C++
generic<typename T>
public interface class IMetaCollection : IEnumerable<IList<T>^>
```

**F#**<br />
``` F#
type IMetaCollection<'T> =  
    interface
        interface IEnumerable<IList<'T>>
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The of the elements in the collection, not the type of the collection.</dd></dl>&nbsp;
The IMetaCollection(T) type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_IMetaCollection_1_Count">Count</a></td><td>
The count of items in the collection. 

 This is not inherited from ICollection since this meta-collection cannot be extended by users.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_IMetaCollection_1_LowerIndex">LowerIndex</a></td><td>
The lower index of the meta-collection, which is the size of each output collection.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_IMetaCollection_1_Type">Type</a></td><td>
The type of the meta-collection, determining how the collections are determined from the inputs.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_IMetaCollection_1_UpperIndex">UpperIndex</a></td><td>
The upper index of the meta-collection, which is the size of the input collection.</td></tr></table>&nbsp;
<a href="#imetacollection(*t*)-interface">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Append__1">Append(IList(T))</a></td><td>
Appends an element to the end of the source collection.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_AsReadOnly__1">AsReadOnly(IList(T))</a></td><td>
Returns a read-only ReadOnlyCollection(T) wrapper for the specified collection.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_CountEmptyItems__1">CountEmptyItems(IList(T))</a></td><td>
Counts the empty items of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_CountNonEmptyItems__1">CountNonEmptyItems(IList(T))</a></td><td>
Counts the non-empty items of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_DistinctBy__2">DistinctBy(IList(T), TKey)(Func(IList(T), TKey))</a></td><td>Overloaded.  
Returns distinct elements from a sequence by using a specified key selector and the default equality comparer to compare values.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_DistinctBy__2_1">DistinctBy(IList(T), TKey)(Func(IList(T), TKey), IEqualityComparer(TKey))</a></td><td>Overloaded.  
Returns distinct elements from a sequence by using a specified key selector and equality comparer to compare values.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Duplicates__1">Duplicates(IList(T))</a></td><td>
Gets all the duplicated values of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ForEach__1">ForEach(IList(T))</a></td><td>
Performs the specified action on each element of the IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GetRandomItem__1">GetRandomItem(IList(T))</a></td><td>
Gets a random element from the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GroupByIntoFirstElement__2">GroupByIntoFirstElement(IList(T), TKey)</a></td><td>
Groups the elements of a sequence according to a specified key selector function and discards all the elements in each group except the first element.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GroupByIntoItemCount__2">GroupByIntoItemCount(IList(T), TKey)</a></td><td>
Groups the elements of a sequence according to a specified key selector function and returns a Dictionary(TKey, TValue) dictionary on which {.key = element} and {.value = element count}.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GroupByIntoMaxNumberOfElements__2">GroupByIntoMaxNumberOfElements(IList(T), TKey)</a></td><td>
Groups the elements of a sequence according to a specified key selector function and takes the specified amount of elements of each group.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_3">IndexOf(IList(T))(IList(T))</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1">IndexOf(IList(T))(IEnumerable(IList(T)))</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_4">IndexOf(IList(T))(IList(T), Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_1">IndexOf(IList(T))(IEnumerable(IList(T)), Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_5">IndexOf(IList(T))(IList(T), Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_2">IndexOf(IList(T))(IEnumerable(IList(T)), Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_3">IndexOfAll(IList(T))(IList(T))</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1">IndexOfAll(IList(T))(IEnumerable(IList(T)))</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_4">IndexOfAll(IList(T))(IList(T), Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_1">IndexOfAll(IList(T))(IEnumerable(IList(T)), Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_5">IndexOfAll(IList(T))(IList(T), Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_2">IndexOfAll(IList(T))(IEnumerable(IList(T)), Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Prepend__1">Prepend(IList(T))</a></td><td>
Prepends an element to the start of the source collection.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Randomize__1">Randomize(IList(T))</a></td><td>
Randomizes the elements of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_RemoveDuplicates__1">RemoveDuplicates(IList(T))</a></td><td>
Removes duplicated values in the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_SplitIntoNumberOfElements__1">SplitIntoNumberOfElements(IList(T))(Int32)</a></td><td>Overloaded.  
Splits the source IEnumerable(T) into secuences with the specified amount of elements.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_SplitIntoNumberOfElements__1_1">SplitIntoNumberOfElements(IList(T))(Int32, Boolean, IList(T))</a></td><td>Overloaded.  
Splits the source IEnumerable(T) into secuences with the specified amount of elements.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_SplitIntoParts__1">SplitIntoParts(IList(T))</a></td><td>
Splits the source IEnumerable(T) into the specified amount of secuences.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ToArray__1">ToArray(IList(T))</a></td><td>
Creates an array from an IEnumerable(T) using the specified transform function.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ToList__1">ToList(IList(T))</a></td><td>
Creates a List(T) from an IEnumerable(T) using the specified transform function.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ToTreeString__1">ToTreeString(IList(T))</a></td><td>
Transforms an array of string into a string with tree formatting.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_UniqueDuplicates__1">UniqueDuplicates(IList(T))</a></td><td>
Gets the unique duplicated values of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Uniques__1">Uniques(IList(T))</a></td><td>
Gets the unique values of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr></table>&nbsp;
<a href="#imetacollection(*t*)-interface">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />