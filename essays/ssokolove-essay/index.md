---
# Change these five lines as soon as you copy this starter.
title: Football UNM 
author: Sarea Sokolove 
category: Sports                  # change to a category from the student guide
header-image: sample-archive-photo.jpg   # the filename of your own image
header-caption: Replace with where your header image came from. Plain text only, no links.

# Fill these in later, once your research is under way.
card-description: Replace this with two sentences that summarize the story your essay tells and why it matters.
start:                                   # the year your story begins, shown on the map

# Leave this line as it is.
layout: essay
---
Football has been an importat part of the Universtiy of New Medxico's hisotry for many years. Today the Universty Stadium is known as the home to the New Mexico Lobos, where students, alimni and fans come together to support their team. however, football at UNM did not alwways look the way it does today. 

Keep the above lead paragraph first. Do not put an image, a heading, or any other component above it.

## Main Story

University Stadium, home of the University of New Mexico Lobos, represents an important part of the university’s athletic history. Since opening in 1960, it has hosted football games and brought together students, alumni, and local supporters. Its history shows how a sports facility can become part of a university’s identity through memorable games, improvements, and shared traditions. Before University Stadium opened, Lobo football had already occupied other locations. UNM’s athletics records identify University Field as the team’s home from 1892 through 1937 and Zimmerman Field from 1938 through 1959. These earlier fields were on the main campus, where academic buildings such as Ortega Hall, the Humanities Building, and Woodward Hall now stand. The move to University Stadium in 1960 marked a new chapter in the program’s history and changed where supporters gathered to watch the Lobos play.


<!-- Full-width figure. This is the default for any landscape photo wider than about 700px.
     image-path is just the filename: upload your images into this essay's folder,
     next to index.md. -->

{% include images/figure.html
  class="img-center"
  width="100%"
  caption="Replace this caption. Say why the image matters, not just what it shows, then cite where you found it: [Center for Southwest Research](https://econtent.unm.edu/), collection and box number."
  image-path="sample-archive-photo.jpg"
%}

Every image needs a caption, including this one. A caption should explain what the reader should notice and where the image came from. Captions accept Markdown, so use `[source](https://example.com/)` to link to a digital collection whenever the image has an online home.

## What Changed

Use this section to explain change over time. What did your topic used to be? How did people use it, describe it, fund it, argue about it, rename it, neglect it, preserve it, or forget it?

This is a good place to connect your specific topic to a larger campus pattern: enrollment growth, architecture, student life, race, gender, labor, protest, public memory, administration, technology, or access.

<!-- Carousel: use when you have three or more images that belong together but do not
     each need their own paragraph. Images are split on commas, captions on the | character.
     Carousel captions are plain text: Markdown links will NOT work here, so write out
     the collection name and box number instead of linking. -->

{% assign images =
"sample-archive-photo.jpg,
sample-second-photo.jpg,
sample-primary-source.jpg" | split: ','
%}

{% assign headers =
"Replace with a short slide title,
Replace with a short slide title,
Replace with a short slide title" | split: ','
%}

{% assign captions =
"Replace this caption. Explain what this slide shows and why it matters. Center for Southwest Research, collection name, box number.|
Replace this caption. Every slide needs one. Center for Southwest Research, collection name, box number.|
Replace this caption. Plain text only in carousels, so spell out the source instead of linking. Center for Southwest Research, collection name, box number." | split: '|'
%}

{% include images/carousel.html
  images=images
  headers=headers
  captions=captions
%}

Delete the carousel if you do not have a set of images that works this way. Three related photographs, a series of floor plans, or a run of newspaper clippings are all good candidates. Two images that need to be compared directly are usually better as a pair than as a carousel.

## Evidence

Use this section to show readers a document, not just a photograph. Scanned letters, meeting minutes, ledgers, clippings, and blueprints all reward close looking, and they prove you spent time in the boxes.

<!-- Portrait documents are the exception to the full-width rule. A tall scan at 100%
     is over 1200px tall and swallows the screen, so center it and leave it near 55%.
     Keep it centered, not floated. -->

{% include images/figure.html
  class="img-center"
  width="55%"
  caption="Replace this caption. Tell readers what to notice in the document and why it changes how they should understand your topic. Cite the collection, box, and folder."
  image-path="sample-primary-source.jpg"
%}

Explain what the document says, what it does not say, and how it fits the story. A source you actually read and explain is worth more than three you only mention.

## Why This History Matters

End by returning to the present. How should readers see this campus place, person, organization, object, or event differently after reading your essay? Point to continued use, memory, loss, gaps in the archive, or campus change rather than announcing a conclusion.

{% capture bibliography %}
- Replace this with your first source. Include enough detail that someone else could find it: collection name, box, and folder for archival material.
- Replace this with your second source.
- Replace this with your third source.
{% endcapture %}

{% include typography/bibliography.html
  title="Bibliography"
  content=bibliography
%}
