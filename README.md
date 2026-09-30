# signde Media Flags

Shared colored media flag artwork used by signde's Arctic Fuse 2, Arctic Fuse 3,
and Arctic Zephyr Reloaded skins.
The images were moved unchanged from those skins so they can be maintained once
and reused by other skins.

## Using the images

Add this requirement to your skin's `addon.xml`:

```xml
<import addon="resource.images.mediaflags.signde" version="1.0.0" />
```

Reference images through Kodi's resource protocol, for example:

```xml
<texture>resource://resource.images.mediaflags.signde/color/hdr/dolbyvision_fel.png</texture>
<texture>$INFO[ListItem.VideoResolution,resource://resource.images.mediaflags.signde/color/resolution/,.png]</texture>
```

Folders under `resources/color`: `audio`, `source`, `hdr`, `resolution`,
`aspectratio`, and `channels`. Existing filenames are retained. The consuming skin
controls format detection, icon visibility, and scaling; this addon contains no scripts.

## Attribution and license

Custom media flag artwork by signde, carried over from the Arctic Fuse skin forks.
The inherited Creative Commons Attribution-NonCommercial-ShareAlike 4.0 terms are
retained; see `LICENSE.txt`. Format and technology logos belong to their respective
owners. This addon is not affiliated with those owners.
