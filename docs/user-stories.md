# Lab 04 - User Stories and Acceptance Criteria

## User Story Format

As a [user role], I want to [goal/action], so that [benefit/value].

## User Stories

| Story ID | Role          | User Story                                                                                                         | Related Requirement | Priority | Acceptance Criteria                                                                                                                           | Demo Evidence                        |
| -------- | ------------- | ------------------------------------------------------------------------------------------------------------------ | ------------------- | -------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------ |
| US-01    | Movie Viewer  | As a movie viewer, I want to chat with the AI assistant, so that I can receive personalized movie recommendations. | FR-02, FR-03        | Must     | Given the user enters a movie preference, when the AI chatbot processes the request, then the system displays relevant movie recommendations. | Screenshot of chatbot recommendation |
| US-02    | Movie Viewer  | As a movie viewer, I want to search for movies by title, so that I can quickly find movies I am interested in.     | FR-04               | Must     | Given a movie title is entered, when the search button is clicked, then matching movies are displayed.                                        | Screenshot of search results         |
| US-03    | Movie Viewer  | As a movie viewer, I want to view movie details, so that I can decide whether to watch the movie.                  | FR-06               | Must     | Given a movie is selected, when the user opens the movie page, then the system displays synopsis, rating, genre, and release date.            | Screenshot of movie detail page      |
| US-04    | Movie Viewer  | As a movie viewer, I want to browse trending movies, so that I can discover popular content.                       | FR-05               | Should   | Given the homepage loads successfully, when the user scrolls to the trending section, then trending movies are displayed.                     | Homepage screenshot                  |
| US-05    | Movie Viewer  | As a movie viewer, I want to save movies to my watchlist, so that I can watch them later.                          | FR-09               | Should   | Given a movie is selected, when the Save button is clicked, then the movie is added to the watchlist.                                         | Screenshot of watchlist              |
| US-06    | Administrator | As an administrator, I want to view users' chatbot conversation history, so that I can understand user preferences and improve recommendation quality. | FR-11               | Must     | Given users have interacted with the chatbot, when the administrator opens the chat history page, then all previous conversations are displayed.            | Screenshot of chat history page |
| US-07    | Administrator | As an administrator, I want to view chatbot usage statistics, so that I can monitor system activity and popular movie requests.                        | FR-12               | Could    | Given chatbot interactions exist, when the administrator opens the dashboard, then summary statistics such as total chats and popular genres are displayed. | Dashboard screenshot            |

## Acceptance Criteria Checklist

A good acceptance criterion should be:

* Testable
* Observable in the final prototype
* Connected to a requirement
* Connected to user evidence
* Not too vague

## Rejected / Future User Stories

| Story ID | Reason for Postponing                                                         | Future Condition                                             |
| -------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| FUT-01   | User account registration and login are outside the MVP scope.                | Implement after the core recommendation system is completed. |
| FUT-02   | Social sharing of recommendations is not essential for the first prototype.   | Add after user engagement features are developed.            |
| FUT-03   | AI recommendation history analytics requires additional storage and tracking. | Implement in Version 2.0.                                    |

