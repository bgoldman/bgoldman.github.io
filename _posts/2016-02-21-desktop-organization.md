---
layout: post
section-type: post
title: There's an App for That, Part One
subtitle: How I Organize My Apps to Optimize My Life
category: Lifehacking
tags: [ 'apps', 'optimization', 'organization', 'productivity', 'software', 'tools' ]
---

I'm a big fan of optimizing everything in my life. But especially the things I do or use most often, where the optimizations can be easily noticed. As a software engineer, I spend the overwhelming majority of my workday in front of my computer. This post will focus on how I use my computer.

The software I've chosen to use, and how I choose to use it, has been based on very precise choices and quite a bit of thinking. Over the past two years, I've changed most of what I use, and I'm pretty happy with these decisions.

This post is part of a series, but this one in particular will focus on organizing my apps and desktops, touch on some general-purpose apps and tools, and also some apps and tools I use for software development. Future posts will get into more detial about the hows and whys of these choices, but for the purposes of this post, you can look into the apps I use, or you can ignore them and use the same strategies with the apps you already use.

Let's get right into it.

## Operating System

I use Mac OSX, and recently upgraded to El Capitan. I've been on a Mac since 2009. I know a lot of people out there like Windows and various flavors of Linux, but here in the bay area, basically everybody uses OSX. Some of the apps I use may be available with other operating systems, but the focus of this post will be assuming you have a Mac also.

## Multiple Desktops

I know this isn't an app, but desktop organization is a huge part of how I use my computer and how I use all of my software most effectively. I've noticed that most people don't pay any special attention to this, and this is one of the biggest areas that people can optimize. The biggest area in my opinion that people could benefit from is multiple desktops. I thougnt it would make a good place to start.

I take full advantage of multiple desktops with Mission Control. To be more specific, I use seven desktops, and rather than complicate things, it's simplified things greatly and makes it much faster for me to do basically anything on my computer.

Switching from one desktop to another with Mission Control, using keyboard shortcuts, is far easier than the alternatives:

1. Mousing to another window. This is the slowest and most inefficient way. You want to avoid the mouse as much as you can. Even if you use Mission Control, you still need to find the correct window.

2. Mousing to an app icon. This is about equal to the previous option, but still is very inefficient. The app icons are in order, but it requires you to use the mouse, and if you have more than one window open in the app, you need to then click to the correct one.

3. `cmd+tab`ing to another app. This is better, but if you have 19 apps open like me, it's too much friction to find the icon and tab the correct number of times, which is different every time and cannot be done by memory.

Keyboard shortcuts on Mission Control make things so easy. All you need to do is `ctrl+left` and `ctrl+right` to move between desktops.  **This is faster than turning my head to look at a second monitor, so I don't even use a second monitor these days.** Turning your head takes more effort than pressing a keyboard shortcut, which has interesting implications. With a focus on one app or group of apps per desktop, it's like having the benefits of multiple desktops, with as many as you want.

## Desktops

### Desktop 1: Text editor

I only have my text editor, used for software development, open on this desktop. I often have more than one window open, each with many tabs. I can navigate between windows using `alt+tab` and `alt+tab+shift`, navigate between tabs using `ctrl+tab` and `ctrl+tab+shift`, and navigate between files using `cmd+p` and typing in a few characters from the file I want.

### Desktop 2: Browser

 As you'll read about in the Browser section, I often have many tabs and windows open. I can navigate between windows using `alt+tab` and `alt+tab+shift`, and if I have more than a few windows open, I just open up Mission Control with `ctrl+up` and mouse to the one I want. To navigate between tabs, I use `ctrl+tab` and `ctrl+tab+shift`.

### Desktop 3: Email

I personally use the Fluid app wrapped around two accounts each of Google Inbox and Google Calendar, but this works for whatever email client you use. I like to keep my email client full-screen and on its own desktop, so I can quickly go to and from email mode, which is important since I get a lot of email. I don't have more than one window open, but since I have four tabs, I use `alt+cmd+left` and `alt+cmd+right` to navigate between the four tabs.

