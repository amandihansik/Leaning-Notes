# HTML Media Elements

In this part, I am learning about **HTML Media Elements**.  
Media elements allow us to add images, audio, and videos to web pages, making them more interactive and engaging.

---

## What Are HTML Media Elements?

HTML media elements are used to embed multimedia content such as images, audio files, and videos into a webpage.

---

## 1. HTML Images (`<img>`)

Images are used to visually represent content on a webpage.

### Example:
```html
<img src="image.jpg" alt="Sample Image">
```

### Explanation:
- `<img>` → Image tag
- `src` → Path to the image file
- `alt` → Alternative text if the image does not load (important for accessibility)

---

## 2. HTML Audio (`<audio>`)

The audio tag is used to play sound files on a webpage.

### Example:
```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

### Explanation:
- `<audio>` → Audio container
- `controls` → Displays play, pause, and volume controls
- `<source>` → Specifies the audio file

---

## 3. HTML Video (`<video>`)

The video tag is used to embed videos into a webpage.

### Example:
```html
<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

### Explanation:
- `<video>` → Video container
- `controls` → Shows video controls
- `width` and `height` → Define video size

---

## Supported Media Formats

- Images: JPG, PNG, GIF, SVG
- Audio: MP3, WAV, OGG
- Video: MP4, WebM, OGG

---

## Why Media Elements Are Important

- Improve user engagement
- Make content more attractive
- Help explain concepts visually and audibly
- Widely used in modern websites

---

## Learning Summary

I learned how to use HTML media elements such as images, audio, and video.  
These elements help create interactive and visually appealing web pages.
