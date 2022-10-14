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
## {{< translate travel_story >}}
Some story

## {{< translate overall_feel >}} flickr_album< score 1 >}}
### + {{< translate what_we_appreciate >}}
- item 1
- item 2
- item 3
### - {{< translate what_we_dislike >}}
- item 1
- item 2
- item 3
## {{< translate in_details >}}
### {{< translate stats >}}
- **{{< translate way_of_travelling >}}**
- **{{< translate starting_date >}}** {{< article_date >}} 
- **{{< translate duration >}}** 
- **{{< translate distance >}}**
- **{{< translate budget >}}**

### {{< translate crossing_the_border >}} flickr_album< score 1 >}}
Some comment about crossing the border
#### Fab 🇫🇷
#### Mina 🇯🇵
### {{< translate road_condition >}} flickr_album< score 1 >}}
Some comment about the road state
### {{< translate accommodations >}} flickr_album< score 1 >}}
Some comment about the accommodation
### {{< translate freedom_camping >}} flickr_album< score 1 >}}
Some comment about the freedom camping
### {{< translate facilities >}} flickr_album< score 1 >}}
Some comment about the facilities
### {{< translate communication_with_the_locals >}} flickr_album< score 1 >}}
Some comment about communication with the locals
### {{< translate food >}} flickr_album< score 1 >}}
#### {{< translate vegetarian_friendly >}} {{< score 1 >}}
#### {{< translate what_we_eat >}} 
Some comment about the food

#### ⭐ {{< translate fab_favourite >}}
Peanuts
#### ⭐ {{< translate mina_favourite >}}
Fromage blanc
### {{< translate top_5_locations >}}
|             |             |
|-------------|-------------|
|   location 1    |   reason    |
|   location 2    |   reason    |
|   location 3    |   reason    |
|   location 4    |   reason    |
|   location 5    |   reason    |

