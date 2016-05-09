autoscale: true

![][title]

# [fit] Vim for
# [fit] Mere Mortals

[@VimIndy][vimindy] 06.2016

-------------------------------------------------------------------------------

# [fit] __Who__ am I?

![][claytron-avatar]

[@claytron][claytron] on the internets

Senior Software Engineer at TinderBox ![fit][tinderbox]

Vim Evangelist

-------------------------------------------------------------------------------

## [fit] ![inline][vim-logo] **is** hard.

^ Steep learning curve.
Take it one step at a time.
Vim used in other editors, not reverse.

-------------------------------------------------------------------------------

Don't rage `:quit!` just yet...

-------------------------------------------------------------------------------

![350%][fundamentals]

# [fit] Fundamentals

-------------------------------------------------------------------------------

> You start by learning the minimal to survive, then you integrate all the tricks slowly.
-- [Learn Vim Progressively][learn-vim-progressively]

^ Excellent post.
You Should read it!

-------------------------------------------------------------------------------

`$ vimtutor`

^ Get used to the default controls.
Build a strong basis in Vim usage.

-------------------------------------------------------------------------------

`:Tutor`

in [Neovim][neovim]

^ Built in to Neovim.
Available as [vim-tutor-mode][vim-tutor-mode] plugin.
Some plugins have written tutorials.

-------------------------------------------------------------------------------

![900%][first-aid]

# [fit] Help!

-------------------------------------------------------------------------------

`:help`

^ There is always help available.

-------------------------------------------------------------------------------

`:help help`

-------------------------------------------------------------------------------

```
For any topic :help syntastic
For an option :help 'syntastic_ignore_files'
For a command :help :SyntasticInfo
```

^ Help subjects have syntax.

-------------------------------------------------------------------------------

`:helpgrep syntastic.*checker\c`

^ Search through the help.
It is hardcore, like vim itself.

-------------------------------------------------------------------------------

`:tab help intro`

^ Easier to read in a tab.

-------------------------------------------------------------------------------

```vim
1. Help commands					*online-help*

			*help* *<Help>* *:h* *:help* *<F1>* *i_<F1>* *i_<Help>*
<Help>		or
:h[elp]		Open a window and display the help file in read-only
			mode.  If there is a help window open already, use
			that one.  Otherwise, if the current window uses the
			full width of the screen or is at least 80 characters
			wide, the help window will appear just above the
			current window.  Otherwise the new window is put at
			the very top.
```

^ Quick aside.
Most commands have shortcuts.

-------------------------------------------------------------------------------

![][help]

VimIndy Slack.

`#vim` on Freenode.

[Vi and Vim][vi-stackexchange] StackExchange.

-------------------------------------------------------------------------------

![][sensible]

Use [vim-sensible][vim-sensible] to start out.

Or go all in with [Vim Bootstrap][vim-bootstrap], [Janus][janus] or [spf13][spf13].

^ Sensible is a nice starting point.
Janus is over the top and opinionated.

-------------------------------------------------------------------------------

![][arrow-keys]

# **Arrow** Keys?

^ Don't worry about forcing `hjkl` at first!
We want to make the switch as easy as possible.
Turn on `hardmode` if you want.

-------------------------------------------------------------------------------

> Experienced users prefer the hjkl keys because they are always right under their fingers.

-------------------------------------------------------------------------------

> Beginners often prefer the arrow keys,
> because they do not know what the hjkl keys do.

-------------------------------------------------------------------------------

> The mnemonic value of hjkl is clear from looking at the keyboard.
> Think of j as an arrow pointing downwards.
-- :help motion.txt

-------------------------------------------------------------------------------

![350%][modal]

# [fit] **Modal** Editing

^ This is what makes Vim powerful.
But confuses newbies.

-------------------------------------------------------------------------------

**Normal**
Visual
Select
**Insert**
**Command**
Ex

^ Vim has 6 basic modes.
We'll focus on these three.

