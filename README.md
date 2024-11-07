location_search app DEMO:

1. Landing page has center of map set to New York.  React useState hook manages application state for given search 'term' input.  React useEffect hook synchronized with search api and external nominatim.openstreetmap.org 'features' json object and stores results in data variable.  Mapping function extracts data's interface properties and stores in 'places' array.

https://github.com/user-attachments/assets/8d77ac48-326b-4f65-9155-c744ec673d59


2. React useRef hook initializes 'current' property allowing useEffect flyTo() method from one 'place' set of coordinates to the next in the array.

https://github.com/user-attachments/assets/c699fd5b-4263-47d3-a250-dbfcea5e5594



