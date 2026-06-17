# Error Handling Strategy

## Project

Live Data Dashboard

## API Used

Fake Store API

## Loading State

When the application sends a request to the API, loading skeletons are displayed. This provides visual feedback to users and prevents a blank screen while data is being fetched.

## Success State

If the API request is successful, the dashboard displays product statistics and product cards using the received data.

## Empty State

If the API returns an empty array or no products are available, a user-friendly "No Products Found" message is displayed along with a reload option.

## Error State

If the API request fails due to network issues, server problems, or unexpected responses, an error message is shown to the user explaining that data could not be loaded.

## Retry Logic

A Retry/Refresh button allows users to fetch data again without reloading the entire application.

## User Experience Considerations

* Clear loading indicators improve usability.
* Friendly error messages prevent confusion.
* Empty states inform users when no data exists.
* Retry functionality enables quick recovery from temporary issues.

## Conclusion

The application implements robust API handling by managing loading, success, empty, and error states, ensuring a smooth and reliable user experience.
