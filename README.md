# PickThisSongForMe
(personal stuff but i like keeping it public)

```
git clone https://github.com/3m44n/PickThisSongForMe
cd PickThisSongForMe/
cp PickThisSongForMe/music.ini ~/.config/fuzzel/
mkdir -p ~/.local/bin
cp PickThisSongForMe/music-picker ~/.local/bin/
chmod +x ~/.local/bin/music-picker
```

#if you cant run "music-picker" in terminal, run  --
micro ~/.bash_profile
#add:  export PATH="$HOME/.local/bin:$PATH"
source ~/.bash_profile

#then add keyboard shortcut (Super+M)
