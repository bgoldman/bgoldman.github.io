---
layout: post
section-type: post
title: There's an App for That, Part One
subtitle: How I Organize My Apps to Optimize My Life
category: Lifehacking
tags: [ 'apps', 'optimization', 'organization', 'productivity', 'software', 'tools' ]
---

I'm a big fan of optimizing everything in my life. But especially the things I do or use most often, where the optimizations can be easily noticed. As a software engineer, I spend the overwhelming majority of my workday in front of my computer. This post will focus on optimizations I've made for myself that might be of value to other people.

Over the past two years, I've changed most of what I use, and I'm pretty happy with these decisions. Hopefully this can save you some time, or introduce you to a new app that might help you with your daily workflow, or maybe more.

This post is part of a series, but this one in particular will focus on organizing apps and desktops, and touch on some useful general-purpose apps and tools. This series is from the perspective of software development; however, if you're not a software developer, most of these ideas are still relevant. Future posts will get into more detail about the hows and whys of these choices, but for the purposes of this post, you can look into the apps I like to use, or you can ignore them and use the same strategies with the apps you already use.

Let's get right into it.

## Operating System

This post focuses on Mac OSX, ideally upgraded to El Capitan. A lot of people out there like Windows and various flavors of Linux, but here in the bay area, more often than not, other software engineers I know use OSX. Some of the recommended apps may be available with other operating systems, or maybe similar apps from other developers, but the focus of this post will be assuming you have a Mac also.

## Multiple Desktops

This isn't an app, but desktop organization is a huge part of how I use my computer and how I use all of my software most effectively. I've noticed that most people don't pay any special attention to this, and this is one of the biggest areas that people can optimize. The biggest area in my opinion that people could benefit from is multiple desktops. As such, this is a good place to start for the first post of this series.

It can be extremely beneficial to take advantage of multiple desktops with Mission Control. You can personally use more or less, but I use seven desktops, and think this is a sufficient and balanced number. Rather than complicate things as someone new to multiple desktops might expect, it's simplified things for me greatly, and makes it much faster for me to do basically anything on my computer.

Switching from one desktop to another with Mission Control, using keyboard shortcuts, is far easier than the alternatives:

1. Mousing to another window. This is the slowest and most inefficient way. You want to avoid the mouse as much as you can. Even if you use Mission Control, you still need to find the correct window.

2. Mousing to an app icon. This is about equal to the previous option, but still is very inefficient. The app icons are in order, but it requires you to use the mouse, and if you have more than one window open in the app, you need to then click to the correct one.

3. `cmd+tab`ing to another app. This is better, but if you have 19 apps open like me, it's too much friction to find the icon and tab the correct number of times, which is different every time and cannot be done by memory.

Keyboard shortcuts on Mission Control make things so easy. All you need to do is `ctrl+left` and `ctrl+right` to move between desktops. **This is faster than turning my head to look at a second monitor, so I don't even use a second monitor these days.** Turning your head takes more effort than pressing a keyboard shortcut, which has interesting implications. With a focus on one app or group of apps per desktop, it's like having the benefits of multiple desktops, with as many as you want.

The bulk of this article will focus on a well-thought-out seven-desktop setup.

## Desktops

### Desktop 1: Text Editor

Your preferred text editor, used for software development, would be the only app open on this desktop. My favorite text editor is Sublime, and it happens to be something of an industry standard. It's common to have more than one window open, each with many tabs, depending on how busy you are and how many projects you work on. You can navigate between windows using `alt+tab` and `alt+tab+shift`, navigate between tabs using `ctrl+tab` and `ctrl+tab+shift`, and navigate between files using `cmd+p` and typing in a few characters from the file you want.

### Desktop 2: Browser

People use browsers differently - some people have 100+ tabs open like me, and others are good about having only a few at a time. Your preferred browser would take over this desktop. Google Chrome is the one I use, but Safari is also a popular choice. You can navigate between windows using `alt+tab` and `alt+tab+shift`, and if you have more than a few windows open, you can open up Mission Control with `ctrl+up` and mouse to the one you want. To navigate between tabs, use `ctrl+tab` and `ctrl+tab+shift`.

### Desktop 3: Email

The Fluid app, which allows you to "app-ify" any website and save it to your dock, really shines here. I use one instance with Fluid wrapped around two accounts each of Google Inbox and Google Calendar, but this works for whatever email client you use. Since it's more productive to do email in focused bursts, it's useful to keep your email client full-screen and on its own desktop, so you can quickly go to and from email mode, which is important if you get a lot of email, a problem I don't wish on anyone. You can keep one window open with multiple tabs, and use `alt+cmd+left` and `alt+cmd+right` to navigate between the different tabs.

### Desktop 4: Chat

