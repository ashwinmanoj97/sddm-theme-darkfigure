# DarkFigure login theme for SDDM

A theme for the [SDDM](https://github.com/sddm/sddm).

### Preview

![Preview](./Previews/preview.png)

### Dependencies

- qt6-5compat
- qt6-declarative
- qt6-svg
- sddm
- JetBrains Mono Nerd Font


### Install

1. Clone this repository:

   ```sh
   sudo git clone https://github.com/ashwinmanoj97/sddm-theme-darkfigure.git /usr/share/sddm/themes/darkfigure
   ```

2. Then edit `/etc/sddm.conf`, so that it looks like this:

    ```
    [Theme]
    Current=darkfigure
    ```

Or use the following command

    echo "[Theme]
    Current=darkfigure" | sudo tee /etc/sddm.conf

### Additional information

When editing the theme you can preview it with:

```sh
sddm-greeter-qt6 --test-mode --theme .
```

### Credits

This is a modified version of [`GreenLeaf login theme for SDDM`](https://github.com/kamack38/sddm-greenleaf) by [**Kamack38**](https://github.com/kamack38)
