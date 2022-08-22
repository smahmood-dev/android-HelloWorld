# Android Prework - *Hello World*

Submitted by: **Sarmad Mahmood**

**Hello World** is an Android app that shows an image and introductory message, and allows pressing a button to display a Toast. 

Time spent: **4** hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] Image and introductory message displayed on screen
* [X] Button displayed on screen
* [X] Toast with message appears when button is pressed 

The following **optional** features are implemented:

* [X] Aesthetic changes such as centering the TextView and adding a black border to the ImageView, as the image used was not a PNG file.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='http://g.recordit.co/8hCShTerzY.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Recordit](https://recordit.co/).  

## Notes

Encountered some difficulty with the ImageView component of the app. The image would properly display in the Design tab, but not in the emulator itself. After troubleshooting the constraints and cropping method, I consulted an existing Stack Overflow thread which resolves the issue. Turns out the default Kotlin code for the ImageView needed to be modified for it to display the image in the emulator. 

## License

    Copyright [2022] [Sarmad Mahmood]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
