wp-fountain
===========

## WP Fountain ##

- <a href="http://parliamentpress.com/wp-fountain.zip">Download WP Fountain</a>
- <a href="http://parliamentpress.com/wp-fountain/">WP Fountain</a> is a Wordpress Plugin to support <a href="http://fountain.io">Fountain markup</a> (aka <a href="http://prolost.com/storage/downloads/spmd/SPMD_proposal.html">SPMD</a>) for screenplays.  
- Contributors: <a href="http://jeffmcneill.com/">jeffmcneill</a>, nyousefi  
- Tags: screenwriting, scrippets, scrippet, screenplay, film scripts, movie scripts, fountain  
- Requires at least: 1.5  
- Tested up to: 3.6  
- Stable tag: 0.0.1  

This plugin modifies screenplay format text for inclusion in web pages. Based on the <a href="http://johnaugust.com/archives/2008/scrippets-are-go">scrippet concept and original code</a> by <a href="http://johnaugust.com">John August</a> and <a href="http://equinox-of-insanity.com">Nima Yousefi</a>.

[flickr]6671819829[/flickr]
<!--more-->

## Description of WP Fountain

The Scrippet format is a text format designed by John August to allow writers to input screenplay text in easy-to-write plain text and have it converted to properly styled HTML. This plugin will automatically convert plain text Scrippet to HTML, and add John August's Scrippets CSS file into your blog. For more information on Scrippets please see <http://parliamentpress.com/wp-fountain/>

## Installation of WP Fountain

1. Download scrippets.zip.
2. Unzip the archive.
3. Upload the entire "wp-scrippets" folder into your "wp-content/plugins" directory.
4. Activate the plugin through the Admin plugins panel.
5. Enjoy!

## Usage of WP Fountain

To include a Scrippet of Fountain in your WordPress blog simply include text in the following format:

> [ scrippet ]  
> INT. HOUSE - DAY  
>   
> MARY yells across the hall to FRANK.  
>   
> MARY  
> Anything you want to tell me?  
>   
> FRANK (O.S.)  
> I swear, honey, I don't know how mayonnaise got in the piano.  
>   
> CUT TO:  
>   
> FRANK  
>   
> running out of the bathroom.  
>   
> FRANK  
> (terrified)  
> There are bees in the toilet!  
> [ /scrippet ]

This renders as:

[scrippet]
INT. HOUSE - DAY

MARY yells across the hall to FRANK.

MARY
Anything you want to tell me?

FRANK (O.S.)
I swear, honey, I don't know how mayonnaise got in the piano.

CUT TO:

FRANK

running out of the bathroom.

FRANK
(terrified)
There are bees in the toliet!
[/scrippet]

Note: Scrippet text must be wrapped in **[ scrippet ][ /scrippet ]** blocks (without the spaces before and after the square brackets), and must have correct line spaces between screenplay elements.

You can make text bold or italic by in the following ways:

## Bold 

- Wrap the text in double asterisks `**bold**`.

## Italic

- Wrap the text in single asterisks `*italic*`.

Please note: text styling does not work for transitions. Sorry.

## Frequently Asked Questions

<br />

> MEEP! It's not formatting correctly. What do I do?

First, please make sure you are inputting the text in the right format. (Line spacing is important!)

However, if you're doing it right and it's still not looking right, please go to scrippets.org for troubleshooting help or to submit a bug report.

> The Scrippets are formatted correctly, but the style of the box doesn't fit in with my blog design. What can I do? 

The Scrippets settings panel in your WordPress administrator's page has several settings that you can change to better suit your blog's design.

However, if those options are insufficient, you can modify the scrippets.css file in *wp-scrippets* plugin folder. Be advised that updates to the Scrippets plugin will overwrite your changes, so you should back them up and remember to add them back in whenever the plugin gets updated.

## Release Notes 

**WP Fountain**

* 0.0.1 - Fork of WP Scrippets

**WP Scrippets**

- 1.5   - Fixed screenshot.
- 1.4   - Various bug fixes.
- 1.35  - Fixed bug resulting from having a character name end in *INT* (ie, VINCINT, QUINT).
- 1.3   - Compatibility fix for WordPress 2.8+
- 1.2   - Fixed *FOREST* bug, added version number to scrippetize.php
- 1.1   - Added support for bold, italic, and underlined text.
- 1.0.2 - Fixed bug in wp-scrippets.php that prevented CSS to be added properly for blogs with different WordPress and Blog addresses.
- 1.0.1 - Fixed scrippetize to work with bbPress.
- 1.0   - Release!
