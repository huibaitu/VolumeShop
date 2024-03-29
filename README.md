# VolumeShop
Medical image essential software for Windows and Linux

![GitHub all releases](https://img.shields.io/github/downloads/huibaitu/volumeshop/total)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/huibaitu/VolumeShop)

[中文](README_CN.md)

This documentation mainly introduces the function and usage of VolumeShop.

## Settings
VolumeShop provides a multilingual (English and Chinese) and multi-theme(dark and light) user interface, you can dynamically switch at any time in the 'Settings' subpanel.

### Language settings
Which language appears when you open VolumeShop for the first time depends on the system locale. For the time being, only two languages (English and Chinese) are available, other language is set as English for default. The language can be changed using the following steps.

1. Click the 'Settings' tab on the toolbar.

2. In the 'Setting' subpanel, click <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/languageButton.png" alt="languageButton" style="zoom:50%" /> button to dynamically change VolumeShop's language or select a language from the drop down menus of the button.

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/languageSwitch.gif" alt="languageSwitch" width="100%"/>

### Theme settings
The default color theme for VolumeShop's user interface is 'Dark'. Here's how to change it to a different color theme.

1. On the menu tab, select 'Settings'.

2. In the 'Settings' subpanel, click <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/themeButton.png" alt="themeButton" style="zoom:50%" /> button to dynamically switch between different themes or select a theme from the button's drop down menus.

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/themeSwitch.gif" alt="themeSwitch" width="100%"/>

### Full screen mode

VolumeShop can enter full screen mode by clicking <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/fullScreenButton.png" alt="fullScreenButton" style="zoom:50%" /> button on the 'Settings' subsubpanel, and exit by clicking <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/exitFullScreenButton.png" alt="exitFullScreenButton" style="zoom:50%" /> button replaced at the same position.

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/fullScreen.gif" alt="fullScreen" width="100%"/>

## Preview DICOM files
VolumeShop provides a "DICOM file preview" feature that lets you view DICOM file (suffix '.dcm') as normal image in Windows Explorer. As shown below, thumbnails of DICOM files are easily presented after VolumeShop is installed. If not, please set VolumeShop as default app for '.dcm' files.

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/preview.jpg" alt="dicomPreview" width="100%"/>

## Import DICOM files
There are a wide range of importing DICOM files to VolumeShop, you can choose the most convenient way depending on circumstances.

### Import files using drag & drop
Simply drag and drop selected files and / or directories into VolumeShop, where these ones are parsed and displayed by way of sorted series.

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/dragFiles.gif" alt="dragFiles" width="100%"/>

### Import files using right-click menu
Right-click on selected files and / or directories and choose "Open with VolumeShop" from popup menu, VolumeShop will start and display those files. 

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/rightButtonOpen.gif" alt="rightButtonOpen" width="100%"/>

### Import file by double-click on it
You can double click to open DICOM file in VolumeShop.

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/doubleClickOpen.gif" alt="rightButtonOpen" width="100%"/>

### Open directory
Display all DICOM files in a directory.

1. Click "Open directory" button or select "Open DICOM directory" from drop-down menu on the right side of the button.

2. From the pop-up dialog, select the directory that contains DICOM files and click "Choose" button.

3. VolumeShop will display DICOM files with the sort by patient, study and series.

### Add directory
Append the DICOM files in a directory to the existing list of series.

1. Select "Add DICOM directory" in drop-down menu that comes up by clicking the arrow button right next to "Open directory" button.

2. Select the directory you want to add and click "Choose" button in the pop-up dialog.

3. The DICOM files in added directory will merge with exsiting files, make sure that neither of patients, studies, series and images is redundant.

### Recent directories
In "Recent directories" of drop-down menu, the five most recent directories are listed that make it easier to find directories you have viewed with VolumeShop.

### Open files
Display the selected files.

1. Click "Open file" button or select "Open file" from drop-down menu on the right side of the button.

2. From the pop-up dialog, select one or more DICOM files and click "Open" button.

3. VolumeShop will display DICOM files with the sort by patient, study and series.

### Add files
Append the chosen files to the existing list of series.

1. Select "Add file" in drop-down menu that comes up by clicking the arrow button right next to "Open file" button.

2. Select the files you want to add and click "Open" button in the pop-up dialog.

3. The added DICOM files will merge with exsiting files, make sure that neither of patients, studies, series and images is redundant.

### Recent files
In "Recent files" of drop-down menu, the five most recent files are listed that make it easier to find DICOM files you have viewed with VolumeShop.

## Export DICOM files
With VolumeShop, it's easy to export a DICOM file to a normal image in BMP, JPG or PNG formats. Start VolumeShop, and open the DICOM files you want to export. You could export current DICOM file or series by "Save as image" or "Save as image series", separately.

### Save as image
Save the current image as image in a specified format.

1. Select "Save as image" in drop-down menu that comes up by clicking the arrow button right next to "Save file" button.

2. From the pop-up dialog, choose a file format, such as BMP, JPG or PNG.

3. Select a folder and input a filename for the exported file.

4. Click "Save" button.

Tip: Check "Open the saved directory" in the Export dialog if you want to work with the exported file immediately.

### Save as image series
Save the current series as image series.

1. Click "Save as image series" in drop-down menu.

2. From the pop-up dialog, choose a file format, such as BMP, JPG or PNG.

3. Select a folder for the exported images and click "Choose" button.

Tip: Check "Rename in numerical order" in the Export dialog if you want to name the exported images in numerical order.

## Manage DICOM files

## Browse DICOM files

### Browse the images of series

### Adjust window

### Zoom image

### Pan image

### Rotate image

### Flip image

### Reset image

### View DICOM tag

Click <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/fileInfomationButton.png" alt="fileInfomationButton" style="zoom:50%" /> button, VolumeShop will pop up a new window to show the details of the current file. 

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/dicomTag.png" alt="dicomTag" width="100%"/>

### Multi-window display

- Select multi-window layout

From the drop-down menu of <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/multiwindowButton.png" alt="multiwindowButton" style="zoom:50%" /> button, select a layout to create multiply windows. The current subwindow will display the series chosen in preview region, you also can drag a series from preview region to the desired subwindow for display. Double-click on the subwindow to maximize it, then double-click again to restore to the multiwindow layout.
<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/multiwindow.gif" alt="multiwindow" width="100%"/>

- Open current study

Click 'Open current study' in the drop-down menu of <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/multiwindowButton.png" alt="multiwindowButton" style="zoom:50%" /> button, you can open conveniently all series of the current study in multiply windows at the same time.
<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/openStudy.jpg" alt="openStudy" width="100%"/>

### Series sync

VolumeShop provides three kinds of sync (slice location, window level, and zoom and pan) between the series opened in multiple windows. ​By default, the sync of the window level is off, the other is on. You can toggle them on and off in the drop-down menu of <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/seriesSyncButton.png" alt="seriesSyncButton" style="zoom:50%" /> button.

- Slice location sync

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/sliceLocationSync.gif" alt="sliceLocationSync" width="100%"/>

- Window level sync

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/windowLevelSync.gif" alt="windowLevelSync" width="100%"/>

- Zoom and pan sync

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/zoomAndPanSync.gif" alt="zoomAndPanSync" width="100%"/>

### Tile images

VolumeShop could tile all images of current series when you click on <img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/tileImagesButton.png" alt="tileImagesButton" style="zoom:50%" /> button. In series tile-view, several interactions are provided as follow:

- Left mouse button double click: Returns to single image browsing mode.
- Ctrl + mouse wheel forward: Zooms in on all images of series by decreasing the number (minimum: 4) of images per line.
- Ctrl + mouse wheel backward: Zooms out on all images of series by increasing the number (maximum: 20) of images per line.

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/tileImages.gif" alt="tileImages" width="100%"/>
