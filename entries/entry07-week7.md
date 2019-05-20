# Entry 7: Errors and Changes

## Fixing my Error

My error from last week, which dealt with a problem with loading files and authors. I discovered when I previously connected one of the buttons to code, this line of code was unfinished, resulting in the error. Once I took out this line, the program was fixed.

## Another Error?

I decided to learn how a user can place their own image in the app from their camera roll when the clubs add their products that are being sold. To do so, I went back my original tutorial from Apple. I began adding the code necessary to put a placeholder image that can be replaced with the user's own image from their camera roll. However, I ran into an issue with one line of code that read:

**"Cannot subscript a value of type '[String : Any]' with an index of type UIImagePickerController"**

When I typed the error into google, I found a page in [Github issues](https://github.com/danielgindi/Charts/issues/2777). It explained that the new version of XCode and Swift caused this error. I was confused at first because I did not think that the programming language had a bug. After further research, I found a page on [Apple](https://developer.apple.com/documentation/uikit/uiimagepickercontrollerdelegate/1619126-imagepickercontroller) that showed `imagePickerController` as an instance method. I replaced the string in the line of code with this method, which fixed the error.

## Changing the MVP

My partner and I decided that an app with multiple views would not be possible to make in the short amount of time we have left. We decided it would be best to create a simple one view app, even if it is something that already exists such as a calculator.

## Takeaway
1. It is ok to change your mind. Nothing needs to be set in stone, and sometimes it is necessary to change for your own benefit.

[Previous](entry06-week6.md)

[Table of Contents](../README.md)