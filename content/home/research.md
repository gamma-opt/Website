+++
# A Skills section created with the Featurette widget.
widget = "featurette"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear.
id = "features"

title = "Research topics"
# subtitle = "Our research interests"

# Showcase personal skills or business features.
#
# Add/remove as many `[[feature]]` blocks below as you like.
#
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons


[[feature]]
  icon = "decision_making"
  icon_pack = "custom"
  align = "2"
  name = "Decision making under uncertainty"
  description = """
  - Endogenous uncertainty
  - Robust optimisation
  - Stochastic programming
  - Time series aggregation
  """

[[feature]]
  icon = "decomposition"
  icon_pack = "custom"
  align = "2"
  name = "Efficient formulations and solution methods"
  description = """
  - Convexification techniques
  - Cutting planes & column generation
  - Lagrangian-based decomposition methods
  - Parallelisation
  """

+++
<style>
    #research .row.featurette .col-12:nth-child(2), 
    #research .row.featurette .col-12:nth-child(3) {
    width: 50% !important;
    max-width: 100% !important;
    flex: 0 0 50%;
}</style>