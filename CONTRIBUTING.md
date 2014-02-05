# Contributing

Thank you for contributing to code-of-conduct-diffinator! 


## Guidelines

### Short Version

* Include all front matter fields. Leaving a front matter attribute empty is fine

* Paste the whole content, including license and attribution.

* Zero formatting, markup, or linking. Good ol' plain text.

The [conference-example-2014.md](conference-example-2014.md) file provides a nice example

### Long Version

A 'Save As' of the example file should work out nicely in most cases. In circumstances where unclear, here's the detailed guidelines:



To make the project maximum diff-friendly, request that you contribute in the following format. 

Save As is nicely easy. But for the sake of clarity, here's the details: 


#### File Name

Please name file in format:

    [conference or organization name, hyphen-delimited]-[applicable year if available]-[long|medium|short if there more than one applicable].md

All character in lower case. Use hyphens for spaces.
    
##### Examples

    rubyconf-2013-long.md
    plone-foundation-2012.md

#### Front Matter

##### Example

    ---
    layout: coc
    conference: [name & year] OR organization [name & year]
    date announced: [mmm dd, yyyy]
    date archived: [mmm dd, yyyy]
    url: [url of policy archived below]
    credited parents: [any that are explicitly credited in the CoC]

    ---

Please include all front matter fields. It's fine if they're empty.

**Note**: The leading triple-hyphen must be the file's first line. The front matter's trailing newline-triple-hyphen-newline combination must terminate the section.

If the code of conduct is maintained by the conf/org in a public repository, please add the optional front matter field "forkable file":

    forkable file: https://github.com/stumpsyn/policies/blob/master/citizen_code_of_conduct.md

**Note**: please use the URL of the code of conduct file itself, rather than to the repository generically.

##### Content

  * Include the text of code of conduct, including title. 

  * Paste as unformatted/marked-up

  * Remove any forced line breaks _within_ text, such as within paragraphs
  
  * Add newline _between_ text, such as between titles or paragraphs
