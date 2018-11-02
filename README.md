# JUCE-colourID-list
A handy list of all the colour IDs used in JUCE LookAndFeel classes :loud_sound: :woman_artist: :man_artist:

LAF Components
*[AlertWindow](AlertWindow)
*AudioDeviceSelectorComponentMethods
*BubbleComponent
*Button
*CallOutBox
*ComboBox
*ConcertinaPanel
*DocumentWindow
*FileBrowserComponent
*FilenameComponent
*GroupComponent
*ImageButton
*KeyMappingEditorComponentMethods
*Label
*LassoComponentMethods
*PopupMenu
*ProgressBar
*PropertyComponent
*ResizableWindow
*ScrollBar
*SidePanel
*Slider
*StretchableLayoutResizerBar
*TabbedButtonBar
*TableHeaderComponent
*TextEditor
*Toolbar
*TooltipWindow
*TreeView


###AlertWindow

```c++
AlertWindow::backgroundColourId = 0x1001800 //The background colour for the window.
AlertWindow::textColourId       = 0x1001810 //The colour for the text.
AlertWindow::outlineColourId    = 0x1001820 //An optional colour to use to draw a border around the window.
```

BooleanPropertyComponent
```c++
BooleanPropertyComponent::backgroundColourId = 0x100e801 //The colour to fill the background of the button area.
BooleanPropertyComponent::outlineColourId    = 0x100e803 //The colour to use to draw an outline around the text area.
```

BubbleComponent
```c++
BubbleComponent::backgroundColourId = 0x1000af0 //A background colour to fill the bubble with. 
BubbleComponent::outlineColourId    = 0x1000af1 //The colour to use for an outline around the bubble. 
```

CaretComponent
```c++
CaretComponent::caretColourId = 0x1000204 //The colour with which to draw the caret.
```

CodeEditorComponent
```c++
CodeEditorComponent::backgroundColourId     = 0x1004500 //A colour to use to fill the editor's background.
CodeEditorComponent::highlightColourId      = 0x1004502 //The colour to use for the highlighted background under selected text.
CodeEditorComponent::defaultTextColourId    = 0x1004503 //The colour to use for text when no syntax colouring is enabled.
CodeEditorComponent::lineNumberBackgroundId = 0x1004504 //The colour to use for filling the background of the line-number gutter.
CodeEditorComponent::lineNumberTextId       = 0x1004505 //The colour to use for drawing the line numbers.
```

ColourSelector
```c++
ColourSelector::backgroundColourId = 0x1007000 //The colour used to fill the component's background.
ColourSelector::labelTextColourId  = 0x1007001 //The colour used for the labels next to the sliders.
```

ComboBox
```c++
ComboBox::backgroundColourId     = 0x1000b00 //The background colour to fill the box with. 
ComboBox::textColourId           = 0x1000a00 //The colour for the text in the box. 
ComboBox::outlineColourId        = 0x1000c00 //The colour for an outline around the box. 
ComboBox::buttonColourId         = 0x1000d00 //The base colour for the button (a LookAndFeel class will probably use variations on this). 
ComboBox::arrowColourId          = 0x1000e00 //The colour for the arrow shape that pops up the menu 
ComboBox::focusedOutlineColourId = 0x1000f00 //The colour that will be used to draw a box around the edge of the component when it has focus. 
```

DirectoryContentsDisplayComponent
```c++
DirectoryContentsDisplayComponent::highlightColourId       = 0x1000540 //The colour to use to fill a highlighted row of the list. 
DirectoryContentsDisplayComponent::textColourId            = 0x1000541 //The colour for the text. 
DirectoryContentsDisplayComponent::highlightedTextColourId = 0x1000542 //The colour with which to draw the text in highlighted sections. 
```

DocumentWindow
```c++
DocumentWindow::textColourId = 0x1005701 //The colour to draw any text with. It's up to the look and feel class how this is used. 
```

DrawableButton
```c++
DrawableButton::textColourId         = 0x1004010 //The colour to use for the button's text label. 
DrawableButton::textColourOnId       = 0x1004013 //The colour to use for the button's text when the button's toggle state is "on". 
DrawableButton::backgroundColourId   = 0x1004011 //The colour used to fill the button's background (when the button is toggled 'off'). Note that if you use the ImageOnButtonBackground style, you should use TextButton::buttonColourId to change the button's colour. 
DrawableButton::backgroundOnColourId = 0x1004012 //The colour used to fill the button's background (when the button is toggled 'on'). Note that if you use the ImageOnButtonBackground style, you should use TextButton::buttonOnColourId to change the button's colour. 
```

