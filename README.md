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
freecodecamp-full-stack-course/
└── Responsive-Web-Design Certification/
    ├── HTML/
    │   ├── build-a-survey-form/
    │   ├── basic-html/
    │   │   ├── build-a-bookstore-page/
    │   │   ├── build-a-cat-photo-app/
    │   │   ├── build-a-curriculum-outline/
    │   │   ├── build-a-heart-icon/
    │   │   ├── build-a-recipe-page/
    │   │   ├── build-a-travela-agency-page/
    │   │   ├── build-a-video-compilation-page/
    │   │   ├── build-a-video-display-using-iframe/
    │   │   ├── build-an-html-audio-and-video-player/
    │   │   ├── build-an-html-music-player/
    │   │   ├── build-an-html-video-player/
    │   │   ├── debug-a-pet-adoption-page/
    │   │   └── debug-camperbot-s-profile-page/
    │   ├── semantic-html/
    │   │   ├── build-a-cat-blog-page/
    │   │   ├── build-a-list-of-major-web-browsers/
    │   │   ├── build-an-event-hub/
    │   │   └── build-quincys-job-tips-page/
    │   ├── forms-and-table/
    │   │   ├── build-a-book-catalog-table/
    │   │   ├── build-a-final-exams-table/
    │   │   └── build-a-hotel-feedback-form/
    │   └── accesibility/
    │       ├── build-a-checkout-page/
    │       ├── build-a-multimedia-player/
    │       ├── build-a-tech-conference-schedule-table/
    │       ├── build-an-accesible-audio-controller/
    │       ├── debug-a-coding-journey-blog-page/
    │       ├── debug-a-donation-form/
    │       └── design-a-movie-review-page/
    └── CSS/
        ├── basic-css/
        │   ├── build-a-stylized-to-do-list/
        │   ├── design-a-blog-post-card/
        │   ├── design-a-business-card/
        │   └── design-a-cafe-menu/
        ├── absolute-and-relative-units/
        │   └── build-a-event-player-page/
        └── pseudo-classes-and-elements/
            ├── build-a-job-application-form/
            ├── design-a-greeting-card/
            └── design-a-parent-teacher-conference-form/
```

Each lab lives in its own folder and follows the same convention:

| File | Purpose |
| --- | --- |
| `index.html` | The lab itself |
| `styles.css` | Styles for the lab (when the lab requires CSS) |
| `hu.md` | The original user stories (*historias de usuario*) provided by freeCodeCamp, kept as a reference |

## Labs

### HTML

- [x] Build a Survey Form
- [x] Build a Multimedia Player
- [x] Build a Checkout Page
- [x] Design a Movie Review Page

### CSS

- [x] Build a Stylized To-Do List
- [x] Design a Blog Post Card
- [x] Design a Business Card
- [x] Build an Event Player Page

Each certification section is developed in its own branch and merged into `main`
through a pull request, so the history shows how the repository grew.

## How to run

There is no build step and no dependencies: every lab is plain HTML, CSS and
JavaScript.

1. Clone the repository:

   ```bash
   git clone https://github.com/Geffrerson7/freecodecamp-full-stack-course.git
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
