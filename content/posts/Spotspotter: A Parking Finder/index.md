+++
date = '2025-01-31T19:52:04-05:00'
draft = false
title = 'Spotspotter: A Parking Finder'
+++

**Tools**: HTML, CSS, Vanilla Javascript (with modules like leaflet and chart.js)

As you circle around the block for the 5th time searching for an empty parking spot, don't you think—wow, I wish there could be an easier option?

**Spotspotter** is an interactive, crowdsourced parking finder that seeks to solve this information gap in Sacramento. 

<div class="gallery">
  <div class="gallery-item">
    <img src="img1.png" alt="Page 1">
    <p> Enter a location and a time slot to see all the available parking within walking distance.
</p>
  </div>
  <div class="gallery-item">
    <img src="img2.png" alt="Page 2">
    <p>The page also deploys an interactive chart showing the number of spots and their maximum parking time.</p>
  </div>
  <div class="gallery-item">
    <img src="img3.png" alt="Page 3">
    <p>You can click around the chart to see all the spots of a given time slot highlighted. </p>
  </div>
  <div class="gallery-item">
    <img src="img4.png" alt="Page 4">
    <p>Find a spot you like? Users can zoom into the particular spot and reserve it for the time limit.</p>
  </div>
    <div class="gallery-item">
    <img src="img5.png" alt="Page 5">
    <p>Reserved spots will then be unavailable to all users until the time slot runs out.</p>
  </div>
</div>



<style>
  .gallery {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
    margin: 20px 0;
  }
  .gallery-item {
    text-align: center;
  }
  .gallery-item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
    align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  .gallery-item p {
    margin-top: 10px;
    font-size: 1rem;
    font-family: "Quicksand", monospace;
    color: #D64933;
  }
</style>