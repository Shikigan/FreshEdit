---
sidebar: false # or false to display the sidebar
sidebarlogo: fresh-white-alt # From (static/images/logo/)
include_footer: true # or false to display the footer
---

<style>
  body {
    background-color: #f4f4f4;
    color: white; /* Makes all text white */
    font-family: Arial, sans-serif; /* Optional: adds a clean font */
  }

  h1, h2 {
    color: black !important; /* Change title color to black */
    text-align: center; /* Centers the title and subtitle */
    margin-bottom: 0 !important; /* Removes any margin below the title */
    padding-bottom: 0 !important; /* Ensures there's no padding below */
  }

  h2 {
    font-size: 1rem !important; /* Makes h2 smaller */
    font-weight: normal !important; /* Removes boldness from h2 */
  }

  .container {
    text-align: center; /* Centers the text */
  }

  .image-container {
    position: relative;
    width: 100%;
    height: 300px;
    border-radius: 8px;
  }

  .image-container img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
  }

  .image-text {
    position: absolute;
    top: 90%; /* Aligns the text */
    left: 50%;
    transform: translateX(-50%);
    color: white;
    font-size: 13px;
    font-weight: normal;
    background-color: transparent;
    padding: 5px;
    white-space: nowrap; /* Prevents text from wrapping */
    overflow: hidden;     /* Hides overflow */
    text-overflow: ellipsis; /* Adds ... if the text is too long */
    max-width: 90%; /* Optional: keeps it within bounds */
  }
</style>

<div class="container">
  <h1>PROJECTS</h1>
  <h2>A selection of past projects we've successfully completed.</h2>
</div>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px; padding: 20px; border-radius: 8px;">
  <div class="image-container">
    <img src="/images/projects/driveway1.png" alt="Project 1">
    <div class="image-text">PRIVATE ROW</div>
  </div>
  <div class="image-container">
    <img src="/images/projects/staircase1.png" alt="Project 2">
    <div class="image-text">PUBLIC STAIRWAY LIGHTING</div>
  </div>
  <div class="image-container">
    <img src="/images/projects/rail_ramp.png" alt="Project 3">
    <div class="image-text">OVERBRIDGE RAMP</div>
  </div>

  <div class="image-container">
    <img src="/images/projects/motorway.png" alt="Project 4">
    <div class="image-text">Project 4</div>
  </div>
  <div class="image-container">
    <img src="/images/projects/driveway1.png" alt="Project 5">
    <div class="image-text">Project 5</div>
  </div>
  <div class="image-container">
    <img src="/images/projects/driveway1.png" alt="Project 6">
    <div class="image-text">Project 6</div>
  </div>

  <div class="image-container">
    <img src="/images/projects/driveway1.png" alt="Project 7">
    <div class="image-text">Project 7</div>
  </div>
  <div class="image-container">
    <img src="/images/projects/driveway1.png" alt="Project 8">
    <div class="image-text">Project 8</div>
  </div>
  <div class="image-container">
    <img src="/images/projects/driveway1.png" alt="Project 9">
    <div class="image-text">Project 9</div>
  </div>
</div>
