# Microframeworks are actually pretty simple #
All you need is:

1. URL routing
2. Static file serving
3. <strike> templating? </strike>

# Use the dominant paradigm #
`http` expects `function(req, resp){}`, it's difficult to make something that
supports its breadth of use cases without imitating the syntax.

# There wasn't really all that much to be done! #

Basically I wrote my own url router, and imported `node-static`. 

