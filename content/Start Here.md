## Forewords
For the rest of this tutorial, I will use terms
- "note" to refer a markdown file inside this folder / vault named "Tutorial"
- [[#Hotkeys]]: ⌘ ⌥ ⌃ will be used instead of Windows Alt Ctrl  respectively

## Welcome to my tutorial
Thank you for spending time to investigate my Tutorial vault. I hope you learn something good from this one. 


I highly recommend that you practice and get familiarized with [[Markdown Syntax]] first. I'd already prepared for you the workspace "Practice Markdown Syntax". There are 2 ways to open the workspace:
1. You can use [[#Hotkeys]] `⌘ ⌥ ⌃ W` > Load "Practice Markdown Syntax"
2. You can manually open *Command Palette* `⌘ P` > `Workspaces: Manage workspace layouts` > Load "Practice Markdown Syntax"

With this workspace, you can see all [[Markdown Syntax]] basics from the left pane while practicing in the right pane.

## Modes of using
![](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/Editor%20update%20chart.png)
There are 3 basic modes in New Editor:
- **Source mode** (behind-the-scene) use this mode when you want to closely examine and quickly edit markdown syntax
- **Live Preview mode** (all-the-time recommended) only when you move your cursor to formatted texts or codes, you can see the markdown syntax. <u>E.g.</u> try moving the cursor to **this** and you will see `**this**`
- **Reading view** (enjoy reading without editing) use this mode when you want to read only

>[!note]+ How do I know which mode I'm in ?
>- When you see book icon ![[Interface-book-icon.jpg|30]], you're in **Editing view** (Source mode / Live Preview mode)
>- When you see pencil icon ![[Interface-pencil-icon.jpg|30]], you're in **Reading view**
>- The philosophy is that when you click ![[Interface-book-icon.jpg|30]], you switch to **Reading view**
> 

> **My thoughts**: When I first used Obsidian, I hated switching back and forth between *Edit mode* and *Preview mode* using [[#Hotkeys]] `⌘ E`. "Why can't I simply type and move on with life ?" I thought. *Edit mode* (Source mode) looks like I'm coding and writing a piece of software. It may be cool or may be a mess to look at. Plus, Obsidian at that time was still in development and poorly designed. After uninstalling Obsidian and a long few months, I decided to re-install Obsidian and officially started using it since. Now, we have **Live Preview** that can make life easier, so you don't have to switch between **Source mode** and **Read mode**.

## Hotkeys 
| Mac Key     | Window Key                 |
| ----------- | -------------------------- |
| ⌘ (command) | ![[Windows.jpg]] (windows) |
| ⌥ (option)  | Alt                        |
| ⌃ (control) | Ctrl                       |
[More Basic Hotkeys](https://help.obsidian.md/Editing+and+formatting/Editing+shortcuts)

>[!note]+ How to find Hotkey setting
> - Go to Settings (`⌘ ,` in MacOS / `Ctrl ,` in Window) > In Options section: Hotkeys

>[!note]+ How to edit Hotkey
> - Click on `+` and type the hotkey combination you want for that command. If the hotkeys are already assigned to a command, it will turn red. 
> - `blank` = no hotkey assigned to that command
> - `🔄` (restore default) = clear all hotkeys assigned to that command back to default setting
> - `X` = remove the hotkey assigned to that command
> - A command can be assigned with more than 1 Hotkey

>[!note]+ How to search Hotkey
> There are 3 ways to search
> 1. Search by text from textfield: type in the command name
> 2. Search by hotkey from keyboard icon: type in the hotkeys 
> 3. Search by filter using filter icon: All (default), Assigned, Assigned by me, Unassigned

>[!note]+ Suggested setup Hotkeys
> 
> | Command                               | Suggested hotkey                 | Function                                                                                                                                       |
> | ------------------------------------- | -------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
> | Command palette: Open command palette | ⌘ P                              | You can search and activate any command from Command Palette (the most frequently used command)                                                |
> | Reload app without saving             | ⌃ R                              | Sometimes, Obsidian needed to be reloaded to function as expected                                                                              |
> | Insert callout                        | ⌘ shift C                        | Quickly insert default callout                                                                                                                 |
> | Delete current file                   | ⌘ delete                         | Quickly delete the current file                                                                                                                |
> | Rename File                           | ⌘ R                              | Quickly rename the current note                                                                                                                |
> | Set as heading x                      | ⌘ 𝓧 (where 𝓧 is heading level) | ⌘ 2 will generate heading 2<br>• I find it more useful than using it for switching tabs                                                        |
> | Cycle bullet/checkbox                 | ⌘ return                         | Quickly turn bullet list into checkbox<br>1. ⌘ return → make a bullet list<br>2. ⌘ return → make a checkbox<br>3. ⌘ return → tick the checkbox |
> | Bookmarks: Bookmark...                | ⌘ shift B                        | Bookmark the current note                                                                                                                      |
> | Audio recorder: Start recording audio | ⌘ ⌥ R                            | Start recording                                                                                                                                |
> | Audio recorder: Stop recording audio  | ⌘ ⌥ S                            | Stop recording. It will embed the recorded file at the cursor                                                                                  |
> | Clear formatting                      | ⌃ C                              | Quickly clear text format                                                                                                                      |
> | Fold More                             | ⌥ 1                              | Fold everything below the level                                                                                                                |
> | Fold Less                             | ⌥ 2                              | Unfold everything at the current line                                                                                                          |



## Interface
![[Interface#^group=BdYzPksIjI_QO2DGHoNNP|1000]]
This is the embedded image from [[Interface]] `v.1.6.4`. This interface may be different, depending on Obsidian version you're using. 

Let's familiarize yourself with Obsidian interface.

| Types         | Image                                | Comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| ------------- | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| File Explorer | ![[Obsidian-file_explorer.jpg\|300]] | • **New note** will create a new note. You can drag a note to any folder<br>• **New folder** will create a new folder. You can create subfolder within a folder<br>• **Sort** based on File name, Modified time, Created time<br>• **Collapse all / Expand all** will collapse or expand everything inside a folder<br><br>• **Folder** has icons thanks to [[Iconize]]. Without icons, you would know it's a folder if it has a toggle `>` or `V` icon<br>• **Note** can be inside a folder or outside in the root folder "Tutorial" |
| Outline       | ![[Obsidian-outline.jpg\|300]]       | • You can easily navigate long documents with headings. Thinking headings as checkpoints/milestones/portals to re-visit important ideas.<br>✽ You can search for headings by click on magnifying glass icon 🔍, especially when you have a lot of headings!<br>✽ You can collapse or expand all headings and subheadings. It's useful that you want to collapse all when you have a lot of subheadings to easily navigate.                                                                                                            |
| Tag           | ![[Obsidian-tag.jpg\|300]]           | • You can see how many times a specific tag is mentioned. When you click on a tag, the search will look for all files using that tag<br>✽ Tags can be useful to quickly see the list of all notes of the same categories, of the same authors                                                                                                                                                                                                                                                                                         |
| Ribbon        | ![[Obsidian-ribbon.jpg\|30]]         | • You can hide/show the ribbon `Setting (⌘,) > Appearance > Toggle 'Show ribbon' `<br>• You can rearrange items in the ribbon `Setting (⌘,) > Appearance > in Ribbon menu congiguration, click on 'Manage' > remove/add/rearrange items`                                                                                                                                                                                                                                                                                              |
| Bookmark      | ![[Obsidian-bookmark.jpg\|300]]      | How to add bookmark from<br>• **Files:** when in the file, `⌘ shift B` > choose a Bookmark group + may change the Title > Save<br>• **Folders:** right-click the folder > `Bookmark...`<br>• **Headings:** right-click the heading > `Bookmark this heading...`<br>• **Blocks:** when cursor at the line > open command palette `⌘ P` > `Bookmarks: Bookmark block under cursor...`<br>• **Searches:** click on `x results ...` > `Bookmark...`<br>• **Graphs:** when in the graph, `⌘ shift B`                                       |

>[!note]+ Note
> - You can toggle show/hide sidebar by using [[#Hotkeys]] or simply click on sidebar icon ![[interface-left_bar.jpg|30]] or ![[interface-right_bar.jpg|30]]
> - You can rearrange any components by dragging them around. E.g. you can move "Search" to the left sidebar by dragging ![[interface-search.jpg|30]] to the left sidebar and dropping it, say, next to the bookmark icon

>[!tip]+ Tip
> - When naming a note, try not to name identi
## Themes
>[!note]+ How to add more themes	?
> Go to Setting `⌘,` > Appearance > in Themes, click 'Manage' to select a theme > Install and use

>[!note]+ How to uninstall a theme ?
> Go to Setting `⌘,` > Appearance > in Themes, click 'Manage' > toggle 'Show installed only' to see all the installed themes > select a theme > Uninstall

>[!note]+ [[#Hotkeys|Hotkey]] to quickly switch between themes
> `⌃ ⌥ ⌘ T`

## Markdown Syntax
[[Markdown Syntax]]

## Author's Note
Not every system is perfect. Not every system can work for everyone. My advice is to take whatever methods or workflows from this tutorial that work for you, to enhance your own system. 

There is a lot more that I have not covered yet. I believe this vault will prepare you with all the basics needed for your journey to second brain system. No time wasted to figure it out on your own. Start doing what matters to you, and start small. It takes time to build up. Any system needs to be used and maintained or it will become irreverent and outdated.

### My use cases
- **Writing Journal** 
- **Writing Lyrics**
- **Learning notes**
- **My Collection List** I call it "The List" of everything, from collection of books, apps, plug-ins, meetings, emails, ...
- **RPG Campaigns**
- **Article collector**
- **Password Manager**
- **Film / TV series summaries** 

There are a lot that you can do with your second brain system (Personal Knowledge Management / Personal Wikipedia). In my use cases, I use it for writing journal/diary, novels, essays, collections of any kind (books, articles, personal items), password manager (I rather take note of my passwords manually cause I don't trust in Safari password manager; sometimes it forgets to save my passwords), memoir to remember important info, and much more. Some people use it for keeping track of their health/mood/finance, to-do list, RPG game campaigns, 

If you have any question, feel free to contact me at vuhaonhien2112@icloud.com

