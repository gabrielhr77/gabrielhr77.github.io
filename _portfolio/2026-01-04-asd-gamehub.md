---
title: "ASD GameHub — Inclusive Educational Games"
excerpt: "Collaborative USP extension project built with Python and Kivy. I developed two of its three games: Social Understanding and Daily Routines."
collection: portfolio
permalink: /portfolio/asd-gamehub/
order: 4
category: "University Extension · Python · Mobile Development"
image: "/images/projects/asd-gamehub/classroom-background.png"
image_alt: "Classroom illustration used as an asset in the ASD GameHub application"
github: "https://github.com/v1n1btt/ASD_GameHub"
technologies:
  - Python
  - Kivy
  - Android
  - UI Development
  - Team Collaboration
---

# ASD GameHub — Inclusive Educational Games

**Project:** Software para a Sociedade (S2S), University of São Paulo (USP)  
**Format:** Collaborative university extension project  
**My role:** Developer of two of the application's three educational games  
**Original team repository:** [v1n1btt/ASD_GameHub](https://github.com/v1n1btt/ASD_GameHub)

## Overview

ASD GameHub is a collaborative educational application designed with autistic children in mind. Developed as a university extension activity, it brings together three interactive games in a Python/Kivy mobile interface: **Social Understanding (Leitura Social)**, **Daily Routines (Rotina do Dia)**, and **Emotional Memory (Jogo da Memória)**.

**My individual contribution was developing Social Understanding and Daily Routines.** The application and its remaining components were built collaboratively by the team.

The screenshots below were captured from the running Android application. Select any image to open it at full resolution.

<style>
/* ASD GameHub: vertical Android screenshots, sized as phone cards. */
.page__content .asd-gamehub-gallery,
.asd-gamehub-gallery {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 215px));
  justify-content: center;
  align-items: start;
  column-gap: 1.2rem;
  row-gap: 1.6rem;
  max-width: 100%;
  margin: 1.4rem auto 2.4rem;
}
.page__content .asd-gamehub-gallery > figure,
.asd-gamehub-gallery > figure {
  display: block;
  box-sizing: border-box;
  width: 100%;
  min-width: 0;
  max-width: 215px;
  margin: 0 !important;
  padding: 0;
  border: 0;
  background: transparent;
}
.page__content .asd-gamehub-gallery > figure > a,
.asd-gamehub-gallery > figure > a {
  display: block;
  width: 100%;
  height: auto;
  padding: 0;
  margin: 0;
  line-height: 0;
  overflow: hidden;
  border: 3px solid #252a32;
  border-radius: 18px;
  box-sizing: border-box;
  background: #f9f5ee;
  box-shadow: 0 7px 18px rgba(0, 0, 0, .17);
  transition: transform .18s ease, box-shadow .18s ease;
}
.page__content .asd-gamehub-gallery > figure > a:hover,
.asd-gamehub-gallery > figure > a:hover {
  transform: translateY(-3px);
  box-shadow: 0 12px 25px rgba(0, 0, 0, .22);
}
.page__content .asd-gamehub-gallery > figure > a > img,
.asd-gamehub-gallery > figure > a > img {
  display: block;
  box-sizing: border-box;
  width: 100% !important;
  max-width: 100% !important;
  height: auto !important;
  max-height: none !important;
  margin: 0 !important;
  padding: 0 !important;
  border: 0;
  border-radius: 0;
  object-fit: contain;
  vertical-align: top;
}
.page__content .asd-gamehub-gallery > figure > figcaption,
.asd-gamehub-gallery > figure > figcaption {
  display: block;
  margin: .65rem 0 0;
  padding: 0 .2rem;
  background: transparent;
  color: inherit;
  font-size: .82rem;
  font-weight: 500;
  line-height: 1.45;
  text-align: center;
}
@media (max-width: 540px) {
  .page__content .asd-gamehub-gallery,
  .asd-gamehub-gallery {
    grid-template-columns: minmax(0, 225px);
    gap: 1.45rem;
    margin: 1rem auto 2rem;
  }
  .page__content .asd-gamehub-gallery > figure,
  .asd-gamehub-gallery > figure {
    max-width: 225px;
  }
}
@media (prefers-reduced-motion: reduce) {
  .asd-gamehub-gallery > figure > a { transition: none; }
}
</style>

