# PDX Pho

I'm visiting all the photo restaurants located within Portland city limits, at least twice, ideally three times. I don't plan to publicly release ratings until I visited a place twice. Follow the journey at https://curtisbarnard.github.io/pdxpho.

## Photo Processing

1. Open JPG images into darktable and process
1. Export square cropped image as 1600px square webp
1. Rename image as `<location_id><A/B>v<visit_number>` (ie. `2Av1.webp`)
   - A is for photos of pho, B is for photos of herbs
1. Strip metadata and add copyright with `exiftool * -all= -overwrite_original -copyright="<YYYY> Curtis Barnard"`
1. Add images to `pdxpho/src/images`
