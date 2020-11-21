# EditControlMessages Enumeration
 

The system sends or posts a message when it communicates with an edit-control. 

 An edit-control is an editable control such a TextBox.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum EditControlMessages
```

**VB**<br />
``` VB
Public Enumeration EditControlMessages
```

**VB Usage**<br />
``` VB Usage
Dim instance As EditControlMessages
```

**C++**<br />
``` C++
public enum class EditControlMessages
```

**F#**<br />
``` F#
type EditControlMessages
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.Null">**Null**</td><td>0</td><td>The Null message performs no operation. 

 An application sends the Null message if it wants to send a message that the recipient window will ignore.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.SetSel">**SetSel**</td><td>177</td><td>Selects a range of characters in an edit control. You can send this message to either an edit control or a rich edit control. 

`wParam` The starting character position of the selection 

`lParam` The ending character position of the selection</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.ReplaceSel">**ReplaceSel**</td><td>194</td><td>Replaces the selected text in an edit control or a rich edit control with the specified text. 

`wParam` Specifies whether the replacement operation can be undone. 

 If this is `true` (`True` in Visual Basic), the operation can be undone. If this is `false` (`False` in Visual Basic), the operation cannot be undone. 

`lParam` A pointer to a null-terminated string containing the replacement text.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.SetCueBanner">**SetCueBanner**</td><td>5377</td><td>Sets the textual cue, or tip, that is displayed by the edit control to prompt the user for information. 

`wParam``true` (`True` in Visual Basic) if the cue banner should show even when the edit control has focus; otherwise, `false` (`False` in Visual Basic). 

`false` (`False` in Visual Basic) is the default behavior—the cue banner disappears when the user clicks in the control. 

`lParam` A pointer to a Unicode string that contains the text to display as the textual cue.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.CanUndo">**CanUndo**</td><td>198</td><td>Determines whether there are any actions in an edit control's undo queue. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` Not used; must be zero 

`lParam` Not used; must be zero</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.CharFromPos">**CharFromPos**</td><td>215</td><td>Gets information about the character closest to a specified point in the client area of an edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` This parameter is not used 

`lParam` The coordinates of a point in the control's client area. 

 The coordinates are in screen units and are relative to the upper-left corner of the control's client area</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.EmptyUndoBuffer">**EmptyUndoBuffer**</td><td>205</td><td>Resets the undo flag of an edit control. 

 The undo flag is set whenever an operation within the edit control can be undone. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` Not used; must be zero 

`lParam` Not used; must be zero</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.GetLimitText">**GetLimitText**</td><td>213</td><td>Gets the current text limit for an edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` Not used; must be zero 

`lParam` Not used; must be zero</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.GetLine">**GetLine**</td><td>196</td><td>Copies a line of text from an edit control and places it in a specified buffer. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` The zero-based index of the line to retrieve from a multiline edit control. 

 A value of zero specifies the topmost line. 

 This parameter is ignored by a single-line edit control. 

`lParam` A pointer to the buffer that receives a copy of the line. 

 Before sending the message, set the first word of this buffer to the size, in TCHARs, of the buffer. 

 For ANSI text, this is the number of bytes; for Unicode text, this is the number of characters. 

 The size in the first word is overwritten by the copied line.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.GetLineCount">**GetLineCount**</td><td>186</td><td>Gets the number of lines in a multiline edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` Not used; must be zero 

`lParam` Not used; must be zero</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.LineFromChar">**LineFromChar**</td><td>201</td><td>Gets the index of the line that contains the specified character index in a multiline edit control. 

 A character index is the zero-based index of the character from the beginning of the edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` The character index of the character contained in the line whose number is to be retrieved. 

 If this parameter is –1, LineFromChar retrieves either the line number of the current line (the line containing the caret) or, if there is a selection, the line number of the line containing the beginning of the selection 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.LineIndex">**LineIndex**</td><td>187</td><td>Gets the character index of the first character of a specified line in a multiline edit control. 

 A character index is the zero-based index of the character from the beginning of the edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` The zero-based line number. 

 A value of –1 specifies the current line number (the line that contains the caret). 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.LineLength">**LineLength**</td><td>193</td><td>Retrieves the length, in characters, of a line in an edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` The character index of a character in the line whose length is to be retrieved. 

 If this parameter is greater than the number of characters in the control, the return value is zero. 

 This parameter can be –1. In this case, the message returns the number of unselected characters on lines containing selected characters. 

 For example, if the selection extended from the fourth character of one line through the eighth character from the end of the next line, the return value would be 10 (three characters on the first line and seven on the next). 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.LineScroll">**LineScroll**</td><td>182</td><td>Scrolls the text in a multiline edit control. 

`wParam` Edit controls: The number of characters to scroll horizontally. 

 Rich edit controls: This parameter is not used; it must be zero. 

`lParam` The number of lines to scroll.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.PosFromChar">**PosFromChar**</td><td>214</td><td>Retrieves the client area coordinates of a specified character in an edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` Rich Edit 1.0 and 3.0: A pointer to a POINTL structure that receives the client area coordinates of the character. The coordinates are in screen units and are relative to the upper-left corner of the control's client area. 

 Edit controls and Rich Edit 2.0: The zero-based index of the character 

`lParam` Rich Edit 1.0 and 3.0: The zero-based index of the character. 

 Edit controls and Rich Edit 2.0: This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.Scroll">**Scroll**</td><td>181</td><td>Scrolls the text vertically in a multiline edit control. 

 This message is equivalent to sending a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_VScroll</a> message to the edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` The action the scroll bar is to take. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.ScrollCaret">**ScrollCaret**</td><td>183</td><td>Scrolls the caret into view in an edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` This parameter is reserved. It should be set to zero. 

`lParam` This parameter is reserved. It should be set to zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.SetLimitText">**SetLimitText**</td><td>197</td><td>Sets the text limit of an edit control. 

 The text limit is the maximum amount of text, in `TCHARs`, that the user can type into the edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` The maximum number of `TCHARs` the user can enter. 

 For ANSI text, this is the number of bytes; for Unicode text, this is the number of characters. 

 This number does not include the terminating null character. 

 Rich edit controls: If this parameter is zero, the text length is set to 64,000 characters 

 If this parameter is zero, the text length is set to 0x7FFFFFFE characters for single-line edit controls or -1 for multiline edit controls. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.SetReadonly">**SetReadonly**</td><td>207</td><td>Sets or removes the read-only style (`ES_READONLY`) of an edit control. 

 You can send this message to either an edit control or a rich edit control. 

`wParam` Specifies whether to set or remove the `ES_READONLY` style. 

 A value of `true` (`True` in Visual Basic) sets the `ES_READONLY` style; a value of `false` (`False` in Visual Basic) removes the `ES_READONLY` style. 

`lParam` This parameter is not used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.Undo">**Undo**</td><td>199</td><td>This message undoes the last edit control operation in the control's undo queue. 

 You can send this message to either an edit control or a rich edit control 

`wParam` Not used; must be zero 

`lParam` Not used; must be zero</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.EditControlMessages.SetMargins">**SetMargins**</td><td>211</td><td>Sets the widths of the left and right margins for an edit control. 

 The message redraws the control to reflect the new margins. 

 You can send this message to either an edit control or a rich edit control 

`wParam` The margins to set. 

`lParam` The LOWORD specifies the new width of the left margin, in pixels. This value is ignored if wParam does not include EC_LEFTMARGIN 

 The HIWORD specifies the new width of the right margin, in pixels. This value is ignored if wParam does not include EC_RIGHTMARGIN</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ff485923%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ff485923%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />