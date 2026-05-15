# 30 Seconds that Lead to a 2-Hour Journey
## Designing a gallery companion app for Shaun Tan's surrealist world

| | |
| :--- | :--- |
| **Year** | 2025 |
| **Role** | UX/UI Designer — research, wireframes, visual design, prototype |
| **Type** | School project |
| **Tools** | Figma, pencil + paper |
| **Prototype** | [Try it in Figma →](https://www.figma.com/proto/7wpjjC9Rh4RkNEgiTwopHB/DD-aplikace-galerie?node-id=178-7863&t=N1YZQwhhy3OGCW7U-1) |



![Three iPhones in lavender cases showing key app screens at an angle: the "Vstupenky" (Tickets) page, the home screen with the featured "Cikáda" exhibition, and the "Shaun Tan Gallery" page with the gallery's address and opening hours.](img/mobiles-app.png)
*Application screens*

## Meet the hero
To understand the audience, you have to understand the artist. Shaun Tan is an Australian illustrator whose work feels like being a small, lost thing in a vast and beautiful world. His paintings are quiet, surreal, and full of detail you only notice on the second look.

That quietness became my design constraint. The app couldn't shout. It had to sit beside the art, not on top of it.

If you aren't familiar with his work, you can [explore more about him](about-shaun.md) to see the visual anchor to this entire system.

![Four Shaun Tan paintings: a shelf lined with tiny potted plants flanking an oversized teacup; a small cicada standing alone among scattered papers; a giant orange parrot's head filling a room while a tiny man sits on a chair facing it; and a close-up pencil sketch of a small horned creature peeking out from the strap in a car.](img/shaun-tan-intro.png)
*Shaun Tan's paintings*

## I'm feeling like a lost thing, and that's a problem!

It's Saturday. It's raining. You remember your favorite gallery has 
a new exhibition, so you open their website — and find nothing useful. 
You go anyway. It's closed. No opening hours, no warning, no way to know.

You finally make it inside on Sunday. And then a second problem occurs: 
you don't know where to go. You wander, you ask a guard, you give up and circle back to the entrance.

This is the gap I wanted to close. Not one frustration, but two — **before the visit** and **during the visit** — stitched together by a single app.

## Here comes the savior: the designer!

Two frustrations, one app. The brief I set myself was simple to say and hard to do: design a minimal, real-time companion that solves the logistics *before* the visit and the navigation *during* it — without ever raising its voice above the art.

Shaun Tan's paintings are incredibly immersive, surreal, and filled with intricate details; the application's interface needed to act as a quiet frame rather than a loud distraction, ensuring the artwork itself never got lost in a messy digital layout.

> "A busy interface is the enemy of a peaceful gallery visit. The app's job is to disappear once you've found what you need."

## Stepping into the user's shoes
Before drawing a single line, I had to understand how people actually behave around cultural spaces such as galleries and museums and their apps. I reached out to my respondents and asked them about their habits, expectations and frustrations when using technologies. 

Our conversations were about the frequency of their gallery visits, where they look for information and what they expect from a dedicated gallery application.

![Two user personas side by side: Ema, an infrequent gallery visitor who prefers minimalist apps and theatre over galleries; and Rudolf, a regular visitor who wants a personal audio guide and deeper content. Each persona is illustrated with a Shaun Tan character.](img/respondents-2.png)
*Respondent preferences*

Three insights changed the direction of the project:

| Research pillar | What users told me | What it changed in the design |
| :--- | :--- | :--- |
| **Tech relationship** | "I forget single-use apps within a week." | The app needed Apple Wallet-level utility to justify staying installed. |
| **Content depth** | "Guided tours feel rushed — I want to set my own pace." | Layered audio: short labels by default, longer stories on tap. |
| **Visual style** | "I like apps that get out of the way, like Strava or Zalando." | An "invisible UI" — neutral palette, minimal chrome, art front and centre. |


## Starting on a blank canvas

With these user expectations, I started sketching. Paper first.

![pencil sketches of wireframes and app map](img/sketches.png)
*Pencil sketches*

From these sketches, I came up with the core elements that would hold the whole experience together:

- **The info hub** — everything you need *before* arriving: opening hours, ticket reservation, event calendar, digital tickets.
- **The audio compass** — a hands-free guide that talks you through rooms at your own pace, with short labels by default and longer stories when you want them.
- **The invisible frame** — a UI quiet enough that the artwork stays the loudest thing in the room.

![App sitemap showing six top-level sections branching from a Welcome screen and Sign-In/Registration: Home (with Exhibition of the Week, Ongoing Exhibitions, and a Reservation/Buy flow leading to Calendar and Pay), Navigation (Tickets, About Shaun Tan, Contact, Audioguide, Virtual Gallery, Ongoing Exhibitions, Language), Audioguide (List of Exhibitions, List of Artworks), Virtual Gallery (Find, Guide), Scan, and Profile (Personal Info, My Tickets, Favorites, My Files, Reviews, Settings).](img/app-map.png)
*Map of the app*

![Eight low-fidelity wireframes for the app's main screens, shown with grey placeholder blocks instead of real content: a splash screen with a logo placeholder, a basic landing layout, a content list, a home screen with a welcome text and ongoing exhibitions list, an audio guide list with three "Cikáda" entries, an exhibition cover screen with playback controls, an artwork track list inside an exhibition, and an exhibition detail page with description text and an audio guide button. Czech-language labels.](img/wireframes.png)
*Wireframes*

### Choosing the right paints

Once the structure was set and the wires were connected, it was time to paint the interface of the app. I moved from pencil sketches and low-fidelity wireframes to defining a high-fidelity visual language. This wasn't just about picking the right colors, it was about creating a digital environment that felt intuitive, ensuring the UI remained a quiet frame that never competed with the artwork for the user's attention.

### The neutral base
Black, white, and grey form the primary palette. They don't compete with the art; they hold it and let the art breathe.

![Three color variants of the same Shaun Tan painting of cicada — gray, white, black — used to show the used colors.](img/neutral-colors.png)
*Neutral colors*

### The accents
Sage green, soft blue, and a vibrant pink act as wayfinding cues — used sparingly, only where the user needs to be drawn forward.
![Three color variants of the same Shaun Tan painting of cicada — pink, blue, and sage green — used to show the used colors](img/colors.png)
*Accent colors*

### Mixing the palette
After defining the colors, I focused on the interface's structural elements to ensure the experience remained both clean and highly functional.

SF Pro Display does the typographic work: legible in low gallery light, neutral enough to never call attention to itself.

Every button and asset was designed to be intuitive, allowing the user to navigate with zero learning curve.

![A collage of app interface elements: a Czech-language account menu (Můj účet) with options for personal info, tickets, favorites, and settings; an iOS-style keyboard; a context menu with Add to Reading List, Bookmark, Favorites, and Find on Page; counter and play/pause button components in different states; an audio guide icon; a search bar; the app's horned-creature logo; a bottom tab bar with home, audio, gallery, scan, and profile icons; and a dark side menu showing a logged-in user "Tim Armstrong" with navigation to tickets, Shaun Tan, contact, audio guide, gallery map, and current exhibitions, plus a Czech/English language toggle.](img/components.png)
*Application components*

![Three app screens from the ticket booking flow, in Czech: a "How many tickets?" selector with counters for adult, child (2–12), student (under 26 with ID), and senior; an Apple Pay checkout sheet showing card and contact details; and an exhibition date picker showing August 2025 with a search field for the exhibition name ("Cikáda" entered). Below: a row of UI icons and accepted payment methods — Visa, Mastercard, Google Pay, Apple Pay.](img/components-2.png)
*Application components*


## The final painting
With components in place, the wireframes came alive — clean, quiet, 
and organised around the moments that actually matter to a gallery 
visitor.

It starts with a quick sign-in — email, password, in.

![Three mobile screens showing the app's onboarding flow in Czech: a splash screen with The Tan Room logo (a black horned creature), a login screen (Přihlášení) with email and password fields plus Facebook, Google, and Apple sign-in options, and a registration screen (Registrace) with username, email, password, and a terms checkbox.](img/Registration.png)
*Registration window*

### Sketching the visit
The home screen leads with the Exhibition of the Week, followed by a list of ongoing exhibitions. Tap any exhibition and you land in the calendar, where you pick a date, reserve your slot, and buy the ticket without leaving the flow.

A hamburger menu in the top corner holds everything you might need before you arrive: your tickets, information about Shaun Tan, contact details, the audio guide, the virtual gallery map, ongoing exhibitions, and a Czech/English language toggle.
![Nine mobile screens showing the full app flow in Czech, arranged in three rows. Top row: home screen with featured exhibition "Cikáda," same screen with a closing-hours notice, and the open side menu (Tim Armstrong logged in). Middle row: exhibition detail page for "The Tales from Outer Suburbia" by Shaun Tan, a date picker for choosing a visit date, and the ticket purchase screen. Bottom row: user profile (Tim) with account menu, a generated QR code ticket for "Cicada," and the "My Tickets" page listing three purchased tickets with QR codes.](img/home-tickets.png)
*Showcase of the pages*

### Walking the canvas

Once you're inside, the **bottom navigation bar** becomes the center of the experience. Four entry points, used hands-free as you walk:

- **Audio guide** — short labels by default, longer stories on tap, paced to your walk rather than a fixed tour.
- **Virtual gallery** — a live map that shows which room you're in and what's around the next corner.
- **Scan a painting** — point your camera at any work and pull up its story, materials, and the artist's notes.
- **Profile** — your tickets, favorites, saved files, reviews, and settings, all in one place.

![Four mobile screens for the audio guide and gallery navigation features in Czech: an audio guide overview listing exhibitions by room, a track list for "The Tales from Outer Suburbia" with play and pause buttons for each artwork, an augmented-reality navigation view showing "Now turn right" with an arrow overlaid on a camera view of the gallery, and a QR-code scanner framed over a painting with instructions to scan the code beside the artwork.](img/audio-map-scan.png)
*Audioguide, virtual gallery-map, images scan*


## What I learned from the painting

This was a school concept project, so I don't have install numbers or conversion rates to point to. What I have instead is three things I'll carry into the next project:

1. **Design is a solution, not decoration.** I came in thinking about how the app would look. I left thinking about what it had to *do* — close a gap, remove a frustration, answer a question someone actually has. The visual language came last, and it should.
2. **It was my first app, and the format taught me more than the topic.** Designing for a phone screen is its own discipline — thumb reach, one-handed use, the way a hamburger menu has to earn its place. None of that shows up in a poster or a website. Every constraint became a lesson.
3. **Less really is more — but only when you mean it.** Stripping things out is easy. Stripping things out *on purpose*, knowing exactly why each remaining element stays, is the harder version. The pink accent only works because everything around it is quiet.


[Try the prototype!](https://www.figma.com/proto/7wpjjC9Rh4RkNEgiTwopHB/DD-aplikace-galerie?node-id=178-7863&t=N1YZQwhhy3OGCW7U-1)

Let's talk. There's more than a UX/UI painting I can do for you!

[Portfolio](https://www.keyspace.cz/projekty)  | [LinkedIn](https://www.linkedin.com/in/barbora-berková-997932351/?skipRedirect=true)

[Go back to Home](./)
