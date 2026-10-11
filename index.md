---
layout: default
title: Tint Meter Support
permalink: /
---

# Support

**Tint Meter** estimates how much visible light a car or house window lets through, its VLT, using only the iPhone camera. It reads the light once with the window down and once through the glass, and the ratio of the two is the result. It then compares that result with the legal tint limit of the region you choose.

There is no account, no server and no network access. Everything is measured and stored on your iPhone.

---

## Contact

**developer.barseghyan@gmail.com**

I usually reply within about two business days. If a reading looks wrong, please read *"A reading looks wrong"* below before writing, and include what it asks for. It makes the fix much faster.

---

## Before anything else

**Tint Meter gives an estimate, not a certified measurement.** A phone camera is not a calibrated photometer. The app is built to make its readings as repeatable as a phone allows and shows its own uncertainty on every result, but it is not approved for inspection, enforcement or any legal purpose. If a decision depends on the number, have the window measured with a certified tint meter.

---

## Frequently asked questions

### How does it work?

With the window down, tap **Set**: the app reads the light coming in from the view outside. Roll the window up: the app reads the same view through the glass. The share of light that got through is the window's VLT.

To make the two readings comparable, the camera is locked to fixed manual exposure, white balance and focus, and the numbers come from the sensor's raw data rather than the processed picture. The two readings are lined up with each other and compared cell by cell over the centre of the view, so a small difference in aim or a single bright reflection does not move the result.

### How do I get a good reading?

The short version (the app's **Get the best reading** screen has the full one):

1. **Measure from inside**, camera facing out through the window opening.
2. **Aim at a steady view**: a building wall, the ground in shade, an overcast sky. Nothing moving in the frame, and never the sun.
3. **Steady daylight.** Overcast or full shade is best. Avoid low sun, racing clouds, lamps and night.
4. **Keep reflections out.** Dark clothing, screen brightness low, the lens close to where the glass will be.
5. **Clean, dry glass** at the spot you measure.
6. **Double-check** important readings: from the result, roll the window down once more and the app confirms the light held steady.

### What are the ring and the cross on the screen?

After the first reading the app remembers where the phone was aiming. The ring marks the centre of the screen and the cross marks that remembered aim, with a faint copy of the first view behind it. If the phone stays in place, the cross stays in the ring. If you put the phone down to work the window switch, pick it up again and move it until the cross sits upright in the ring; the app takes the reading by itself once the view is steady there.

On a plain view such as an even sky, the cross follows the phone's motion sensors instead of the picture. That works too, but it is a little less exact, so try to come back within a minute.

### My window doesn't open.

For a house window, a rear windshield or any fixed pane, tap **Window doesn't open?** on the first step. You then take the first reading from the open side (outside, or at an open section) with the phone where the glass would be, and the second from the other side, through the glass, facing the same view. The cross helps you aim the same way both times. Results taken this way are marked as measured from both sides.

### How accurate is it?

Careful readings of the same window usually agree within a few percentage points. Every result shows its own **± band** and a confidence rating, worked out from that measurement: how steady the frames were, whether the light changed, and how dark the glass is. A double-check narrows the band and lets the app rate the reading **high confidence**.

What most often makes a reading wrong is not the camera but the setup: the light changing between the two readings, a reflection on the inside of the glass, or the view changing because the phone moved. The app warns about each of these when it sees them.

### Why doesn't the result match the number on my film?

Film is sold by the light **the film alone** lets through: 70, 50, 35, 20, 15 or 5 %. On a window it is stuck to glass that already passes only about 72–88 % on its own, so the window as a whole reads the product of the two. A 35 % film on typical side glass reads about 25–31 %, and an untinted front side window about 75–85 %.

That is why results are rarely round numbers, and why the app does not round them. Under the result, a card suggests which film shade the reading most likely corresponds to, assuming clear glass. It is a guide for comparing with the label, never a replacement for the measured number. Rear windows are often dark from the factory, and there the suggestion does not apply.

### What do the legal verdicts mean?

<span class="tag good">Likely within the limit</span> The whole ± band is at or above the minimum for the window position you picked.

<span class="tag bad">Likely below the limit</span> The whole band is below the minimum.

<span class="tag warn">Too close to call</span> The band straddles the minimum. Only a certified meter can settle it.

<span class="tag neutral">No confirmed limit</span> The app has no reliable figure for that window in that region. Check locally.

Limits are bundled for 83 regions, including every US state and DC, Canadian provinces, the UK, much of Europe, Armenia, Georgia, Turkey, the UAE, Australian states and New Zealand. Each shows the date it was last checked. Laws change and many have exceptions (vehicle type, medical permits, windshield strips), so the verdict is information, **not legal advice**.

### The app says "Too Bright", "Too Dark" or "Hold Steady".

Each message says what to change:

- **Too Bright**: part of the view is overexposed. Turn away from the sun, a sunlit window or chrome.
- **Too Dark**: not enough light. Measure in daylight, aimed at a brighter view.
- **Uneven View**: something covers part of the camera, often a finger, the edge of the glass or the window frame.
- **Hold Steady**: the light jumped around during the reading. Brace the phone on the door or the seat.
- **Brighter Than Before**: more light came through the glass than with the window down. Usually the window was not all the way up, or the sun came out. Redo the first reading.

### Why does the app need the camera?

The camera is the light meter. Each frame is reduced to numbers on the spot, plus a small greyscale preview kept in memory to help you aim. No photo or video is ever saved or sent anywhere. The app also uses the motion sensors, without a permission prompt, only to guide the aim. See the [Privacy Policy]({{ site.baseurl }}/privacy).

### What is free, and what does Pro include?

**Free:** 3 complete measurements every calendar month, each with the full result, uncertainty, confidence and the legal verdict for your region. The allowance comes back on the first day of each month. A double-check does not count as an extra measurement.

**Pro:** unlimited measurements; saved history with vehicle or location labels and window positions; notes for film brand and install date; PDF reports; and comparing a result against every bundled region.

Pro is a **one-time purchase**. There is no subscription. The price is shown in the app in your own currency before you buy.

### How do I restore my purchase?

On a new or reset iPhone, open **Get Tint Meter Pro** from the menu on the home screen and tap **Restore purchase**. You must be signed in with the same Apple Account that bought Pro.

### Can I get a refund?

Purchases are made from Apple, and refunds are decided by Apple. Request one at [reportaproblem.apple.com](https://reportaproblem.apple.com). I cannot issue refunds myself.

### Is there an iPad or Android version?

Not yet. The app is for iPhone and needs iOS 17 or later.

### A reading looks wrong.

Please tell me. Send to **developer.barseghyan@gmail.com**:

1. a screenshot of the result
2. which window it was (front side, rear side, rear windshield, house window), and whether it has film, with its shade if you know it
3. the conditions: what the camera was aimed at, sun or overcast, inside or outside
4. if you have one, a reading of the same window from a certified tint meter

A reading compared with a certified meter is the most useful report there is.

---

[Privacy Policy]({{ site.baseurl }}/privacy) · [Terms of Use]({{ site.baseurl }}/terms)