FileBrowserComponent
```c++
FileBrowserComponent::currentPathBoxBackgroundColourId = 0x1000640 //The colour to use to fill the background of the current path ComboBox. 
FileBrowserComponent::currentPathBoxTextColourId       = 0x1000641 //The colour to use for the text of the current path ComboBox. 
FileBrowserComponent::currentPathBoxArrowColourId      = 0x1000642 //The colour to use to draw the arrow of the current path ComboBox. 
FileBrowserComponent::filenameBoxBackgroundColourId    = 0x1000643 //The colour to use to fill the background of the filename TextEditor. 
FileBrowserComponent::filenameBoxTextColourId          = 0x1000644 //The colour to use for the text of the filename TextEditor. 
```

FileChooserDialogBox
```c++
FileChooserDialogBox::titleTextColourId = 0x1000850 //The colour to use to draw the box's title. 
```

FileSearchPathListComponent
```c++
FileSearchPathListComponent::backgroundColourId = 0x1004100 //The background colour to fill the component with Make this transparent if you don't want the background to be filled. 
```

GroupComponent
```c++
GroupComponent::outlineColourId            = 0x1005400 //The colour to use for drawing the line around the edge. 
GroupComponent::GroupComponenttextColourId = 0x1005410 //The colour to use to draw the text label. 
```

HyperlinkButton
```c++
HyperlinkButton::textColourId = 0x1001f00 //The colour to use for the URL text. 
```

KeyMappingEditorComponent
```c++
KeyMappingEditorComponent::backgroundColourId = 0x100ad00 //The background colour to fill the editor background.
KeyMappingEditorComponent::textColourId       = 0x100ad01 //The colour for the text.
```

Label
```c++
Label::backgroundColourId            = 0x1000280 //The background colour to fill the label with.
Label::textColourId                  = 0x1000281 //The colour for the text.
Label::outlineColourId               = 0x1000282 //An optional colour to use to draw a border around the label. Leave this transparent to not have an outline.
Label::backgroundWhenEditingColourId = 0x1000283 //The background colour when the label is being edited.
Label::textWhenEditingColourId       = 0x1000284 //The colour for the text when the label is being edited.
Label::outlineWhenEditingColourId    = 0x1000285 //An optional border colour when the label is being edited.
```

LassoComponent
```c++
LassoComponent::lassoFillColourId    = 0x1000440 //The colour to fill the lasso rectangle with.
LassoComponent::lassoOutlineColourId = 0x1000441 //The colour to draw the outline with.
```

ListBox
```c++
ListBox::backgroundColourId = 0x1002800 //The background colour to fill the list with. Make this transparent if you don't want the background to be filled. 
ListBox::outlineColourId    = 0x1002810 //An optional colour to use to draw a border around the list. Make this transparent to not have an outline. 
ListBox::textColourId       = 0x1002820 //The preferred colour to use for drawing text in the listbox. 
```

MidiKeyboardComponent
```c++
MidiKeyboardComponent::whiteNoteColourId              = 0x1005000
MidiKeyboardComponent::blackNoteColourId              = 0x1005001
MidiKeyboardComponent::keySeparatorLineColourId       = 0x1005002
MidiKeyboardComponent::mouseOverKeyOverlayColourId    = 0x1005003 //This colour will be overlaid on the normal note colour.
MidiKeyboardComponent::keyDownOverlayColourId         = 0x1005004 //This colour will be overlaid on the normal note colour.
MidiKeyboardComponent::textLabelColourId              = 0x1005005
MidiKeyboardComponent::upDownButtonBackgroundColourId = 0x1005006
MidiKeyboardComponent::upDownButtonArrowColourId      = 0x1005007
MidiKeyboardComponent::shadowColourId                 = 0x1005008
```

