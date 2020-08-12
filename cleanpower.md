---
title:
permalink: /cleanpowerreport/
---



To edit any of the main tabs of the website:

-Homepage: home.markdown

-Team: members.markdown

-Projects: projects.markdown

-Research: research.markdown

-Timeline: timeline.markdown

-Reports: reports.markdown


All of the pages except for the team page (members.markdown) are written in markdown for easy access and editing. The html for the team page is necessary for formatting, but the regular text between the html tags can still be edited.


The team pictures are stored in the team folder under images and then teampic (team/images/teampic). The carousel pictures are stored in the images folder under slider (images/slider). All other images included on the projects and research page are included under the images folder (images/).


The main style sheet for this site is in assets/main.css.


The layouts for the different pages of the site are in the layouts folder. They are all in html. The includes folder holds various elements (headers, footers) that can be easily added to a layout or page.


To add a new tab/page to the website, simply duplicate one of the .markdown files (home, members, etc.) and edit the heading of the page to have the appropriate title and permalink. It should appear automatically on the website.
