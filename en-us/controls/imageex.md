---
permalink: /en-US/controls/imageex.htm
title: ImageEx XAML Control
description: The ImageEx Control downloads images asynchronously while showing a loading indicator
keywords: windows, app, toolkit, ImageEx, loading indicator, ImageExControl, UWP
layout: default
search.product: eADQiWindows 10XVcnh
---

# ImageEx XAML Control

The **ImageEx Control** downloads images asynchronously, while showing a loading indicator. Source images are then stored in the application's local cache to preserve resources and load time. ImageEx also extends the default *Image* Platform control to improve performance through caching. 
 
## Syntax

```xaml
<controls:ImageEx Name="ImageExControl"
	IsCacheEnabled="True"
	PlaceholderSource="/assets/thumbnails/thumbnails.png"
	Source="/assets/bigPicture.png"
/> 
```

## Example Image

![ImageEx animation]({{site.baseurl}}/resources/images/Controls-ImageEx.gif "ImageEx")

## Example Code

[ImageExControl Sample Page](https://github.com/Microsoft/UWPCommunityToolkit/tree/master/Microsoft.Toolkit.Uwp.SampleApp/SamplePages/ImageEx)

## Default Template 

[ImageExControl XAML File](https://github.com/Microsoft/UWPCommunityToolkit/tree/master/Microsoft.Toolkit.Uwp.UI.Controls/ImageEx) is the XAML template used in the toolkit for the default styling.

## Platforms 

Windows 10 SDK 10586 or higher

## API

* [ImageEx source code](https://github.com/Microsoft/UWPCommunityToolkit/tree/master/Microsoft.Toolkit.Uwp.UI.Controls/ImageEx)
* [ImageEx API documentation]({{site.baseurl}}/api/Microsoft_Toolkit_Uwp_UI_Controls_ImageEx.htm)