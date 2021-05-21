---
title: Microcosms in OSM
tags: Templates, Talk
description: View the slide with "Slide Mode".
---

## Microcosms in OSM

Brian DeRocher
Mapping USA
May 21^st^, 2021


---

## Who am I?

- Software Developer
- Volunteer mapper with MappingDC :heart: 

---

## MappingDC

> Our mission is to improve the quality of OpenStreetMap in the Washington DC urban area. 

---

![](https://i.imgur.com/YX0L0wJ.png)

$200 per year

---

| Advantages | Disadvantages |
| --- | --- |
| publicity, membership | didn't expect to do work, few returning participants |

---

!["These are not the mappers you are looking for."](https://i.imgur.com/jJOGvKV.png)

---

![](https://i.imgur.com/8RyFQ9O.png)


---

The mappers are already mapping.

(Meetup is still good for finding new mappers.)

---

```vega
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple bar chart with embedded data.",
  "data": {
    "values": [
      {"type": "Meetup", "returns": 5}, {"type": "mapper", "returns": 19}
    ]
  },
  "mark": "bar",
  "encoding": {
    "x": {"field": "type", "type": "nominal", "axis": {"labelAngle": 45}},
    "y": {"field": "returns", "type": "quantitative"}
  }
}
```

---

![](https://i.imgur.com/Ife7Gmc.png)

---

## Next Steps

- [x] DONE Write the PR
- [x] DONE Stop adding features for now
- [x] DONE 100% test coverage on all new features
- [x] DONE Spam prevention
- [ ] Rewrite the PR into 4 PRs

* 6 resources
* 10 migrations
* 200 commits

---

### Thank you! :cake: 

You can find me on

- GitHub
- Twitter
- or email me

---

Brian DeRocher

Tomorrow at 1pm Workshopt to get your microcosm into OSM or to try it out.

