# ubuntu setup

## enter key

https://github.com/alols/xcape

```
sudo apt-get install git gcc make pkg-config libx11-dev libxtst-dev libxi-dev
```

```
git clone https://github.com/alols/xcape.git
cd xcape
make
sudo make install
```

```
xcape -e 'Control_L=Enter'
```

## vscode keyboard sync

## red light

no need to setup flux
see ubuntu params ( display> night light tab)
do not 00 => 23:59 but rather 00 => 00

## install

chromium
docker

## mouse speed

crank to max

## term promp

```sh
# https://askubuntu.com/questions/145618/how-can-i-shorten-my-command-line-bash-prompt
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;34m\]\w\[\033[00m\]\$ '
else
    PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '
fi
```

## disable ctrl+shift+e (emoji typing)

https://askubuntu.com/questions/1125726/how-to-disable-ctrl-shift-e-keybinding-from-showing-eeeee-and-loading-emoji-opti

```
ibus-setup
```

## order apps in launch bar

1. vscode
2. chromium
3. settings

## chrome setup extensiosn

-   dark reader
-   ublock origins
-   1passeG

-   login into gmail / github

## git setup

```
git config --global user.email "vion.remi@gmail.com"
git config --global user.name "rvion"
```

## settings

appearance black
bg black

## settings

-   accessibility
    -   key repeat rate
        -   low delay (not 0)
        -   high speed (not max !)
-   appearrance
    -   theme black
    -   auto hide the dock
-   mouse & touchpad
    -   speed to the max

## mouse speed

https://dev.to/bbavouzet/ubuntu-20-04-mouse-scroll-wheel-speed-536o

1.

```
sudo apt install imwheel

```

fix annoying shortcuts buggy

```sh
# https://askubuntu.com/questions/1125726/how-to-disable-ctrl-shift-e-keybinding-from-showing-eeeee-and-loading-emoji-opti

code /var/lib/snapd/desktop/applications/code_code.desktop
code ~/.local/share/applications/code_code.desktop

```

## misc

lauch `Language Support`, install missing stuff

switch to XIM insead of ibus.
xim is legacy, but at least it works.
