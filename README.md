# In Memory of Friedrich Zawrel

In Memory of Friedrich Zawrel is a memorial to the Nazi euthanasia survivor Friedrich Zawrel. The site aims to make his life story accessible to an English-speaking younger generations by presenting the information in an intuitive, user-friendly and media-supported way. The site has a secondary aim of making users connect Zawrel's story to current political events and ethical questions. The site addresses both, users who want to learn about Zawrel and educators who might find it useful as class material. A small catalogue of questions to discuss in class has been added to the page. 

<!-- In this section, you will include one or two paragraphs providing an overview of your project. Essentially, this part is your sales pitch. At this stage, you should have a name for your project so use it! Don’t introduce the project as a Portfolio project for the diploma. In this section, describe what the project hopes to accomplish, who it is intended to target and how it will be useful to the target audience. 

For example; Love Running is a site that hopes to help keep people motivated to meet up for runs on a regular basis in Dublin, Ireland. The site will be targeted toward runners who are looking for a way to socialise and keep themselves fit. Love Running will be useful for runners to see exactly when and where they should be to join the running club.  -->

![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

## Features 
<!-- 
In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things. -->

### Existing Features

- __Custom Favicon__

The website has a custom favicon that is a picture of as sunflower. 

- __Navigation Bar__

 A full responsive navigation bar is featured on all pages. It includes links to the home page, resources page and guestbook page. 
 
 The nav bar is sticky so that users can easily access navigation even though the page scrolls down quite a bit. 
 
 The sticky nav bar separates from the page logo when scrolling in order to save space.


![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)


- __The intro section__

The intro section equips the user with a quick introduction of the site's contents. It explains who Friedrich Zawrel was. It is accompanied by a background image of an old blurry newspaper article. 

In the smaller size screens we only see Zawrel's image from the article, but in larger size screens, as the image quality deteriorates beyond usable, part of the article text is also shown. The image quality is still not very good but I think the context of it being an image of an old newspaper, and the page being about a historical figure, justifies the image quality. 

The introductory text scrolls over the fixed image on a semitransparent black background. This contrasts the grainy picture with a nifty, modern sleek look and adds visual interest. The text box is fitted with a little down arrow to signal the users that there is more scrollable content below.


![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __Childhood section__

  - The childhood section is the first of the three (planned: 5) biographical sections that make up the meat of the site. 
  
  It lets the user enter the narrative of Zawrel's life. The text is kept short and on point in order to keep readers interested. It is split up over two square divs to reduce information overload and make it visually appealing. The color scheme is reverted and the div backgrounds are given round edges. The background image to the section is a grainy video still of Hitler Youth marching in Austria. It is not fixed but scrolls with the text. This again, adds visual interest. 

![Club Ethos](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __Am Spiegelgrund section__

  - This section narrates briefly Zawrel's experiences in the clinic Am Spiegelgrund. It is styled with another fixed background, which, different from the intro picture, now fills the entire screen. The textbox has the same colour scheme and background style as the intro section's textbox. 

  - The main text is accompanied by an aside, visually separated in a div with a dark grey background. The aside textbox is similar to the ones in the childhood section. The text delivers facts about the clinic "Am Spiegelgrund." It is accompanied by an old areal photograph. The photograph has a caption.  

![Meetup Times](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __Meeting Gross section__

  - This section is the most text-heavy and the most climactic part of the narrative. It is kept simple, separated in paragraphs, white text on a dark background. The textbox shares features from both previous textbox styles. 


  __Guestbook entry form__

  - At the end of the narrative, users are invited to share their thoughts on Friedrich Zawrel's story.
  - They can do so via a simple form that features an optional text input field for their name, an obligatory e-mail input field and an obligatory textarray field for the message. 

__The Footer__

- The footer is fixed to the bottom of the page and visible at all times. It includes links to a few social media sites that will open in a new tab. 






![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __The Guestbook page__

  - The guestbook page consist of a simple table that lists messages left, optionally with the sender's name. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __The Resources page__

  - This page features relevant resources that the users can peruse to further their knowledge about Friedrich Zawrel and the things he experienced. It includes an embedded video of an interview with Zawrel (in German), additional photos and a list of thematically sorted links that might be of interest to the user.

![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- To complete the story, two more sections of the biography are necessary. Of these, the last one would break up the black-grey-white scheme and introduce some photographs in colour. 
- The resources list should also have a catalogue of questions and current developments in society and politics that an educator might want to use to discuss with their students on the background of Zawrel's experiences. 
- The footer should have more relevant information and links. 
- A small section that lists image sources. 
- The paragraphs in the Meeting Gross section should be styled for different screen sizes to be more digestible.
- The favicon should be changed to a more suitable one. 



## Testing 

I haven't been able to do a lot of testing apart from how it looks in devtools and the screens I have at hand. There is a bug on my Xiaomi phone where the second textbox of the Childhood section overlaps into the Spiegelgrund section. I tried fixing it but it didn't work. 




 The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user. 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

- The guestbook form doesn't actually work since I am not able to create a MySQL database for it yet. 
- 

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://tina7e.github.io/memorial-f-zawrel/


## Credits 

I have started following the steps for basic page set-up from the Love Running Walkthrough. I recreated the code used to create header and footer, and to push the footer down.

I have looked up bits and pieces on various pages online but I believe I haven't outright copied code, rather looked it up and adjusted it to my specific situation. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The content was taken from 
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 