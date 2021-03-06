---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_UI_Controls_ImageEx.htm
title: Microsoft.Toolkit.Uwp.UI.Controls.ImageEx API 
description: API page for Microsoft.Toolkit.Uwp.UI.Controls.ImageEx
keywords: windows, app, toolkit, UWP, API
layout: api
search.product: eADQiWindows 10XVcnh
---


# ImageEx class

The ImageEx control extends the default Image platform control improving the performance and responsiveness of your Apps. Source images are downloaded asynchronously showing a load indicator while in progress. Once downloaded, the source image is stored in the App local cache to preserve resources and load time next time the image needs to be displayed.

## Members

The **ImageEx** class has the following types of members:

### Constructors

#### contructor

Initializes a new instance of the [ImageEx](Microsoft_Toolkit_Uwp_UI_Controls_ImageEx.htm) class.



### Methods

#### GetAsCastingSource()

Returns the image as a [CastingSource](https://msdn.microsoft.com/library/windows/apps/Windows.Media.Casting.CastingSource).

##### Parameters



| Name | Description | Type || --- | --- | --- || return |The image as a [CastingSource](https://msdn.microsoft.com/library/windows/apps/Windows.Media.Casting.CastingSource). |


#### MeasureOverride(Windows.Foundation.Size availableSize)

Measures the size in layout required for child elements and determines a size for the control.

##### Parameters



| Name | Description | Type || --- | --- | --- || availableSize | The available size that this element can give to child elements. Infinity can be specified as a value to indicate that the element will size to whatever content is available. | [Size](https://msdn.microsoft.com/library/windows/apps/Windows.Foundation.Size) || return |The size that this element determines it needs during layout, based on its calculations of child element sizes. |


#### OnApplyTemplate()

Update the visual state of the control when its template is changed.



### Properties

#### Source

Gets or sets get or set the source used by the image



#### Stretch

Gets or sets the stretch of the image.



#### NineGrid

Gets or sets the nine-grid used by the image.



#### IsCacheEnabled

Gets or sets a value indicating whether gets or sets cache state



#### PlaceholderSource

Gets or sets the placeholder source.



#### PlaceholderStretch

Gets or sets the placeholder stretch.



#### PlaceholderAnimationDuration

Gets or sets the placeholder animation duration.



### Events

#### ImageOpened

Event raised when the image is successfully loaded and opened.



#### ImageFailed

Event raised if the image failed loading.



### Fields

#### PlaceholderAnimationDurationProperty

Identifies the PlaceholderAnimationDuration dependency property.



#### StretchProperty

Identifies the Stretch dependency property.



#### NineGridProperty

Identifies the NineGrid dependency property.



#### PlaceholderStretchProperty

Identifies the PlaceholderStretch dependency property.



#### SourceProperty

Identifies the Source dependency property.



#### PlaceholderSourceProperty

Identifies the PlaceholderSource dependency property.


