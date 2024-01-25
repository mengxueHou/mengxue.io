+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
weight = 65  # Order that this section will appear.

title = "Research"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  # columns = "2"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DarkGreen"
  # gradient_end = "ForestGreen"
  
  # Background image.
  # image = "pylons.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  # text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  # padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<img class="special-img-class" src="/uploads/research.png" />

---

To enable exploration of unstructured and dynamic open worlds, robotic systems have to **collaborate with human operators to co-exist in a complex, ever-changing and unknown environment**, and should feature behaviors that are **cognizant**, **adaptive**, and **taskable**: the robots need to be aware of their capabilities, identify the changes in environmental dynamics, learn from past experiences to improve system performance, and understand high-level instructions to plan multi-modal strategies that are dependent on the context in which the system is operating. Such features result in the following research questions:


**Cognizant:** how to represent the agent's knowledge in an unstructured environment, without a pre-defined set of scene parameters? 

**Taskable:** how to efficiently discover useful multi-modal distributed strategies for human-robot teams? 

**Adaptive:** how to learn from past sensory data to build  skills that can adapt over time to the particularities of the environment?


In this context, my research focuses on  foundational advances in robotics and autonomy. I aim to devise practical, computationally-efficient, and provably-correct algorithms that prepare autonomous systems working synergistically with human operators to explore unknown, unstructured and dynamic environments. I will also seek to develop robotic platforms to validate the autonomy algorithms. The underlying hypothesis in my research is that the interactions between agents and  the environment provide rich information: on one hand, the robot can leverage its actions and observed effects to train a high-fidelity prediction model (Thrust A). The learned model enables planning and control synergies of interaction policy for  human-robot team (Thrust B). On the other hand, the robot can also use the historical perception data to directly learn the skills to achieve efficient sensorimotor understanding and planning (Thrust C). 

