### [exa](https://github.com/ogham/exa)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash

    git clone https://github.com/dracula/exa.git

```

#### Install manually

- Download using the [exa dracula.zip](https://github.com/urrickhunt/Dracula-universal-for-exa/files/11250829/exa.dracula.zip) link or
- Download using the [GitHub `.zip` download](https://github.com/dracula/exa/archive/refs/heads/main.zip) option and unzip them.

#### Activating theme

1. Simply add the exa_colors to the end of your .zshrc:
#### ------------------------------
#### exa - Color Scheme Definitions
#### ------------------------------
export EXA_COLORS="\
uu=36:\
gu=37:\
sn=32:\
sb=32:\
da=34:\
ur=34:\
uw=35:\
ux=36:\
ue=36:\
gr=34:\
gw=35:\
gx=36:\
tr=34:\
tw=35:\
tx=36:"


#### Suggested Aliases

For normal & larger displays include group (-g flag)

        alias xl='exa -lag --icons --color=always'

For smaller or limited displays no group

        alias xl='exa -la --icons --color=always'     


