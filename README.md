<img width="1600" height="400" alt="Artboard 1" src="https://github.com/user-attachments/assets/96517ab5-e5d1-4df7-90f2-a23cf91d30f2" />

# AsciiReel

Convert MP4 video into ASCII animation that plays as pure JavaScript, with no video file needed.

## Features
- Converts an MP4 into a `.js` file that plays in the browser

## Requirements
- Python 3.xx
- Libraries in `requirements.txt`

## Install
```
git clone https://github.com/lahirunim/AsciiReel.git
cd AsciiReel
pip install -r requirements.txt
```

## Usage
1. Put your video in the same folder as `AsciiReel.py` and name it `input.mp4`.
2. Run:
```
python AsciiReel.py
```
3. The result, `video_data.js`, appears in the same folder.
   
## Preview
1. Copy `video_data.js` into the `previews` folder, next to the preview pages.
2. Open one of the pages in your web browser by double-clicking it:
   - `[Preview_With_Controls.html]`: idk test by yourself
   - `[Preview_Tiles.html]`: idk test by yourself, its for backgrounds
   - `[Preview_Overlap.html]`: this is little bit tricky this overlap one ascii animation on another. rename those files like "video_data.js" and "video_data_2.js".
3. The animation plays with the controls.

If the page is blank, press F12 in the browser and check the Console tab. The usual cause is a file name that doesn't match.

## Roadmap
- [ ] Graphical interface
- [ ] Smaller output files
- [ ] Colour support

## AI disclosure
Parts of this code were generated with AI assistance and then edited and tested by the author.

## License
MIT. See the LICENSE file.

