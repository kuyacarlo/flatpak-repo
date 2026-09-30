# Dock Flatpak repository

This branch publishes the signed OSTree repository served at
https://kuyacarlo.github.io/flatpak-repo/.

Add it with `flatpak remote-add --user --if-not-exists dock
https://kuyacarlo.github.io/flatpak-repo/dock.flatpakrepo`, then install with
`flatpak install dock dev.kuyacarlo.Dock`.
