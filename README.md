# Wallpaper Shavings
I have been saving wallpapers from left and right, and this is a ~500MB Wallpaper library that has both vertical and horizontal resolutions, because I used to have a tendency to pivot my screens, it was for me the best way to use all available space. 

### Horizontal resolutions
- 1920x1080
- 1920x1200
- 2560x1440
- 3840x2560
- some obscure resolutions, but still nice images.

### Vertical resolutions
- 1080x1920
- 1440x2560
- 2560x3840
- some obscure resolutions, but still nice images.

## GRUB Theme Installation:

### Step 1
Find your monitor's resolution and copy the corresponding folder to `/boot/grub/themes`

### Step 2
Edit your `/etc/default/grub` file to include `GRUB_THEME="/boot/grub/themes/ *folder you copied* /theme.txt"`

**For example:** `GRUB_THEME="/boot/grub/themes/qndwm-onek.hd/theme.txt"`

### Step 3
Finalize your changes with `sudo update-grub`
