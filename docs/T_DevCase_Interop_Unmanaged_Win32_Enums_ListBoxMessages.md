# ListBoxMessages Enumeration
 

The system sends or posts a system-defined message when it communicates with an application. 

 It uses these messages to control the operations of applications and to provide input and other information for applications to process. 

 An application can also send or post system-defined messages. 

 Applications generally use these messages to control the operation of control windows created by using preregistered window classes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ListBoxMessages
```

**VB**<br />
``` VB
Public Enumeration ListBoxMessages
```

**VB Usage**<br />
``` VB Usage
Dim instance As ListBoxMessages
```

**C++**<br />
``` C++
public enum class ListBoxMessages
```

**F#**<br />
``` F#
type ListBoxMessages
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.Null">**Null**</td><td>0</td><td>The Null message performs no operation. 

 An application sends the Null message if it wants to post a message that the recipient window will ignore.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetSel">**GetSel**</td><td>391</td><td>Gets the selection state of a ListBox item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.SetSel">**SetSel**</td><td>389</td><td>Selects an item in a multiple-selection ListBox and, if necessary, scrolls the item into view.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetSelItems">**GetSelItems**</td><td>401</td><td>Fills a buffer with an array of integers that specify the item numbers of selected items in a multiple-selection ListBox.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetSelCount">**GetSelCount**</td><td>400</td><td>Gets the total number of selected items in a multiple-selection ListBox.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetCurSel">**GetCurSel**</td><td>392</td><td>Gets the index of the currently selected item, if any, in a single-selection ListBox</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.SetCurSel">**SetCurSel**</td><td>390</td><td>Selects a string and scrolls it into view, if necessary. 

 When the new string is selected, the ListBox removes the highlight from the previously selected string.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.SelectString">**SelectString**</td><td>396</td><td>Use this message only with single-selection list boxes. 

 You cannot use it to set or remove a selection in a multiple-selection ListBox.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.FindString">**FindString**</td><td>399</td><td>Finds the first string in a ListBox that begins with the specified string.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetCount">**GetCount**</td><td>395</td><td>Gets the number of items in a ListBox.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetText">**GetText**</td><td>393</td><td>Gets a string from a ListBox.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.ResetContent">**ResetContent**</td><td>388</td><td>Removes all items from a ListBox.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetHorizontalExtent">**GetHorizontalExtent**</td><td>403</td><td>Gets the width, in pixels, that a ListBox can be scrolled horizontally (the scrollable width) if the ListBox has a horizontal scroll bar.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.SetHorizontalExtent">**SetHorizontalExtent**</td><td>404</td><td>Sets the width, in pixels, by which a ListBox can be scrolled horizontally (the scrollable width). 

 If the width of the list box is smaller than this value, the horizontal scroll bar horizontally scrolls items in the list box. 

 If the width of the list box is equal to or greater than this value, the horizontal scroll bar is hidden.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetTopIndex">**GetTopIndex**</td><td>398</td><td>Gets the index of the first visible item in a ListBox. 

 Initially the item with index 
```
0
```
 is at the top of the ListBox, but if the ListBox contents have been scrolled another item may be at the top. 

 The first visible item in a multiple-column list box is the top-left item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.SetTopIndex">**SetTopIndex**</td><td>407</td><td>Ensures that the specified item in a ListBox is visible.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.InsertString">**InsertString**</td><td>385</td><td>Inserts a string or item data into a ListBox. 

 Unlike the AddString message, the InsertString message does not cause a list with the `LBS_SORT` style to be sorted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.AddString">**AddString**</td><td>384</td><td>Adds a string to a ListBox. If the ListBox does not have the `LBS_SORT` style, the string is added to the end of the list. 

 Otherwise, the string is inserted into the list and the list is sorted.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.DeleteString">**DeleteString**</td><td>386</td><td>Deletes a string in a ListBox.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.GetItemData">**GetItemData**</td><td>409</td><td>Gets the application-defined value associated with the specified ListBox item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ListBoxMessages.SetItemData">**SetItemData**</td><td>410</td><td>Sets a value associated with the specified item in a ListBox item.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ff485967%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ff485967%28v=vs.85%29.aspx</a>

 The definitions can be found in the Windows SDK file: WinUser.h

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />