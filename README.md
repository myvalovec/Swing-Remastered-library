# Swing Remastered: library
Modernize your Java applications instantly.

Let’s be honest. Java Swing is a incredibly lightweight, but visually, it’s stuck in the 90s. I built Swing Remastered because I wanted the stability of Java with the aesthetics of a modern UI without having to use heavier JavaFX or even heavier to web technologies like Electron.

This isn’t just a skin. It’s a complete remaster of the core components, adding smooth animations and transitions, all while remaining 100% compatible with the Swing logic you already know.

# Usage
incredibly simple usage just adding one extra letter.
- JButton -> JRButton
- JFrame -> JRFrame
- works exactly the same for every component.

# Installation
- Download the JAR file.
- Add to Path: Add the JAR to your project's Build Path / Libraries.
- No Extrenal Dependencies: The library is standalone. No extra downloads required.

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
    <td align="center"><b>Old</b></td>
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
      <img src="./gifs/JRCheckBox.gif" height="300" alt="JRCheckBox">
    </td>
    <td align="center">
      <img src="./gifs/JCheckBox.gif" height="300" alt="JCheckBox">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>Old</b></td>
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
    <td align="center"><b>Old</b></td>
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
    <td align="center"><b>Old</b></td>
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
      <img src="./gifs/JRComboBox_1.gif" height="300" alt="JRComboBox 1">
    </td>
    <td align="center">
      <img src="./gifs/JComboBox_1.gif" height="300" alt="JComboBox 1">
    </td>
  </tr>
  <tr>
    <td align="center"><b>Remastered</b></td>
    <td align="center"><b>Old</b></td>
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
    <td align="center"><b>Standard OS Look (uncustomizable)</b></td>
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

# Pricing & License
