---
layout: post
title: Graduated with a Masters degree in Computer Science from Arizona State University
date: 2024-05-06 16:11:00-0400
inline: false
related_posts: false
---

I graduated from Arizona State University with a masters degree in Computer Information Technology with a GPA of 4.26/4.0 <span id="replayEmoji" title="Replay Confetti" style="cursor: pointer;">🎉</span>

These two years (2022 - 2024) have been quite a wild ride. If you ask about my experience, I'd describe it this way:
> Masters is definitely not easy, but not that difficult as well. The support of friends, family, and cherished memories—along with all the late-night study sessions and celebratory parties—lifts you up and helps you cross the finish line.
>

I appeared on the ASU-ISSC's instagram page as part of their convocation series. Watch the <a href="https://www.instagram.com/p/C6udyj_PHi_/" target="_blank">reel</a>.

---

## Graduation Gallery

<div class="row mt-3">

    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Grad_6.jpg" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="assets/img/Grad_2.jpg" class="img-fluid rounded z-depth-1"  %}
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Grad_3.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>

</div>

----

#### TOMNET Team

<div class="row mt-3">

    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Grad_4.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">
          (Left to Right) Dr. Pendyala, Dr. Batur, Ashwath
        </div>
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Grad_5.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
        <div class="caption">
          (Left to Right) Fan, Miguel, Ashwath, Victor, Roberto
        </div>
    </div>
</div>
<div class="caption">
    CAVC #575 <span id="replayHeart" title="Replay Confetti" style="cursor: pointer;"> &hearts; </span>
</div>

<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.4.0/dist/confetti.browser.min.js"></script>
<script>
  var duration = 5 * 1000;
  var animationEnd = Date.now() + duration;
  var defaults = { startVelocity: 30, spread: 360, ticks: 60, zIndex: 0 };

  function randomInRange(min, max) {
    return Math.random() * (max - min) + min;
  }

  function launchConfetti() {
    var interval = setInterval(function() {
      var timeLeft = animationEnd - Date.now();

      if (timeLeft <= 0) {
        return clearInterval(interval);
      }

      var particleCount = 50 * (timeLeft / duration);
      // since particles fall down, start a bit higher than random
      confetti(Object.assign({}, defaults, { particleCount, origin: { x: randomInRange(0.1, 0.3), y: Math.random() - 0.2 } }));
      confetti(Object.assign({}, defaults, { particleCount, origin: { x: randomInRange(0.7, 0.9), y: Math.random() - 0.2 } }));
    }, 250);
  }

  document.addEventListener('DOMContentLoaded', function() {
    launchConfetti();
    document.getElementById('replayEmoji').addEventListener('click', function() {
      animationEnd = Date.now() + duration;  // Reset the animation end time
      launchConfetti();
    });
  });

  document.addEventListener('DOMContentLoaded', function() {
    launchConfetti();
    document.getElementById('replayHeart').addEventListener('click', function() {
      animationEnd = Date.now() + duration;  // Reset the animation end time
      launchConfetti();
    });
  });
</script>
