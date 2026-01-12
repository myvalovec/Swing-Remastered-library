# Swing Remastered: library
A showcase of Swing Remastered. A java swing library that remasters basic swing components that are fully compatible with basic components.


# Available Components
## JRButton
<table>
  <tr>
    <td align="center">
      <img src="./gifs/JRButton_1.gif" height="300" alt="JRButton 1">
    </td>
    <td align="center">
      <img src="./gifs/JButton_1.gif" height="300" alt="JButton 1">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>old</b></td>
  </tr>
</table>

### Constructors:
- JRButton()
- JRButton(String title)
### Modified functions:
- setRadius(int radius)
- setAnimationStep(double step)
  - sets speed of hover and press animations.
- setHoverEffectIntensity(double intensity)
  - sets intensity of hover and press animations.
- setBackground(Color bg)

## JRCheckBox
<table>
  <tr>
    <td align="center">
      <img src="./gifs/JRCheckBox_1.gif" height="300" alt="JRCheckBox 1">
    </td>
    <td align="center">
      <img src="./gifs/JCheckBox_1.gif" height="300" alt="JCheckBox 1">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>old</b></td>
  </tr>
</table>

### Constructors:
- JRCheckBox()
- JRCheckBox(String title)
### Modified functions:
- setBoxSize(int size)
- setRadius(int radius)
- setCheckStroke(float width)
- setCheckmarkOffsets(float x, float y)
- setBoxColor(Color color)
- setBorderColor(Color color)
- setCheckColor(Color color)

## JRScrollPane
<table>
  <tr>
    <td align="center">
      <img src="./gifs/JRScrollPane_1.gif" height="300" alt="JRScrollPane 1">
    </td>
    <td align="center">
      <img src="./gifs/JScrollPane_1.gif" height="300" alt="JScrollPane 1">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>old</b></td>
  </tr>
</table>

### Constructors:
- JRScrollPane()
- JRScrollPane(Component holder)
### Modified functions:
- setBackground(Color color)
  - sets background of the scroll pane and both scrollers tracks
- setScrollWidth(int width)
- setThumbRadius(int radius)
- setThumb(Color color)
- setCheckmarkOffsets(float x, float y)
- setHover(Color color)

## JRProgressBar
<table>
  <tr>
    <td align="center">
      <img src="./gifs/JRProgressBar_1.gif" height="300" alt="JRProgressBar 1">
    </td>
    <td align="center">
      <img src="./gifs/JProgressBar_1.gif" height="300" alt="JProgressBar 1">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>old</b></td>
  </tr>
</table>

### Constructors:
- JRProgressBar()
- JRProgressBar(int min, int max)
### Modified functions:
- setValue(int n)
- setTrackColor(Color track)
- setTextColors(Color onTrack, Color onFill)
- setRadius(int r)

## JRComboBox
<table>
  <tr>
    <td align="center">
      <img src="./gifs/JRComboBox.gif" height="300" alt="JRComboBox">
    </td>
    <td align="center">
      <img src="./gifs/JComboBox.gif" height="300" alt="JComboBox">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>old</b></td>
  </tr>
</table>

### Constructors:
- JRComboBox()
- JRComboBox(E[] items)
### Modified functions:
- setAccentColor(Color color)
- setBackground(Color bg)
- setBorderColor(Color color)
- setRadius(int radius)

## JRPanel

## JRFrame
<table>
  <tr>
    <td align="center">
      <img src="./gifs/JRFrame_1.gif" height="300" alt="JRFrame 1">
    </td>
    <td align="center">
      <img src="./gifs/JFrame_1.gif" height="300" alt="JFrame 1">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>default OS look(uncustomizable)</b></td>
  </tr>
</table>

### Constructors:
- JRFrame()
- JRFrame(String title)
### Modified functions:
- setTitleBarBackground(Color color)
  - sets color of the title bar.
- setTitleBarForeground(Color color)
  - sets color of the frames title text.
- setTitle(String title)
- setBackground(Color color)
  - sets the background of the frame with its borders(left, right, bottom).