PopupMenu
```c++
PopupMenu::backgroundColourId            = 0x1000700 //The colour to fill the menu's background with. 
PopupMenu::textColourId                  = 0x1000600 //The colour for normal menu item text, (unless the colour is specified when the item is added). 
PopupMenu::headerTextColourId            = 0x1000601 //The colour for section header item text (see the addSectionHeader() method). 
PopupMenu::highlightedBackgroundColourId = 0x1000900 //The colour to fill the background of the currently highlighted menu item. 
PopupMenu::highlightedTextColourId       = 0x1000800 //The colour to use for the text of the currently highlighted item. 
```

ProgressBar
```c++
ProgressBar::backgroundColourId = 0x1001900 //The background colour, behind the bar. 
ProgressBar::foregroundColourId = 0x1001a00 //The colour to use to draw the bar itself. LookAndFeel classes will probably use variations on this colour. 
```

PropertyComponent
```c++
PropertyComponent::backgroundColourId = 0x1008300 //The background colour to fill the component with. 
PropertyComponent::labelTextColourId  = 0x1008301 //The colour for the property's label text. 
```

ResixeableWindows
```c++
ResizableWindow::backgroundColourId = 0x1005700 //A colour to use to fill the window's background. 
```

Scrollbar
```c++
ScrollBar::backgroundColourId = 0x1000300    //The background colour of the scrollbar. 
ScrollBar::thumbColourId      = 0x1000400    //A base colour to use for the thumb. The look and feel will probably use variations on this colour. 
ScrollBar::trackColourId      = 0x1000401     //A base colour to use for the slot area of the bar. The look and feel will probably use variations on this colour. 
```

SidePanel
```c++
SidePanel::backgroundColour          = 0x100f001
SidePanel::titleTextColour           = 0x100f002
SidePanel::shadowBaseColour          = 0x100f003
SidePanel::dismissButtonNormalColour = 0x100f004
SidePanel::dismissButtonOverColour   = 0x100f004
SidePanel::dismissButtonDownColour   = 0x100f005
```

Slider
```c++
Slider::backgroundColourId          = 0x1001200 //A colour to use to fill the slider's background. 
Slider::thumbColourId               = 0x1001300 //The colour to draw the thumb with. It's up to the look and feel class how this is used. 
Slider::trackColourId               = 0x1001310 //The colour to draw the groove that the thumb moves along. 
Slider::rotarySliderFillColourId    = 0x1001311 //For rotary sliders, this colour fills the outer curve. 
Slider::rotarySliderOutlineColourId = 0x1001312 //For rotary sliders, this colour is used to draw the outer curve's outline. 
Slider::textBoxTextColourId         = 0x1001400 //The colour for the text in the text-editor box used for editing the value. 
Slider::textBoxBackgroundColourId   = 0x1001500 //The background colour for the text-editor box. 
Slider::textBoxHighlightColourId    = 0x1001600 //The text highlight colour for the text-editor box. 
Slider::textBoxOutlineColourId      = 0x1001700 //The colour to use for a border around the text-editor box. 
```

TabbedButtonBar
```c++
TabbedButtonBar::tabOutlineColourId   = 0x1005812 //The colour to use to draw an outline around the tabs.  
TabbedButtonBar::tabTextColourId      = 0x1005813 //The colour to use to draw the tab names. If this isn't specified, the look and feel will choose an appropriate colour. 
TabbedButtonBar::frontOutlineColourId = 0x1005814 //The colour to use to draw an outline around the currently-selected tab.  
TabbedButtonBar::frontTextColourId    = 0x1005815 //The colour to use to draw the currently-selected tab name. If this isn't specified, the look and feel will choose an appropriate colour. 
```

TabbedComponent
```c++
TabbedComponent::backgroundColourId = 0x1005800 //The colour to fill the background behind the tabs. 
TabbedComponent::outlineColourId    = 0x1005801 //The colour to use to draw an outline around the content. (See setOutline)  
```

TableHeaderComponent
```c++
TableHeaderComponent::textColourId       = 0x1003800 //The colour for the text in the header. 
TableHeaderComponent::backgroundColourId = 0x1003810 //The colour of the table header background. It's up to the LookAndFeel how this is used. 
TableHeaderComponent::outlineColourId    = 0x1003820 //The colour of the table header's outline. 
TableHeaderComponent::highlightColourId  = 0x1003830 //The colour of the table header background when the mouse is over or down above the the table header. It's up to the LookAndFeel to use a variant of this colour to destiuish between the down and hover state. 
```