Everybody chats. It's just a matter of what chat apps you use. I personally use Slack, Messages, Facebook Messenger, and Skype, in that order. Each chat app does not deserve its own desktop - that would just be too cumbersome, as we need the smallest number of desktops that still allows clean separation. This desktop is a bit complicated because there are four apps, so I'll explain how I personally have mine set up. I keep Slack taking up about half the screen on the left. The Messages buddy list anchored to the right, with the Messages window open about 40% wide and 60% tall, anchored to the top right, next to the buddy list. Skype and Facebook Messenger fight for the remaining space at the bottom, because I don't use them as much. You can navigate between windows using `alt+tab` and `alt+tab+shift`, and also use each chat apps' keyboard shortcuts.

### Desktop 5: Notes

Regardless of which notes app you use, you may benefit from using it a lot to organize your thoughts, keep important data, brainstorm, schedule, etc. I like Evernote, but used to use the Notes app that came with OSX. It's useful to have a short-term high-priority note open, which is important to be able to tab to quickly as you use any other app. Some people are editing their notes dozens of times per day, so it makes sense to have a dedicated desktop for it that you can switch to whenever you think of something.

### Desktop 6: Todo

This covers tasks, scheduling, and reminders. If you're not using an app to manage your todo list, you could likely benefit from doing so. I think Wunderlist is fantastic for a personal todo list, and other people swear by their todo list apps, so it makes sense for your todo app of choice to be a first-class resource, not something to should be accessing in a browser tab, that's way too much friction. You can tab to and from Wunderlist many times throughout the day, as you complete tasks, add new tasks, reschedule tasks, etc. It's important to be able to get in and get out quick up to dozens of time a day.

### Desktop 7. Music and Utilities

The last desktop. It's kind of freeform, and I use this for iTunes, Hermes, and Activity Monitor, but you might have different music and utility apps you want open, or maybe even no music at all. This is the least important desktop, as you can do most music-related tasks using the `F7`-`F12` keys, and you probably don't need to use Activity Monitor very often.

## Other Considerations

**Why this order? What about another desktop order?** Ordering by relatedness and frequency of use can help you navigate between different apps quickly. This is the order that works for me, but there might be an equally-valid but different order that works for you. For example, one would often need to go from the text editor to the browser, so those would benefit from being right next to each other. The browser's other best friend is the email client, so those should also be right next to each other. Chat is often the next-most used app and is more related to email than software development, so that's why it's to the right of the email desktop. For Notes, Todo, and Music and Utilities, it doesn't really matter what order they're in, but I keep them to the right, closer to Email and Chat.

**What about Finder?** You can just keep random Finder windows between any desktops. You may need finders near your text editor (for better file manipulation than what the text editor offers), browser (for uploading), your email client (for adding attachments or opening downloading files), and your chat apps (for sending cat pictures, obviously). You may rarely need Finder in the other desktops, but you have that option available if you need it.

**What about the terminal?** You might have noticed that I didn't mention a terminal app, like Terminal or iTerm. I used to use Terminal, and had one additional desktop all the way on the left, but recently switched to iTerm. One of iTerm's best features allows you to hide iTerm and bring it to the foreground at will, available on all desktops. A couple good layouts for this would be to have one half terminal next to two quarter terminals, and other times, to have four quarter terminals, although people who use the terminal less might be happy to just anchor one terminal to the bottom. You can toggle the visibility of iTerm using `alt+space`, which is very convenient, because sometimes you might want to use the terminal when coding, and other times you might want to use the terminal when reading documentation or when browing other websites in your browser. You can navigate between terminals using `alt+cmd+left`, `alt+cmd+right`, `alt+cmd+up`, and `alt+cmd+down`.

**What about my office apps, like word processing and spreadsheets?** If you live in one or more of these apps throughout the day, you might benefit from creating one or two desktops, and maybe getting rid of one or two others. However, if you're a software engineer, you might not need these very often, and/or might just be using Google Docs. For the occasional times you do need to use an office app, you can just keep it on the screen that is move relevant at the time, and keep it side-by-side with the app you're using it for, like typing an email or looking something up on Google.

**What about XYZ App which I use every day?** Yes, of course, make a desktop for it and put it there! And vice versa; if I've written about categories of apps that you don't use, and you want to try this, you can remove those desktops as well. Everybody uses different software, but this strategy may be useful to you regardless of what software you use.

## Feedback

If you have any ideas for things to add or change, or just have any questions about these strategies, feel free to post a comment or shoot me an email. All feedback is appreciated!

## Next Post

This is the first post of a series. I don't know what order they'll be in yet, but I plan to share more about what I've learned trying to optimize everything I do on the computer, including the tools used every day as a software engineer.

*Thanks to Nico Hinderling and Isaac Shapira for reading drafts of this.*
