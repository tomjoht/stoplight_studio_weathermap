---
tags: [Introduction]
---

# Sample article

this is an article.

## Some task

1.  first step

2.  second step

    some result

3.  list continues

4.  some options

    -   option 2

5.  list continues

| Column A | Column B | Column C |
| -------- | -------- | -------- |
| A1       | B1       | C1       |
| A2       | B2       | C2       |
| A3       | B3       | C3       |

## HTML table

<table>
   <colgroup>
      <col width="30%" />
      <col width="70%" />
   </colgroup>
   <thead>
      <tr>
         <th markdown="span">Field</th>
         <th markdown="span">Property</th>
      </tr>
   </thead>
   <tbody>
      <tr>
         <td markdown="span">acme</td>
         <td markdown="span">description ...</td>
      </tr>
      <tr>
         <td markdown="span">beta</td>
         <td markdown="span">description...</td>
      </tr>
   </tbody>
</table>

## Subheading

 Some code block:

```json
{
    "coord": {
        "lon": -121.95,
        "lat": 37.35
    },
    "weather": [
        {
            "id": 803,
            "main": "Clouds",
            "description": "broken clouds",
            "icon": "04n"
        }
    ],
    "base": "stations",
    "main": {
        "temp": 45.25,
        "feels_like": 41.16,
        "temp_min": 41,
        "temp_max": 50,
        "pressure": 1026,
        "humidity": 75
    },
    "visibility": 16093,
    "wind": {
        "speed": 2.57,
        "deg": 36
    },
    "clouds": {
        "all": 75
    },
    "dt": 1579415808,
    "sys": {
        "type": 1,
        "id": 5845,
        "country": "US",
        "sunrise": 1579360793,
        "sunset": 1579396557
    },
    "timezone": -28800,
    "id": 0,
    "name": "Santa Clara",
    "cod": 200
}
```
