# BackendBible

- Connection resources should persist accross requests. Stop re-initialisiing a database connection every time you receive a request.
  - This extends to Threadpools where ContextVariables are involved
