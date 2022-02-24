+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # Do not modify this line!
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

# Note: a full width section format can be enabled by commenting out the `title` and `subtitle` with a `#`.
title = "Software"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  #image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  #image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  #text_color_light = true

[advanced]
 # Custom CSS. 
 #css_style = "padding-top: 20px; padding-bottom: 20px;"
 css_style = ""
 # CSS class.
 css_class = ""
+++

## JMbayes2 <img src="../../img/Hex_Stickers/JMbayes2_logo.png" width="160" height="160" align="right">
[GitHub](https://github.com/drizopoulos/JMbayes2) | 
[website](https://drizopoulos.github.io/JMbayes2/)

<b>JMbayes2</b> is an R-package that was co-developed by Prof. [Dimitris Rizopoulos](https://www.drizopoulos.com), me, and [Pedro M. Afonso](https://www.pafonso.com/)

The package <b>JMbayes2</b> fits joint models for longitudinal and time-to-event data. It can accommodate multiple longitudinal outcomes of different type (e.g., continuous, dichotomous, ordinal, counts), and assuming different distributions, i.e., Gaussian, Student’s-t, Gamma, Beta, unit Lindley, censored Normal, Binomial, Poisson, Negative Binomial, and Beta-Binomial. For the event time process, right, left and interval censored data can be handled, while competing risks and multi-state processes are also covered.

<b>JMbayes2</b> fits joint models using Markov chain Monte Carlo algorithms implemented in C++. Besides the main modeling function, the package also provides a number of functions to summarize and visualize the results.
