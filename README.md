# google-map-refactored-draggable-marker
Refactored Google Map implementation with search box autocomplete. Map is in a Bootstrap modal and pops up when user navigates away from address text field. Markers can be moved by dragging or clicking another point in the map. 

The implementation is in Ruby on Rails. Feel free to extract what you need (esp. the Javascript portion).

###The flow is:

- User navigates away from address text field
- The modal pops up
- User enters a location to be searched
- User can click/drag marker
- User clicks Done button
- The city field gets updated
- The next field (Phone) is highlighted
