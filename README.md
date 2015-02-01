## hackersaurus Theme for Oh-My-Zsh

This is a theme for [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh). It
does **not** require special font installation or settings to work correctly,
and should work out-of-the-box once you install it.

### Features
* Shows lots of information about Git repositories, including:
    * branch / tag name
    * current action status (rebasing, merging, etc.,)
    * being behind / ahead of your remote
    * various local working tree statuses
* Shows command number in right-prompt (so you can `$ !<num>` to re-run)
* Shows return-code of command if it is an error code
* Shows system time in right-prompt

This screenshot should give you an idea of what it looks like:

![](http://bhilburn.org/content/images/2014/11/hokietux_theme.png)

**If you like the features of this theme, but want something that looks even
more awesome (and you are willing to install some fonts), check out the sister
theme, [powerlevel9k](https://github.com/bhilburn/powerlevel9k).**

### Installation

To install this theme, drop the `.zsh-theme` file into your `.oh-my-zsh/themes`
directory. A better form of installation is to clone this repository and then
create a symlink in your 'themes' directory:

    $ git clone https://github.com/bhilburn/hackersaurus.git
    $ ln -s hackersaurus.git/hackersaurus.zsh-theme ~/.oh-my-zsh/themes/hackersaurus.zsh-theme

You then need to select it in your `~/.zshrc`:

    ZSH_THEME="hackersaurus"

Note that *you cannot clone this repository into your `~/.oh-my-zsh/themes/` directory*.
Oh-My-Zsh does not traverse subdirectories, and will not find your theme.

### History
This theme was first announced [on my blog](http://bhilburn.org/the-hokietux-oh-my-zsh-theme/) in May of 2013.

I submitted a pull-request to OMZ, but [Robby is no longer accepting new
themes](https://github.com/robbyrussell/oh-my-zsh/pull/1804).

### Bugs / Contact

If you have any requests or bug reports, please use the tracker in this Github
repository.

