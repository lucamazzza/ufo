---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Spotify 1.2M+ Songs
info: |
  ## Dataset Presentation
  by Mazza Luca, Hoxha Roeld, Masciocchi Andrea

  Learn more at [GitHub](https://github.com/lucamazzza/spoty)
# apply unocss classes to the current slide
class: text-center

# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# open graph
# seoMeta:
#  ogImage: https://cover.sli.dev
---

# Dataset Presentation

UFO Sightings Redux • *Giada Galdiolo, Mazza Luca, Vasco Silva Pereira*

<div class="abs-br m-6 text-xl">
  <a href="https://github.com/lucamazzza/ufo" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

---
transition: fade-out
---

# [UFO Sightings Redux](https://github.com/rfordatascience/tidytuesday/blob/main/data/2023/2023-06-20/readme.md)

What does the dataset represent?
<br>
<br>
<br>

- <span v-mark.blue="1">**Row**</span> - Each row represents a <span v-mark.blue="1">UFO Sighting</span>
- **Columns** - Time, location, characteristics, places, day parts <span v-mark.blue="2">(35 columns)</span>
- **Time Span** - <span v-mark.blue="3">1925 - 2023</span> 
- **Locations** - All USA
- **Data Source**: <span v-mark.blue="4">National UFO Reporting Center</span>

<br>
<br>
<br>

---
transition: slide-up
level: 2
---

# Interesting Columns
Some interesting columns to analyze

|                                            |                                        |
|--------------------------------------------|----------------------------------------|
| **Publication/Report Date** `DateTime`     | Evolution of UFO Conception            |
| **Day Part** `Object`                      | Correlation and Frequency of day parts |
| City<br>**State**<br>Country Code `Object` | Geospatial Heatmap Visualization       |
| **Duration** `DateTime`                    | Find Patterns and Similarities         |

---
transition: fade-out
---

# Sightings per Year

<img src="./assets/spr.png" width="1000">

---
transition: fade-out
---

# Distribution of sighting durations 
<img src="./assets/dist.png" width="1000">

---
transition: slide-left
level: 2
---

# Why?
Why is this dataset interesting (to us)?

<br>
<br>
<br>

- UFOs are <span v-mark.blue="1">controversial</span> 
- Analyze Reports and Find <span v-mark.blue="2">Patterns</span>
- Identify <span v-mark.blue="3">Hoaxes</span>
- Read some absurd stories 

<br>
<br>
<br>

---
layout: center
class: text-center
---

# Thank you!

[Dataset](https://github.com/rfordatascience/tidytuesday/blob/main/data/2023/2023-06-20/readme.md) · [GitHub](https://github.com/lucamazzza/ufo)

