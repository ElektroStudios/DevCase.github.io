# PIDL Class
 

Represents a managed pointer to an ITEMIDLIST structure.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Runtime.ConstrainedExecution.CriticalFinalizerObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Runtime.InteropServices.SafeHandle<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Win32.SafeHandles.SafeHandleZeroOrMinusOneIsInvalid<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Interop.Unmanaged.PIDL<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class PIDL : SafeHandleZeroOrMinusOneIsInvalid, IEnumerable<PIDL>, 
	IEquatable<PIDL>, IEquatable<IntPtr>
```

**VB**<br />
``` VB
Public NotInheritable Class PIDL
	Inherits SafeHandleZeroOrMinusOneIsInvalid
	Implements IEnumerable(Of PIDL), IEquatable(Of PIDL), 
	IEquatable(Of IntPtr)
```

**VB Usage**<br />
``` VB Usage
Dim instance As PIDL
```

**C++**<br />
``` C++
public ref class PIDL sealed : public SafeHandleZeroOrMinusOneIsInvalid, 
	IEnumerable<PIDL^>, IEquatable<PIDL^>, IEquatable<IntPtr>
```

**F#**<br />
``` F#
[<SealedAttribute>]
type PIDL =  
    class
        inherit SafeHandleZeroOrMinusOneIsInvalid
        interface IEnumerable<PIDL>
        interface IEquatable<PIDL>
        interface IEquatable<IntPtr>
    end
