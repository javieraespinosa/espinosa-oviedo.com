+++

widget = "portfolio"  
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 22  

title = "Projects"
subtitle = "Coordinator, Researcher and/or Research Engineer"

[content]
  # Page type to display. E.g. project.
  page_type = "project"

  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.

  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 1

  [[content.filter_button]]
    name = "All"
    tag = "*"

  [[content.filter_button]]
    name = "Active 🔥"
    tag = "Ongoing"


#  [[content.filter_button]]
#    name = "EUROPEAN"
#    tag = "EU"  

#  [[content.filter_button]]
#    name = "STIC-AMSUD"
#    tag = "STIC-AMSUD"

#  [[content.filter_button]]
#    name = "ECOS-NORD"
#    tag = "ECOS-NORD"

  [[content.filter_button]]
    name = "TechnoTransfer"
    tag = "Techno Transfer"

  [[content.filter_button]]
    name = "Services & Cloud"
    tag = "SOC"

  [[content.filter_button]]
    name = "Urban Computing"
    tag = "Urban Computing"

  [[content.filter_button]]
    name = "Digital Humanities"
    tag = "Digital Humanities"

  [[content.filter_button]]
    name = "IoT"
    tag = "IoT"

[design]
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false
+++
