+++
title = "Invited talk, Vrije Universiteit Amsterdam"

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Katherine R. Storrs", "Onno Kampmann", "Reuben Rideaux", "Guido Maiello", "Roland Fleming"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2022-05-17T17:15:00
date_end = 2020-12-04T19:15:00
all_day = false

# Location of event.
location = "St Pete Beach, Florida"

# Name of event and optional event URL.
event = "Properties of V1 and MT motion tuning emerge from unsupervised learning"
event_url = ""

# Abstract. What's your talk about?
abstract = "Our ability to perceive motion arises from a hierarchy of motion-tuned cells in visual cortices. Signatures of V1 and MT motion tuning emerge in artificial neural networks trained to report speed and direction of sliding images (Rideaux & Welchman, 2020). However, the brain's motion code must develop without access to such ground truth information. Here we tested whether a more realistic learning objective—unsupervised learning by predicting future observations—also yields motion processing that resembles physiology. We trained a two-layer recurrent convolutional network based on predictive coding principles (PredNet; Lotter, Kreiman & Cox, 2016) to predict the next frame in videos. Training stimuli were 64,000 six-frame videos depicting natural image fragments sliding with uniformly-sampled random velocity and direction. The network's learning objective was to minimise mean absolute pixel error between its prediction and the actual next frame. Despite receiving no explicit information about direction or velocity, we found that almost all units in both layers of the network developed tuning to a specific motion direction and velocity, when probed with sliding sinusoidal gratings. The network also recapitulated population-level properties of motion tuning in V1. In both layers, mean activation across the population of units showed a motion direction anisotropy, peaking at 90 and 270 degrees (vertical motion), likely due to static orientation statistics of natural images. Like MT neurons, units in the network appeared to solve the 'aperture problem'. When probed using pairs of orthogonally-drifting gratings superimposed to create plaid patterns, almost all units were tuned to the direction of the whole pattern, rather than its individual components. Unsupervised predictive learning creates neural-like single-unit tuning, population tuning statistics, and integration of locally-ambiguous motion signals, and provides an interrogable model of why motion computations take the form they do."

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["display"]

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = ""

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Links (optional).
url_pdf = ""
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"
+++
