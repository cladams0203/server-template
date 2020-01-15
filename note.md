rest() 

constraints. 

## Design Process

- gather requirements
- list of resources (nouns) [song, user, pets]
- list of endpoints

## Endpoints

- avoid using verbs, it's not a URL, it's a URI.  (instead creat-song => /api/songs)
- actions are expressed with http methods.

Songs

- create
-find a song by (filters)
-update
-delete
-paginated list (filters)
-album art

|Action|Method|Endpoint|
|:--|:--:|:--|
|List songs|GET|/api/songs|
|Create a Song|POST|/api/songs|
|Update a Song|

hello