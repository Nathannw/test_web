---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Transient Surrogate Modeling for Thermal Management Systems"
authors: [Andrew T. Van Zwieten, Gokcin Cinar, Elena Garcia, Jonathan C. Gladin, Dimitri N. Mavris]
date: 2020-01-05
doi: "10.2514/6.2020-1616"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-01-19T12:39:40-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "AIAA Scitech 2020 Forum"
publication_short: ""

abstract: "In typical multidisciplinary design optimization problems, with varying missions, aerodynamic data, engine data, Thermal Management Systems (TMS), and other parameters it can take upwards of millions of runs to cover the full design space which result in extremely large computational burden, reducing the effectiveness of the design process. The objective of this work is to create a technical approach, leveraging existing concepts in surrogate modeling and other relevant fields, for the creation of a Transient TMS surrogate model. This work utilizes Design of Experiments to intelligently sample a model’s design space, surrogate modeling to enable instantaneous predictions, and state space modeling to allows surrogates to carry predictions forward. By leveraging these three components, a six step methodology was developed. This paper explains the developed methodology with an application on a notional Transient TMS. We first pre-process the time dependent data and possible correlations between input variables, then break down a set of input variables into a series of step functions which represent input schedules in a fraction of the time. We create Artificial Neural Network models to predict the future response of a metric of interest using the current response of both the input step functions and the corresponding output. We finally test whether the surrogates which were created with step functions could be used to predict the future response of the metric of interest for a full time trace of a sample aircraft mission. We show that this methodology yields acceptable predictions for both the partial and full time trace, with a maximum error of 5% and 10%, respectively."

# Summary. An optional shortened abstract.
summary: ""

tags: [thermal management systems, transients, surrogate modeling, artificial neural networks]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://smartech.gatech.edu/handle/1853/62476
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
