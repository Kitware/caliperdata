---
layout: home

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

# ==================================================
# THE DIFFERENCE
# ==================================================
difference:
  subheadline: What makes it different?
  headline: Largest Open Long-Range Person Recognition dataset
  items:
    - title: Observations out to one kilometer
      text: Ground cameras record people at multiple standoff distances up to 1,000 m, providing real observations of the image degradation encountered in long-range recognition.
    - title: Multiple viewpoints of the same activity
      text: Ground and elevated cameras provide near-simultaneous views of a participant's activity within a collection site, including elevated observations at depression angles up to 43°. 
    - title: Enrollment beyond a single photograph
      text: Controlled indoor enrollment includes face photographs, whole-body imagery, gait video, and depth scans alongside each participant's field observations. 
    - title: Clothing changes and a year between captures
      text: Both collections were designed to capture participants in two outfits, with 39 people returning for field recordings one year later.
    - title: Sensor profiles for controlled simulation
      text: Camera profiles combine sensor specifications with modeling parameters for camera jitter, radial lens distortion, optical aberrations, and detector noise. These settings support controlled studies of imaging degradation and can be used to configure physics-based simulators like <a href="https://github.com/Kitware/pybsm" target=_blank">pybsm</a>.
    - title: Cleaner background class
      text: 8km ship-free radius ensures quieter ambient samples for the background class

# ==================================================
# RELEASES
# ==================================================
releases:
  subheadline: Data and Code Releases
  headline: The Dataset
  paragraphs:
    - >-
      <strong>CALIPeR is planned for release in four stages:</strong> ground camera data, elevated data in two parts, and indoor enrollment data. Each stage will have its own release information, including download links, version, package size, contents, and usage terms. Dates and the camera coverage of each elevated part are pending.
  data:
    - title: Ground Camera Data
      text: >-
        Ground-camera observations span multiple distances for studying recognition at long range.
      image:
        src: "https://plus.unsplash.com/premium_photo-1749724692055-396120163730?q=80&w=1416&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D"
        alt: Image needed
      metadata:
        - icon: ri-time-line
          text: "To be released"
      button:
        text: Get Data
        url: "#"
        target: "_blank"

    - title: Elevated Camera Data - Part 1
      text: >-
        Elevated cameras observe participants from downward-looking viewpoints from collect 1.
      image:
        src: "https://plus.unsplash.com/premium_photo-1749724692055-396120163730?q=80&w=1416&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D"
        alt: Image needed
      metadata:
        - icon: ri-time-line
          text: "To be released"
      button:
        text: Get Data
        url: "#"
        target: "_blank"

    - title: Elevated Camera Data - Part 2
      text: >-
        Elevated cameras observe participants from downward-looking viewpoints from collect-2.
      image:
        src: "https://plus.unsplash.com/premium_photo-1749724692055-396120163730?q=80&w=1416&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D"
        alt: Image needed
      metadata:
        - icon: ri-time-line
          text: "To be released"
      button:
        text: Get Data
        url: "#"
        target: "_blank"

    - title: Indoor Enrollment Data
      text: >-
        Face, whole-body, gait, and depth observations provide close-up views of subjects under controlled conditions.
      image:
        src: "https://plus.unsplash.com/premium_photo-1749724692055-396120163730?q=80&w=1416&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=NHwxMjA3fDA%3D"
        alt: Image needed
      metadata:
        - icon: ri-time-line
          text: "To be released"
      button:
        text: Get Data
        url: "#"
        target: "_blank"
  code:
    title: Paper Benchmark Code
    text: >-
      A companion GitHub repository is planned for the paper's benchmarking code. This repo includes evaluation protocols, split manifests, baseline configurations, and documentation for the ReID and synthetic imagery experiments. Camera profiles and simulation settings support studies of atmospheric, sensor, and optical degradation.
    metadata:
      - icon: ri-time-line
        text: "Repository Status: To be released"
    button:
      text: View on GitHub
      icon: ri-github-line
      url: "#"
      target: "_blank"


---
