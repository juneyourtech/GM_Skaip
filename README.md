# GM_Skaip
Userstyle(s) to adjust Skype for Web for small-resolution displays on Android (320x480 px).

# Long form:
This userstyle is meant for use in Firefox for Android to adjust Skype for Web for small displays — those at width of 500 pixels or less, and specifically displays with a 320x480px resolution.

Use cases: In devices with Android 2.3, where the Skype app has ceased working, Firefox for Android can be configured to pose as a desktop browser, thus enabling use of Skype for Web.

# Changes in design.
* The message entry textarea switches location to top when active, so that it would not hide behind the virtual keyboard. This enables most of the entered text to visible until the lower edge of the textarea reaches the top edge of the virtual keyboard.

# Requirements
* Firefox for Android
* Stylish extension
* Firefox must be configured in about:config to identify itself as Firefox for desktop to all top-level Skype-related domains.

# Considerations
* NoScript must be configured to permit all Skype-related domains.
* I have not tested all of this with any other Firefox add-ons, such as adblockers.

# Caveats
* Note, that this only works with text-based messaging; sending of SMS's should also be possible. Therefore, do not expect use of video or audio, especially if your device is slow; see this section's last point.
* Access to settings is somewhat limited. The settings category links work, and that section is appropriately scrollable, but actual settings sections are limited in view, making some settings inaccessible due to formatting and space constraints. — Because I primarily created the userstyle to allow text-based messaging as the bare minimum.
* Skype for Web in Android Firefox can be very slow on older devices, particularly those with slow CPUs and low amounts of RAM memory. On a device with an 800 MHz CPU and 512 Mb physical RAM, loading from login entry to visible active online status can take around 3–4 minutes, and the entire site is very memory-intensive. YMMV.

# Other functionality.
* To see, if there are any unread messages, tap on the Firefox Tab button for a list of tabs. Next to the site thumbnail is the site title: If any unread messages await, their number is displayed in parentheses. (Due to space constraints, it can be cumbersome to scroll through all contacts in order to see, if there are any unread messages.)
* You can have newlines and paragraphs in the same message by using the Shift+Enter combination. The plain Enter/Return button sends the message.
* In case of a long-form message, tilt the screen sideways (into landscape mode) to get the native editing area of the virtual keyboard: text is there in a bigger font. Once the message is finished, tilt the screen into portrait mode and send the message. This requires, that screen tilting is available and turned on in your device.
* Skype for Web allows editing and deleting messages. To do either, long-tap on the entered message to get the context menu.

# Legal
The userstyle is free to use by anyone. No copyright infringment is intended. Skype is the registered trademark of Microsoft. Android is the registered trademark of Google. Firefox is the registere trademark of Mozilla.
