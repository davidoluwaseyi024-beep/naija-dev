# NaijaDevs Conference 2026 - HTML Project

NDI Full-Stack Development Programme - HTML Capstone Project
Instructor: Bamidele | March 2026

---

## About This Project

This is a 5-page conference website built using pure HTML only.
No CSS and no JavaScript has been added yet. This is the structure
(skeleton) of the site. CSS with Tailwind will be added in the next phase.

---

## Pages

| File                | Description                              |
|---------------------|------------------------------------------|
| index.html          | Homepage - hero, event details, sponsors |
| speakers.html       | Speaker cards, bios, and full schedule   |
| register.html       | Registration form with all input types   |
| venue.html          | Venue info, map, travel guide            |
| confirmation.html   | Thank-you page shown after registration  |

---

## Folder Structure

```
naija-devs-conference/
|
|-- index.html
|-- speakers.html
|-- register.html
|-- venue.html
|-- confirmation.html
|-- favicon.ico
|
|-- images/
|   |-- logo.png
|   |-- banner.jpg
|   |-- speakers/
|   |   |-- speaker-1.jpg
|   |   |-- speaker-2.jpg
|   |   |-- speaker-3.jpg
|   |   |-- speaker-4.jpg
|   |   |-- speaker-5.jpg
|   |   |-- speaker-6.jpg
|   |-- venue/
|   |   |-- venue-main.jpg
|   |   |-- floor-plan.png
|   |-- sponsors/
|       |-- sponsor-1.png
|       |-- sponsor-2.png
|       |-- sponsor-3.png
|       |-- sponsor-4.png
|       |-- sponsor-5.png
|
|-- media/
    |-- welcome.mp3
    |-- highlights.mp4
```

---

## Images

All images are currently referenced using relative paths.
The placeholder images in the images/ folders need to be replaced
with real images when they are available.

For now, some pages fall back to placeholder.co for images that
do not have a local file yet (such as the extra venue photos).

---

## How to Open

1. Extract this folder to your computer
2. Open the folder in VS Code
3. Open index.html in your browser to start
4. All internal links between pages use relative paths and will work
   as long as all files are in the same folder structure shown above

---

## Venue

International Conference Centre (ICC)
Herbert Macaulay Way, Central Business District
Abuja, FCT, Nigeria

---

## HTML Concepts Covered

This project uses every major HTML concept from the W3Schools tutorial:

- Document structure: DOCTYPE, html, head, meta, title, link
- Semantic layout: header, nav, main, section, article, aside, footer
- Text: h1-h6, p, strong, em, b, i, mark, small, del, ins, sub, sup
- Links: relative, absolute, mailto, tel, target blank, bookmark (#id)
- Images: img, picture, source, figure, figcaption, map, area
- Tables: table, thead, tbody, tfoot, caption, th, td, colspan, rowspan, colgroup, col
- Lists: ul, ol, dl, nested lists, ol with type and start attributes
- Forms: form, fieldset, legend, label, input (all types), textarea, select, datalist, meter, progress, output, button
- Media: video, audio with multiple source elements
- Semantic text: abbr, address, blockquote, cite, pre, code, kbd, samp, var, time, bdo
- Layout: details, summary, div, span
- Entities: &copy; &amp; &lt; &gt; &hearts; &rarr; &#8358;
- Other: iframe, colgroup, html lang attribute, meta charset, viewport

---

## Notes

- All internal page links use relative paths (e.g. href="speakers.html")
- External links use target="_blank" and rel="noopener" for security
- Form action points to confirmation.html using method GET
  so submitted data is visible in the URL (for learning purposes)
- Images folder structure matches the project brief exactly
