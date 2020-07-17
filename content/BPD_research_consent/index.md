---
title: Consent Form
summary: for the use of data in academic research and for publishing
date: "2020-07-16T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `static/img/` folder).
header:
  caption: ""
  image: ""
---

<form name="BPD_research_consent" method="POST" data-netlify="true" netlify-honeypot="test-field">
  <p>
  <label>Not for you: <input name="test-field" /></label>
  </p>
  <p>
  By completing and submitting this form, you are agreeing to contribute your data to the research component for my MSc Integrative Psychotherapy dissertation at the Sherwood Psychotherapy Training Institute (SPTI), and for the preparation of the research findings for publication in a peer-reviewed journal (if indicated below).
  <br/>
  You are also signing to indicate that (please tick the applicable boxes below):
  </p>
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label for="Telephone">Enter your phone number: <input type="tel" id="phone" name="phone" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"></label>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
 
  <p>
    <input type="checkbox" id="consent1" name="consent1" value="agree">
  <label for="consent1"> you have voluntarily agreed to be a participant in this research.</label><br>
  <input type="checkbox" id="consent2" name="consent2" value="infopack">
  <label for="consent2"> you have read and understood the accompanying Information Pack, poster, and letter sent with this consent form.</label><br>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
