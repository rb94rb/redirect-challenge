# redirect-challenge
ASP.NET Core solution with redirect component and API

Component that can be added to any ASP.NET core app to handle redirects.

Acceptance Criteria
   •    The component will get the redirects from a RESTful API, but for now create a mock service that returns the following JSON.
   •    The component must cache the results in memory, but allow multiple threads to read the cache.
   •    The cache must be updated every few minutes, without requiring any HTTP request to wait for the refresh.
   •    The cache duration must be configurable.
   •    Failed API calls are logged as errors
   •    Successful API calls and cache refreshes are logged as information.
   •    If useRelative is true, redirects target a relative destination instead of an exact destination. 
