# Basic API Fetch with RxJS

### Objective
Learn how to use RxJS with Angular's HttpClient to fetch data from an API and display it. This task introduces Observable, HttpClient, and the subscription pattern, which are foundational for handling asynchronous data streams in Angular.

### Acceptance Criteria (AC)
- The component should fetch data from a public API (e.g., JSONPlaceholder or another REST API) upon initialization.
- The fetched data should be displayed in a list on the UI.
- The implementation should handle errors gracefully and display an error message when the API call fails.
  - If the API response is empty, the UI should display a "No data available" message.

URL to Get Data: https://jsonplaceholder.typicode.com/posts

_The component should use RxJS operators for transformation (e.g., map)._
