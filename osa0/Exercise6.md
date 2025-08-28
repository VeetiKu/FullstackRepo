```mermaid
sequenceDiagram
    participant browser
    participant server

    note right of browser: User types the note and presses the save button

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server
    note right of browser: Server recives the note in json format
    server->>browser: 201 Created   

```
