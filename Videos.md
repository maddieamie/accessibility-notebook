# Web Accessibility Videos

[Chrome's Accessibility Tree](https://www.youtube.com/watch?v=pJL6qtfYkBo)

**What**
- You can try using WAVE extension that exposes the ARIA tree
- Objects that make up content on the page, based on the DOM
- only shows accessiblity data 
    - span becomes StaticText, H1 becomes Heading

**How access**
- Inspect (hit icon to see the accessibility tree instead of the DOM (little person icon))
- Styles tab, right arrow, choose Accessibility, ReloadDevtools
- ARIA attributes attached to the element 
- aria-label trumps HTML label 

**Debugging with it**
- Accessibility Tree has it hidden (aria-hidden removes it from the Accessibility Tree)
- check custom widgets 
- common things -> setting combobox element role to combobox, setting aria-expanded to false when the pop up is not visible and to true when it is visible. 

[What is ARIA & its impact on Accessibility](https://www.youtube.com/watch?v=BDPMUq__gIM)

**What it is & number one rule**
- used to make webpages more accessibility 
- Don't use ARIA -> if there is an HTML element that will get you the behavior you are looking for, then use that HTML element. 

**Impact of using incorrectly**
- No ARIA is better than bad ARIA
- users who navigate with a keyboard expect a button to activate, or be selected, when they click enter or spacebar
- ARIA - expanded -> tells us if accordion is collapsed or expanded 
- ARIA - label -> renames an HTML element when it's being read by screen reader 
- ARIA - hidden -> hides from assistive tech (user isn't getting that content)

