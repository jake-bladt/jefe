## JavaScript Entity Framework Extensions

The purpose of this project is to create a set of extensions for Entity Framework that allow front-end 
web developers to handle entities with the same ease as .net back-end developers.

### Architectural plan

JEFE is a developer tool that integrates smoothly with the existing Entity Framework workflows. As such,
it will be distributed as a NuGet package and a browser plug-in. It will generate code scaffolding using
the T4 engine and should require minimal inclusion of support libraries in your project outside of the
generated code.
