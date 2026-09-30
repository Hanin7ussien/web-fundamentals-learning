# Walking An Application

## Platform
TryHackMe

## Topic
Web Application Reconnaissance & Developer Tools

## What I Learned

### Content Discovery

- robots.txt can reveal interesting paths.
- Page Source can reveal hidden links and comments.
- JavaScript files may reveal useful information.
- Directory listing can expose files.

### Page Source

Things to look for:

- HTML comments
- Hidden links
- href attributes
- JavaScript files
- Framework information
- Directory paths

### Developer Tools

#### Inspector

Used to inspect the current DOM and CSS.

Changes made through Developer Tools are local to the browser
and disappear after refreshing the page.

#### Debugger

Used to inspect JavaScript execution.

Important concepts:

- Minified JavaScript
- Obfuscated JavaScript
- Pretty Print
- Breakpoints

#### Network

Used to inspect requests made by the browser.

Important things to check:

- HTTP method
- URL
- Status code
- Request headers
- Response
- Parameters
- AJAX requests

## Key Takeaways

- Manually explore the application before using automated tools.
- Check robots.txt.
- Review the page source.
- Inspect JavaScript files.
- Use Developer Tools to understand client-side behavior.
- Use Network to understand browser-server communication.
