+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 65  # Order that this section will appear.

title = "Projects"
subtitle = "Significant"

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   3 = Card
  #   5 = Showcase
  view = 3

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

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
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++
***1. Natural Language Generation (NLG) from Structured Data*** 

(*Duration: 2017- , Status: Ongoing*)

The research aims at generating natural language descriptions from structured data such as knowledge graphs, tables \textit{etc}. Motivated by the need to approach this problem in a manner that is scalable and adaptable to newer domain (unlike existing related systems that are rule/template-based or end-to-end neural systems), we introduce scalable modular approaches that do not require any labelled data for generation. Rather, these systems require only large scale unlabelled text and basic NLP tools such as Part of Speech taggers. Our initial experiments on a benchmark mixed domain dataset reveal the superiority of our framework over various existing data-to-text systems. We are currently focusing on generation of interesting narratives from structured data.

***2. Unsupervised Controllable Language Generation*** 

(*Duration: 2017-, Status: Ongoing*)

Like data-to-text NLG, scalable and interpretable solutions are also elusive for text-to-text NLG problems such as text-simplification, formalization, purpose paraphrasing. We aim to devise new unsupervised learning schemes for text-to-text NLG problems. So far we have proposed novel and practical solutions for unsupervised text simplification and controllable text transformation. We have also attempted to provide solutions for sarcasm generation, a highly nuanced task that requires language understanding at deep semantic and pragmatic levels.

***3. Cognitive NLP through Eye-tracking*** 

(*Duration: 2013-2017, Status: Completed, Remark: PhD. Thesis*)

The research attempts to gain insights into the cognitive underpinnings of human language processing and understanding. The insights are then translated to methods and models that contribute to the field of NLP by achieving the following objectives: (1) Optimizing Human \textit{Annotation Effort} for better annotation management for NLP, and (2) Improving existing NLP systems by introducing cognitive features.
    
Today’s NLP is highly statistical in nature and needs massive amount of human annotated data. In our setting, apart from collecting the annotations, we aim to record annotators’ activities in the form of their eye movement patterns, key-strokes and neuro-eletric signals obtained using EEG. Through a series of studies using eye-tracking alone, we show that data of such kind, can be used to model complexities of tasks like translation and sentiment annotation, where eye-movement data is used to label training data that model annotation effort for the specified tasks. This can be useful for better annotation management (for example, proposing better annotation cost models).  We also show that eye movement data can also be used to extract \textit{Cognition Driven} Features, to be used to be used for difficult NLP tasks like Sentiment Analysis and Sarcasm Detection. Our proposed approaches consistently perform better than state-of-the-art sentiment and sarcasm classifiers, showing that cognitive features can be useful for tasks that are nuanced by linguistic subtleties. For more information, visit the [Cognitive NLP](http://www.cfilt.iitb.ac.in/~cognitive-nlp) website.

***4. Indian Language Machine Translation*** 

(*Duration: 2013-2014, Status: Completed*)

We developed a compendium of 110 Statistical Machine Translation systems built from parallel corpora of 11 Indian languages belonging to the Indo-Aryan and Dravidian families. We analyze the relationship between translation accuracy and the language families involved. We feel that insights obtained from this analysis will provide guidelines for creating machine translation systems for specific Indian language pairs. For our studies, we built phrase based systems and some extensions. Across multiple languages, we show improvements on the baseline phrase based systems using these extensions: (1) Source side reordering for English-Indian language translation, and (2) Transliteration of untranslated words for Indian language-Indian language translation. These enhancements harness shared characteristics of Indian languages. To stimulate similar innovation widely in the NLP community, we have made the trained models for these language pairs publicly available. The system is available at: [http://www.cfilt.iitb.ac.in/indic-translator](http://www.cfilt.iitb.ac.in/indic-translator)

***5. Crowdsourcing for NLP Resources*** 

(*Duration: 2011-2013, Status: Completed*)

We developed a framework (Funded by Xerox Research Center, India) that helps an NLP developer to customize and float linguistic annotation tasks through popular crowdsourcing service providers (like Amazon’s Mechanical Turk). Though the framework is generic and flexible enough to tackle different linguistic tasks, we took Machine Translation as our use case to demonstrate its efficacy. We show that, using this framework, multilingual translation parallel corpora could be collected and quality controlled with less expenditure in comparison to the traditional way of outsourcing translation tasks to professional translators.
