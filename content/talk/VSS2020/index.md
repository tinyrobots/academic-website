+++
title = "VSS 2020 accepted poster (conference cancelled)"

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Katherine R. Storrs", "Roland W. Fleming"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2020-05-16T08:30:00
date_end = 2020-05-16T12:30:00
all_day = false

# Location of event.
location = "Banyan Breezeway, VSS 2020, St Pete's Beach, Florida"

# Name of event and optional event URL.
event = "Learning to see gloss by predicting videos"
event_url = ""

# Abstract. What's your talk about?
abstract = "Despite the impressive achievements of supervised deep neural networks, brains must learn to represent the world without access to ground-truth training data. We propose that perception of distal properties arises instead from unsupervised learning objectives, such as temporal prediction, applied to proximal sensory data. To test this, we rendered 10,000 videos of objects moving with random rotational axis, speed, illumination, and reflectance. We trained a four-layer recurrent 'PredNet' network to predict the pixels of the next frame in each video. After training, object shape, material, position, and illumination could be decoded for new videos by taking linear combinations of unit activations. Representations were hierarchical, with scene properties better estimated from deep than shallow layers (e.g., material reflectance could be predicted with R$^2$=0.92 from layer 4, but only 0.54 from layer 1). Visualising single 'neurons' revealed selectivity for distal features: a 'shadow unit' in layer 4 responds exclusively to image locations containing the object's shadow, while a 'reflectance edge' unit in layer 3 tracks image edges caused by reflectance changes. Material decoding was higher for moving than static objects, and increased over the first five frames, demonstrating that the model is sensitive to motion features disambiguating reflective from textured surfaces. To test whether these features are similar to those used by humans, we rendered test stimuli depicting reflective objects that were either static, moving, or moving with 'reflections' fixed to their surface. All conditions had near-identical static image properties, but motion cues in the latter conditions give rise to glossy vs matte percepts, respectively. Model-predicted gloss agreed with human judgements of the relative glossiness of all stimuli. Our results suggest unsupervised deep learning discovers motion cues to material similar to those represented in human vision, and provides a framework for understanding how brains learn rich scene representations without ground-truth world information."

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = true

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
