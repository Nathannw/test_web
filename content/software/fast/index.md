---
title: Future Aircraft Sizing Tool (FAST)
subtitle: 'An open-source, MATLAB-based aircraft sizing tool for designing and analyzing conventional and electrified aircraft concepts with any propulsion architecture.'

summary: <font size="4">An open-source, MATLAB-based aircraft sizing tool for designing and analyzing conventional and electrified aircraft concepts with any propulsion architecture. It requires minimal knowledge and inputs from the user about the design, making it a versatile tool for aerospace engineers, researchers, and enthusiasts. This work was sponsored by the NASA Aeronautics Research Mission Directorate and the Electrified Powertrain Flight Demonstration (EPFD) project.</font>
authors: [gokcin-cinar, maxfield-arnson, paul-mokotoff, nawa-khalainy]
tags: [software]
categories: [aircraft design, electrification, open-source]
date: 2024-06-07T06:34:52-05:00
lastmod: 2024-06-07T06:34:52-05:00
featured: yes
draft: false
show_date: false

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: ""
  focal_point: Center
  preview_only: false

links:
#- icon: paper-plane
#  icon_pack: fas
#  name: Learn more
#  url: project/ideas
#- icon: "fas fa-users"
#  icon_pack: fas
#  name: Meet the team
#  url: /team
url_code: "https://github.com/ideas-um/FAST"
url_pdf: ""
url_slides: ""
url_video: "https://youtube.com/playlist?list=PLNbQSl1VumqhNHgNOq9oxm4_Toi4_7v3-&si=Q5wyAndeUVA0ZX89"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
projects: [FAST]
tags: [software, FAST]
categories: [software]

---
**Overview**

The Future Aircraft Sizing Tool (FAST) is an innovative, open-source, MATLAB-based aircraft design and analysis software developed by the IDEAS Lab at the University of Michigan. FAST was developed as part of a research project funded by the NASA Aeronautics Research Mission Directorate's Electrified Powertrain Flight Demonstration (EPFD) project. This tool facilitates the design and analysis of both conventional and electrified aircraft concepts. It supports any propulsion architecture and requires minimal knowledge and inputs from the user about the design, making it a versatile tool for aerospace engineers, researchers, and enthusiasts.
![High Level Aircraft Sizing Procedure](dsm.png "High Level Aircraft Sizing Procedure within FAST. *Source: Wang, Y.C., Arnson, M., Mokotoff, P.R., & Cinar, G. (2025). SUbsonic Single Aft eNgine (SUSAN) System Integration Analysis With the Future Aircraft Sizing Tool (FAST). AIAA SciTech Forum 2025. Paper submitted, awaiting decision.*")

**Disclaimer:** The figures on this page are part of a series of manuscripts in progress and should not be used without permission. Please cite them using the citation provided under each figure.

**Key Features:**

