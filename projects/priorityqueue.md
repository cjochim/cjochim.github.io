---
layout: project
type: project
image: img/clip-art-task-15.jpg
title: "Priority Queue"
date: 2023
published: true
labels:
  - Heapsort
  - Java
  - GUI
summary: "In my 211 class, one of the projects I completed was demonstrating a priority queue using a GUI program."
---

<div class="text-center p-4">
  <img width="600px" src="../img/guiheapscreenshot.png" class="img-thumbnail" >
</div>

Throughout my ICS 211 class, I was introduced to abstract data types such as lists, stacks, queues, etc. During the last segment of the class, I learned about different sorting methods and determining the order for complex algorithms, which gave me a deeper understanding that a sorting method can be more efficient than another depending on the situation. For my last project, I learned the outlining methods for a binary search tree (BST), which I would intertwine this knowledge of BSTs with heap sorts. This last simple yet educational project summarized what I learned since the beginning of the course.  

The concept of a priority queue is to input items with the highest priority to the end of the queue. The highest priority item will be the first to dequeue, then the next highest priority and so on. To summarize, a queue is a first in first out data structure.The goal of the project is to create a priority queue of tasks with different priorities. 

To implement the priority queue, I used heap sort methods. The function of the heap sort is to find the minimum element and place that element at the beginning. Comparing the order of the sorting methods I learned in the semester, heap sort was the most efficient solution for this project, especially because the program is structured with a binary tree. When the program is running, the first task will be inputted with the priority displayed -- 1 as least priority. The next tasks will be inputted and sorted in a tree-like fashion. The task of highest priority will be displayed until executed using a queue method. 
