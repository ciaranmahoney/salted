# Salted for MailChimp

I liked the look of Salted so I added MailChimp tags so I could use this template in my campaigns... Most of the credit goes to the guys mentioned below.

Original template by [Jason Rodriguez](https://github.com/rodriguezcommaj/salted).

## Features 

### Four content types with repeatable components

* Full width section with a featured image on top.
* Full width section with a featured image below.
* Two column highlighted feature section.
* Section for articles.
* 

### Each text block is editable
Edit titles, buttons, links and images in each content type.

### Version with A/B testing tags
Always be testing, right?! So I created a version with the entire template duplicated and each copy wrapped in MailChimp's A/B testing tags. For more info about how MailChimp does A/B testing, [read here](http://kb.mailchimp.com/campaigns/ab-split/getting-started-with-a-b-split-campaigns).

### Version with RSS tags
These tags will bring in the title, an excerpt, an image (if it's setup) and provide a read more link to the post. It can be a little quirky, depending on how your RSS feed is setup. If you want to tweak it, read MailChimp's [RSS feeds](http://kb.mailchimp.com/merge-tags/rss-merge-tags) kb article.

## Setup 
1. Copy the code from the html file.
2. Create a new template in MailChimp - select the "Paste in Code" option. 
3. Delete all existing code and paste the copied html code in.
4. Click save.
5. Create beautiful, responsive emails in MailChimp!
6. If you want to use the A/B testing functionality, create and A/B split campaign and just create two version of your email. They will look like they are just one email in the editing screen, but they will be split when sent. You can send test emails of each version to ensure they work properly.

## Button editing is a little quirky

If you use MailChimp's WYSIWYG to edit the button text or url, be careful not to delete the styles. You're better off using the "source" editor when you want to change the button's text and destination url.

## Screenshots

*Apple Mail*

![Apple Mail](https://github.com/ciaranmahoney/salted/blob/master/screenshots/apple-mail1.PNG "apple mail")

![Apple Mail](https://github.com/ciaranmahoney/salted/blob/master/screenshots/apple-mail3.PNG "apple mail")

![Apple Mail](https://github.com/ciaranmahoney/salted/blob/master/screenshots/apple-mail4.PNG "apple mail")

*Gmail Desktop*

![Gmail Desktop](https://github.com/ciaranmahoney/salted/blob/master/screenshots/gmail-desktop1.png "Gmail desktop")

![Gmail Desktop](https://github.com/ciaranmahoney/salted/blob/master/screenshots/gmail-desktop2.png "Gmail desktop")

![Gmail Desktop](https://github.com/ciaranmahoney/salted/blob/master/screenshots/gmail-desktop3.png "Gmail desktop")

*Gmail iOS*

![Gmail iOS](https://github.com/ciaranmahoney/salted/blob/master/screenshots/gmail-ios1.PNG "Gmail iOS")

![Gmail iOS](https://github.com/ciaranmahoney/salted/blob/master/screenshots/gmail-ios2.PNG "Gmail iOS")

![Gmail iOS](https://github.com/ciaranmahoney/salted/blob/master/screenshots/gmail-ios3.PNG "Gmail iOS")

---
**Original Readme for Salted below.**

## A responsive email template

Creating HTML email that renders well across most clients is surprisingly hard, especially when you want it to be responsive. Salted is a responsive email template that tries to make things easier.

Based on code originally developed by [Kevin Mandeville](http://twitter.com/KEVINgotbounce) and used in the [Litmus](http://litmus.com) email newsletters, Salted provides a base on which to build responsive HTML emails.

*Disclosure: I’m lucky enough to work for Litmus, one of the smartest groups of people around. Our emails typically take an opinionated approach to design and code, and the Salted template reflects that. Adapt as necessary!*

A lot of web designers are surprised by some of the stuff going on in HTML email, so here’s a breakdown of what you’ll find in the Salted template.

### Stacked Tables

At [Litmus](http://litmus.com), we love modularity. Being able to easily swap out pieces of our emails and work on sections in isolation is very important. Therefore, we tend not to nest tables too deep. Each horizontal section of the Salted template is its own table. You will find modules for a main hero section,  a single-column copy section, a two-column grid section, and an article listing section, as well as both a header and footer.

Feel free to swap them out and adjust for your own purposes.

### Robust Images

Unfortunately, a lot of email clients block images by default. The images in the stacked tables are examples of how to properly code images for email—they include specific dimensions, ALT text, and styles for keeping your ALT text looking nice when images are disabled.

*Note: The images in the Salted template use relative paths, which will not work in real campaigns. Update your image paths to be absolute and point to a publicly accessible server to ensure that your subscribers get to look at all of your pretty graphics.*

### Bulletproof Buttons

Using images for buttons is so last season. To ensure that your calls-to-action display even when images are disabled, we use our own breed of bulletproof buttons throughout.

The buttons rely on thick borders for their structure, and some CSS3 for round corners. Using borders instead of padding on the table cell (our old approach) keeps the entire button tappable, not just the text inside. You can easily style the buttons using the inline styles, and adjust on mobile by targeting the *mobile-button* class.

### Responsive Goodness

The Salted template is fully responsive (so much as an HTML email can be). It uses fluid tables, fluid images, and media queries to adjust content and layout on mobile devices that support it.

*Be warned: If you thought the browser wars were bad, just wait until you start dealing with email clients. There are dozens of popular email clients that all support HTML and CSS to varying degrees. While the Salted template is very robust, it won’t look perfect in every client. That’s just the nature of the game.*

The *head* section of the email has a style block with all that good stuff going on. There are some client-specific resets (re: hacks) in there, as well as a general media query targeting screens below 525px. As always, test out your content and allow that to determine your breakpoints. This is just what works for us at [Litmus](http://litmus.com).

### Test Everything

While this code has been tested thoroughly through countless Litmus newsletter sends, when adapting it for your own purposes, I recommend you test the hell out of your campaigns. As mentioned before, email clients are a finicky bunch and you’re likely to run into issues at some point.

Naturally, I suggest sending your campaigns through [Litmus](http://litmus.com) for testing on dozens of different clients. It’s always a good idea to test on as many real devices as possible, too.

Enjoy!

