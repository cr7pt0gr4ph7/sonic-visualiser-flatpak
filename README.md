# sonic-visualizer-flatpak
Packages the [Sonic Visualiser] application (source code available on [GitHub]) as a [Flatpak].
Inspired by [tinywrkb/flatpaks] and based on the [andyholmes/flatter] GitHub action and [flatpak-builder-repo].

Not tested in any meaningful way except for "works on my machine", so use at your own discretion.

[Sonic Visualiser]: https://www.sonicvisualiser.org/
[GitHub]: https://github.com/sonic-visualiser/sonic-visualiser

[AppImage]: https://appimage.org/
[Flatpak]: https://docs.flatpak.org/
[Bluefin]: https://projectbluefin.org/

[tinywrkb/flatpaks]: https://github.com/tinywrkb/flatpaks
[andyholmes/flatter]: https://github.com/andyholmes/flatter
[flatpak-builder]: https://docs.flatpak.org/en/latest/flatpak-builder.html
[flatpak-builder-install]: https://docs.flatpak.org/en/latest/first-build.html
[flatpak-builder-repo]: https://github.com/flatpak/flatpak-builder

## Building locally

Use the following command after checking out the repository to build & install the Flatpak locally
(requires [Flatpak Builder][flatpak-builder] to be [installed][flatpak-builder-install]):

```bash
flatpak-builder --force-clean --user --install-deps-from=flathub --install install io.github.cr7pt0gr4ph7.flatpaks.sonic-visualiser/io.github.cr7pt0gr4ph7.flatpaks.sonic-visualiser.yml
```
