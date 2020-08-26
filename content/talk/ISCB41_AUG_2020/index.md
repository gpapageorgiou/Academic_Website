+++
title = "An Alternative Characterization of Missing at Random in Shared Parameter Models"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2020-08-25T14:24:00
#date_end = 2019-07-15T14:42:00
all_day = true

# Schedule page publish date (NOT talk date).
publishDate = 2017-01-01T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

# Location of event.
location = "Krakow, Poland"

# Name of event and optional event URL.
event = "ISCB"
event_url = "https://iscb2020.info/"

# Abstract. What's your talk about?
abstract = ""

# Summary. An optional shortened abstract.
summary = "Missing at Random Shared Parameter Models and Sensitivity Analysis using Joint Models for Longitudinal and Time-to-Event data"

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = "ISCB_2020.pdf"

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

# Demo talk page uses LaTeX math.
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
+++

<b>Background</b>:

Dropout is a common complication in longitudinal studies, especially since the distinction between random (MAR) and non-random (MNAR) dropout is intractable. Consequently, one starts with an analysis that is valid under MAR and then performs sensitivity analysis by considering MNAR departures from it. To this end, specific classes of joint models, such as pattern-mixture models (PMMs) and selection models (SeMs), have been proposed. Contrariwise, shared-parameter models (SPMs) have received less attention as they do not embody a characterization of MAR. A few approaches to achieve MAR in SPMs exist, but are challenging to implement in existing software. 
 
<b>Objectives</b>:

Motivated by randomized clinical trial data on the efficacy of drugs on HIV patients, we propose an alternative characterization of MAR in SPMs by exploiting the conditional independence between outcome and missingness given a set of common random-effects. By doing so, we can utilize the censoring distribution to cover various assumptions for the missing data generating mechanism on the subject-specific level. Our objective is to assess the plausibility of different assumptions concerning missingness under the SPM framework.

<b>Methods</b>:

We use joint models for incomplete longitudinal and time-to-event data to investigate how considering all dropout cases to be MNAR, MAR, or partly MNAR and MAR impacts model coefficients and subject-specific predictions. The behavior of our approach under different settings for the amount of MAR and MNAR dropout is stressed in a simulation study.
 
<b>Results</b>:

Our results suggest that MAR and MNAR models can lead to differences in model coefficients and subject-specific predictions. The magnitude of these differences and the performance of each model may be affected by the amount of MAR and MNAR dropout cases, as suggested by our simulation findings.
 
<b>Conclusion</b>:

This intuitive approach offers substantial advantages and can be easily implemented in existing software. It offers flexibility over the missing data generating mechanism by allowing subject-specific perturbations of the censoring distribution, whereas, in PMMs and SeMs, dropout is strictly considered MNAR. Finally, the subject-specific nature of such a sensitivity analysis framework encompasses a toolkit for both individual-specific and risk-specific assumptions, with the latter allowing the consideration of competing dropout mechanisms.
