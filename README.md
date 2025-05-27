# Celeste Flatpak

## Building

```
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.hunterwittenborn.Celeste.yml
```

Then you can run it via the command line:

```
flatpak run com.hunterwittenborn.Celeste
```

or just search for the installed app on your system

## Aditional sources

`cargo-sources` are generated from the project itself. `go-sources` and `modules.txt` are generated from https://github.com/trevyn/librclone/tree/master/librclone-sys