-------------------------------------------------------------------------------

> How do you generate a random string?

-------------------------------------------------------------------------------

> Put a first year CS student in front of Vim and tell them to save and exit.

-------------------------------------------------------------------------------

**Normal** Mode

^ This is the mode you start in.
And the start of the confusion.
All your keys are now shortcuts.

-------------------------------------------------------------------------------

**Insert** Mode

^ Just like it sounds.
This is the only mode of most editors.

-------------------------------------------------------------------------------

**Command** Mode

^ This is a way to interact with Vim.
Run commands, change settings, etc.

-------------------------------------------------------------------------------

![70%][speak-vim]

# [fit] Vim! Do you **speak** it?

^ Once you know the basics, learn to speak vim.

-------------------------------------------------------------------------------

`ggguG`

<sub>the jerry yang treatment.</sub>

-------------------------------------------------------------------------------

![][plugins]

## [fit] Plugins

^ Enhance the editor.
You will be doing this very soon.

-------------------------------------------------------------------------------

# **Plugin** Managers

Pathogen
Vundle
**vim-plug**
vim-addon-manager
dein.vim
Vizardry
Vimana

^ There are a lot of choices.
Just use `vim-plug`!

-------------------------------------------------------------------------------

# Install **Plugins**

```vim
call plug#begin()
Plug 'tpope/vim-sensible'
Plug 'scrooloose/syntastic'
call plug#end()
```

-------------------------------------------------------------------------------

![][pillaging]

# [fit] Pillaging **`.vimrc`**

-------------------------------------------------------------------------------

# [fit] THE **END**

-------------------------------------------------------------------------------

# Links

- [@VimIndy][vimindy]
- [vim.org][vim]
- [Neovim][neovim]
- [Help always in a tab][vim-help-tab]
- [VIM: Hard Mode][hard-mode]
- [vim-galore: Everything you need to know about Vim][vim-galore]

![right filtered][links]

-------------------------------------------------------------------------------

### Screencasts

- [Vimcasts][vimcasts]
- [Derek Wyatt Tutorials][derek-wyatt-tutorials]

![right filtered][links]

-------------------------------------------------------------------------------

### Articles / Books

- [Learn Vim Progressively][learn-vim-progressively]
- [Coming Home to Vim][coming-home-to-vim]
- [Everyone Who Tried to Convince Me to use Vim was Wrong][yehuda-rant]
- [Learn to Speak Vim][learn-to-speak-vim]
- [Vim Text Objects: The Definitive Guide][vim-text-objects]
- [Practical Vim][practical-vim]

![right filtered][links]

-------------------------------------------------------------------------------

# Photo Credits

![][title] Title ([B.B. Wijdieks][title-credit])
![][fundamentals] Fundamentals ([@nobida][fundamentals-credit])
![][first-aid] Help ([@mountaineer4061][first-aid-credit])
![][sensible] Sensible ([@matt_gibson][sensible-credit])
![][arrow-keys] Arrow Keys ([@regocasasnovas][arrow-keys-credit])
![][help] Help ([@carbonated][help-credit])
![][modal] Modal ([@chrisobayda][modal-credit])
![][speak-vim] Do you speak it? ([@reallyboring][speak-vim-credit])
![][plugins] Plugins ([@chicagobart][plugins-credit])
![][pillaging] Pillaging ([Damian Gadal][pillaging-credit])
![][links] Links ([@volvob12b][links-credit])
:arrow_left: This Picture ([@rhodes][images-credit])

Thanks to [![][flickr-logo]][flickr]<br>and [![][cc-logo]][cc]

![left filtered][images]

-------------------------------------------------------------------------------

[![inline 200%][cc-by-sa-4-0-logo]][cc-by-sa-4-0]

Vim for Mere Mortals by [claytron][claytron] is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa-4-0].

-------------------------------------------------------------------------------

