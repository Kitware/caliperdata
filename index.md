---
layout: home
title: Sample Site
description: Site description here

# ==================================================
# HERO AREA
# Button styles: btn-primary or btn-outline
# ==================================================
hero:
  # Replace this path with the final hero image in assets/images.
  background_image: ""
  subheadline: Open Benchmark. Long Range Person Recognition
  headline: >-
    CALIPeR: Co-Temporal Atmospheric Long-range Imagery for Person Re-identification
  text: >-
    Explore person recognition across distance, viewpoint, clothing, and time. The dataset features over 1,100 hours of multi-view, co-temporal field recordings alongside controlled indoor biometric captures—covering face, body, and gait—collected under a structured enrollment protocol. 
  buttons:
    - label: Button 1
      url: "#overview"
      style: btn-secondary
    - label: Button 2
      url: "#overview"
      style: btn-outline

# ==================================================
# OVERVIEW
# Button styles: btn-primary or btn-outline
# ==================================================
overview:
  subheadline: Overview
  headline: Built to study person recognition across distance, viewpoint and changing environmental/physical conditions.
  paragraphs:
    - >-
      CALIPeR combines two collects, captured a year apart, containing outdoor video from ground and elevated cameras with controlled face and whole-body images, gait videos, and depth scans. Its near-simultaneous views capture the same person and activity from multiple distances and angles, upto ground-camera ranges reaching 1,000 m.
  cta_section:
    paragraphs:
      - >-
        <strong>The paper</strong> describes the dataset and evaluation protocols, reports baseline results, and explores ground-camera calibration and the use of simulated imagery for recognition research.
    buttons:
      - label: Read the paper
        url: "#"
        target: _blank
        style: primary

  stats:
    - value: ">1,100"
      label: Raw video hours
    - value: "~53M"
      label: Annotated frames@30fps
    - value: "411"
      label: Unique subjects with clothing changes
    - label: Co-Temporal, cross-range Ground and Aerial view Outdoor collects with camera sensor calibration profiles
    - value: "5-station"
      label: Biometric indoor enrollment
    - label: 1-year apart longitudinal collects across varying physical/weather conditions


---
