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
# {{< translate stats >}}
- **{{< translate way_of_travelling >}}**
- **{{< translate starting_date >}}** {{< article_date >}} 
- **{{< translate duration >}}** 
- **{{< translate distance >}}**
- **{{< translate budget >}}**
# {{< translate in_details >}}
## {{< translate road_condition >}} | {{< score 1 >}}
Some comment about the road state
## {{< translate accommodations >}} | {{< score 1 >}}
Some comment about the accommodation
## {{< translate freedom_camping >}} | {{< score 1 >}}
Some comment about the freedom camping
## {{< translate facilities >}} | {{< score 1 >}}
Some comment about the facilities
## {{< translate communication_with_the_locals >}} | {{< score 1 >}}
Some comment about communication with the locals
## {{< translate food >}} | {{< score 1 >}}
#### {{< translate vegetarian_friendly >}} {{< score 1 >}}
### {{< translate what_we_eat >}} 
Some comment about the food

{{< figure src="https://media.githubusercontent.com/media/fabandmina/piskel-projects/main/fabandmina/render/fabandmina_food.png" alt="food" height="32" width="32" >}} 

#### ⭐ {{< translate fab_favourite >}}
Peanuts
#### ⭐ {{< translate mina_favourite >}}
Fromage blanc

## {{< translate overall_feel >}} | {{< score 1 >}}
## {{< translate overall_feel >}} | {{< score 1 >}}
| {{< translate what_we_appreciate >}} | {{< translate what_we_dislike >}} |
|-------|-------|
|   item 1    |   item 1    |
|   item 2    |   item 2    |
|   item 3    |   item 3    |
|   item 4    |   item 4    |
|   item 5    |   item 5    |

# {{< translate top_5_locations >}}
|             |             |
|-------------|-------------|
|   location 1    |   reason    |
|   location 2    |   reason    |
|   location 3    |   reason    |
|   location 4    |   reason    |
|   location 5    |   reason    |

# {{< translate travel_story >}}
Some story

<!-- How to add a picture with size

{{< figure src="https://media.githubusercontent.com/media/fabandmina/piskel-projects/main/fabandmina/render/fabandmina_food.png" alt="food" height="32" width="32" >}} 

-->