# ToolbarMessages Enumeration
 

The system sends or posts a system-defined message when it communicates with an application. 

 It uses these messages to control the operations of applications and to provide input and other information for applications to process. 

 An application can also send or post system-defined messages. 

 Applications generally use these messages to control the operation of control windows created by using preregistered window classes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ToolbarMessages
```

**VB**<br />
``` VB
Public Enumeration ToolbarMessages
```

**VB Usage**<br />
``` VB Usage
Dim instance As ToolbarMessages
```

**C++**<br />
``` C++
public enum class ToolbarMessages
```

**F#**<br />
``` F#
type ToolbarMessages
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.Null">**Null**</td><td>0</td><td>The Null message performs no operation. 

 An application sends the Null message if it wants to post a message that the recipient window will ignore.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.ButtonCount">**ButtonCount**</td><td>1048</td><td>Retrieves a count of the buttons currently in a ToolBar control. 

`wParam` Must be zero. 

`lParam` Must be zero. 

 Returns: The count of the buttons</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.CommandIdToIndex">**CommandIdToIndex**</td><td>1049</td><td>Retrieves the zero-based index for the button associated with the specified command identifier on a ToolBar control. 

`wParam` Command identifier associated with the button. 

`lParam` Must be zero. 

 Returns: The zero-based index for the button or `-1` if the specified command identifier is invalid.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetCommandId">**SetCommandId**</td><td>1066</td><td>Sets the command identifier of a ToolBar control. 

`wParam` Zero-based index of the button whose command identifier is to be set. 

`lParam` The new Command identifier. 

 Returns: `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.IsButtonEnabled">**IsButtonEnabled**</td><td>1033</td><td>Determines whether the specified button in a ToolBar control is enabled. 

`wParam` Command identifier of the button. 

`lParam` Must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is enabled, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.IsButtonHidden">**IsButtonHidden**</td><td>1036</td><td>Determines whether the specified button in a ToolBar control is hidden. 

`wParam` Command identifier of the button. 

`lParam` Must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is hidden, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.IsButtonPressed">**IsButtonPressed**</td><td>1035</td><td>Determines whether the specified button in a ToolBar control is pressed. 

`wParam` Command identifier of the button. 

`lParam` Must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is pressed, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.EnableButton">**EnableButton**</td><td>1025</td><td>Enables or disables the specified button in a ToolBar control. 

`wParam` Command identifier of the button to enable or disable. 

`lParam` The `LOWORD` is a `Boolean` value that indicates whether to enable or disable the specified button. 

 If `true` (`True` in Visual Basic), the button is enabled. If `false` (`False` in Visual Basic), the button is disabled. 

 Returns: `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.HideButton">**HideButton**</td><td>1028</td><td>Hides or shows the specified button in a ToolBar control. 

`wParam` Command identifier of the button to hide or show. 

`lParam` The `LOWORD` is a Boolean value that indicates whether to hide or show the specified button. 

 If `true` (`True` in Visual Basic), the button is hidden. If `false` (`False` in Visual Basic), the button is shown. 

 The `HIWORD` must be zero. 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.DeleteButton">**DeleteButton**</td><td>1046</td><td>Deletes a button from a ToolBar control. 

`wParam` Zero-based index of the button to delete. 

