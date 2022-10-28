# rofi-ykman

Yubikey manager script for rofi

## Dependencies

* ykman for Yubikey
* rofi
* xclip
* dunst

## Usage

Add the key binding to your `sxhkdrc` file:

```ini
# Yubikey Account Manager
super + shift + p
    ~/.config/rofi/rofi-ykman/rofi-ykman
```

After pressing `super + shift + p`, you will see a rofi prompt listing all available TOTP keys. Choose one and the code will be copied to your clipboard; if the token requires the touch of the key a notification will appear.
