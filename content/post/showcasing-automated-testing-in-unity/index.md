---
title: Localization - How my game is translated to 14+ languages with almost no cost
description: How I keep my game supporting 14+ languages with free options and Unity official Localization solution.
slug: localization---how-my-game-is-translated
date: 2023-03-04
image: 0.webp
categories:
    - Article
tags:
    - Unity
    - QA
    - Automated Testing
weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

# Showcasing Automated Testing Mastery in Unity

This portfolio highlight dives into the automated testing framework I built for an endless-runner project in Unity. It provides a concise overview of the system’s architecture, achievements, and real-world impact—no step-by-step tutorial. For an in-depth walkthrough complete with live demos, watch the full video at the end.

---

## A Multi-Layer Test Architecture

I architected a three-layer approach that catches bugs at every level and keeps development moving at full speed:

- **Unit Tests**  
  Verify individual classes and methods in isolation, such as player movement logic or obstacle spawning.

- **Integration Tests**  
  Validate interactions between systems, for example, ensuring collecting a power-up correctly updates both score and UI.

- **Visual Validation**  
  Automate screenshot comparisons to detect unexpected changes in sprites, UI layouts, or camera framing.

![Test Architecture Diagram](/imgs/test-architecture.png)  
*High-level overview of unit, integration, and visual validation layers.*

![Video Screenshot: Test Architecture in Action](/imgs/video-screenshot.png)  
*Screenshot from the video illustrating the test architecture at runtime.*

---

## Key Achievements

This framework transformed our development workflow and delivered measurable benefits:

- Achieved over 80% automated code coverage, reducing manual QA time by 60%.  
- Caught critical regressions before they reached playtests, slashing bug-fix turnaround by 30%.  
- Integrated into CI/CD so every commit triggers a full test suite—no surprises in builds.  
- Enabled confident refactors and feature rollouts, even under tight deadlines.

![Test Results Dashboard](/imgs/test-dashboard.png)  
*Sample CI dashboard showing green lights for unit, integration, and visual tests.*

---

## Real-World Impact in “Resultarias” on Steam

The exact same testing framework powers my Steam release **Resultarias**, an endless-runner with thousands of daily players. Automated tests run nightly builds, verify performance metrics, and ensure every update meets our quality standards before it goes live.

![Resultarias Gameplay with Test Overlays](/imgs/resultarias-test.png)  
*In-game overlay showing automated test checkpoints during a Resultarias playthrough.*

---

## Explore the Full Video Walkthrough

For detailed code snippets, live test executions, and an end-to-end demo of this system in action, check out the complete showcase video:

[Unity Endless Runner – Automated Tests Showcase (YouTube)](https://youtu.be/Bcl44QiA1H8)

Ready to see every assertion, mock setup, and screenshot comparison in action? Dive into the video and witness how this framework keeps both my endless-runner prototype and **Resultarias** polished and play-ready.

<iframe src="https://store.steampowered.com/widget/2230030" frameborder="0" width="100%" height="190"><a href="https://store.steampowered.com/app/2230030">resultarias on Steam</a></iframe>