`lParam` Must be zero. 

 Returns: `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetButton">**GetButton**</td><td>1047</td><td>Retrieves information about the specified button in a ToolBar control. 

`wParam` Zero-based index of the button for which to retrieve information. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton">ToolBarButton</a> structure that receives the button information. 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetButtonInfoAnsi">**GetButtonInfoAnsi**</td><td>1089</td><td>Retrieves extended information for a button in a ToolBar control. 

`wParam` Command identifier of the button. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA">ToolBarButtonInfoA</a> structure that receives the button information. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_SizeOfStruct">SizeOfStruct</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Mask">Mask</a> members of this structure must be filled in prior to sending this message. 

 Returns: The zero-based index of the button, or `-1` if an error occurs.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetButtonInfoUnicode">**GetButtonInfoUnicode**</td><td>1087</td><td>Retrieves extended information for a button in a ToolBar control. 

`wParam` Command identifier of the button. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW">ToolBarButtonInfoW</a> structure that receives the button information. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_SizeOfStruct">SizeOfStruct</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_Mask">Mask</a> members of this structure must be filled in prior to sending this message. 

 Returns: The zero-based index of the button, or `-1` if an error occurs.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetButtonTextAnsi">**GetButtonTextAnsi**</td><td>1069</td><td>Retrieves the display text (in `ANSI`) of a button on a ToolBar control. 

`wParam` Command identifier of the button whose text is to be retrieved. 

`lParam` A pointer to a buffer that receives the button text. 

 Returns: The length, in characters, of the string pointed to by lParam. The length does not include the terminating null character. If unsuccessful, the return value is `-1`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetButtonTextUnicode">**GetButtonTextUnicode**</td><td>1099</td><td>Retrieves the display text (in `Unicode`) of a button on a ToolBar control. 

`wParam` Command identifier of the button whose text is to be retrieved. 

`lParam` A pointer to a buffer that receives the button text. 

 Returns: The length, in characters, of the string pointed to by lParam. The length does not include the terminating null character. If unsuccessful, the return value is `-1`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.InsertButtonAnsi">**InsertButtonAnsi**</td><td>1045</td><td>Inserts a button in a ToolBar control. 

`wParam` Zero-based index of a button. The message inserts the new button to the left of this button. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton">ToolBarButton</a> structure containing information about the button to insert. 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.InsertButtonUnicode">**InsertButtonUnicode**</td><td>1091</td><td>Inserts a button in a ToolBar control. 

`wParam` Zero-based index of a button. The message inserts the new button to the left of this button. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton">ToolBarButton</a> structure containing information about the button to insert. 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetButtonInfoAnsi">**SetButtonInfoAnsi**</td><td>1090</td><td>Sets the information for an existing button in a ToolBar control. 

`wParam` Command identifier of the button. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA">ToolBarButtonInfoA</a> structure that contains the new button information. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_SizeOfStruct">SizeOfStruct</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoA_Mask">Mask</a> members of this structure must be filled in prior to sending this message. 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetButtonInfounicode">**SetButtonInfounicode**</td><td>1088</td><td>Sets the information for an existing button in a ToolBar control. 

`wParam` Command identifier of the button. 

`lParam` A pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW">ToolBarButtonInfoW</a> structure that contains the new button information. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_SizeOfStruct">SizeOfStruct</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButtonInfoW_Mask">Mask</a> members of this structure must be filled in prior to sending this message. 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.MoveButton">**MoveButton**</td><td>1106</td><td>Moves a button from one index to another in a ToolBar control. 

`wParam` Zero-based index of the button to be moved. 

`lParam` Zero-based index where the button will be moved. 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.PressButton">**PressButton**</td><td>1027</td><td>Presses or releases the specified button in a ToolBar control. 

`wParam` Command identifier of the button to press or release. 

`lParam` The LOWORD is a Boolean value that indicates whether to press or release the specified button. If `true` (`True` in Visual Basic), the button is pressed. If `false` (`False` in Visual Basic), the button is released. 

 The HIWORD must be zero 

 Returns: `true` (`True` in Visual Basic) if successful, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.AutoSize">**AutoSize**</td><td>1057</td><td>Causes a toolbar to be resized. 

`wParam` Must be zero. 

`lParam` Must be zero 

 Returns: No return value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetPadding">**SetPadding**</td><td>1111</td><td>Sets the padding for a toolbar control. 

`wParam` Must be zero. 

`lParam` The LOWORD specifies the horizontal padding, in pixels. The HIWORD specifies the vertical padding, in pixels. 

 Returns: Returns a DWORD value that contains the previous horizontal padding in the LOWORD and the previous vertical padding in the HIWORD, in pixels.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetPadding">**GetPadding**</td><td>1110</td><td>Retrieves the padding for a toolbar control. 

`wParam` Must be zero. 

`lParam` Must be zero. 

 Returns: Returns a DWORD value that contains the horizontal padding in the low word and the vertical padding in the high word, in pixels.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.Customize">**Customize**</td><td>1051</td><td>Displays the Customize Toolbar dialog box. 

`wParam` Must be zero. 

`lParam` Must be zero. 

 Returns: No return value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetButtonSize">**GetButtonSize**</td><td>1082</td><td>Retrieves the current width and height of toolbar buttons, in pixels. 

`wParam` Must be zero. 

`lParam` Must be zero. 

 Returns: Returns a DWORD value that contains the width and height values in the low word and high word, respectively.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetIdealSize">**GetIdealSize**</td><td>1123</td><td>Gets the ideal size of the toolbar. 

`wParam` A Boolean that indicates whether to retrieve the ideal height or width of the toolbar. 

 Use `true` (`True` in Visual Basic) to retrieve the ideal height, `false` (`False` in Visual Basic) to retrieve the ideal width. 

`lParam` Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a> structure that receives the height or width at which all buttons would be displayed. 

 If wParam is `true` (`True` in Visual Basic), only the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize_Height">Height</a> member is valid. If wParam is `false` (`False` in Visual Basic), only the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize_Width">Width</a> member is valid. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetMaxSize">**GetMaxSize**</td><td>1107</td><td>Retrieves the total size of all of the visible buttons and separators in the toolbar. 

`wParam` Must be zero. 

`lParam` Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a> structure that receives the size of the items. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetRect">**GetRect**</td><td>1075</td><td>Retrieves the bounding rectangle for a specified toolbar button. 

`wParam` Command identifier of the button. 

`lParam` Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that will receive the bounding rectangle information. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetItemRect">**GetItemRect**</td><td>1053</td><td>Retrieves the bounding rectangle of a button in a toolbar. 

`wParam` Zero-based index of the button for which to retrieve information. 

`lParam` Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that receives the client coordinates of the bounding rectangle. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetListGap">**SetListGap**</td><td>1120</td><td>Sets the distance between the toolbar buttons on a specific toolbar. 

`wParam` The gap, in pixels, between buttons on the toolbar. 

`lParam` Ignored. 

 Returns: No return value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.MarkButton">**MarkButton**</td><td>1030</td><td>Sets the highlight state of a given button in a toolbar control. 

`wParam` Command identifier for a toolbar button. 

`lParam` The LOWORD is a Boolean that indicates the new highlight state. If `true` (`True` in Visual Basic), the button is highlighted. If `false` (`False` in Visual Basic), the button is set to its default state. 

 The HIWORD must be zero 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetButtonSize">**SetButtonSize**</td><td>1055</td><td>Sets the size of buttons on a toolbar. 

`wParam` Must be zero. 

`lParam` The LOWORD specifies the width, in pixels, of the buttons. The HIWORD specifies the height, in pixels, of the buttons. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.Indeterminate">**Indeterminate**</td><td>1029</td><td>Sets or clears the indeterminate state of the specified button in a toolbar. 

`wParam` Command identifier of the button whose indeterminate state is to be set or cleared. 

`lParam` The LOWORD is a Boolean that indicates whether to set or clear the indeterminate state. If `true` (`True` in Visual Basic), the indeterminate state is set. If `false` (`False` in Visual Basic), the state is cleared. 

 The HIWORD must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetButtonWidth">**SetButtonWidth**</td><td>1083</td><td>Sets the minimum and maximum button widths in the toolbar control. 

`wParam` Must be zero. 

`lParam` The LOWORD specifies the minimum button width, in pixels. Toolbar buttons will never be narrower than this value. 

 The HIWORD specifies the maximum button width, in pixels. If button text is too wide, the control displays it with ellipsis points. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetBoundingSize">**SetBoundingSize**</td><td>1117</td><td>Sets the bounding size for a multi-column toolbar control. 

`wParam` Must be zero. 

`lParam` A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize">NativeSize</a> structure whose <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize_Height">Height</a> member contains the bounding height. The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativeSize_Width">Width</a> member is ignored. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetState">**SetState**</td><td>1041</td><td>Sets the state for the specified button in a toolbar. 

`wParam` Command identifier of the button. 

`lParam` The LOWORD is a combination of values listed in <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ToolbarButtonStates">ToolbarButtonStates</a> enumeration. The HIWORD must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetState">**GetState**</td><td>1042</td><td>Retrieves information about the state of the specified button in a toolbar, such as whether it is enabled, pressed, or checked. 

`wParam` Command identifier of the button for which to retrieve information. 

`lParam` Must be zero. 

 Returns: Returns the button state information if successful, or -1 otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.IsButtonChecked">**IsButtonChecked**</td><td>1034</td><td>Determines whether the specified button in a toolbar is checked. 

`wParam` Command identifier of the button. 

`lParam` Must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is checked, zero otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.IsButtonHighlighted">**IsButtonHighlighted**</td><td>1038</td><td>Checks the highlight state of a toolbar button. 

`wParam` Command identifier of the button. 

`lParam` Must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is highlighted, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.IsButtonIndeterminate">**IsButtonIndeterminate**</td><td>1037</td><td>Determines whether the specified button in a toolbar is indeterminate. 

`wParam` Command identifier of the button. 

`lParam` Must be zero. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is indeterminate, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.AddButtonsAnsi">**AddButtonsAnsi**</td><td>1044</td><td>Adds one or more buttons to a toolbar. 

`wParam` Number of buttons to add. 

`lParam` An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton">ToolBarButton</a> structures that contain information about the buttons to add. 

 There must be the same number of elements in the array as buttons specified by wParam. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is indeterminate, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.AddButtonsUnicode">**AddButtonsUnicode**</td><td>1092</td><td>Adds one or more buttons to a toolbar. 

`wParam` Number of buttons to add. 

`lParam` An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ToolBarButton">ToolBarButton</a> structures that contain information about the buttons to add. 

 There must be the same number of elements in the array as buttons specified by wParam. 

 Returns: Returns `true` (`True` in Visual Basic) if the button is indeterminate, `false` (`False` in Visual Basic) otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.HitTest">**HitTest**</td><td>1093</td><td>Determines where a point lies in a toolbar control. 

`wParam` Must be zero. 

`lParam` A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> structure that contains the x-coordinate of the hit test in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint_X">X</a> member and the y-coordinate of the hit test in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint_Y">Y</a> member. 

 The coordinates are relative to the toolbar's client area. 

 Returns: Returns an integer value. 

 If the return value is zero or a positive value, it is the zero-based index of the nonseparator item in which the point lies. 

 If the return value is negative, the point does not lie within a button. 

 The absolute value of the return value is the index of a separator item or the nearest nonseparator item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.SetImageList">**SetImageList**</td><td>1072</td><td>Sets the image list that the toolbar uses to display buttons that are in their default state. 

`wParam` The index of the list. 

 If you use only one image list, or an earlier version of the common controls, set wParam to zero. 

`lParam` Handle to the image list to set. 

 If this parameter is Zero, no images are displayed in the buttons. 

 Returns: Returns the handle to the image list previously used to display buttons in their default state, or Zero if no image list was previously set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetImageList">**GetImageList**</td><td>1073</td><td>Retrieves the image list that a toolbar control uses to display buttons in their default state. 

 A toolbar control uses this image list to display buttons when they are not hot or disabled. 

`wParam` Must be zero. 

`lParam` Must be zero. 

 Returns: Returns the handle to the image list, or Zero if no image list is set.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetImageListCount">**GetImageListCount**</td><td>1122</td><td>Gets the number of image lists associated with the toolbar. 

`wParam` Must be zero. 

`lParam` Must be zero. 

 Returns: Returns the number of image lists.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetBitmapIndex">**GetBitmapIndex**</td><td>1068</td><td>Retrieves the index of the bitmap associated with a button in a toolbar. 

`wParam` Command identifier of the button whose bitmap index is to be retrieved. 

`lParam` Must be zero. 

 Returns: Returns the index of the bitmap if successful, or zero otherwise.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ToolbarMessages.GetBitmapFlags">**GetBitmapFlags**</td><td>1065</td><td>Retrieves the flags that describe the type of bitmap to be used. 

`wParam` Must be zero. 

`lParam` Must be zero. 

 Returns: Returns a DWORD value that describes the type of bitmap that should be used. 

 If this return value has the TBBF_LARGE flag set, applications should use large bitmaps (24 x 24); otherwise, applications should use small bitmaps (16 x 16). All other bits are reserved.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ff486063%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ff486063%28v=vs.85%29.aspx</a>

 The definitions can be found in the Windows SDK file: CommCtrl.h

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />