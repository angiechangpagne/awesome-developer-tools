# Awesome Developer Tools

# Contents
- [Desktop Apps](#desktop)
- [Command Line Apps](#command-line)
- [Text Editors](#text-editors)
- [Web Browsers](#web-browsers)
- [Cloud Solutions](#cloud-solutions)
- [Dotfiles](#dotfiles)
- [Third Party Lists](#third-party-lists)

# Desktop

## [CloudApp](https://www.getcloudapp.com/) - Screenshots, GIFs, and videos with annotation, security controls, and cloud storage

## [ShiftIt](https://github.com/fikovnik/ShiftIt) - Window sizing and positioning

  - Includes an "Increase Size" hotkey that other apps like Spectacle might not have

## [BeardedSpice](https://beardedspice.github.io/) - Media hotkeys to control Spotify or other preferred music players

## [Insomnia](http://insomnia.rest/) - REST Client with a great UI

  - Paste cURL commands into the URL bar (including those copied from Chrome Network tab)
  - Organize commands into folders, and quickly search the folders by folder name, URI, command name
  
<img src="https://insomnia.rest/static/main-ac0a1732afac19acce5ad6825595c3bb-f3479.webp">

## [Alfred](https://www.alfredapp.com/) - Spotlight search alternative

  - Clipboard manager with search history
  - Snippets with some scripting and templating capabilities
  - Search for Chrome or Safari bookmarks

## [Shift](https://tryshift.com/) - Interface container for Gmail/Inbox, Google Calendar, Google Drive

  - There are many good alternatives, but notifications never seem to work for me for the alternatives, for example:
    - Franz
    - Station
    - WaveBox

<img src="https://tryshiftcdn.com/static/images/v2/shift20@2x.gif"> 

## [Magnet](http://magnet.crowdcafe.com/)

*Window manager for mac*

- Snap windows to halfscreen, fullscreen
- Keyboard shortcuts for moving windows around

## [Transmit 5](https://panic.com/transmit/)

*FTP/SFTP/AWS/etc file transfer*

- Transmit now connects to 11 new cloud services, like Backblaze B2, Box, Google Drive, DreamObjects, Dropbox, Microsoft Azure, and Rackspace Cloud Files. 
- Mount cloud service as a hard drive
- Filezilla alternative for mac

## [Little Snitch 4](https://www.obdev.at/products/littlesnitch/index.html)

*Reverse Firewall and traffic monitor*

- View and block outgoing connections
- Capture traffic by process

## [Viscosity](https://www.sparklabs.com/viscosity/)

*OpenVPN client for Mac*

- For all your VPN needs.
- Scripting behaviors for VPN events
- Menu bar icons

## [Quiver](http://happenapps.com/) 

*The programmers Notebook*

- Markdown
- Snippets
- Notes

# Command Line

## [FZF](https://github.com/junegunn/fzf) - Versatile fuzzy search tool that can be used for virtually any lists or input

<img src="https://raw.githubusercontent.com/junegunn/i/master/fzf-preview.png">

## [autojump](https://github.com/wting/autojump) - Jump to recently visited folders based on partial name match

```
30   /home/user/mail/inbox
10   /home/user/work/inbox
```

> j wor in


## [Hyper](https://hyper.is/) - iTerm2 alternative shell with text-based configuration, built on Electron

<img src="https://hyper.is/static/hyperyellow.gif">

## [Fish Shell](https://fishshell.com/) - Bash and Zsh alternative with batteries included

  - Syntax highlighting
  - Smart command completion
  
<img src="https://fishshell.com/assets/img/screenshots/autosuggestion.png">

## [Tmuxinator](https://github.com/tmuxinator/tmuxinator) - Manage complex tmux sessions easily

  - Declaritive set up of Tmux panes
  - Quickly set up your development environment
  
## [W3M](http://w3m.sourceforge.net/)
  *Text based web browser*

  - Surf the web inside the terminal
  - No images!!!
  
## [exa](https://the.exa.website/)
  *Modern replacement for ls*
  
  - Icons
  - Colors
  - Github integration

# Web Browsers

## Chrome

### Extensions

#### [Tab Wrangler](https://chrome.google.com/webstore/detail/tab-wrangler/egnjhciaieeiiohknchakcodbpgjnchh) - Auto clean up inactive tabs

  - Very customizable
  - Saves closed tabs into a searchable list

#### [Pushbullet](https://www.pushbullet.com/) - Send SMS from Chrome, or push files to or from your phone

#### [Pin Tab](https://chrome.google.com/webstore/detail/pin-tab/dgldedkigbbalaioohedddpameekglma) - Simply pin the current tab in one click

  - Good to use with Tab Wrangler, since Tab Wrangler doesn't close pinned tabs

#### [cVim](https://chrome.google.com/webstore/detail/cvim/ihlenndgcmojhcghmfjfneahoeklbjjh) - Vim hotkeys for Chrome

  - Navigate page with h/j/k/l/g/G
  - Open files with "f" key and an assigned letter for hyperlinks
  - Search browser history or bookmarks

# Text Editors

## Vim

### Plugins

#### [Vim-Fugitive](https://github.com/tpope/vim-fugitive) - Git integration with Vim

  - Git Blame view where you can press Enter to jump to commit before a change was made to a line.
  - Git Status, Git Diff, etc

#### [Vim-Dispatch](https://github.com/tpope/vim-dispatch) - Execute commands in a Tmux pane

  - Pulls results into Vim for easy paging and searching
  
#### [Ultisnips](https://github.com/SirVer/ultisnips) - Text-completion snippets with templating and scripting support


#### [Vim-Quickly](https://github.com/axs221/vim-quickly) - FZF jump-to-file alternative

  - CtrlP-like jump-to-file functionality, sorting by most recently used, visited, etc. A plugin I made that is similar to FZF, but uses more native Vim features like the quicklist for easy paging.

#### [Vim-Dirvish](https://github.com/justinmk/vim-dirvish) - Minimal file manager, light-weight alternative to NERDtree.

  - Easy to script or run commands against selected files.

# Cloud Solutions

## Task Management

### [Nuclino](https://nuclino.com)

A cloud-based outliner for taking team notes. More reasonably priced than competitors, and with a fluid UI.

### [Airtable](https://airtable.com)

Like Trello + Google Sheets.

I've heard a lot of buzz about Airtable lately and finally tried it out. It lives up to the hype I'd say. Provides Kanban like Trello, but with very flexible custom fields, different views, more powerful and seamless "powerups". Try the "group by" features - you can essentially turn *any* fields, custom or not, into its own kanban view. Extremely flexible.

### [Notion](https://www.notion.so)

Like Nuclino + Airtable.

Instead of spreadsheets being the central model, an outliner knowledge base is. But they seemed to have stole much of Airtable's Kanban capabilities. While Airtable has a few additional features, Notion integrates with its building block/knowledge base approach, such that you can have essentially an outliner/wiki within each task, and you can also use double-square-brackets to link to other permanent nodes in the knowledge base.

# Dotfiles

  - [Shawn Axsom](https://github.com/axs221/dotfiles)
    - neovim, fish shell, tmuxinator, Hyper.js, etc

# Third Party Lists

  - https://github.com/nikitavoloboev/my-mac-os
  - https://github.com/alebcay/awesome-shell

