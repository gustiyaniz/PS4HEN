# G-Playstation PS4 HEN

Personalized PS4 firmware host based on the public `mustafs-ps4-ps5/stabli`
project. The interface uses the `G-Playstation PS4 HEN` brand by `gustiyan_iz`; the
underlying scene contributors remain credited in the website.

## Supported firmware

PS4 10.00–11.02, following the compatibility range stated by the upstream
project.

The root page and every required payload are listed in one Application Cache
manifest. The interface no longer depends on external fonts, so a completed
cache works without internet. A separate local-host package can serve the same
site from an Android phone or computer when the PS4 browser cache is lost.

## Deployment

This is a static site. Publish the contents of `dist/` with any static host.

## Credits

- Original project: `mustafs-ps4-ps5/stabli`
- Personalized version: `gustiyan_iz`
- Exploit research and payload work: respective scene developers
