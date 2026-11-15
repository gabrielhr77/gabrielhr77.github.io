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
/* Scoped gallery styles: no changes to the site's global SCSS are needed. */
.asd-gamehub-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 1rem;
  margin: 1.2rem 0 2rem;
}
.asd-gamehub-gallery figure {
  min-width: 0;
  margin: 0;
  overflow: hidden;
  border: 1px solid var(--global-border-color, #d0d4d8);
  border-radius: 10px;
  background: var(--global-bg-color, #fff);
}
.asd-gamehub-gallery a {
  display: flex;
  height: 305px;
  align-items: center;
  justify-content: center;
  background: #eae5dc;
}
.asd-gamehub-gallery img {
  display: block;
  width: auto;
  max-width: 100%;
  height: auto;
  max-height: 100%;
  object-fit: contain;
}
.asd-gamehub-gallery figcaption {
  padding: .7rem .8rem;
  font-size: .78rem;
  line-height: 1.45;
  color: var(--global-text-color, inherit);
}
@media (max-width: 550px) {
  .asd-gamehub-gallery { grid-template-columns: repeat(2, minmax(0, 1fr)); gap: .65rem; }
  .asd-gamehub-gallery a { height: 245px; }
  .asd-gamehub-gallery figcaption { padding: .55rem; font-size: .73rem; }
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