TextButton
```c++
TextButton::buttonColourId   = 0x1000100  //The colour used to fill the button shape (when the button is toggled 'off'). The look-and-feel class might re-interpret this to add effects, etc.
TextButton::buttonOnColourId = 0x1000101  //The colour used to fill the button shape (when the button is toggled  'on'). The look-and-feel class might re-interpret this to add effects, etc.
TextButton::textColourOnId   = 0x1000102  //The colour to use for the button's text when the button's toggle state is "off".
TextButton::textColourOffId  = 0x1000103  //The colour to use for the button's text.when the button's toggle state is "on".
```

TextEditor
```c++
TextEditor::backgroundColourId      = 0x1000200 //The colour to use for the text component's background - this can be transparent if necessary.
TextEditor::textColourId            = 0x1000201 //The colour that will be used when text is added to the editor. Note that because the editor can contain multiple colours, calling this method won't change the colour of existing text - to do that, use the applyColourToAllText() method.
TextEditor::highlightColourId       = 0x1000202 //The colour with which to fill the background of highlighted sections of the text - this can be transparent if you don't want to show any highlighting.
TextEditor::highlightedTextColourId = 0x1000203 //The colour with which to draw the text in highlighted sections.
TextEditor::outlineColourId         = 0x1000205 //If this is non-transparent, it will be used to draw a box around the edge of the component.
TextEditor::focusedOutlineColourId  = 0x1000206 //If this is non-transparent, it will be used to draw a box around the edge of the component when it has focus.
TextEditor::shadowColourId          = 0x1000207 //If this is non-transparent, it'll be used to draw an inner shadow around the edge of the editor.
```

TreeView
```c++
TreeView::backgroundColourId             = 0x1000500 //A background colour to fill the component with. 
TreeView::linesColourId                  = 0x1000501 //The colour to draw the lines with.
TreeView::dragAndDropIndicatorColourId   = 0x1000502 //The colour to use for the drag-and-drop target position indicator. 
TreeView::selectedItemBackgroundColourId = 0x1000503 //The colour to use to fill the background of any selected items. 
TreeView::oddItemsColourId               = 0x1000504 //The colour to use to fill the backround of the odd numbered items. 
TreeView::evenItemsColourId              = 0x1000505  //The colour to use to fill the backround of the even numbered items. 
```

TextPropertyComponent
```c++
TextPropertyComponent::backgroundColourId = 0x100e401 //The colour to fill the background of the text area. 
TextPropertyComponent::textColourId       = 0x100e402 //The colour to use for the editable text. 
TextPropertyComponent::outlineColourId    = 0x100e403 //The colour to use to draw an outline around the text area. 
```

ToggleButton
```c++
ToggleButton::textColourId         = 0x1006501 //The colour to use for the button's text.
ToggleButton::tickColourId         = 0x1006502 //The colour to use for the tick mark.
ToggleButton::tickDisabledColourId = 0x1006503 //The colour to use for the disabled tick mark.
```

Toolbar
```c++
Toolbar::backgroundColourId                = 0x1003200 //A colour to use to fill the toolbar's background. For more control over this, override LookAndFeel::paintToolbarBackground(). 
Toolbar::separatorColourId                 = 0x1003210 //A colour to use to draw the separator lines. 
Toolbar::buttonMouseOverBackgroundColourId = 0x1003220 //A colour used to paint the background of buttons when the mouse is over them. 
Toolbar::buttonMouseDownBackgroundColourId = 0x1003230 //A colour used to paint the background of buttons when the mouse is held down on them. 
Toolbar::labelTextColourId                 = 0x1003240 //A colour to use for drawing the text under buttons when the style is set to iconsWithText or textOnly. 
Toolbar::editingModeOutlineColourId        = 0x1003250 //A colour to use for an outline around buttons when the customisation dialog is active and the mouse moves over them. 
```

TooltipWindow
```c++
TooltipWindow::backgroundColourId = 0x1001b00 //The colour to fill the background with. 
TooltipWindow::textColourId       = 0x1001c00 //The colour to use for the text. 
TooltipWindow::outlineColourId    = 0x1001c10 //The colour to use to draw an outline around the tooltip. 
```