## Level 3

We now want to suggest a place to meet for the two matched users based on their location.

Given the list of places in `places.json`, compute a new value for each match item in the match results list, like this:

```
{
  "matches": [
    {
      "user1_id": 164757,
      "user2_id": 277487,
      "place_suggestion": {
        "name": "L'Atelier des Artistes",
        "lat": 48.850397,
        "lon": 2.335467
      }
    },
    ...
}
```
