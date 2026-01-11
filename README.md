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
  - sets radius of the button.
- setAnimationStep(double step)
  - sets speed of hover and press animations.
- setHoverEffectIntensity(double intensity)
  - sets intensity of hover and press animations.
- setBackground(Color bg)
  - sets background color of the button.

## JRCheckBox

## JRSCrollPane

## JRProgressBar

## JRComboBox
<table>
  <tr>
    <td align="center">
      <img src="./gifs/JRComboBox_1.gif" height="300" alt="JRComboBox 1">
    </td>
    <td align="center">
      <img src="./gifs/JComboBox_1.gif" height="300" alt="JComboBox 1">
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
  - sets accent color.
- setBackground(Color bg)
  - sets background color.
- setHoverBackgroundColor(Color color)
  - sets on hover backgeound color.
- setBorderColor(Color color)
  - sets border color of the combo box
- setHoverBorderColor(Color color)
  - sets on hover border color.
- setRadius(int radius)
  - sets border radius.

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
  - sets title text of the frame.
- setBackground(Color color)
  - sets the background of the frame with its borders(left, right, bottom).
