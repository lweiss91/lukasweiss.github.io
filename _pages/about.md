---
layout: about
title: about
permalink: /
subtitle: 'C.V. Starr Postdoctoral Fellow<br><a href="https://pni.princeton.edu/">Princeton Neuroscience Institute</a><br>& <a href="https://eeb.princeton.edu/">Princeton Ecology & Evolutionary Biology</a>'

profile:
  align: right
  image: lukas-weiss2.jpeg
  image_circular: true

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>
.post-header {
  position: relative;
  isolation: isolate;
  padding-top: 130px;
  margin-bottom: 20px;
}

.post-header::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  height: 230px;
  background-image: url('{{ "/assets/img/Picture1.png" | relative_url }}');
  background-size: contain;
  background-position: top center;
  background-repeat: no-repeat;
  opacity: 0.35;
  z-index: -1;
  pointer-events: none;
}

.profile {
  position: relative;
  margin-top: -65px;
  z-index: 2;
}
  
.profile img {
  border: none !important;
  border-radius: 50% !important;
  aspect-ratio: 1 / 1;
  object-fit: cover;
  padding: 0 !important;
  box-shadow: none !important;
}

/* Hide artwork in dark mode */
html[data-theme="dark"] .post-header::before {
  display: none;
}

html[data-theme="dark"] .post-header {
  padding-top: 0;
}

html[data-theme="dark"] .profile {
  margin-top: 0;
}

/* Mobile layout */
@media (max-width: 576px) {
  .post-header {
    padding-top: 85px;
  }

  .post-header::before {
    height: 160px;
  }

  .profile {
    margin-top: 0;
  }

  html[data-theme="dark"] .post-header {
    padding-top: 0;
  }
}
  
/* Social media icons */
.social .contact-icons {
  font-size: 2.5rem !important;
}

.social .contact-icons a {
  margin: 0 6px;
}
  
</style>

I am a neuroscientist interested in how nervous systems evolve to give rise to novel behaviors. My research lies at the intersection of neuroethology, evolutionary biology, and sensory neuroscience.

I am particularly interested in the different modes of evolution through which neural circuits can change as animals adapt to new ecological niches. My interests span both insects and vertebrates, with a special focus on olfaction.

## Current research: Evolution of olfactory circuits during host specialization in mosquitoes

How does the nervous system evolve as animals adapt to new ecological niches?

In my current research at Princeton University, I investigate how the mosquito *Aedes aegypti* reshaped its olfactory circuits as it evolved to specialize on human hosts. By combining comparative neuroanatomy, functional imaging, neurogenetics, and behavior, I aim to understand how evolutionary changes in sensory circuits give rise to novel behavioral preferences.
