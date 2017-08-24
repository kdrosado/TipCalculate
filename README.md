# Pre-work - TipCalculate

TipCalculate is a tip calculator application for iOS.

Submitted by: Kerry D. Rosado

Time spent: **3** hours spent in total

## User Stories

The following **required** functionality is complete:

* [ x ] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [ x ] Settings page to change the default tip percentage.

The following **optional** features are implemented:
* [ ] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [ ] Using locale-specific currency and currency thousands separators.
* [ ] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Project Analysis

As part of your pre-work submission, please reflect on the app and answer the following questions below:

**Question 1**: "What are your reactions to the iOS app development platform so far? How would you describe outlets and actions to another developer? Bonus: any idea how they are being implemented under the hood? (It might give you some ideas if you right-click on the Storyboard and click Open As->Source Code")

**Answer:** 
The iOS app development platform is great to work with.  Look forward to working more with it to create more complex projects.

An outlet connection is created when you need to send a message from your code to a user interface object in Xcode’s storyboard. The object can be a control, such as a button, a slider, and a switch, or it can be any other object defined in your storyboard, such as a label and a progress bar. For example, when your code determines that a label should display some texts, the code sends a message through the outlet telling the label to display the new text.

An action connection is created when you need to send a message from a control in the storyboard to your code. A control is a user interface object that causes actions or visible results when a user manipulates the object. For example, when a user taps a button, the button sends an action message to your code telling it to execute the appropriate method. Other examples of controls that can be used to create action connections are text fields, sliders, and switches.

Question 2: "Swift uses [Automatic Reference Counting](https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/AutomaticReferenceCounting.html#//apple_ref/doc/uid/TP40014097-CH20-ID49) (ARC), which is not a garbage collector, to manage memory. Can you explain how you can get a strong reference cycle for closures? (There's a section explaining this concept in the link, how would you summarize as simply as possible?)"

**Answer:** 



## License

    Copyright 2017 Kerry D. Rosado

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