```

The PIDL type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL__ctor_2">PIDL(String)</a></td><td>
Initializes a new instance of the PIDL class from a file or folder path.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL__ctor">PIDL(PIDL)</a></td><td>
Initializes a new instance of the PIDL class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL__ctor_1">PIDL(IntPtr, Boolean, Boolean)</a></td><td>
Initializes a new instance of the PIDL class.</td></tr></table>&nbsp;
<a href="#pidl-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_PIDL_IsEmpty">IsEmpty</a></td><td>
Gets a value indicating whether this ITEMIDLIST is empty.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_PIDL_LastId">LastId</a></td><td>
Gets the last SHITEMID in this ITEMIDLIST.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_PIDL_Parent">Parent</a></td><td>
Gets an ITEMIDLIST with the last ID removed. If this is the topmost ID, a clone of the current is returned.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_PIDL_Size">Size</a></td><td>
Gets the size, in bytes, of this ITEMIDLIST.</td></tr></table>&nbsp;
<a href="#pidl-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_Append">Append</a></td><td>
Appends the specified PIDL to the current ITEMIDLIST.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_Combine">Combine</a></td><td>
Combines the specified PIDL instances to create a new one.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_Equals_1">Equals(IntPtr)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_Equals">Equals(PIDL)</a></td><td>
Indicates whether the current object is equal to another object of the same type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_GetEnumerator">GetEnumerator</a></td><td>
Returns an enumerator that iterates through the collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_Insert">Insert</a></td><td>
Inserts the specified PIDL before the current ITEMIDLIST.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_IsParentOf">IsParentOf</a></td><td>
Determines if this instance is a parent or ancestor of the specified PIDL.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_RemoveLastId">RemoveLastId</a></td><td>
Removes the last identifier from the ITEMIDLIST.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_ToString">ToString()</a></td><td>
Returns a String that represents this PIDL.
 (Overrides Object.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_ToString_1">ToString(ShellItemGetDisplayName)</a></td><td>
Returns a String that represents this PIDL according to the format provided by *displayNameFormat*.</td></tr></table>&nbsp;
<a href="#pidl-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_op_Addition">Addition</a></td><td>
Combines the specified PIDL instances to create a new one.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_op_Explicit">Explicit(PIDL to IntPtr)</a></td><td>
Performs an explicit conversion from PIDL to IntPtr.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_op_Implicit">Implicit(IntPtr to PIDL)</a></td><td>
Performs an implicit conversion from IntPtr to PIDL.</td></tr></table>&nbsp;
<a href="#pidl-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Append__1">Append(PIDL)</a></td><td>
Appends an element to the end of the source collection.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_AsReadOnly__1">AsReadOnly(PIDL)</a></td><td>
Returns a read-only ReadOnlyCollection(T) wrapper for the specified collection.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_CountEmptyItems__1">CountEmptyItems(PIDL)</a></td><td>
Counts the empty items of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_CountNonEmptyItems__1">CountNonEmptyItems(PIDL)</a></td><td>
Counts the non-empty items of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_DistinctBy__2">DistinctBy(PIDL, TKey)(Func(PIDL, TKey))</a></td><td>Overloaded.  
Returns distinct elements from a sequence by using a specified key selector and the default equality comparer to compare values.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_DistinctBy__2_1">DistinctBy(PIDL, TKey)(Func(PIDL, TKey), IEqualityComparer(TKey))</a></td><td>Overloaded.  
Returns distinct elements from a sequence by using a specified key selector and equality comparer to compare values.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Duplicates__1">Duplicates(PIDL)</a></td><td>
Gets all the duplicated values of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ForEach__1">ForEach(PIDL)</a></td><td>
Performs the specified action on each element of the IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GetRandomItem__1">GetRandomItem(PIDL)</a></td><td>
Gets a random element from the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GroupByIntoFirstElement__2">GroupByIntoFirstElement(PIDL, TKey)</a></td><td>
Groups the elements of a sequence according to a specified key selector function and discards all the elements in each group except the first element.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GroupByIntoItemCount__2">GroupByIntoItemCount(PIDL, TKey)</a></td><td>
Groups the elements of a sequence according to a specified key selector function and returns a Dictionary(TKey, TValue) dictionary on which {.key = element} and {.value = element count}.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_GroupByIntoMaxNumberOfElements__2">GroupByIntoMaxNumberOfElements(PIDL, TKey)</a></td><td>
Groups the elements of a sequence according to a specified key selector function and takes the specified amount of elements of each group.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_3">IndexOf(PIDL)(PIDL)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1">IndexOf(PIDL)(IEnumerable(PIDL))</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_4">IndexOf(PIDL)(PIDL, Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_1">IndexOf(PIDL)(IEnumerable(PIDL), Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_5">IndexOf(PIDL)(PIDL, Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOf__1_2">IndexOf(PIDL)(IEnumerable(PIDL), Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based index of the first occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_3">IndexOfAll(PIDL)(PIDL)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1">IndexOfAll(PIDL)(IEnumerable(PIDL))</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_4">IndexOfAll(PIDL)(PIDL, Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_1">IndexOfAll(PIDL)(IEnumerable(PIDL), Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_5">IndexOfAll(PIDL)(PIDL, Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_IndexOfAll__1_2">IndexOfAll(PIDL)(IEnumerable(PIDL), Int32, Int32)</a></td><td>Overloaded.  
Searches for the specified object pattern and returns the zero-based indices of all the occurrence within the entire IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Prepend__1">Prepend(PIDL)</a></td><td>
Prepends an element to the start of the source collection.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Randomize__1">Randomize(PIDL)</a></td><td>
Randomizes the elements of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_RemoveDuplicates__1">RemoveDuplicates(PIDL)</a></td><td>
Removes duplicated values in the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_SplitIntoNumberOfElements__1">SplitIntoNumberOfElements(PIDL)(Int32)</a></td><td>Overloaded.  
Splits the source IEnumerable(T) into secuences with the specified amount of elements.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_SplitIntoNumberOfElements__1_1">SplitIntoNumberOfElements(PIDL)(Int32, Boolean, PIDL)</a></td><td>Overloaded.  
Splits the source IEnumerable(T) into secuences with the specified amount of elements.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_SplitIntoParts__1">SplitIntoParts(PIDL)</a></td><td>
Splits the source IEnumerable(T) into the specified amount of secuences.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ToArray__1">ToArray(PIDL)</a></td><td>
Creates an array from an IEnumerable(T) using the specified transform function.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ToList__1">ToList(PIDL)</a></td><td>
Creates a List(T) from an IEnumerable(T) using the specified transform function.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_ToTreeString__1">ToTreeString(PIDL)</a></td><td>
Transforms an array of string into a string with tree formatting.
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_UniqueDuplicates__1">UniqueDuplicates(PIDL)</a></td><td>
Gets the unique duplicated values of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions_Uniques__1">Uniques(PIDL)</a></td><td>
Gets the unique values of the source IEnumerable(T).
 (Defined by <a href="T_DevCase_Core_Extensions_IEnumerable_IEnumerableExtensions">IEnumerableExtensions</a>.)</td></tr></table>&nbsp;
<a href="#pidl-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Interop_Unmanaged_PIDL_System_Collections_IEnumerable_GetEnumerator">IEnumerable.GetEnumerator</a></td><td /></tr></table>&nbsp;
<a href="#pidl-class">Back to Top</a>

## Remarks
ITEMIDLIST documentation: <a href="https://docs.microsoft.com/en-us/windows/desktop/api/shtypes/ns-shtypes-_itemidlist" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shtypes/ns-shtypes-_itemidlist</a>

 Original source-code: <a href="https://github.com/dahall/Vanara/blob/master/PInvoke/Shell32/ShTypes.PIDL.cs" target="_blank">https://github.com/dahall/Vanara/blob/master/PInvoke/Shell32/ShTypes.PIDL.cs</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pidl As New PIDL("C:\Windows")
Console.WriteLine(pidl.ToString(ShellItemGetDisplayName.DesktopAbsoluteParsing))
pidl.Dispose()
```


## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pidl As PIDL = NativeMethods.ILCreateFromPath("C:\Windows")
Console.WriteLine(pidl.ToString(ShellItemGetDisplayName.DesktopAbsoluteParsing))
pidl.Dispose()
```


## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />