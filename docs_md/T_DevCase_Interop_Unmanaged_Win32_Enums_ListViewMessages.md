# ListViewMessages Enumeration
 

The system sends or posts a system-defined message when it communicates with an application. 

 It uses these messages to control the operations of applications and to provide input and other information for applications to process. 

 An application can also send or post system-defined messages. 

 Applications generally use these messages to control the operation of control windows created by using preregistered window classes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ListViewMessages
```

**VB**<br />
``` VB
Public Enumeration ListViewMessages
```

**VB Usage**<br />
``` VB Usage
Dim instance As ListViewMessages
```

**C++**<br />
``` C++
public enum class ListViewMessages
```

**F#**<br />
``` F#
type ListViewMessages
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.Null">**Null**</td><td>0</td><td>The Null message performs no operation. 

 An application sends the Null message if it wants to post a message that the recipient window will ignore.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.GetHeader">**GetHeader**</td><td>4127</td><td>Gets the handle to the header control used by a ListView control. 

`wParam` Must be zero. 

`lParam` Must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.GetView">**GetView**</td><td>4239</td><td>Retrieves the current view of a ListView control. 

`wParam` Must be zero. 

`lParam` Must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.EnsureVisible">**EnsureVisible**</td><td>4115</td><td>Ensures that a ListViewItem is either entirely or partially visible, scrolling the ListView control if necessary. 

`wParam` The index of the ListViewItem. 

`lParam` A value specifying whether the item must be entirely visible. 

 If this parameter is `true` (`True` in Visual Basic), no scrolling occurs if the item is at least partially visible.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.DeleteItem">**DeleteItem**</td><td>4104</td><td>Removes an item from a ListView control. 

`wParam` The index of the ListViewItem to delete. 

`lParam` Must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.DeleteAllItems">**DeleteAllItems**</td><td>4105</td><td>Removes all items from a ListView control. 

`wParam` Must be zero. 

`lParam` Must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.DeleteColumn">**DeleteColumn**</td><td>4124</td><td>Removes a ColumnHeader from a ListView control. 

`wParam` The index of the column to delete 

`lParam` Must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.GetItemCount">**GetItemCount**</td><td>4100</td><td>Retrieves the number of items in a ListView control. 

`wParam` Must be zero. 

`lParam` Must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.RedrawItems">**RedrawItems**</td><td>4117</td><td>Forces a ListView control to redraw a range of items. 

`wParam` Index of the first item to redraw. 

`lParam` Index of the last item to redraw.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.Scroll">**Scroll**</td><td>4116</td><td>Scrolls the content of a ListView control. 

`wParam` Value that specifies the amount of horizontal scrolling, in pixels, relative to the current position of the list view content. 

 If the list-view control is in list view, this value is rounded up to the nearest number of pixels that form a whole column. 

`lParam` Value that specifies the amount of vertical scrolling, in pixels, relative to the current position of the list view content.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.SetColumnWidth">**SetColumnWidth**</td><td>4126</td><td>Changes the width of a ColumnHeader in report-view mode or the width of all columns in list-view mode 

`wParam` Zero-based index of a valid column. 

 For list-view mode, this parameter must be set to zero. 

`lParam` New width of the column, in pixels.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.SetView">**SetView**</td><td>4238</td><td>Sets the view of a ListView control. 

`wParam` A value that specifies the new view. 

`lParam` Must be zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListViewMessages.SortItems">**SortItems**</td><td>4144</td><td>Uses an application-defined comparison function to sort the items of a ListView control. 

`wParam` Application-defined value that is passed to the comparison function. 

`lParam` Pointer to the application-defined comparison function. 

 The comparison function is called during the sort operation each time the relative order of two list items needs to be compared.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb774937%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb774937%28v=vs.85%29.aspx</a>

 The definitions can be found in the Windows SDK file: CommCtrl.h

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />