---
layout: page.html
title: Google Maps Review Links & QR Codes Generator
meta_title: Google Maps Review Links & QR Code Generator | Free Tool
meta_description: Free tool to generate Google Maps review links and QR codes - no registration needed, no data collected - Manchester web developer
---

# Google Maps Links & QR Codes Generator

I noticed that when I searched for ways to easily get links or create QR codes for Google Maps listing reviews, many of the options asked for your personal data or were iffy in some other way, so I made this little tool to help you create them.

No registration is required, and no data is collected.

**Note: This tool won't work if your business is set to "service area" in Google Maps, meaning it doesn't show at an address. There's no easy way around this - sorry!**

<form class="google-maps">
  <h2>Search For A Business</h2>
  <input type="text" class="search-text" placeholder="Enter business name" />
  <button type="submit">Search</button>
  <div class="results-container">
    <h3>Select the correct business:</h3>
    <div class="results-list"></div>
  </div>
  <div class="place-id"></div>
  <div class="urls">
    <div class="read">
      <div>
        <a href="#" target="_blank">Read Reviews</a>
      </div>
      <input type="text" />
      <div class="qr"></div>
    </div>
    <div class="write">
      <div>
        <a href="#" target="_blank">Write a Review</a>
      </div>
      <input type="text" />
      <div class="qr"></div>
    </div>
  </div>
</form>

<script src="/assets/qrcode.min.js" async defer></script>
<script src="/assets/google-reviews.js" async defer></script>
<script
  src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAXFyPM5DP1cpETPtYHFuW1i3h387gX6L0&libraries=places&callback=initGooglePlacesFinder"
  async
  defer
></script>
