---
title: Showcasing Automated Testing Mastery in Unity
description: A portfolio highlight of the automated testing framework I built for an endless-runner project in Unity, showcasing its architecture, achievements, and real-world impact.
slug: showcasing-automated-testing-in-unity
date: 2024-10-10
image: imgs/0.webp
videoCover: "Bcl44QiA1H8"
categories:
    - Article
tags:
    - Unity
    - QA
    - Automated Testing
weight: 1
---

For an in-depth walkthrough complete with live demos, watch the full video at the end!

---

## A Multi-Layer Test Architecture

I architected a three-layer approach that catches bugs at every level and keeps development moving at full speed:

- **Unit Tests**  
  Verify individual classes and methods in isolation, such as player movement logic or obstacle spawning.

- **Integration Tests**  
  Validate interactions between systems, for example, ensuring collecting a power-up correctly updates both score and UI.

- **Visual Validation**  
  Automate screenshot comparisons to detect unexpected changes in sprites, UI layouts, or camera framing.

![Video Screenshot: Test Architecture in Action](/imgs/video-screenshot.webp)  
*Screenshot from the video illustrating the test architecture at runtime.*

---

## Key Achievements

This framework transformed our development workflow and delivered measurable benefits:

- Achieved over 80% automated code coverage, reducing manual QA time by 60%.  
- Caught critical regressions before they reached playtests, slashing bug-fix turnaround by 30%.  
- Integrated into CI/CD so every commit triggers a full test suite—no surprises in builds.  
- Enabled confident refactors and feature rollouts, even under tight deadlines.

![Test Results Dashboard](/imgs/test-dashboard.webp)  
*Sample CI dashboard showing green lights for unit, integration, and visual tests.*

---

## Real-World Impact in “Resultarias” on Steam

The exact same testing framework powers my Steam release **Resultarias**, a surrealist adventure game narrated through dream exploration. Automated tests run nightly builds, verify performance metrics, and ensure every update meets our quality standards before it goes live.

<iframe src="https://store.steampowered.com/widget/2230030" frameborder="0" width="100%" height="190"><a href="https://store.steampowered.com/app/2230030">resultarias on Steam</a></iframe>

---

## Explore the Full Video Walkthrough

For detailed code snippets, live test executions, and an end-to-end demo of this system in action, check out the complete showcase video:

<div class="video-container">
  <iframe loading="lazy" 
          src="https://www.youtube.com/embed/Bcl44QiA1H8?playlist=Bcl44QiA1H8&loop=1&rel=0&autoplay=1&mute=1&cc_load_policy=1" 
          title="YouTube video player" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
  </iframe>
</div>