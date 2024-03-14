# Foundations of Web Development
01. In your own words, why do we use Git?
    > We use git to help manage our projects, as it allows us to upload the current state of a project online. This lets us do a few things. It gives us more than one place to store a project, this is helpful in the case that our harddrive for our computer dies. Git being online is also much more convenient that say having an external harddrive and uploading the project to that. 
    
    Git also offers version control, allowing us to essentially roll back a project. So that in the off chance the project breaks beyond all comprehension we can simply go back to an older version of the project that wasn't broken.

02. In the terminal, what is the command `mkdir` used for?
    > `mkdir` makes a new folder at the current location of the filepath in the command prompt.

03. What is a ***pseudo-class*** and what are some of the most common ones you think you will use?
    > A pseudo-class is like a special adjustment given to a selector for more control over interactions. I think "hover" and "required" will be used relatively often. "Hover" is great for giving the user that extra bit of feedback to know their interactions on a page are being received. "Required" makes a field required to move forward, great for anytime you need the user to input information such as a username/password to login to something.

04. What is ***specificity*** and how might you use it to your benefit?
    > Specificity is the internal value given to a css selector, telling the code which set of property styling instructions to prioritize over another.

05. What problems do you think you could run into if you over-utilized the `!important` feature?
    >  `!important` ignores rules of specificty to give priority of one over another. If used too often you could easily create a scenario where the feature becomes useless. Since if using `important` gives priority where it normally wouldn't be, giving it to both selectors will overwrite the functionality and return it to normal. This would cause a lot of unnecessary confusion, which is why it's recommended against using regularly.

06. What are the three components that makeup a `CSS` rule? <br> Example:

    ```css
        h1 {
            color: rgba(255, 210, 33, .75);
        }
    ```

    > The Selector(what we're targeting), "h1"; The Property(what we're changing), "color"; and The Value(value of the property) "rgba(255, 210, 33, .75)"

07. How do you think good design influences people when visiting a website, and what sorts of things could you convey through design alone?
    > A lot can be conveyed through design and there's a lot of importance in design. For example mood can be conveyed through color, images, and even font. If someone wanted to make a website about vampires(I don't know why) then a darker page with a more gothic font could really bring the feeling home. Where if that site had more bubbly font it could end up feeling off or a like a joke.

    Another good design choice, is attempting to make font readable and accessible. Here style and font color are both important. If you have someone with weaker vision they may not even be able to see the text on your page if two colors are too close. Or those colors could clash like putting white on yellow or vice versa.

08. What is the purpose of ***wireframing***?
    > Wireframing allows a developer, designer or really anyone wanting to lay out their ideas for any kind of app, webpage or product in a low investment environment. Rather than spending an extended period of time making something only to throw all that work away. A wireframe allows for a quick iterative process to come up with the best solutions for goals possible before investing time into development.

09. Do you think wireframes are worth the time, energy, and effort that they require? Why or Why not?
    > I do think they're worth the time and effort. The larger the project, the more costly changes down the line can become. So having a strong start point with a good wireframe can save money and more importantly time.

10. Define the display `:flex property:`
    > The flex property gives you control of how to organize content, spacing the content evenly with a handful of options to seperate things evenly with varying amounts of space and positioning on the page.

11. What `CSS` properties affect the size of a box model?
    > Content, padding, border, and margin.
