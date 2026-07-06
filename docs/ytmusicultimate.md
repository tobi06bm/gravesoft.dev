# YTMusicUltimate

The best tweak for the YouTube Music app on iOS.

**Author:** [dayanch96](https://github.com/dayanch96) & [Ginsu](https://github.com/ginsudev)  
**Github Repo:** https://github.com/dayanch96/YTMusicUltimate  

---

How to use it
-------------

**Jailbreak**

- Add __[https://ginsu.dev/repo](https://ginsu.dev/repo)__ to your favorite package manager (Sileo, Zebra, etc.) and download the latest version from there, or grab the `.deb` directly from the __[Releases](https://github.com/dayanch96/YTMusicUltimate/releases)__ page.
- Use the `arm.deb` version for Rootful devices and `arm64.deb` for Rootless devices.

**Sideloading**

Pre-built IPAs are no longer provided, but you can build one yourself:

- **Github Actions:** Fork the repo, enable Read and Write permissions under Repository Settings > Actions, then run the "Build and Release YTMusicUltimate" workflow, providing a link to a decrypted YTMusic IPA (hosted on filebin.net, Dropbox, etc). The tweaked IPA will appear in your fork's Releases page.
- **Build locally with Theos:** Install __[Theos](https://theos.dev/docs/installation)__, clone the repo, then run `make clean package` (rootful), `make clean package ROOTLESS=1` (rootless), or `make clean package SIDELOADING=1` (for IPA injection).
- **IPA injection:** Use a tool like __[Azule](https://github.com/Al4ise/Azule)__ to inject the built package into an existing IPA.

Note
----

You must provide your own decrypted YTMusic IPA - the developers cannot legally distribute one.

License
-------
The project is licensed under the terms of the GPL-3.0 License.
