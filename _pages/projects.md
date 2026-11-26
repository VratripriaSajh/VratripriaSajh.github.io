---
title: "Selected Projects"
permalink: /projects/
author_profile: true
layout: single
---

These academic design projects showcase work in building design, interior planning, and landscape design.

## Design of a Vacation House

A physical architectural model illustrating building form, site arrangement, access path, outdoor seating, and the relationship between the house and its landscape. The model includes a curved stepping-stone path, seating, and a small water feature.

<div class="project-gallery">
  <a class="gallery-lightbox-trigger" href="/assets/images/vacation-house-1.jpg" aria-label="View enlarged image"><img src="/assets/images/vacation-house-1.jpg" alt="Vacation house physical model showing site arrangement"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/vacation-house-2.jpg" aria-label="View enlarged image"><img src="/assets/images/vacation-house-2.jpg" alt="Vacation house model with curved pathway and outdoor seating"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/vacation-house-3.jpg" aria-label="View enlarged image"><img src="/assets/images/vacation-house-3.jpg" alt="Vacation house model from another angle"></a>
</div>

## Interior Design of an Office Building

An office layout combining individual work areas, shared workstations, meeting spaces, and a reception zone around a central circulation area.

<div class="project-gallery">
  <a class="gallery-lightbox-trigger" href="/assets/images/office-floor-plan.jpg" aria-label="View enlarged image"><img src="/assets/images/office-floor-plan.jpg" alt="Office building floor plan"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/office-conference.jpg" aria-label="View enlarged image"><img src="/assets/images/office-conference.jpg" alt="3D conference room interior view"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/office-workstations.jpg" aria-label="View enlarged image"><img src="/assets/images/office-workstations.jpg" alt="3D office workstation and reception view"></a>
  <a class="gallery-lightbox-trigger" href="/assets/images/office-interior.jpg" aria-label="View enlarged image"><img src="/assets/images/office-interior.jpg" alt="3D individual office interior view"></a>
</div>

## Proposed Landscaping Design for Tong Area at RUET

A proposed outdoor space arranging seating, a gazebo, greenery and planting, pedestrian walkways, a water feature, and an open lawn. The concept aims to provide RUET students with a comfortable place for relaxation, study, social interaction, and recreation.

<a class="gallery-lightbox-trigger" href="/assets/images/tong-landscape.jpg" aria-label="View enlarged image"><img class="project-feature" src="/assets/images/tong-landscape.jpg" alt="Proposed landscape design for Tong Area at RUET"></a>

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
