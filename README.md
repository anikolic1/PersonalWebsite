# PersonalWebsite
Responsive personal website for professional use. Created to showcase
myself to others, so that they can know more about me and the work I do.

## Content
The website contains a Home page, which directs the user to all other pages.
It also has an "about me" which describes some information about myself, 
and "my projects" which is a gallery of some of my projects. It also includes
a "contact me" page which describes the best ways to get in touch with me.

Additionally, the home page contains links to my relevant social media such as
my Github, Linkedin, and professional Twitter.

## Implementation

### How it's made
I used HTML to display all my content and CSS to make it look pretty.
In this current build, I used SCSS as a precompiler to generate
compact CSS code. Even though this tool generates pretty clean CSS,
sometimes there is extraneous code that can still be cleaned up by hand.
So I went through the generated CSS afterwards to clean what I could.

### Tools
I used Node.js to install and run the SCSS precompiler. I wrote a small npm script
that watches my SCSS files and precompiles them as I write. I also installed the
VS Code Live Server extension to watch my site change as I'm writing the code.
Other than that I used git for version control and VSCode as a file editor.

I chose not to include the SCSS files in the repository because they don't really show anything
that the cleaned up CSS doesn't already show. There's no real need to have them
when the CSS is available.

## Planned Features
I plan on adding ways for visitors to comment on my projects and describe what they think.
I also plan on adding a blog page that I would update once in a while to talk about
my work or what I'm interested in, in terms of technology and programming.
