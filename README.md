<h2 align="center">🗼 Simple SDDM Theme 2 - QT6 🗼</h2>

<h1 align="center"> This will be the SDDM theme to be installed in my Hyprland Scripts</h1>
<h1 align="center"> Not my own work. See below `Credits` for link of original author </h1>

<p align=center>
A Simple theme variant for the <a href="https://github.com/sddm/sddm">SDDM Login Manager</a>
</p>

<h2 align=center>Preview</h2>
<center>
<img src="./Previews/1.png" alt="preview-1">
<details>
<summary align=center>More Previews</summary>
<img src="./Previews/2.png" alt="preview-2">
<img src="./Previews/3.png" alt="preview-4">
<img src="./Previews/4.png" alt="preview-3">
<img src="./Previews/5.png" alt="preview-5">
</details>
</center>

## Install
### From sources
> _Assumes that you've installed and configured SDDM correctly_ (if not [read more](https://wiki.archlinux.org/title/SDDM))

>  Please make sure you have the following dependencies installed:
- ` For Arch Linux`
`qt6-5compat` `qt6-declarative` `qt6-svg` `sddm` 

- ` For Fedora 40 `
`qt6-qt5compat` `qt6-declarative` `qt6-qtsvg` `sddm` 

- `For OpenSuse TW`
`qt6-qt5compat` `qt6-declarative` `qt6-svg` `sddm` 

## Configure

Edit the `/etc/sddm.conf.d/10-theme.conf` (with any text editor with **raised** privileges), so that it looks like this:

```bash
sudo nano /etc/sddm.conf.d/10-theme.conf  # use any text editor with raised privileges
---

[Theme]
Current=simple-sddm-2
   ```

### Language and time format
- By default, it is configured with 24H format. You can change to AM/PM variant by editing the theme.conf
```bash
sudo nano /usr/share/sddm/themes/simple-sddm/theme.conf  # use any text editor with raised privileges
```
- `HourFormat="hh:mm AP` . Make sure to disable the above of this part
- To change the default wallpaper put desired image in the `simple-sddm/Backgrounds/` folder and add the name of the image followed by its extension (`.jpg` or `.png`) in `theme.conf` file.
- You can also customize it further if you wish in the `theme.conf`
(blur, form position, etc).

## Credits
- Full credit goes to original autor [`LINK`](https://github.com/Keyitdev/sddm-astronaut-theme) by [**Keyitdev**](https://github.com/Keyitdev)


