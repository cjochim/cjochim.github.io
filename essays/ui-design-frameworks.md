---
layout: essay
type: essay
title: "(frame)Working with UI"
# All dates must be 2023-09-05 format!
date: 2023-10-04
published: true
labels:
  - UI Design
  - HTML
  - CSS
  - Bootstrap 5	
---

## UI Design: This is What I Want to Do. 

From my first computer science class up until now, the majority of what I knew in computer science was the backend development material. Honestly, I struggle with backend – for-loops, arrays, objects, algorithms etc. Because the struggle began to outweigh the passion and curiosity, I questioned, “Is this really something I want to do in the future?” The materials introduced to me never sparked any interest. For me, I only learned for the sake of getting through the course.

However, in my software engineering class, the upcoming module was “UI Design (Basics)” which is learning how to design web pages using HTML and CSS. Admittedly, that was the first time I felt inclined to learn more about a topic. For one of the assignments in the UI design module, I had to complete a HTML and CSS course which is supposedly 5 hours long, but I wouldn’t mind the 5 hours if I’m learning how to design a web page. 

## HTML & CSS : Canvas & Palette

UI designing is similar to painting: HTML is the canvas and CSS is the palette. When the CSS “palette” is linked to the HTML “canvas,” a web page “painting” is created. It is not the best analogy, but that is how I picture the relationship between HTML and CSS. Basically, CSS is an essential for designing web pages. For my assignments, I mainly used an external stylesheet and linked the stylesheet to the HTML file. 

## Too Slow & Tedious...

While working on the assignments using CSS, I noticed that creating customizations and alignments took a while for me, so I wondered, “Am I the problem? Do all web pages take this long to create?” For example, creating three columns of equal width involved implementing three different classes in the stylesheet for each column:

```
.left {
	float: left;
	width: 300px;
}

.right {
	float: right;
	width: 300px;
}

.center {
	margin-left: 300px;
	margin-right: 300px;
}
```
This process is disorganized to me because then I would have to memorize the column classes I created, and I would have to refer back to the margins I created and constantly adjust or create a new column class with different margins. This is not the only tedious disadvantage; creating a navbar is another example. I will not go into full detail with the process but similar to columns, I implemented multiple classes in my stylesheet to design the layout of my navbar. In addition, I noticed my CSS appeared to lack a few characteristics and structures of a web page. 

## UI Frameworks: A New Lifesaver?

After learning the basics of UI design and going through the treacherous journey of creating stylesheets for different scenarios like 3-column layouts and navbars, I encountered a set of tools to make my journey less rigorous, UI frameworks! UI frameworks are designed to relieve the workload and time by providing a ready-to-use CSS library. The UI framework introduced to me is Bootstrap 5, which is one of the most widely and frequently used UI frameworks. 

## Bootstrap 5: Helpful yet Difficult

Initially, I thought everything in Bootstrap is simply copy and paste, however, Bootstrap and other UI frameworks involve learning how and when to utilize the tools. Similar to learning a new language, I had to research the function of each component, layout, utilities, etc. Honestly, despite completing the Bootstrap crash course and reviewing the material, I had a much harder time learning how to implement Bootstrap than implementing my own CSS. I thought, “Bootstrap is supposed to make my life easier but why am I struggling so much? Is the problem me again?”

Frustrated and confused, I continued to review and practice with Bootstrap. I admired Bootstrap’s navbar design the most, but I deeply struggled with the navbar – my nav-items did not align correctly, the spacing was off, I could not fit an image to size, etc. Once I got the hang of it, I started to enjoy and appreciate Bootstrap. For instance, referring back to columns, Bootstrap already has a built-in column feature, “col,” so no need to create a column design, yay! Moreover, I noticed how uniformed and “cleaner” my web page looked compared to not using any UI framework.

<img width="300px" class="rounded pe-4" src="../img/bootstrapbrowserhist.png">
<img width="300px" class="rounded pe-4" src="../img/cssbrowserhist.png">

Bootstrap is indeed difficult because of the numerous content. However, once I got through the learning barrier, Bootstrap is a useful tool in UI design, saving lots of time and providing a “skeleton” of a web page. Bootstrap is one of many UI frameworks, so I am really curious on how the other UI frameworks function such as Semantic UI. I noticed that Bootstrap and Semantic UI are evenly biased, so it’s up to personal preference. After I fully grasp Bootstrap, Semantic UI will definitely be my next UI framework that I will learn. 