---
layout: about
title: About
permalink: /
subtitle: "Computational imaging researcher at the University of California, Davis."

profile:
  align: right
  more_info: >
    <swiper-container class="profile-photo-carousel" keyboard="true" navigation="true" pagination="true" pagination-clickable="true" rewind="true" aria-label="Profile photos">
      <swiper-slide>
        <img src="/fengtian.github.io/assets/img/profile-lakeside.jpeg" alt="Feng Tian at a lakeside in Lake Tahoe" style="display: block; width: 100%; aspect-ratio: 4 / 3; object-fit: cover; border-radius: 4px;">
        <p class="caption">Lakeside, Lake Tahoe</p>
      </swiper-slide>
      <swiper-slide>
        <img src="/fengtian.github.io/assets/img/profile-boardwalk.jpeg" alt="Feng Tian on a misty boardwalk in Yellowstone National Park" style="display: block; width: 100%; aspect-ratio: 4 / 3; object-fit: cover; border-radius: 4px;">
        <p class="caption">Misty boardwalk, Yellowstone National Park</p>
      </swiper-slide>
    </swiper-container>
    <p>University of California, Davis</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts

images:
  slider: true
---

<style>
.profile {
  width: min(42%, 400px);
}

.post-title {
  font-family: "Times New Roman", Times, serif;
  font-weight: 700;
}

.profile-photo-carousel::part(button-prev),
.profile-photo-carousel::part(button-next) {
  opacity: 0;
  pointer-events: none;
  transition: opacity 160ms ease;
}

.profile-photo-carousel:hover::part(button-prev),
.profile-photo-carousel:hover::part(button-next),
.profile-photo-carousel:focus-within::part(button-prev),
.profile-photo-carousel:focus-within::part(button-next) {
  opacity: 1;
  pointer-events: auto;
}

.post h2 a[href$="/news/"],
.post h2 a[href$="/publications/"] {
  text-transform: capitalize;
}

@media (max-width: 575px) {
  .profile {
    float: none !important;
    width: min(100%, 400px);
    margin-inline: auto;
  }
}
</style>

I am a researcher working on computational imaging, lensless cameras, and machine-learning methods for 3D microscopy. My work combines optical design, physics-informed reconstruction, and deep learning to build compact imaging systems with large fields of view and practical computational requirements.

My research includes lensless 3D cameras, integrated fluorescence microscopy, learned reconstruction algorithms, and computational microscopy.

<div class="social">
  <div class="contact-icons">{% social_links %}</div>
</div>

<!-- Edit `_bibliography/papers.bib` to populate the publications page. Edit `_data/socials.yml` to set your social links. -->
