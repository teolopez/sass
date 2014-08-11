#sass
====

A Sass startup/barebones package for web projects.

<p>Every project needs some organization. Throwing every new style you create onto the end of a single file would make finding things more difficult and would be very confusing for anybody else working on the project.</p>

###There are four types of categories:

1. Base
2. Layout
3. Module
4. Tools

### Categories Defined

**Base** rules are the defaults. They are almost exclusively single element selectors but it could include attribute selectors, pseudo-class selectors, child selectors or sibling selectors.

**Layout** rules divide the page into sections. Layouts hold one or more modules together.

**Modules** are the reusable, modular parts of our design. They are the callouts, the sidebar sections, the product lists and so on.

**Tools** are things such as functions, mixins, or any other helpers for when using foundation by zurb or bootstrap.