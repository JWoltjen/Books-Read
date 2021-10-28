
<h1 align="center">
  Books Read
</h1>

<h4 align="center">A responsive full-stack application built with Mongoose, Express, React, and Node.</h4>

## What does this do?

## What technologies does this project use? 

  -Material UI
  
  -React-File-Base
  
  -Express
  
  -MongoDB
  
  -React-Redux
  
  -SVGBackgrounds

## Lessons Learned

Material UI is an opinionated component-based library for react that favors in-line styling over traditional cascading style sheet rules. Material UI is really strong in making things responsive. This is because it uses premade components and containers. As long as the developer knows which container to use in a certain situation, it is difficult to get the layout to break on mobile and it is easy to correct.

React Filebase is a super-easy way to link data from a user's computer into application state on form submit. It plays nicely with the following piece of code within the Form component: 
-<div className={classes.fileInput}><FileBase type="file" multiple={false} onDone={({base64}) => setPostData({ ...postData, selectedFile: base64})}/> </div>
