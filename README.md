# WCAG-Testing-of-a-Website
Tested CVS Investors' website for WCAG Compliance and I am sharing a sample of what I can do.

Testing Website: CVS Health - Investors: https://investors.cvshealth.com/investors/default.aspx#maincontent

# Types of Disabilities:

1. Permanent: like deaf/blind
2. Temporary: broken arm
3. Conditional/Situational: slow internet connection

 
# Why Accessibility is Important

It is important that the Web be accessible to everyone in order to provide equal access and equal opportunity to people with disabilities. An accessible Web can help people with disabilities participate more actively in society.

* Improves maintainability and efficiency

* Increase market share and audience reach

* Aids usability

* Easy and efficient access to users with impairment and challenges

* Assists in access for low-bandwidth users

* Better and more maintainable code

* Good SEO (Search Engine Optimization)

* Maintains customer loyalty and brand value


# Things to keep in mind while designing a web page or an application:

1. Use Alt-tag:
  - Use <alt= “alternative text for images”>
  - Alt-text as “a woman” is not helpful, rather be descriptive
  
2. Closed Media Caption
  - Include transcript for podcasts/video/audio, not only helpful for disabled but also for those who can’t listen to audio or video bcz they are in office or a quiet place
  - Also helps in SEO for indexing if you have text transcripts on the page
  
3. Keyboard Navigation
  - By default whatever is there on website should be accessible only via keyboard
  
4. Use Default HTML Tags
  - Buttons: Use <button> tag; NOT Anchors 
  - Links: Anchor <a> for links, 
  - Tables: \<table>, \<tbody>,\<td>, \<th> for tables; 
  - Headings: \<h1>, \<h2 >\.. for headings
  
5. Better tables
  - Try including \<caption>\</caption> for the titles of the table instead of bolding the title
  - Always use <scope> to define the table cells, so that screen readers don’t rattle them, without giving any context
 
6. ARIA Tag
  - It defines \<role> of every object on the page; 
  - It gives the description for a form or the current width of a progressbar, also tells the current state of the buttons like active or disabled
  
7. Use HTML Title Tag
  - Always title your page so that users know what the page is about, it’s helpful for screen readers



# QA Checklist For Accessibility Testing + What I prefer

## Desktop/mobile online tools: 
  - WAT (Web accessibility toolbar): 
      - Extension for IE and Opera browser: [Web Accessibility Toolbar](https://developer.paciellogroup.com/resources/wat/)
      
  - aXe plugin: Deque Tools: Works for all browsers: 
      - Extension available for Chrome and Firefox [aXe plugin](https://www.deque.com/axe/)
      
## Testing using keyboard navigation
  - This check is performed using Keyboard only and we test the focus, tab order, forms, Dialog box and popups, multimedia links, and navigation links. The first step in manual testing is to throw away your mouse. Verify that the user is able to navigate the website page, including the header, footer, all menus and interactive elements using only the keyboard.


## Testing using screen reader: *Browsers + Best tool to use*
  1. Firefox + [NVDA](https://webaim.org/resources/shortcuts/nvda)
  2. Safari + [Voiceover](https://www.applevis.com/guides/macos-voiceover/complete-list-voiceover-keyboard-shortcuts-available-macos)
  3. Chrome + [Talkback](https://support.google.com/accessibility/android/answer/6283677?hl=en)
  4. IE + [JAWS](https://webaim.org/resources/shortcuts/jaws)

## Testing using color contrast tools: 
  - [Color Contrast analyser tool](https://webaim.org/resources/contrastchecker/)
