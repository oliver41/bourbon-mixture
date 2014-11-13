
***  Bourbon Neat and Bitter for Mixture  *** 

A simple, lightweight and semantic sass framework build for speed


Version (Date 13.Nov 2015):
---------------------------

Bourbon v. 4.0.2 / Neat v. 1.7.0 / Bitter v. 0.10.1



BOURBON - A simple and lightweight mixin library for Sass
----------------------------------------------------------

Bourbon is a library of pure Sass mixins that are designed to be simple and easy to use. No configuration required. The mixins aim to be as vanilla as possible, meaning they should be as close to the original CSS syntax as possible.

The mixins contain vendor specific prefixes for all CSS3 properties for support amongst modern browsers. The prefixes also ensure graceful degradation for older browsers that support only CSS3 prefixed properties. Bourbon uses SCSS syntax.



NEAT - A lightweight semantic grid framework for Sass and Bourbon
------------------------------------------------------------------

Neat is a semantic grid framework built on top of Sass and Bourbon. It is simple enough to get you up and running in minutes, and powerful enough to handle any responsive layout you can dream of.

Neat is build with the aim of promoting clean and semantic markup; it relies entirely on Sass mixins and does not pollute your HTML with presentation classes and extra wrapping div's.

It also aims to stay as lightweight as possible; just enough to handle the most common grid uses in modern Web design.



BITTERS - Scaffold styles, variables and structure
---------------------------------------------------
### Built for speed
Bitters helps designers start projects faster by defining a basic set of Sass variables, default element style and project structure.

### Made to change
After you have Bitters installed, jump in and start customizing the styles and variables to your design and brand requirements.

Sass Structure

The Bitters folder should contain styles for all the basic elements used throughout the site’s style. Add code to the existing files or add new files to the folders. Customize Bitters for your site as you see fit.
Variables

This houses all variables that are used, or will be used, in more than one file in your site. Variable names in Bitters that are used outside of the variables file start with $base to indicate that they are the most basic variables.
Grid Settings

Variables specifically created for Neat resets and breakpoints. To be used, these need to be imported separately from the rest of your base file above Neat in your main stylesheet. Otherwise just remove the file.
Typography

All type is based on $base-font-size which is set to 1em (16px) by default. The spacing around type is based on $base-line-height to keep a semi-baseline grid. All sizes are scaled up or down by a factor of 0.25.
Lists

All lists have stripped out styles. No bullets, no left padding. To add back the expected browser default styles add @extend %default-ul; or @extend %default-ol; to the <ul> or <ol> respectively.
Forms

Adds basic styles all form elements. Form-specific variables make it really easy to be overridden.


http://bourbon.io


Bourbon is maintained and funded by Thoughtbot, inc.

This boilerplate for mixture is from:
oliverp
