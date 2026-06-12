# Photos for the carousel

Drop your images into these folders (from your computer's Downloads folders):

| Your local folder       | Repo folder         | Expected file names                  |
|-------------------------|---------------------|--------------------------------------|
| `/downloads/zone`       | `photos/zone/`      | `zone-1.jpg` … `zone-6.jpg`          |
| `/downloads/COng`       | `photos/cong/`      | `cong-1.jpg` … `cong-6.jpg`          |
| `/downloads/Preaching`  | `photos/preaching/` | `preaching-1.jpg` … `preaching-6.jpg`|

Either rename your files to the names above, or edit the `PHOTO_THEMES`
manifest in `index.html` (search for `TODO: photo manifest`) to match your
file names — you can also add or remove entries there to change how many
photos each theme shows, and edit the bilingual captions.

Tips: landscape 3:2 photos around 1200×800 px look best and load fast.
Until a file exists, the site shows a tasteful placeholder automatically.
