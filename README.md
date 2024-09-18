# Custom HTML Snippets Extension

This Visual Studio Code extension provides a collection of custom HTML snippets to streamline your web development workflow. These snippets cover various basic HTML structures and commonly used elements.

## Installation Process

copy this code: `npm install -g vsce` open your terminal inside the source code and paste it and this code `vsce package` in a same way
`vsce package --baseContentUrl . --baseImagesUrl '/images'`

published to vsix for installation
`vsce package --baseContentUrl  --baseImagesUrl /images`

## Publish Your Extension

`vsce publish -p <your_personal_access_token>`
and
`export VSCE_PAT=<your_personal_access_token>`
`vsce publish`

## Snippets List

### Basic HTML Structure

![Basic HTML Structure](/images/basic-html-structure.png)

This snippet provides a basic HTML structure with meta tags, CSS styles, and placeholders for your content. With Darkmode Enable

**Shortcode:** `!SA-HTML-A-AScafold`

### Table with Both Side 20px Space

![Table with Both Side 20px Space](/images/table-both-side-space.png)

This snippet generates a basic HTML table with 20px space on both sides.

**Shortcode:** `!SA-HTML-A-Table-Space-Both-Side-20px`

### Header 3 Part 4 Link with Logo

![Header with 3 Part 4 Link and Logo](/images/header-3part-4link-logo.png)

Creates a header with three parts including four links and a logo.

**Shortcode:** `!SA-HTML-A-Header-3Part-4Link-With-Logo`

### Header Logo Only in Center

![Header with Logo Only in Center](/images/header-logo-center.png)

Generates a header with a logo centered.

**Shortcode:** `!SA-HTML-A-Header-Only-Logo-in-Center`

### Fluid Hero Image

![Fluid Hero Image](/images/fluid-hero-image.png)

Inserts a fluid hero image placeholder.

**Shortcode:** `!SA-HTML-A-Fluid-Hero-Image`

### Spacer Height 30px

![Spacer Height 30px](/images/spacer-height-30px.png)

Adds a spacer with a height of 30px.

**Shortcode:** `!SA-HTML-B-Spacer-h-30px`

### @ Symbol UTF8 and Sup

![@ Symbol UTF8 and Sup](/images/at-symbol-sup.png)

Inserts the @ symbol with UTF8 and Superscript.

**Shortcode:** `!SA-HTML-C-@-symbol-UTF8-sup`

### Outlook Hack Code !mso

![Outlook Hack Code !mso](/images/outlook-hack-code.png)

Provides a snippet for Outlook hack code.

**Shortcode:** `!SA-HTML-H-Outlook-Hack-Code_!mso`

### 3 Blue Link Inline

![3 Blue Link Inline](/images/3-blue-link-inline.png)

**Shortcode:** `!SA-HTML-F-3-Blue-Link-Inline`

### 3 Line Lorem Ipsum Dummy Copy

![3 Line Lorem Ipsum Dummy Copy](/images/3-line-lorem-ipsum.png)

Generates three lines of Lorem Ipsum dummy text.

**Shortcode:** `!SA-HTML-F-3-Line-Lorem-Ipsum-Dummy-Copy`

### Copyright

Adds a copyright statement.

**Shortcode:** `!SA-HTML-F-Copyright`

@ Copyright 20..

![Template Can Make Like this](/images/template-can-made-like-this.png)

## Using this extension easily with in 1 or 2 min you can create like this template fully responsive with 90 Mejor email client compitable with darkmode support.

## Installation

1. Launch Visual Studio Code
2. Go to Extensions view by clicking on the square icon in the sidebar
3. Search for "Custom HTML Snippets" extension
4. Click on Install to install it
5. Reload Visual Studio Code

## Usage

1. Open an HTML file
2. Type any of the snippet prefixes to trigger the snippet
3. Press `Enter` to insert the snippet
4. Customize the placeholder content as needed

## Issues

If you encounter any issues or have suggestions for improvement, please feel free to [create an issue](https://github.com/your-username/your-repo-name/issues) on the GitHub repository.

## License

This extension is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

For more information, see the [LICENSE](/LICENSE) file.
