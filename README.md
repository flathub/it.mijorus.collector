# Collector

___Drag and Drop to the next level___

Collector is a simple utility that allows you to drag multiple files into a single window and drop them anywhere! It can also download images automatically when pasting urls.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub it.mijorus.collector
flatpak run it.mijorus.collector
```

## Building

```
git clone git@github.com:flathub/it.mijorus.collector.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install it.mijorus.collector.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Python
