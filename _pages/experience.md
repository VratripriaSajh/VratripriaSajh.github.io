---
title: "Experience & Leadership"
permalink: /experience/
author_profile: true
layout: single
---

## Industrial Attachment

**Industrial Trainee — Tricon Properties, Rajshahi**  
6–20 September 2026

The industrial attachment provided exposure to construction site activities, site-related communication, project information collection, project management, site operations, and construction processes.

<div class="project-gallery">
  <a class="gallery-lightbox-trigger" href="/assets/images/site-observation.jpg" aria-label="View enlarged image"><img src="/assets/images/site-observation.jpg" alt="Construction site observation during industrial attachment"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/information-collection.jpg" aria-label="View enlarged image"><img src="/assets/images/information-collection.jpg" alt="Collecting project information with site professionals"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/training-completion.jpg" aria-label="View enlarged image"><img src="/assets/images/training-completion.jpg" alt="Industrial training completion"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/training-certificate.jpg" aria-label="View enlarged image"><img src="/assets/images/training-certificate.jpg" alt="Tricon Properties training completion certificate"></a>
</div>

## Leadership

- **General Secretary**, GKA Association at RUET — December 2025 – Present
- **Cultural Secretary**, BECM Club, RUET — January 2026 – Present

## Extra-curricular Activities & Achievements

- Architectural Sketching Competition (2019) — **1st Place**
- National-Level Recitation, 10th Inter-School Competition (2018) — **1st Place**
- National-Level Debate, 8th Education Week Competition (2016) — **2nd Place**

<style>
.gallery-lightbox-trigger { display: inline-block; cursor: zoom-in; }
.gallery-lightbox-trigger img { cursor: zoom-in; }
.gallery-lightbox { position: fixed; inset: 0; z-index: 99999; display: none; align-items: center; justify-content: center; padding: 24px; background: rgba(0,0,0,.88); }
.gallery-lightbox.is-open { display: flex; }
.gallery-lightbox img { display: block; max-width: 92vw; max-height: 88vh; width: auto; height: auto; object-fit: contain; box-shadow: 0 8px 36px rgba(0,0,0,.45); }
.gallery-lightbox-close { position: absolute; top: 14px; right: 22px; border: 0; background: transparent; color: #fff; font-size: 38px; line-height: 1; cursor: pointer; }
.gallery-lightbox-caption { position: absolute; left: 5%; right: 5%; bottom: 12px; color: #fff; text-align: center; font-size: 14px; }
body.gallery-lightbox-active { overflow: hidden; }
</style>
<div class="gallery-lightbox" id="gallery-lightbox" role="dialog" aria-modal="true" aria-label="Enlarged project or experience image">
  <button class="gallery-lightbox-close" type="button" aria-label="Close enlarged image">&times;</button>
  <img src="" alt="">
  <div class="gallery-lightbox-caption"></div>
</div>
<script>
(function () {
  var overlay = document.getElementById('gallery-lightbox');
  if (!overlay || overlay.dataset.ready === 'true') return;
  overlay.dataset.ready = 'true';
  var enlarged = overlay.querySelector('img');
  var caption = overlay.querySelector('.gallery-lightbox-caption');
  var closeButton = overlay.querySelector('.gallery-lightbox-close');

  function closeLightbox() {
    overlay.classList.remove('is-open');
    document.body.classList.remove('gallery-lightbox-active');
    enlarged.removeAttribute('src');
  }

  document.addEventListener('click', function (event) {
    var trigger = event.target.closest('.gallery-lightbox-trigger');
    if (trigger) {
      event.preventDefault();
      var thumbnail = trigger.querySelector('img');
      enlarged.src = trigger.href;
      enlarged.alt = thumbnail ? thumbnail.alt : '';
      caption.textContent = enlarged.alt;
      overlay.classList.add('is-open');
      document.body.classList.add('gallery-lightbox-active');
    } else if (event.target === overlay || event.target === closeButton) {
      closeLightbox();
    }
  });

  document.addEventListener('keydown', function (event) {
    if (event.key === 'Escape' && overlay.classList.contains('is-open')) closeLightbox();
  });
})();
</script>
