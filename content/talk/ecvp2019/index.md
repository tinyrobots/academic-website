+++
title = "ECVP talk: Learning about Shape, Material, and Illumination by Predicting Videos"

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Katherine R. Storrs", "Roland W. Fleming"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2019-08-29T12:00:00
date_end = 2019-08-29T12:30:00
all_day = false

# Location of event.
location = "European Conference on Visual Perception, Leuven, Belgium"

# Name of event and optional event URL.
event = "Conference Talk"
event_url = ""

# Abstract. What's your talk about?
abstract = "Unsupervised deep learning provides a framework for understanding how brains learn rich scene representations without ground-truth world information. We rendered 10,000 videos of irregularly-shaped objects moving with random rotational axis, speed, illumination, and reflectance. We trained a recurrent four-layer 'PredNet' to predict the next frame in each video. After training, object shape, material, position, and lighting angle could be predicted for new videos by taking linear combinations of unit activations. Representations are hierarchical, with scene properties better estimated from deep than shallow layers (e.g., reflectance can be predicted with R<sup>2</sup>=0.78 from layer 4, but only 0.43 from layer 1). Different properties emerge with different temporal dynamics: reflectance can be decoded at frame 1, whereas decoding of object shape and position improve over frames, showing that information is integrated over time to disambiguate scene properties. Visualising single 'neurons' revealed selectivity for distal features: a 'shadow unit' in layer 3 responds exclusively to image locations containing the object's shadow, while a 'salient feature' unit appears to track high curvature points on the object. Comparing network predictions to human judgments of scene properties reveals they rely on similar image information. Our findings suggest unsupervised objectives lead to representations that are useful for many estimation tasks."

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
