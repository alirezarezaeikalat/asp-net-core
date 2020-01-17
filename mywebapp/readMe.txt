1. the better name for ConfigureServices is
  addServices. (This function prep the environment)

2. In Configure function we use this services.
  (This function use the environment)

3. By putting app.UseMvc middleware in configure 
  function by default the routing system points
  to the pages folder and the name of the pages
  in the pages folder is the routes for get requests

4. to publish the project and make neccessary .dll files
  dotnet publish

5. Attention:
  we don't need to build the project for changes
  in razor pages