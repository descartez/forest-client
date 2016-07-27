#Design and Intention Doc

##Goal
Front-end client which interacts with Forest API.

##API handling
Since the API is HATEOS, all relevant links for direction and entities are immediately consumable by the client. Directions will be stored in their own variables which are handled by an input module which will hand the next link to call to the API handler. Entities will be handled separately.

##Appearance
Terminal like appearance with some graphics.
Should have:

  - Terminal which user can input commands
  - Buttons with basic commands
    - makes it more mobile accessible
    - makes it more accessible in general
  - ASCII graphics
    - handled by front end entirely
  - "chat" log
    - logs previous actions
      - refreshes on user move to new area?