- **Aircraft Conceptual Design Tool:** FAST is designed for rapid exploration of the design space at the early stages of aircraft development. It supports the evaluation of thousands of configurations, offering rapid calculations essential for early-stage analysis.
- **Minimal Input Requirements:** FAST requires very few inputs to design an aircraft. Users only need to provide the range, payload, vehicle class, and propulsion system type to start designing a new concept.
- **Embedded Historical Database with Predictive Modeling:** FAST uses a historical database of over 200 aircraft and engines, compiled from type certificate data sheets (TCDS) provided by governing bodies like the FAA and EASA, and supplemented by existing databases. This open-source, collaborative database is continuously updated. FAST employs Gaussian Process Regressions (GPRs) to predict unknown aircraft parameters from fundamental requirements such as range and payload weight, as well as designer-specified constraints like thrust-to-weight ratio and wing loading. This allows FAST to function with minimal input by estimating missing variables required for sizing analysis and making future projections on key performance parameters.
![Gaussian Process Regressions](regression.png "Operating Empty Weight (OEW) Regression Response Surfaces created in FAST. *Source: Arnson, M., Aljaber, R., & Cinar, G. (2025). Predicting Aircraft Design Parameters using Gaussian Process Regressions on Historical Data. AIAA SciTech Forum 2025. Paper submitted, awaiting decision.*")
- **Versatile Design Capabilities:** FAST supports a wide range of aircraft concepts, from conventional designs to advanced electrified aircraft. It can size and design both fully electric and hybrid electric aircraft, powered by batteries and/or hydrogen fuel cells.
- **Propulsion Architecture Flexibility:** FAST can represent and size any propulsion architecture and unconventional energy sources, providing unparalleled flexibility in design and analysis. This facilitates the exploration and development of next-generation electrified aircraft.
- **Embedded Physics-based and Data-driven Models:** FAST uses a combination of physics-based and data-driven models for increased accuracy beyond conventional methods.
- **Future Technology and Key Performance Parameter Projection:** FAST leverages historical data, regressions, and physical drivers to predict future trends in aircraft design. This capability enables FAST to size and analyze aircraft concepts up to the year 2050, projecting key performance parameter values into the future. These insights can support further studies on cost and emission reduction strategies.
![Future Projections](projection.png "Cruise Specific Fuel Consumption (SFC) projection based on historical data and technology limits. *Source: Acar, H., Arnson, M., Tsai, M., & Cinar, G. (2024). Historical Trends and Future Projections of Key Performance Parameters in Aircraft Design. Manuscript under progress.*")
- **Detailed Mission Performance Analysis:** FAST offers full mission history, time step by time step, for flight mission performance evaluation. This allows for both design and off-design analyses.
![Mission History](mission_history.png "FAST output: A subset of figures summarizing the flight mission history. *Source: Mokotoff, P., Arnson, M., & Cinar, G. (2025). FAST: A Future Aircraft Sizing Tool for Electrified Aircraft Design. AIAA SciTech Forum 2025. Paper submitted, awaiting decision.*")
- **Integrated Visualization Feature:** FAST provides visualizations of the aircraft geometry's outer mold line and schematic representations of its propulsion architecture. Users can create custom geometries or utilize preset configurations available in FAST. The tool dynamically updates to reflect changes in the aircraft's shape and size as the design process converges, allowing users to see how the aircraft's dimensions change from its initial condition.
![Visualization Feature](visualization.png "FAST output: Scaling a notional LM-100J concept by changing the design requirements. Initial geometry in blue, sized geometry in red. *Source: Khailany, N., Mokotoff, P., & Cinar, G. (2025). Aircraft Geometry and Propulsion Architecture Visualization for the Future Aircraft Sizing Tool (FAST). Paper submitted, awaiting decision.*")

**Get Started with FAST**

FAST is open-source and freely available under an Apache 2.0 license. [To start using FAST, visit the GitHub repository here.](https://github.com/ideas-um/FAST) The repository contains detailed documentation, including a comprehensive user guide to help you get started with the software.

If you use FAST in your research or projects, please cite our work as follows:
- Future Aircraft Sizing Tool (FAST) developed by the IDEAS Lab at the University of Michigan. Available at: https://github.com/ideas-um/FAST

**FAST Video Tutorials**
Explore our comprehensive video tutorials to get the most out of the Future Aircraft Sizing Tool (FAST). Hosted by the IDEAS Lab researchers, these tutorials cover everything from installation to advanced features. Visit our [YouTube channel for all videos](https://www.youtube.com/channel/UC5ntmOSA1_YWu1ljQ5hXn0Q).

Stay tuned for more tutorials and updates. 

**Watch the Playlist**
<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?si=sWTFXYJsC8HX4XtE&amp;list=PLNbQSl1VumqhNHgNOq9oxm4_Toi4_7v3-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Visit our [YouTube channel for more tutorials.](https://www.youtube.com/channel/UC5ntmOSA1_YWu1ljQ5hXn0Q)

**Sign up for the FAST newsletter**
To stay informed about upcoming papers, new releases, and news about FAST, sign up for [our newsletter here](https://forms.gle/b8sPXKnRAfi5ZsARA):

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdsza7_s-xI7XTJ1BRzsDGluTcpxeR9zLnO77JezpmoGpljGA/viewform?embedded=true" width="640" height="570" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

**Funding and Acknowledgment:**
This work is sponsored by the NASA Aeronautics Research Mission Directorate and the Electrified Powertrain Flight Demonstration (EPFD) project, "Development of a Parametrically Driven Electrified Aircraft Design and Optimization Tool". The IDEAS Lab would like to thank Ralph Jansen, Andrew Meade, Karin Bozak, Amy Chicatelli, Noah Listgarten, Dennis Rohn, and Gaudy Bezos-O'Connor from the NASA EPFD project for supporting this work and providing valuable technical input and feedback throughout the duration of the project.

Glenn Engineering and Research Support Contract (GEARS) Contract No. 80GRC020D0003
