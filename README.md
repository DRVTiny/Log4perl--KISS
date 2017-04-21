# Log4perl--KISS
Simple logging functions using Log::Log4perl - simplest than EASY!

= Why?
* Performance: Using code block as a first argument garantie that your output string will be computed only if target log level is enabled
* Clean syntax: `debug {'Now i want to say "Good bye" for the summer'}` and `debug_ 'You were just a prototype'` - looks clear and obvious
* Lightweight and fast by design: this is Log::Log4perl wrapper only, not yet-another-logging framework. 89 lines of code that help you work with the best perl logging framework in a comfort manner.
* Absolute minimum of initialisation: `use Log4perl::KISS` is enough to output clever-formatted messages. No bull shit! Write faster code faster, that can log more.   