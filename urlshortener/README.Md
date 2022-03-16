## URL Shortener

The goal of this exercise is to create an http.Handler that will look at the path of any incoming web request and determine if it should redirect the user to a new page, much like URL shortener would.

For instance, if we have a redirect setup for /dogs to https://www.somesite.com/a-story-about-dogs we would look for any incoming web requests with the path /dogs and redirect them.

I implement the stubbed out methods in handler.go which has a good bit of comments explaining what each method should do, and there is also a main/main.go source file that uses the package to help you test your code and get an idea of what your program should be doing.
