# HTML CSS Git: Code Refactor Challenge

This week our challenge is an on-the-job ticket, which means we began with starter code that we needed to modify. This week's challenge involved a very important aspect of web development: **accessibility**. 

I began the challenge by creating my github repository and cloning the folder onto my gitbash/terminal. 

![Screenshot of cloning the github repo to my computer through SSH](<Github Repo.png>)

Next I opened the index.html file using terminal and began looking at the code. The first thing I tackled was adding the `alt` attributes to all the images so that there is a description of all the images as shown below: 

![Screenshot of an example alt attribute added to an image](<alt attributes added to img tags.png>)

I then proceeded to repeat this for all the images and Icons. 

The next step was to replace all `div` (non semantic) tags and replace them with `header`, `nav`, `figure`, `main`, `section`, `aside` and `footer` (semantic) tags to make the page more accessible. This took some time as I was refreshing the page on chrome everytime I changed a tag to make sure the code still worked. 

Correspondingly, this also meant that the css style page had to be amended to change any `div` elements to the respectively changed semantic tags for e.g. the `span` tag was replaced with `nav` and the style page had to be amended to the below: 

![Screenshot of the amended style page code showing 'nav' elements instead of the previously used 'span' elements](<Nav styling on CSS page.png>)

After replacing all the `div` tags on my html file, I though the next best step would be to paste my code into a html validator to spot any errors I may have missed. 

![Screenshot of html validator webpage](<html validator.png>)

I then slowly worked my way through the errors, one of which, was the `img` tags being incorrectly closed. 

![Screenshot of html validator img error](<html validator example.png>)

To fix this, I remembered that `img` tags are self closing hence, not needing the '/' at the end. 

Lastly for my challenge, I reorganised my CSS style page to group up relevant styling and added some comments. 












### Github Repo link 
https://github.com/abdeeg/ub-refactor-code

### Deployed page link
