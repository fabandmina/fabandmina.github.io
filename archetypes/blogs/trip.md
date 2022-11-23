---
title: "{{ replace .Name "-" " " | title }}"
subtitle: "A Subtitle"
introduction: "A short paragraph of text, shown as the first paragraph of the article, and on list pages."
date: {{ .Date }}
thumbnail:
tags: trip
flickr_album:
map: 
---
{{< collapsible "travel_story" 2 >}}
Some story
{{< /collapsible >}}

{{< collapsible "overall_feel" 2 5 >}}
<h3>{{< translate what_we_appreciate >}}</h3>

- item 1
- item 2
- item 3
  
<h3>{{< translate what_we_dislike >}}</h3>

- item 1
- item 2
- item 3

{{< /collapsible >}}

{{< collapsible "in_details" 2 >}}

<h3>{{< translate stats >}}</h3>

<li><b>{{< translate way_of_travelling >}}</b> Vélos, autostop, randonnée</li>
<li><b>{{< translate starting_date >}} </b>{{< article_date >}}</li> 
<li><b>{{< translate duration >}}</b> 28 jours</li>
<li><b>{{< translate distance >}}</b> 1000 km</li>
<li><b>{{< translate budget >}}</b> 1000 €</li>

{{< collapsible "crossing_the_border" 3 5 >}}

Some comment about crossing the border
<h4>{{< translate fab >}} 🇫🇷</h4>
<h4>{{< translate Mina >}} 🇯🇵</h4>

{{< /collapsible >}}

{{< collapsible "road_condition" 3 5 >}}
Some comment about the road state
{{< /collapsible >}}

{{< collapsible "accommodations" 3 4 >}}
Some comment about the accommodation
{{< /collapsible >}}

{{< collapsible "freedom_camping" 3 4 >}}
Some comment about the freedom camping
{{< /collapsible >}}

{{< collapsible "facilities" 3 5 >}}
Some comment about the facilities
{{< /collapsible >}}

{{< collapsible "communication_with_the_locals" 3 4 >}}
Some comment about communication with the locals
{{< /collapsible >}}

{{< collapsible "food" 3 5 >}}
<h4>{{< translate vegetarian_friendly >}} {{< score 4 >}}</h4>

<h4>{{< translate what_we_eat >}}</h4> 
Some comment about the food

<h4>⭐{{< translate fab_favourite >}}</h4>
Peanuts
<h4>⭐{{< translate mina_favourite >}}</h4>
Fromage blanc

{{< /collapsible >}}
{{< /collapsible >}}

### {{< translate top_5_locations >}}
|             |             |
|-------------|-------------|
|   location 1    |   reason    |
|   location 2    |   reason    |
|   location 3    |   reason    |
|   location 4    |   reason    |
|   location 5    |   reason    |

