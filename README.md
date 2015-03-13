# Angular Server Routing

This repo will contain my notes on using the new Angular router to render on the server as well
as some sample code as I start getting something prototyped.

## References

* [Router documentation](http://angular.github.io/router/)
* [A 10 minute primary to the new Angular Router]( )

## Notes

* If we use the Angular router, we would not do anything with the server framework routing.
    * Essentially, for the server routing would be * to one handler which would be our Angular rendering engine
    * The Angular router works within the view rendering step just like a directive
* We can use LifeCycle hooks for data retrieval (i.e. async operations)
* How would we share components across projects? Need to play with [$componentLoaderProvider](http://angular.github.io/router/$componentLoaderProvider)
* Treat routing just like any other directive
* Are there any downsides to figuring out routes at runtime?
    * Can't dynamically generate Google Sitemap (well, not as easily)
    * ??
