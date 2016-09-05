# Zulip User Documentation (draft)

**Caveat**: This file is intended to collect all proposed user documentation into one place. Ultimately, a single file is probably not the best format for documentation when it is published to the world, but for purposes of discussion it seems easiest to put everything into a solitary and linear page.

---

Zulip is a chat app. Its most distinctive characteristic is that conversation among a group of people can be divided according to subject "**streams**" and further subdivided into "**topics**", so much finer-grained conversations are possible than with IRC or other chat tools. 

Most people use currently Zulip on the Web. There are also versions for Android/iOS, and for Mac/Linux/Windows, as well as a cross-platform version and a version for Platform 9. See https://zulip.tabbott.net/apps for more information. 

One Zulip account, associated with a particular organization, is known as a "**realm**". 

# Table of contents:

**[The Zulip browser window](#the-zulip-browser-window)** |
**[Posting and replying](#posting-and-replying)** |
**[Other common questions](#other-common-questions)**

---

## The Zulip browser window

 * There are three panes in your browser window. 
    
   The middle one, the "**message table**",  is the stream of messages.
    
   To its left is the "**left sidebar**", showing "filters" or "views" for different kinds of messages, and below it a menu of streams you are subscribed to:
    
   ![Left sidebar](images/left_sidebar.png)

   On the right side of the browser window is the "**right sidebar**", showing users and some configuration settings:
    
   ![Right sidebar](images/right_sidebar.png)
   
   **[Go back to "The Zulip browser window"](#the-zulip-browser-window)** | **[Go back to "Table of contents"](#table-of-contents)**
    
 * If your browser  window is narrow, you'll see only the message table, or the message table and the left sidebar but not the right sidebar.
 
**[Go back to "The Zulip browser window"](#the-zulip-browser-window)** | **[Go back to "Table of contents"](#table-of-contents)**

---

## Posting and replying

**[… To a stream](#posting-and-replying-to-a-stream)** |
**[… To individual users](#posting-and-replying-to-individual-users)** |
**[Some facts about messages](#some-facts-about-messages)** |
**[Editing past messages](#editing-past-messages)**

At the bottom of your screen, choose whether to post to a stream or to individual users. ![New message](images/new_message.png)

### Posting and replying to a stream
    
 1. Click "New stream message" at the bottom of your screen (or select a stream from the list on the left side of your screen). ![Post to stream](images/post_to_stream.png)
    
 1. Enter a stream name, or the beginning of one. Private ("invite-only") streams show a lock next to the name.
    
 1. Enter a topic name — we recommend keeping them brief, and they are truncated after 50 characters.
    
 1. Enter your message.
 
**[Go back to "Posting and replying"](#posting-and-replying)** | **[Go back to "Table of contents"](#table-of-contents)**

### Posting and replying to individual users ("PM": private message) ![Post to user](images/post_to_user.png)

 * Enter the name or email address of a user, or the first letters of one. There is no topic when you PM someone.

 * You can send a message to multiple users at once, by separating their email addresses with a comma. Each recipient will see all the other recipients. For several days, the list of recipients will appear under "GROUP PMs" at the lower right corner of your screen.

 * You can ping other users with a particular stream-message from within the body of the message itself. Type `@` and the beginning of their email address or one of their names, and the system will offer you tab-completions. The completed ping will look something like this: `@**name@email.address**`, and it will appear as **@name** in your posted message.
    
 * If you're bashful about using the pronoun "I", you can get your own registered name to appear boldfaced in a message by entering `/me`. At present it has to be the first thing on a line, and followed by at least one non-space character. Some people find it easier to say things like `/me is puzzled` or `/me nods` than to use a massively freighted word like "I".
 
**[Go back to "Posting and replying"](#posting-and-replying)** | **[Go back to "Table of contents"](#table-of-contents)**

### Some facts about messages

 * The paperclip icon (![paperclip](images/paperclip.png)) under the message field lets you attach files, including images, sound, and video. These are uploaded to a server, but we display a thumbnail if we can.

 * Zulip uses a subset of [GitHub Flavored Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables) (GFM), and the **A** icon under the message field brings up a cheat-sheet for what we support. You can also see that cheat-sheat by going to the cog (![cog](images/cog.png)) in the upper right corner of the right sidebar and choosing "Message formatting" from the drop-down menu.

 * If a message is interrupted before you send it, the next time you open the "New stream message" interface you'll see "Restore draft" below the message field. Currently we only save a single interrupted message, and if you leave the Zulip site the message will be deleted.

 * Type a tab and then the "return" key to click the Send button without having to use your mouse.

 * Typing "return" will begin a new paragraph within your message; if you want it to send, check the "Press Enter to send" box under the message field. It stays checked until you uncheck it.

 * If you want greater separation of your paragraphs, enter a non-breaking space (option-space on Macintosh) on a line alone between other paragraphs.
 
**[Go back to "Posting and replying"](#posting-and-replying)** | **[Go back to "Table of contents"](#table-of-contents)**

### Editing past messages

 * If you want to edit a past message of your own after it has been posted, make sure the mouse is over that message. You should see a little pencil ![pencil](images/pencil.png) at the end of the message and a "down-chevron" ![down chevron](images/down_chevron.png) near the upper right corner of the message. Clicking either one of these will give you editing options.

 * If you completely delete the text of a message, you won't be able to save it — so try putting a dash or "(deleted)" in as the message text. The fact that there was once a message there will still be evident, and the time stamp of the original posting date and time will still be shown.
    
 * After you have edited a message, `(EDITED)` appears over the message and to the right of your name.
    
 * Editing topic titles is discussed in a separate answer, **[below](#editing-a-topic-title)**.
 
**[Go back to "Posting and replying"](#posting-and-replying)** | **[Go back to "Table of contents"](#table-of-contents)**

---

## Other common questions

**[Searching](#searching)** | 
**[Date of a message](#date-of-a-message)** | 
**[Show only particular messages](#show-only-particular-messages)** |
**[Change topic title or stream name](#changing-the-title-of-a-topic-or-stream)** | 
**[Edit topic titles](#editing-a-topic-title)** | 
**[Keyboard shortcuts](#keyboard-shortcuts)** | 
**[Message formatting](#message-formatting)** | 
**[Search for past messages](#searching-for-past-messages)** | 
**[User status](#user-status)** | 
**[Interact with Zulip by email](#interacting-with-zulip-by-email)** | 
**[Customization](#customization)** 


### Searching

Zulip searches incrementally (and case-independent) as you type, but will only match your typing at the beginning of a stream name. So typing _el_ won't bring up "Help", but _he_ will.

**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Date of a message

If you "mouse over" the time stamp of a message (upper right corner of the message), you'll see a fuller date-time stamp and time zone.

**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Show only particular messages

 * Show only messages in a particular stream

   This is called "narrowing" to a stream. The simplest way is by clicking on the stream's name in the left sidebar.

 * Show only messages in a particular topic

   Click on the topic, on a message containing it in the message table. You can do the same thing by clicking on a stream in the left sidebar to open a list of recent topics, and then click on a topic there. Only the most topics are listed, though; if you want to find an older topic, you may have to use the search box (above the message table) or scroll back in time by hand.

 * Show only messages with a particular user

   Click on the user's name in the right sidebar and your PM history will appear. If you have had group-PM conversations, they will only show up if you "narrow to" private messages with all participants — narrowing to just one user will not show group PMs including that user.
   
**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Changing the title of a topic or stream

If discussion drifts, at what point should the title of a topic or stream be changed?

In the end, this is a question of realm culture. 

 * **Topics**: Topics drift more often than streams. Some people like to announce that they are "moving" or "forking" the topic and then creating a new topic with its own title — the new title could, if you wish, say "was 'former topic'" or "forked from 'previous topic'". Also, please see **[Editing a topic titles](#editing-a-topic-title)**, below.

 * **Streams**: If a stream has to be divided, it is best if the original stream name be retired, otherwise it may prove hard to keep the separated-out subject from reappearing in the original stream. This is is an issue for administrators to watch for.
 
**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Editing a topic title

As long you have contributed a message to that topic, you can edit the topic title. Go to one of your own messages in that topic and follow the instructions for editing it. The topic title is now editable. You will be offered the chance to change the topic in one of three ways: 
    
 * Change only this message topic
 * Change later messages to this topic
 * Change previous and later messages to this topic
 
**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Keyboard shortcuts

Go to the cog (![cog](images/cog.png)) in the upper right corner of the right sidebar and choose "Keyboard shortcuts" from the drop-down menu.

**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Message formatting

Zulip uses a subset of [GitHub Flavored Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#tables) (GFM), To see the current subset, go to the cog (![cog](images/cog.png)) in the upper right corner of the right sidebar and choose "Message formatting" from the drop-down menu.

**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Searching for past messages

It is possible to do limited searches on past messages. Some special features and limitations:

 * If there are many hits, only the most recent ones are returned.
    
 * Searching by date isn't currently possible. 

 * Search hits include morphological variants by default (if you search for _walking_ you'll also get _walk_, _walks_, _walked_, and so on). Sometimes putting a search term in quotes seems to eliminate the morphological variants, but that behavior isn't consistent right now.

 * It's possible to combine search terms within parentheses using logical operators — searching for `("arrays" and "queues")` will return only those messages containing both _arrays_ and _queues_.

 * Many common words are "stop words" — the search tool will ignore them, because they appear in too many messages to be useful.
    
 * To see a list of search operators, go to the cog (![cog](images/cog.png)) in the upper right corner of the right sidebar and choose "Search help" from the drop-down menu.
 
**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### User status

… is marked by little circles to the left of a user's name:

 * A green circle (![green circle](images/green_circle.png)) means the user is "active" — the browser has determined that the Zulip page has "focus" at the moment on the user's computer.

 * A orange half-filled circle (![orange half circle](images/orange_half_circle.png)) means the user is "not active" but was recently so.

 * A white, circle (![white empty circle](images/white_empty_circle.png)) means the user is not active and was not recently so.

 The same information is available by mousing over a given user's name.

 If you have messaged multiple individual users, their names will appear at the bottom of the right sidebar. In that case, a pale green circle (![pale green circle](images/pale_green_circle.png)) means that some are recently but not currently active, while others are state unknown. A regular green circle (![green circle](images/green_circle.png)) means they are all at least recently active. 
 
**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Interacting with Zulip by email

You can receive all activity from all streams, or just some streams, or just messages in which you were mentioned, by playing with the Settings — go to the cog (![cog](images/cog.png)) in the upper right corner of the right sidebar and choose "Settings" there. You can also post to a stream by email — the Manage Streams pane shows you the email address to use for any particular stream.

**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

### Customization

 * **Zulip**. For customizing Zulip itself, there is a cog (![cog](images/cog.png)) in the upper right corner of the right sidebar, and it brings up a menu of options.
 
 * **Streams**. For customizing your stream subscriptions and individual streams, you can either use the "Manage Streams" menu-option under the main cog, or use the smaller cog above the list of streams in the left sidebar. The message table will be replaced with a "Streams" pane. (You can also get to this pane using the cog-icon above the list of streams in the left sidebar.) On the Streams pane you can create streams, subscribe or unsubscribe to existing streams, subscribe other people, mute or unmute a stream, and control a stream's color and notification settings.

   For customizing an individual stream without opening the Streams pane, there is a "down-chevron" ![down chevron](images/down_chevron.png) to the right of each stream-name in the left sidebar. Clicking the chevron opens a menu of options.

   Special things you can do with a stream you are subscribed to:

   * Turning off ("muting") a stream, while staying subscribed to it.

   * "Pinning" a stream (moving it to the top of the list of streams).

   * Marking all messages as read.

   * Choosing a custom color.

   You can leave the Streams pane by clicking on Home near the top of the left sidebar.

 * **Other customizations** are available in the Settings pane. Please experiment with them.
 
**[Go back to "Other common questions"](#other-common-questions)** | **[Go back to "Table of contents"](#table-of-contents)**

[end]
