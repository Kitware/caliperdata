---
layout: home

# ==================================================
# HERO AREA
# Button styles: btn-primary or btn-outline
# ==================================================
hero:
  # Replace image paths with the final hero image in assets/images.
  # background_image is faded into background
  # feature_image is on the right side in the foreground.
  background_image: ""
  feature_image: "/assets/images/Banner_Image.png"
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
    - value: "9"
      label: Co-Temporal, cross-range Ground and Aerial view Outdoor camera sources
    - value: "5-station"
      label: Biometric indoor enrollment
    - value: "1-year apart"
      label: Longitudinal collects at the same location across varying physical/weather conditions

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

# ==================================================
# RELEASES
# ==================================================
releases:
  subheadline: Data and Code Releases
  headline: The Dataset
  paragraphs:
    - >-
      <strong>CALIPeR is planned for release in six parts:</strong> ground camera data, elevated camera data, and indoor enrollment data, each split into part 1 for collect-1 and part 2 for collect-2. Each part will have its own release information, including download links, version, package size, contents, and usage terms. Release dates and detailed package coverage are pending.
  data:
    - title: Ground Camera Data - Part 1
      text: >-
        Ground-camera data from collect-1 provide observations of participants at multiple distances for studying long-range recognition.
      image:
        src: "/assets/images/ground_range-collect_1.png"
        alt: Image needed
      metadata:
        - icon: ri-time-line
          text: "To be released"
      button:
        text: Get Data
        url: "#"
        target: "_blank"

    - title: Ground Camera Data - Part 2
      text: >-
        Ground-camera data from collect-2 provide observations of participants at multiple distances for studying long-range recognition.
      image:
        src: "/assets/images/ground_range-collect_2.png"
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
        Elevated-camera data from collect-1 provide observations of participants from downward-looking viewpoints for studying recognition across viewing angles.
      image:
        src: "/assets/images/elevated-collect1.png"
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
        Elevated-camera data from collect-2 provide observations of participants from downward-looking viewpoints for studying recognition across viewing angles.
      image:
        src: "/assets/images/elevated-collect2.png"
        alt: Image needed
      metadata:
        - icon: ri-time-line
          text: "To be released"
      button:
        text: Get Data
        url: "#"
        target: "_blank"

    - title: Indoor Enrollment Data - Part 1
      text: >-
        Indoor enrollment data from collect-1 provide face, whole-body, gait, and depth observations of participants under controlled conditions.
      image:
        src: "/assets/images/indoor_enrollment-collect_1.png"
        alt: Image needed
      metadata:
        - icon: ri-time-line
          text: "To be released"
      button:
        text: Get Data
        url: "#"
        target: "_blank"

    - title: Indoor Enrollment Data - Part 2
      text: >-
        Indoor enrollment data from collect-2 provide face, whole-body, gait, and depth observations of participants under controlled conditions.
      image:
        src: "/assets/images/indoor_enrollment-collect_2.png"
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
      url: "https://github.com/Kitware/CALIPeR-Experiments"
      target: "_blank"


---