## App Navigation

The main menu presents all three games. Players can also choose a character before starting the Social Understanding activity.

<div class="asd-gamehub-gallery" aria-label="ASD GameHub menu and character selection">
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/game-selection.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Main menu with three educational games">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/game-selection.webp' | relative_url }}" alt="Main menu showing the three games in ASD GameHub" loading="lazy" decoding="async">
    </a>
    <figcaption>Main menu with three educational games</figcaption>
  </figure>
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/character-selection.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Choosing a character for Social Understanding">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/character-selection.webp' | relative_url }}" alt="Character selection screen showing six illustrated characters" loading="lazy" decoding="async">
    </a>
    <figcaption>Choosing a character for Social Understanding</figcaption>
  </figure>
</div>

## My Contributions

### Social Understanding — Leitura Social

This game presents everyday social situations and asks players to choose how they would respond. It uses illustrated characters and contextual feedback to explain the consequences of different choices.

- Implemented gameplay using **20 social scenarios**.
- Built multiple-choice interactions and feedback screens.
- Integrated character selection, visual responses, and navigation between situations.

<div class="asd-gamehub-gallery" aria-label="Social Understanding game screenshots">
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/social-question.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Social Understanding — choosing a response">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/social-question.webp' | relative_url }}" alt="Social Understanding scenario with three possible responses" loading="lazy" decoding="async">
    </a>
    <figcaption>Social Understanding — choosing a response</figcaption>
  </figure>
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/social-feedback.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Social Understanding — contextual feedback">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/social-feedback.webp' | relative_url }}" alt="Social Understanding positive feedback after choosing a helpful response" loading="lazy" decoding="async">
    </a>
    <figcaption>Social Understanding — contextual feedback</figcaption>
  </figure>
</div>

### Daily Routines — Rotina do Dia

This sequencing game invites players to arrange steps of familiar daily activities in the correct order, using illustrated cards and completion feedback.

- Developed activities covering **five everyday routines**.
- Implemented ordering interactions and progress feedback.
- Integrated illustrated steps, controls, and game-state transitions.

<div class="asd-gamehub-gallery" aria-label="Daily Routines game screenshots">
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/routine-intro.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Daily Routines — start screen">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/routine-intro.webp' | relative_url }}" alt="Daily Routines game introductory screen" loading="lazy" decoding="async">
    </a>
    <figcaption>Daily Routines — start screen</figcaption>
  </figure>
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/routine-sequencing.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Daily Routines — arranging toothbrushing steps">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/routine-sequencing.webp' | relative_url }}" alt="Toothbrushing routine with steps to arrange in the correct order" loading="lazy" decoding="async">
    </a>
    <figcaption>Daily Routines — arranging toothbrushing steps</figcaption>
  </figure>
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/routine-success.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Daily Routines — successful sequence">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/routine-success.webp' | relative_url }}" alt="Completed toothbrushing routine showing the correct sequence and feedback" loading="lazy" decoding="async">
    </a>
    <figcaption>Daily Routines — successful sequence</figcaption>
  </figure>
  <figure>
    <a href="{{ '/images/projects/asd-gamehub/screenshots/routine-bedtime.webp' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="Open full-size screenshot: Daily Routines — bedtime sequence">
      <img src="{{ '/images/projects/asd-gamehub/screenshots/routine-bedtime.webp' | relative_url }}" alt="Completed bedtime routine with visual step cards" loading="lazy" decoding="async">
    </a>
    <figcaption>Daily Routines — bedtime sequence</figcaption>
  </figure>
</div>

## Technical Implementation

The application uses **Python** and **Kivy** for its interface and gameplay. Navigation between menus, games, and completion screens uses Kivy screen-management features, with game content and graphical assets organized in separate modules.

The original repository also contains a `buildozer.spec` file for Android packaging. The screenshots document the app running on Android, but do not by themselves establish a published app-store release.

## Collaboration and Scope

This was a **team project**, not a solo application. I developed two of the three games; other team members contributed to the overall application and Emotional Memory game.

The project was developed as an educational initiative. These screenshots demonstrate its functionality, not a claim of clinical effectiveness or formal validation.

## Source Code

[View the original team repository on GitHub](https://github.com/v1n1btt/ASD_GameHub)

[Back to all projects]({{ '/portfolio/' | relative_url }})
