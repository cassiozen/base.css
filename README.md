# base.css
It's not huge and bloated. Not normalize nor reset, just a basic set of rules to make modern browsers behave.

### How is Base.css different?
The common objective for projects like base.css, normalize and reset is to achieve consistency across browsers.
Normalize does this by taking in consideration what should be considered the standart 'look and behaviour' of a given element and fixing the browsers where it acts differently.
It was born as an alternative to reset.css, which simply stripped many html elements default styling (with the same objective: achieve consistency through browsers)

Base.css is different in three ways: It only targets modern browsers (IE 10+) and it does a little of both: Normalizing and resetting behaviour. It normalizes what is considered de facto behaviours that we rely and some browsers screw (like IE not resizing a button with a big text inside it - all other browsers does this). For elements that usually tend to have its defaults overwritten on new projects (like heading styles, for example), base.css simply applies a reset (which have a smaller footprint).
Finally, base.css applies the box-sizing property to make building CSS layouts easier and a lot more intuitive. It's such a boon for developers that there's even an International Box-Sizing Awareness Day in February ;)
