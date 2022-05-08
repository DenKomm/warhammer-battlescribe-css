# Warhammer CSS for Battlescribe

This CSS adds Warhammer flavour to Battlescribe's HTML output for your Warhammer 40,000 and Kill Team rosters. It’s designed to be more practical for referencing during games and features a print-friendly mode.

Kill Team sheets look like this:

![](pics/kt_screen.png)

40,000 sheets look like this:

![](pics/40k_screen.png)

When printed, sheets are set into two columns, which works well for most Kill Team rosters but not so well for 40K because units feature more information. Printed Kill Team sheets look like this:

![](pics/kt_print.jpg)

## How to use

1. Grab the replacement CSS for the roster type you want:
    - [Kill Team](killteam-battlescribe.css)
    - [40,000](40k-battlescribe.css)
2. Use Battlescribe to generate an HTML file and open in a text editor
3. Copy the CSS you wish to use into the same folder as your html file.
4. Paste the following into the HTML file, replacing everything between and *including* the `<style>` and `</style>` tags:
For 40k copy:
     `<link rel="stylesheet" href="40k-battlescribe.css">`
     
For KillTeam copy:
     `<link rel="stylesheet" href="killteam-battlescribe.css">`

5. Save the HTML and open it in a web browser
6. To print, please use Chrome or Firefox (Safari won't print with the print viewm for some reason). Ensure that the Background Graphics option is checked in the print dialog

OR! For Kill Team you can use a web interface built by [/u/czi](https://www.reddit.com/u/czi). Just visit [http://killteam.lovegronvall.se:81](http://killteam.lovegronvall.se:81) and upload your Battlescribe HTML output. Just to note that since it's not made by me, I can't guarantee if/when it incorporates updates I make to the CSS.

## Notes

- I'm neither a designer nor a web developer, so I'm making no claims for my CSS skills. The 40K CSS is relatively untested, so I welcome feedback to improve it.
- The CSS displays your roster in two ways. On your screen it should appear as a single column and be fairly clear to reference on a tablet during a game. Print it out and it switches to a two-column view with smaller text.
- There are page break rules to prevent entries from splitting over columns and pages. I optimised it for keeping specialists, leaders/commanders/fire teams on single pages. The first page will be almost empty, and models with long lists of rules might break over pages and generally look terrible, but I've done what I can to make it practical.


Please feel free to use as-is and, of course, adapt/amend to your heart's content. Share any improvements with the community; I'll do my best to add any changes I feel improve the stylesheet. Hope it's useful!
