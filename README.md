SEW | CORE | Simple CRUD Operations

## User Story 1
*As a song provider I want to upload new songs, so that everyone can enjoy my music.*

### Acceptance Criteria
- A button to create new songs is available.
- An editor for entering data is available.
- When clicking the button, the user is taken to a new state showing the editor.
- A success message is displayed aber creating a new song successfully.

## User Story 2
*As a musician I want to edit my songs, so that I can keep them up to date and upload new versions of my songs.*

### Acceptance Criteria
- There is an edit button in each line of the song list.
- Clicking the edit button changes the state to the editor.
- In the edit state the editor is prefilled with the current data of the song.
- When pressing the save button, the data is stored to the server.

## User Story 3
*As a song provider I want to delete old songs, so that listens can only listen to my best music*

### Acceptance Criteria
- There is an delete button in each line of the song list.
- Clicking the delete button sends a delete request to the server.
