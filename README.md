# My Maps 

## *Rachael Wang*

**My Maps** displays a list of maps, each of which show user-defined markers with a title, description, and location. The user can also create a new map. 

Time spent: **18** hours spent in total  (Just ran into a lot of bugs. :/ ) 

## Functionality 

The following **required** functionality is completed:

* [X] The list of map titles is displayed.
* [X] After tapping on a map title, the associated markers in the map are shown.
* [X] The user is able to create a new map.

The following **extensions** are implemented:

* [X] When a map marker is created, the pin is animated.
* [X] Changed color design of the app
* [X] Changed inital view when entering the map into general North America

## Video Walkthrough

<img src='https://imgur.com/Vq49JkJ.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

I learned a lot from working on this project and ran into quite a few bugs. For one, in the beginning my emulator keep re-opening prior projects instead of running the current project. I could download a new phone and run the project on a new phone but the old emulators didn't work. In order to fix this, I took advice I found on stackoverflow and imported a new projects settings.gradle file. 

I ran into a bug when implementing the CreateMap file, the program would shut down and restart whenever I tried to zoom forward to directly to the pins. This bug eventually disappeared but I wasn't able to find the cause of it. Instead I decided to extended the opening view when entering a map into general North America. 

## License

    Copyright [2020] [Rachael Wang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
