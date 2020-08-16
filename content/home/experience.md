+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 25  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Software Developer"
  company = "Center for Research in Open Source Software"
  company_url = "https://cross.ucsc.edu/"
  location = "California"
  date_start = "2020-06-01"
  date_end = ""
  description = """Developed a client-layer Python application for the SkyhookDM -- a data management system that extends the Ceph object storage system with management functionality for tabular data -- that parses SQL statements into SkyhookDM CLI commands, executes them, and serializes the resulting Arrow, FlatBuffer, or CSV data frames. Worked on C++ libraries that defined the SkyhookDM API for applications by abstracting underlying binaries. Assisted a team with merging multiple Python modules into a single frontend for Skyhook. Designing a SkyhookDM SQL dialect that will be used to set SkyhookDM specific options for querying."""

[[experience]]
  title = "Research Assistant"
  company = "Baskin School of Engineering"
  company_url = "https://www.soe.ucsc.edu/"
  location = "California"
  date_start = "2020-06-01"
  date_end = ""
  description = """Implemented 3D geometry support in Scenic, a probabilistic programming language for designing and analyzing perception systems. Extended Scenic’s compiler and runtime in Python to support new syntax and semantics. Integrated 3D simulators by generalizing Scenic’s API to support new types and classes for simulator models. Collaborated with other research groups who use Scenic in order to incorporate features they need.ying."""

+++
