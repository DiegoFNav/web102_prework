# WEB102 Prework - Diego Crowdfunding

Submitted by: Diego Navarro

Diego Crowdfunding is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: 10 hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!
   Added pointer to turn into cursor when hovering buttons

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='record.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with LiceCap.
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.

I was having difficulty at first creating html elements and adding them inside of other elements.
This was due to me not understanding the difference between appendChild and innerHTML. I was at first trying to create an element then set the innerhtml of a div to it in order to get the element into the div. However I was supposed to use appendChild to make the new element a child of the div in order to be inserted inside. Meanwhile I later had to add text inside a paragraph element. I realized that then I am meant to use the innerHTML attribute as it inserts text inside of an element rather than an element.

## License

    Copyright 2024 Diego Navarro

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
