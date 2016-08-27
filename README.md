# Blink Mobile Shell for iOS
We are excited to introduce you to Blink. Blink is a unique mobile shell for iOS. We are creating the terminal we wanted to have and use all day: fully configurable, great keyboard support, great terminal rendering, and crazy fast thanks to [Mosh](https://github.com/mobile-shell/mosh). We won't stop there, and plan to convert this into a great work environment by adding other tools like scp. Hope you find on it a trusty and enjoyable tool too.

# Obtaining Blink
We want to share all the fun by inviting you to our Alpha. Would love to have you on board! If you would like to participate, follow and tweet us [@BlinkShell](https://twitter.com/BlinkShell) a little about your interest and usage scenarios. Invitations will be sent out in waves, please be patient if you do not receive yours immediately.

Bugs should be reported here on GitHub. Crash reports will be automatically reported back to us thanks to HockeyApp. If you have any questions or want to make sure we do not miss on an interesting feature, please send your suggestions to our Twitter account [@BlinkShell](https://twitter.com/BlinkShell). We would love to discuss them with you! Please do not use Twitter to report bugs.

We can't wait to receive your valuable feedback. Enjoy!

# Using Blink
Our UI is very straightforward and optimizes the experience on touch devices for the really important part, the terminal. You will jump right into a very simple shell, so you will know what to do. Here are a few more tricks:
- Use two fingers tap to create a new shell.
- Move between shells by swapping your finger.
- You can exit the session and get back to the shell to open a new connection.
- You can also close a session by dragging two fingers down.
- Use pinch gesture to increase or reduce size of text. You can also use Cmd+ or Cmd- if using the keyboard.
- Copy and Paste by selecting text o tapping the screen.
- Run 'config' to setup your keys. Install them to a server through ssh-copy-id.
- Ctrl and Alt modifiers at the SmartKeys bar allow for continuous presses, like in a real keyboard.
- In an external keyboard, use Cmd or Caps as Ctrl and Alt as meta (Default configuration).

# Changelog
## Version 0.927
	This version should complete the experience in relation to ssh and terminal configurations, mimicking a big part of what you can do in a normal shell:
	- Hosts Configuration. Preconfigure a host parameters, like user, port, key and commands.
	- Connect to a Host by specifying its name. Do "mosh plankton"
	- Overwrite parameters from host configuration from the shell. So carlos@plankton will override the user field on plankton.
	- Default Modifier keys settings changed: Ctrl is Ctrl, and Alt sends Esc. Everything else is undefined.
	- Modifier keys configuration. CAPS as Ctrl or ESC, no problem! Cmd as Ctrl? You have it! Configure everything to you liking.
	- Added secure passwords stored on Keychain to Host Configuration.
	- Exiting the session within the MCP closes the Space.

	- Fixed hang after "exec request accepted". Establishing connections should be smooth now.
	- Fixed adjustments on viewport after rotating the display.
	- Fixed Ctrl + Space sequences.
	- Fixed wrong/unexisting Ctrl sequences.
	- Added Esc+any character support.

	- New settings added to project. Will start to fill up in raw branch.

[View all changes](CHANGELOG.md)

# Attributions
- [Mosh](https://mosh.mit.edu) was written by Keith Winstein, along with Anders Kaseorg, Quentin Smith, Richard Tibbetts, Keegan McAllister, and John Hood.
- This product includes software developed by the OpenSSL Project
for use in the OpenSSL Toolkit. (http://www.openssl.org/).
- [Libssh2](https://www.libssh2.org)
- Entypo pictograms by Bruce Daniel www.entypo.com.