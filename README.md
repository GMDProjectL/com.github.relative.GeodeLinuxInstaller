# Geode Linux Installer Flatpak

## Building

```bash
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.github.relative.GeodeLinuxInstaller.json
```


## Running

There's a .desktop file in this flatpak, but regardless, you can run the installer via the CLI:

```bash
flatpak run com.github.relative.GeodeLinuxInstaller
```
