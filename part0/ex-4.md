```mermaid
sequenceDiagram
  participent browser
  participent server

  browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note with form data note={input}
  activate server
  server-->>browser: Redirect to /notes page
  deactivate server
```
