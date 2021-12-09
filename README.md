[![Build](https://github.com/applibgroup/RichButtons/actions/workflows/main.yml/badge.svg)](https://github.com/applibgroup/RichButtons/actions/workflows/main.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=applibgroup_RichButtons&metric=alert_status)](https://sonarcloud.io/dashboard?id=applibgroup_RichButtons)

# Wearable Reply

## Introduction:
'RichButtons' is a set of button styles for openharmony applications. All of the styles are made of XML.

# Source
This library has been inspired by [ksoichiro//RichButtons](https://github.com/ksoichiro/RichButtons).


## Usage:

#Blue

<p>
	<image src = "/screenshots/blue.png" width = 320 height = 40/>
</p>
<p>
	<image src = "/screenshots/blue_pressed.png" width = 275 height = 38/>
</p>



            <Button
                ohos:background_element="$graphic:rb__blue_button"               
                ohos:text="RbButton.Blue"/>
#Purple
<p>
	<image src = "/screenshots/purple.png" width = 320 height = 40/>
	<image src = "/screenshots/purple_pressed.png" width = 320 height = 40/>

</p>

            <Button               
                ohos:background_element="$graphic:rb__button_purple"
                ohos:text="RbButton.purple"/>
#Green
<p>
	<image src = "/screenshots/green.png" width = 320 height = 40/>
	<image src = "/screenshots/green_pressed.png" width = 320 height = 40/>

</p>

            <Button                
                ohos:background_element="$graphic:rb__button_green"
                ohos:text="RbButton.green"/>
#Yellow
<p>
	<image src = "/screenshots/yellow.png" width = 320 height = 40/>
	<image src = "/screenshots/yellow_pressed.png" width = 320 height = 40/>

</p>

            <Button
                ohos:background_element="$graphic:rb__button_yellow"
                ohos:text="RbButton.yellow"/>
#Red
<p>
	<image src = "/screenshots/red.png" width = 320 height = 40/>
	<image src = "/screenshots/red_pressed.png" width = 320 height = 40/>

</p>

            <Button                
                ohos:background_element="$graphic:rb__button_red"
                ohos:text="RbButton.red"/>

## Installation instructions:

```
Method 1:
    Generate the .har package through the library and add the .har package to the libs folder.
    Add the following code to the entry gradle:
        implementation fileTree  (dir: 'libs', include: ['*.jar', '*.har'])

Method 2:
    allprojects{
        repositories{
            mavenCentral()
        }
    }
implementation 'dev.applibgroup:richbutton:1.0.0'
```

## License

    Copyright (c) 2013 Soichiro Kashima.

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
