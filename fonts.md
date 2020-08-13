# Fonts

## Tools
Packages:
- fontconfig
  - fc-list
  - fc-match
- xorg-xrdb
  - `xrdb -merge .Xresources`

Listing available fonts

`fc-list`

Checking which fonts provide the character
- For example, to see what fonts provide the unicode symbol used in the kube-ps1 prompt

`fc-match -s monospace:charset=2739`

Apply Xresources modifications

`xrdb -merge ~/.Xresources`





