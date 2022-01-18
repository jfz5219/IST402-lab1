
## Open package.json and look at the scripts devDependencies and dependencies sections. What do you think each section does here? What commands can you run?

  * The dependencies section shows what version of the litelement. The devDependencies section shows information relating to the web server as well as the analyzer.

  * I'm not sure what commands you can run since it's just a text file.

## The "demo" for your hello-world element is found in index.html. Reading this code, what does it do and how does it work? What HTML is making your script load to show a demo? How is this file rendering HTML via JavaScript?

  * `<script type="module" src="./hello-world.js"></script>` is what loads the script into the webpage in order to show the demo.

  * The file is rendering HTML via JavaScript by having a script line within an HTML file which means you can run JavaScript on the HTML based web-file.

## The Definition of your element is in your-element-name.js, while the class JS object is found in src/YourElementName.js. Why do you think they put these in two separate files? What do you think each code block is doing in the class'ed object?

  * I think that these two are put into separate files because you need to import the file in src into the your-element-name.js file.

  * In the class object, it first extends LitElement. The rest of the code runs css code in order to add styling to the class like, "display, padding, background." Then applying a color style to items labeled with "object."

## Try to explain what Lit is providing to the repo. What's so special about what Lit is providing that I'd be so bold to say it changes how the web is developed, forever?

  * Lit does a lot of things for you related to components as well as giving a basic lit-html template that the component uses to be built. I think that you think of Lit so highly because of how lightweight it is and how easy making components becomes using Lit's templates and how it can be used with any framework.
