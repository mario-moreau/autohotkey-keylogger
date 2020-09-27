# autohotkey-keylogger
A little keylogger running using an AutoHotKey script.

AutoHotKey is a scripting program for Windows (https://www.autohotkey.com/). It can be used to create powerful macros and many other things that I couldn't think of.

A keylogger is something that can record your keyboard inputs. It can be a hardware keylogger, but it can also be a software keylogger. The first one usually being much easier to spot than the second one.

I created that script back in 2018, it was on my hard drive and I thought it would be interesting for me to upload it.

## Disclaimer
Keyloggers don't have many good uses. The only ones that I can think of are:
- You are a parent wanting to monitor your child's actions on a computer.
- You want to prank your friends and need their social media passwords to mess a little with them.

Keyloggers are mainly used with bad intentions in mind.
My point, by uploading this keylogger, is to show everyone how easy it is for someone to steal your passwords if you let your computer unsupervised or if you enter your passwords on a computer that isn't yours.
That way, you will be able to prevent yourself from such tricks.

#### I am not responsible of anything you will do with that script. This is for education purposes only.

## How it works
The script records every key listed in it inside a 'keylog.txt' file.
It is possible to add other keys if your keyboard layout contains caracters that aren't listed.

The #NoTrayIcon option hides the icon from Windows tray. The easiest way to spot the keylogger is to open Task Manager and see that AutoHotKey is running in the background.
It's probably possible to hide it a little more by modifying the AutoHotKey program name and icon, to mislead someone looking for it.
