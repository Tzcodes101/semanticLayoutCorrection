# semanticLayoutCorrection
I turned the first div with class of header in to a section.
I want to turn the div containing the ul into a section as well, but I think I'll have to change the CSS.
I changed the div within the first section to a section without changing the CSS, and the items went to bulleted, and appeared on top of one another instead of side by side without the bullets. 
So I left the ul as a div because the items are still part of the heading section, and not their own section. 
But why did changing the ul from div to section change the default html or CSS? 
Ohhhh, it changed because the css had a .header div ul selector... so do I change this div to a section? I want to because a list is it's own section, but I am unsure if I should because the list is still part of the header section... but it's it's own section within the header section. 
I made the ul a section within the original section, and changed the css so it still applied to the ul. The items were then below the h1, and I changed the padding. I like the wat this looks better than having the items with the h1. 
When I made this change, the items also moved more to the right side of the page, which I like the look of. Although I am not 100% sure why this happened... I think it has to do with the left margin and then being separated from the parent section a bit.
I added an id to the ul and li to simplify the CSS selectors. 
I changed the <div class="hero"></div> to section tags as this is it's own section on the page. 
Changed the div with class="content" to a section.
For something on the left do you not need a right margin and vice versa for something on the right? Does size then control that?
Made search-engine-optimization an id and appropriate changes in CSS.
Changed .online-reputation-managment to an #online-reputation-management to align with the html.