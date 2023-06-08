# Prework - *CodePathProject

Submitted by: **Lorenzo Balderrama Porras**

**CodePath-Project** is an app that changes the colors of a background when you click on the Change Color Button.

Time spent: **2** hours spent in total

## Required Features

The following **required** functionality is completed:

- [X] Users are see a screen with three labels and a button
- [X] Tapping the button changes the screen color to a random color
 
## Video Walkthrough

https://imgur.com/m1ZuAii

Here's a walkthrough of implemented user stories:
<img src='[Imgur](https://i.imgur.com/m1ZuAii.gifv)' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with (https://getkap.co/)

<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## App Brainstorming (Step 4)
- Notion
1. Allows for quick search of any specific word(s) throughout the different note pages you have.
2. Quick add a note without having to work through the process of setting up new pages.
3. Add a URL and it displays the preview to that page / integration with other apps like safari

- Outlook / Gmail
1. Quickly compose any email using the compose button found immediately to the left of your thumb! Has saved me so much time to quickly open and make an email.
2. View calendar within the app to see meetings set through an email! Saved me from being late plenty of times!
3. Search for emails with images and not have to go through and find the specific emails that have an attachment to find information you need immediately.

- Venmo
1. Connect with others with a quick capture of their QR code. I've met new friends and quickly need to add their Venmo or they need to add mine to repay a dinner or something along those lines.
2. Quickly transfer money to my bank account using their transfer button on the profile section.
3. Pay/Request button in the middle of the navigation bar allows for a quick transaction especially at the end of the night when everyone is going home you can quickly add friends/family/and even aquaintences and send them money.

- An app that I would love to build is a project manager app that has capabilities to add notes, code and other snippets of information. The notes section should work better than the current application for Notion. I need it to help me organize my notes, make projects that can be broken down into steps or lists, and have a fun integration with Spotify music because who doesn't love to listen to music or a podcast while working! 

## Notes

Describe any challenges encountered while building the app.
- I had problems with adding the IBAction. I initially wrote the wrong name for that function and changed it without going back to the Connections Inspector on the right hand side of Xcode. This made my app crash and gave me the following error: 

Thread 1: "-[CodePathProject.ViewController Button:]: unrecognized selector sent to instance 0x127707b00"

This was corrected with going through and deleting the other IBAction's and make it have one connection from the main storyboard to the ViewController class.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
