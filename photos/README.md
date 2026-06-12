# Photos for the carousel

The site's themed carousel loads images from these folders:

| Repo folder         | Theme tab            | Files                                 |
|---------------------|----------------------|---------------------------------------|
| `photos/zone/`      | Zone                 | `zone-1.jpg` … `zone-17.jpg`          |
| `photos/cong/`      | Congregation         | `cong-1.jpg` … `cong-17.jpg`          |
| `photos/preaching/` | Preaching & people   | `preaching-1.jpg` … `preaching-5.jpg` |

All images were converted from the original phone photos (HEIC → JPEG),
auto-rotated, resized to max 1600 px and optimized for the web.

To add or change photos: drop an optimized JPEG here, then update the
`PHOTO_THEMES` manifest in `index.html` (search for `TODO: photo manifest`)
— each entry has the file name plus an English and Romanian caption
(captions may be left empty: the caption bar is hidden then).

The featured clip in the video section lives in `videos/`
(`preaching-cart.mp4` + `preaching-cart-poster.jpg`).
