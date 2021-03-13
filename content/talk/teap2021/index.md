+++
title = "Symposium organiser and speaker at TeaP 2021"

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Katherine R. Storrs", "Roland W. Fleming"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2021-03-15T09:00:00
date_end = 2020-03-15T10:30:00
all_day = false

# Location of event.
location = "TeaP"

# Name of event and optional event URL.
event = "Unsupervised learning predicts both successes and failures of gloss constancy"
event_url = "https://cops.ifp.uni-ulm.de/teap2021/"

# Abstract. What's your talk about?
abstract = "We rely on vision to understand the physical structure of our surroundings. Yet, the raw visual input is ambiguous—retinal images result from complex interactions between 3D shape, lighting and surface reflectance. How do we disentangle these to perceive individual physical quantities, like how glossy a surface is? We reasoned that, paradoxically, it may be possible to learn to infer properties of the distal world by learning to model statistical structure in proximal images. To test this, we rendered 10,000 images of bumpy surfaces of random colours, bump heights, illuminations, and gloss levels. We trained an unsupervised neural network to learn the statistics of this dataset by learning to predict pixel values in images, and then compared its internal representations with human gloss judgments. Despite receiving no information about gloss, shape or lighting during training, we found that the model spontaneously clustered images according to physical properties like reflectance and illumination. Most strikingly, it also displayed characteristic 'illusions' of human gloss perception caused by interactions between material, shape and illumination. For example, both humans and the model tended to see more highly curved surfaces as glossier. Across four psychophysical experiments, we found that the model's representations predicted specific patterns of successes and errors in human gloss perception better than ground truth, supervised neural networks, or diverse rival models. We suggest that unsupervised statistical learning may explain both the broad successes and idiosyncratic errors in our perception of physical quantities, in vision and beyond."

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
