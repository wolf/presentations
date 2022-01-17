%title: Modern Shell Tools
%author: Wolf
%date: 2022-02-08

-> # Modern Shell Tools <-
-> ## MUG Presentation by Wolf, 8 February 2022 <-

---

-> # Who am I? <-

* Wolf
^
* Long-time software engineer
^
* I'm a strong fan of automation.  That colors this presentation
^
* Standard editor disclaimer:
^
    * I have no problem with Emacs; but I also have almost no knowledge of Emacs
    ^
    * Vim is typically my editor of choice.  That also colors this presentation a bit
    ^
    * Where tools covered here have key-bindings, they provide for both Emacs and Vim
    ^
* I'm a heavy Bash user.  I don't have a ton of knowedge about other shells
^
    * Where I know, I'll mention shells that **don't** run particular tools

---

-> # What I'm going to talk about <-


* tldr
^
* bat
^
* as-tree
^
* sd
^
* amber: ambs, ambr
^
* exa
^
* jq
^
* HTTPie: http, https
^
* McFly
^
* fd
^
* ripgrep: rg
^
* fzf

---

-> # Does the command-line still matter? <-
^



-> **Yes** <-

---

-> # tldr <-
-> ## "Simplified and community-driven man pages" <-


* man pages are long and tedious.  Sometimes you just need a few examples
^
* [The tldr project](https://tldr.sh) provides [a list of clients](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients) with installation instructions
^
* I'm using the ["tealdear"](https://github.com/dbrgn/tealdeer) implementation.  It's written in Rust
^
* No config needed; but if your client supports caching, load it with: tldr -u
^
* Not everything is covered, but they accept pull requests
^
* Doesn't replace man, it's just your first (and sometimes only) stop along the path

---

-> # bat <-
-> ## A cat clone with syntax highlighting and Git integration <-


---

-> # as-tree <-
-> ##  <-


---

-> # sd <-
-> ## An intuitive find & replace CLI <-


---

-> # amber <-
-> ## Code search and replace tool <-


---

-> # exa <-
-> ## A modern replacement for ls <-


---

-> # HTTPie <-
-> ## Command-line HTTP and API testing client <-


---

-> # jq <-
-> ## Play with JSON as easily as sed, awk, and grep play with text <-


---

-> # McFly <-
-> ## Fly through your shell history <-


---

-> # ripgrep <-
-> ##  <-


---

-> # fd <-
-> ## A simple, fast, and user-friendly alternative to find <-


---

-> # fzf <-
-> ## This one's a big deal and I've got a lot to say about it <-


---

-> # fzf out of the box <-


---

-> # Building with fzf <-


---

-> # fzf in Vim <-


---

-> # fzf + Git: forgit <-


---

-> # Honorable mention: nvim <-
-> ##  <-


---

-> # Honorable mention: Nerd Fonts <-
-> ##  <-


---

-> # Wrap-up <-
-> ## What we covered <-


* tldr
* bat
* as-tree
* sd
* amber: ambs, ambr
* exa
* jq
* HTTPie: http, https
* McFly
* fd
* ripgrep: rg
* fzf
* Nerd Fonts
* Bash
* Homebrew

---

-> # Colophon <-
-> ## You probably don't want to know, but I always get asked <-


* I'm doing this presentation on a Mac and connecting to an Ubuntu server
* I'm using (if I remember to start it) the open source tool [KeyCastr](https://github.com/keycastr/keycastr) to show my actual typing on-screen
* My Mac is running macOS 12.1; GNU Bash 5.1.16
* My server is running Ubuntu 20.04.3; and is also at GNU Bash 5.1.16
* I'm giving this presentation with [mdp](https://github.com/visit1985/mdp); but I'm providing the slides as a PDF
* My terminal app is [iTerm2](https://iterm2.com/) version 3.4
* I'm using the open source font [JetBrainsMono Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/JetBrainsMono.zip); here's the [original unmodified JetBrains Mono](https://www.jetbrains.com/lp/mono/)