```
											*bar*
|			To screen column [count] in the current line.
			|exclusive| motion.  Ceci n'est pas une pipe.
```

[//]: # ( Links                                                               )
[//]: # ( ------------------------------------------------------------------- )
[vimindy]: https://twitter.com/vimindy
[claytron]: http://twitter.com/claytron
[claytron-avatar]: images/claytron.jpg
[tinderbox]: images/TinderboxLogo.png
[vim-logo]: images/vim-logo.png
[vim]: http://www.vim.org/
[vim-tutor-mode]: https://github.com/fmoralesc/vim-tutor-mode
[neovim]: https://neovim.io
[vim-sensible]: https://github.com/tpope/vim-sensible/
[vim-bootstrap]: http://vim-bootstrap.com/
[janus]: https://github.com/carlhuda/janus/
[spf13]: https://github.com/spf13/spf13-vim
[vi-stackexchange]: https://vi.stackexchange.com
[vim-help-tab]: https://github.com/claytron/dotfiles/blob/bfb8a497f1fd770cbed612f9401a7a335736e8ff/.vimrc#L731
[hard-mode]: https://github.com/wikitopian/hardmode
[vim-galore]: https://github.com/mhinz/vim-galore
[vimcasts]: http://vimcasts.org/
[derek-wyatt-tutorials]: http://derekwyatt.org/vim/tutorials/
[learn-vim-progressively]: http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/
[coming-home-to-vim]: http://stevelosh.com/blog/2010/09/coming-home-to-vim/
[yehuda-rant]: http://yehudakatz.com/2010/07/29/everyone-who-tried-to-convince-me-to-use-vim-was-wrong/
[learn-to-speak-vim]: http://yanpritzker.com/2011/12/16/learn-to-speak-vim-verbs-nouns-and-modifiers/
[vim-text-objects]: http://blog.carbonfive.com/2011/10/17/vim-text-objects-the-definitive-guide/
[practical-vim]: https://pragprog.com/book/dnvim2/practical-vim-second-edition

[//]: # ( Online Videos                                                       )
[//]: # ( ------------------------------------------------------------------- )

[//]: # ( CC Images                                                           )
[//]: # ( ------------------------------------------------------------------- )
[title]: images/title.jpg
[title-credit]: https://flic.kr/p/jaYcP6
[fundamentals]: images/fundamentals.jpg
[fundamentals-credit]: https://flic.kr/p/cmBpNL
[first-aid]: images/first_aid.jpg
[first-aid-credit]: https://flic.kr/p/5qrhwr
[sensible]: images/sensible.jpg
[sensible-credit]: https://flic.kr/p/dMBvmp
[arrow-keys]: images/arrow_keys.jpg
[arrow-keys-credit]: https://flic.kr/p/7vSVVd
[help]: images/help.jpg
[help-credit]: https://flic.kr/p/3q8dM
[modal]: images/modal.jpg
[modal-credit]: https://flic.kr/p/bZDVDs
[speak-vim]: images/speak_vim.jpg
[speak-vim-credit]: https://flic.kr/p/5bwqyZ
[plugins]: images/plugins.jpg
[plugins-credit]: https://flic.kr/p/7SQuUv
[pillaging]: images/pillaging.jpg
[pillaging-credit]: https://flic.kr/p/58ifNU
[links]: images/links.jpg
[links-credit]: https://flic.kr/p/fTfXkN
[images]: images/images.jpg
[images-credit]: https://flic.kr/p/dDdb1M
[cc-logo]: images/cc.logo.large.png
[cc]: https://creativecommons.org
[flickr-logo]: images/flickr.png
[flickr]: https://www.flickr.com

[//]: # ( CC Attribution                                                      )
[//]: # ( ------------------------------------------------------------------- )
[cc-by-sa-4-0-logo]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
[cc-by-sa-4-0]: http://creativecommons.org/licenses/by-sa/4.0/

[//]: # ( ------------------------------------------------------------------- )
