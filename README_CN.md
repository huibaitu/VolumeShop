# VolumeShop
医学图像必备软件

![GitHub all releases](https://img.shields.io/github/downloads/huibaitu/volumeshop/total)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/huibaitu/VolumeShop)

[English](README.md)

本文档是VolumeShop的功能介绍和使用说明。

## 设置
VolumeShop提供了多语言(英语和汉语)与多主题(深色和亮色)的用户界面，您可以在“设置”子面板随时进行动态切换。 

### 语言设置
VolumeShop首次打开时，界面语言与系统语言设置一致。 目前软件暂时只支持中文和英文两种语言，其他语言默认设置为英文。 可以通过以下步骤更改界面语言。  

1. 点击工具栏上的“设置”选项卡。

2. 在“设置”子面板中，单击<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/languageButton.png" alt="languageButton" style="zoom:50%" />按钮，可以动态地更改VolumeShop的界面语言，或者从该按钮的下拉菜单中选择一种语言。  

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/languageSwitch.gif" alt="languageSwitch" width="100%"/>

### 主题设置
VolumeShop用户界面的默认颜色主题是“深色”。下面介绍如何将其更改为其他颜色主题。

1. 在菜单选项卡选择“设置”标签。

2. 在“设置”子面板,点击<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/themeButton.png" alt="themeButton" style="zoom:50%" />按钮切换不同主题，或者从下拉菜单选择主题。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/themeSwitch.gif" alt="themeSwitch" width="100%"/>

### 全屏模式

VolumeShop可以通过单击“设置”子面板上的<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/fullScreenButton.png" alt="fullScreenButton" style="zoom:50%" />按钮进入全屏模式，并通过单击<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/exitFullScreenButton.png" alt="exitFullScreenButton" style="zoom:50%" />按钮退出。  

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/fullScreen.gif" alt="fullScreen" width="100%"/>

## DICOM文件预览
VolumeShop提供了DICOM文件预览功能，能够让DICOM文件（后缀 “.dcm”）像普通图像文件一样在Windows资源管理器中预览。如下图所示，在VolumeShop完成安装之后，DICOM文件可以直接显示略缩图。如果未能达到效果，请将VolumeShop设为“.dcm"文件的默认打开程序。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/preview.jpg" alt="dicomPreview" width="100%"/>

## 导入DICOM文件
VolumeShop支持多种文件导入方式，可以根据实际场景选择最方便的方式。

### 使用文件拖拽操作导入
拖拽选中的目录和文件到VolumeShop，软件将解析并按照序列分类显示这些文件。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/dragFiles.gif" alt="dragFiles" width="100%"/>

### 使用右键菜单导入文件
右键单击选中的文件或目录，在弹出的菜单中选择“使用VolumeShop打开”，软件将显示这些文件。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/rightButtonOpen.gif" alt="rightButtonOpen" width="100%"/>

### 双击文件导入
双击DICOM文件直接打开。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/doubleClickOpen.gif" alt="rightButtonOpen" width="100%"/>

### 打开目录
显示目录中的所有DICOM文件。

1. 点击“打开目录”按钮或从按钮下拉菜单中选择“打开DICOM目录”。

2. 从弹出的对话框选中打开的目录，点击“选择”按钮。 

3. VolumeShop按照病人、检查和序列的方式排列显示文件。

### 增加目录
在已经打开的文件基础上，增加DICOM目录。

1. 在“打开目录”按钮下拉菜单中选择“增加DICOM目录”。

2. 在弹出对话框中选中添加的目录，点击“选择”按钮。

3. 增加DICOM目录中的文件与已经打开的文件进行合并，确保病人、检查、序列和图像不重复。

### 最近打开的目录
在“打开目录”按钮下拉菜单“最近打开的目录”罗列最近打开的五个文件目录，可再次打开这些目录。

### 打开文件
显示选中的文件。

1. 点击“打开文件”按钮或从按钮下拉菜单中选择“打开文件”。

2. 在弹出对话框选择一个或多个DICOM文件，点击“打开”按钮。

3. VolumeShop按照病人、检查和序列的方式排列显示文件。

### 增加文件
在VolumeShop已有打开文件时，添加DICOM文件。

1. 在“打开文件”按钮下拉菜单中选择“增加文件”。

2. 选择添加的文件，点击“打开”按钮。

3. 增加的文件与已经打开的文件进行合并，确保病人、检查、序列和图像不重复。

### 最近打开的文件
I在“打开文件”按钮下拉菜单“最近打开的文件”罗列最近打开的五个文件目录，可再次打开这些文件。

## 导出DICOM文件
使用VolumeShop，可以很方便地将DICOM文件导出为BMP、JPG、PNG图像。在“保存文件”按钮下拉菜单选择“另存为图像”或“另存为图像序列”可导出当前显示的DICOM文件或序列。

### 另存为图像
将当前显示的DICOM文件另存为特定格式的图像。

1. 在“保存文件”按钮下拉菜单选择“另存为图像”。

2. 在弹出对话框选择导出图像格式，例如BMP、JPG、PNG等格式。

3. 选择保存的目录，输入保存的文件名。

4. 点击“保存”按钮。

提示：在导出对话框选中“打开保存的目录”选项，在Windows资源管理器将打开保存的目录，方便对保存的图像做进一步处理。

### 另存为图像序列
将当前DICOM序列另存为图像序列。

1. 在“保存文件”按钮下拉菜单选择“另存为图像序列”。

2. 在弹出对话框选择导出图像格式，例如BMP、JPG、PNG等格式。

3. 选中导出图像序列的目录，点击“选择”按钮。

提示：在导出对话框选中“以数字顺序重命名”选项，导出的图像将按照数字顺序命名。

## 管理DICOM文件

## 浏览DICOM文件

### 浏览序列图像

### 调窗


### 缩放图像

### 平移图像

### 旋转图像

### 翻转图像

### 重置图像

### 查看DICOM标签

点击<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/fileInfomationButton.png" alt="fileInfomationButton" style="zoom:50%" />按钮，VolumeShop将弹出一个显示当前浏览文件详细信息的新窗口。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/dicomTag.png" alt="dicomTag" width="100%"/>

### 多窗口显示

- 选择多窗布局

从<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/multiwindowButton.png" alt="multiwindowButton" style="zoom:50%" />按钮的下拉菜单选择一个布局来创建多个窗口，当前子窗口将显示在预览区选中的序列，您也可以将一个序列从预览区域拖动到所需的子窗口进行显示。双击子窗口使其最大化，然后再次双击以恢复到多窗口布局。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/multiwindow.gif" alt="multiwindow" width="100%"/>

- 打开当前检查

点击<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/multiwindowButton.png" alt="multiwindowButton" style="zoom:50%" />按钮下拉菜单中的“打开当前检查”，可以方便地在多个窗口中同时打开当前检查的所有序列。  

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/openStudy.jpg" alt="openStudy" width="100%"/>

### 序列同步

VolumeShop提供了三种序列之间的同步（切片位置、窗宽窗位以及缩放和平移）。窗宽窗位同步缺省是关闭状态，其它同步缺省是开启状态。在<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/seriesSyncButton.png" alt="seriesSyncButton" style="zoom:50%" />按钮下拉菜单可以切换这些同步的开启和关闭状态。

- 切片位置同步

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/sliceLocationSync.gif" alt="sliceLocationSync" width="100%"/>

- 窗宽窗位同步

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/windowLevelSync.gif" alt="windowLevelSync" width="100%"/>

- 缩放和平移同步

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/zoomAndPanSync.gif" alt="zoomAndPanSync" width="100%"/>

### 平铺图像

点击<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/tileImagesButton.png" alt="tileImagesButton" style="zoom:50%" />按钮，VolumeShop可以平铺显示序列中的所有图像。在序列平铺视图，提供了如下几种交互方式：

- 鼠标左键双击：返回单图像浏览模式。
- Ctrl + 鼠标滚轮向前：通过减少每行图像的数量(最小为4)来放大序列的所有图像。
- Ctrl + 鼠标滚轮向后：通过增加每行图像的数量(最大为20)来缩小序列的所有图像。

<img src="https://res.cloudinary.com/huibaitu/image/upload/VolumeShop/tileImages.gif" alt="tileImages" width="100%"/>
