# freeCodeCamp Full Stack Development Labs

This repository contains the lab projects I build while working through the
**freeCodeCamp Full Stack Developer** curriculum. Every folder is a hands-on
exercise from the certification program: I start from the user stories and
write the HTML, CSS and JavaScript myself instead of copying the demo project.

The goal is to keep a public record of my progress and to practice writing
clean, semantic and accessible code.

## About the curriculum

freeCodeCamp's Full Stack Developer path is made up of certifications such as
*Responsive Web Design*, *JavaScript Algorithms and Data Structures*, *Front
End Development Libraries*, *Data Visualization*, *Back End Development and
APIs* and *Quality Assurance*. This repository starts with the first one and
will grow as I move forward.

## Repository structure

```
freeCodeCamp/
└── Responsive-Web-Design Certification/
    ├── HTML/
    │   ├── build-a-survey-form/
    │   └── accesibility/
    │       └── build-a-multimedia-player/
    └── CSS/
        ├── basic-css/
        │   ├── build-a-stylized-to-do-list/
        │   ├── design-a-blog-post-card/
        │   └── design-a-business-card/
        └── absolute-and-relative-units/
            └── build-a-event-player-page/
```

Each lab lives in its own folder and follows the same convention:

| File | Purpose |
| --- | --- |
| `index.html` | The lab itself |
| `styles.css` | Styles for the lab (when the lab requires CSS) |
| `hu.md` | The original user stories (*historias de usuario*) provided by freeCodeCamp, kept as a reference |

## Labs

- [x] Build a Survey Form
- [x] Build a Multimedia Player
- [x] Build a Stylized To-Do List
- [x] Design a Blog Post Card
- [x] Design a Business Card
- [x] Build an Event Player Page

## How to run

There is no build step and no dependencies: every lab is plain HTML, CSS and
JavaScript.

1. Clone the repository:

   ```bash
   git clone https://github.com/Geffrerson7/freeCodeCamp.git
   ```

2. Open the `index.html` of any lab in your browser, or serve the root folder
   with any static server, for example:

   ```bash
   npx serve .
   ```

## Notes

- The `hu.md` files are written in Spanish because that is the language of the
  freeCodeCamp curriculum I am following; the code and this README are in
  English.
- Some labs load fonts or media from external CDNs, so an internet connection
  is needed to see them exactly as intended.
- I try to keep every page accessible: semantic landmarks, labels tied to
  inputs, `alt` text, `aria-label` on media elements and transcripts for video.
