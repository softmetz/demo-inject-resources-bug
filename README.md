# inject-resources-mr-17 Project

The build fails with the error 

`FooClassTest » Reflections Scanner SubTypesScanner was not configured`

when the test class is annotated with `@TestWithResources` and version 0.3.1 of `inject-resources-junit-jupiter`.
Version 0.3.0 works.

I used a Quarkus quickstart as base as I encountered the problem during developing a new Quarkus service.
Strangely it still works in our existing very similar projects, and I was not able to find out what's the difference. 