### Desktop 4: Chat

Everybody chats. It's just a matter of what chat apps you use. I personally use Slack, Messages, Facebook Messenger, and Skype, in that order, which I'll explain below in another section. Each chat app does not deserve its own desktop, that would just be too cumbersome, as we need the smallest number of desktops that still allows clean separation. I keep Slack taking up about half the screen on the left. The Messages buddy list anchored to the right, with the Messages window open about 40% wide and 60% tall, anchored to the top right, next to the buddy list. The Skype and Facebook Messenger fight for the remaining space at the bottom, because I don't use them as much. I navigate between windows using `alt+tab` and `alt+tab+shift`, and each chat app has its own keyboard shortcuts, too.

### Desktop 5: Notes

I like Evernote, but I used to use the Notes app that came with OSX. Regardless of which notes app you use, you should be using it a lot to organize your thoughts, keep important data, brainstorm, schedule, etc. I usually have a short-term high-priority note open, which is important to be able to tab to quickly as I use any other app.

### Desktop 6: Todo

This covers tasks, reminders, scheduling, and reminders.If you're not using an app to manage your todo list, you could likely benefit from doing so. I think Wunderlist is fantastic for a personal todo list, and I view my todo list as a first-class resource, not something I should be accessing in a browser tab. I tab to and from Wunderlist many times throughout the day, as I complete tasks, add new tasks, reschedule tasks, etc. It's important to be able to get in and get out quick.

### Desktop 7. Music and Utilities

The last desktop. I use this for iTunes, Hermes, and Activity Monitor, but you might have different music and utility apps you want open. This is the least important desktop, as I can do most music-related tasks using the `F7`-`F12` keys, and I don't need to use Activity Monitor very often.

## Other Considerations

**Why this order? What about another desktop order?** No problem, you can order your desktops in any order you want. But this is the order that works for me. I kind of order it by relatedness. I often need to go from the text editor to the browser, so those should be right next to each other. The browser's other best friend is your email client, so those should also be right next to each other. Chat is the next-most used app and is more related to email than software development, so that's why it's to the right of the email desktop. For Notes, Todo, and Music and Utilities, it doesn't really matter what order they're in, but I keep them to the right, closer to Email and Chat.

**What about Finder?** I just keep random finder windows between any desktops. I often need finders near my text editor (for better file manipulation than what the text editor offers), browser (for uploading), my email client (for adding attachments or opening downloading files), and my chat apps (for sending cat pictures, obviously). I rarely need Finder in the other desktops, but I have that option available to me.

**What about the terminal?** You might have noticed that I didn't mention a terminal app, like Terminal or iTerm. I used to use Terminal, and had one additional desktop all the way on the left, but recently switched to iTerm, with one of the main features being that I can hide iTerm and bring it to the foreground at will, available on all desktops. I like to have one half terminal next to two quarter terminals, and other times, like to have four quarter terminals, although people who use the terminal less might be happy to just anchor one terminal to the bottom. I toggle the visibility of iTerm using `alt+space`, which is very convenient, because sometimes I like to use the terminal when coding, and other times I like to use the terminal when reading documentation or at other websites in my browser.. I navigate between terminals using `alt+cmd+left`, `alt+cmd+right`, `alt+cmd+up`, and `alt+cmd+down`.

**What about XYZ App which I use every day?** Yes, of course, make a desktop for it and put it there! And if I have categorioes of apps that you don't use, you should remove those desktops as well. Everybody uses different software, but this strategy can be useful to you regardless of what software you use.

## Feedback

If you have any ideas for things to add or change, or just have any questions about these strategies, feel free to post a comment or shoot me an email. All feedback is appreciated!

## Next Post

This is the first post of a series. I don't know what order I'll go in yet, but I plan to share more about how I optimize everything I do on the computer, including the tools I use every day as a software engineer.

*Thanks to ___ for reading drafts of this.*
