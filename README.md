# **Planning blog application**
  
  1. Answer questions
      - What am I building?
      - Who am I building it for?
      - What features do i need to have?
  2. User Stories
  3. Model our data
  4. Think through the pages that may be needed in the app
  

### Questions
1. What am I building? 
  -- I am building a personal site where I can blog, share my body of work, and have people contact me.
2. Who am I building it for?
  -- I am building it for myself but also the community. Sharing what I have learned through blogging, which in the process 
     may teach others. Also, to show potential employers that I do know and understand what I am talking about.
3. What features do I need?
   - Post 
      - Create / Edit / Destroy
      - Markdown formatting
      - Syntax highlighting
      - comments (Disqus)
   - Projects
        - Create / Edit / Destroy
   - Contact
        - Contact form
        - Sendgrid
   - User (Devise)


### User stories 
 As a blank, I want to be able to blank, so that blank.  
 - As a user, I want to be able to create a post so that I can share what I am learning with the community.
 - As a user I want ot be able to edit and destroy post so that I can better manage my blog.
 - As a user I want to be able to write post in markdown format so that it is easier for me to write posts.
 - As a user I want to be able to highlight various syntax of code blocks that i share on my blog.
 - As a user I want to be able to show the visitors and potential employers examples of my work, or stuff I've built.
 - As a user I want people to be able to contact me directly through my site.
 - As a user I want people to be able to leave comments on my posts.
 
### Modeling the data
**Post**
   - title:string
   - content:text
**Project**
   - title:string
   - description:text
   - link:string
**User**
   - Devise

### Think through the pages that may be needed
   - Home
   - Posts#index
   - Posts#show
   - Projects#index
   - Projects#show
   - Contact
   
   
   
   
   
   