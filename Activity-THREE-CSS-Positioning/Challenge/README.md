#  A note about Z-Index

Think of z-index like layers of paper stacked on your desk. When you have multiple papers, 
the one on top is what you see first. In web design, z-index works the same way - it controls 
which elements appear on top of others.

The value z-index: 100 means that element will be positioned 100 layers up from the base layer. 
The higher the number, the closer it appears to be to you (like it's floating above other elements).

Here's a practical way to think about z-index values:

Base elements usually don't need a z-index (they default to 0)
Navigation bars and headers often use values around 100
Dropdowns and tooltips might use 200-300
Modals/popups usually get higher values like 1000
Important alerts or loading screens might get 9999

The actual numbers don't matter as much as their relationship to each other. Using values like 
100, 200, 300 (instead of 1, 2, 3) gives you room to add elements in between later if needed.


# 🏗️ Implement Absolute and Relative Positioning to Change Layout

Work with a partner to implement the following user story:

* As a developer, I want to use the CSS position property to change the layout of my page.

## Acceptance Criteria

* It's done when `box 2` is positioned in the middle of `square 1` using relative positioning.

* It's done when `box 2` is positioned outside of the upper-right corner of `square 2` using absolute positioning.

* It's done when the finished page matches the mockup.  

## Assets

The following image demonstrates the web application's appearance and functionality:

![Box 2 is positioned in the center of Square 1, while in Square 2, Box 2 is positioned outside the square.](./assets/image-1.png)

---

## 💡 Hints

How does the CSS `position` property change the document's normal flow? 

## 🏆 Bonus

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* What is the `z-index` property? 

Use [Google](https://www.google.com) or another search engine to research this.

