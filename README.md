# SIMPLE PORFOLIO HTML WITH CONTACT FORM

## ABOUT
    Netlify is a fantastic service for hosting with free SSL, server-side 
    functions and even built in form functionality.
    
## EXAMPLE CASE
    This Simple Portfolio Html and Contact Form Submission With Netlify
    This is the easiest way to add a contact or any type of form to your 
    website by using the Netlify form feature including file uploads and 
    spam filtering

## THE STEPS
  - [x] Register or make Account in [Netlify](https://app.netlify.com/)
  - [x] Find & download any contact-form html on internet
  - [x] modify it like this :
  
	    <form action="POST" data-netlify="true">
		<div class="row gtr-uniform gtr-50">
		<div class="col-6 col-12-xsmall">
		<input type="text" name="name" id="name" placeholder="Input Your Name" /></div>
		<div class="col-6 col-12-xsmall">
		<input type="email" name="email" id="email" placeholder="Input Your Email" /></div>
		<div class="col-12">
		<textarea name="message" id="message" placeholder="Input Your Message" rows="4"></textarea></div>
		<div class="col-12"><input type="file" name="myfile" id="myfile" placeholder="Upload File" rows="4"></div>
		<div class="col-12"><div data-netlify-recaptcha="true"></div>
		</div>
		</div>
	    </form>
    
  - [x] then push it to github,
  - [x] open [Netlify](https://app.netlify.com/),
  - [x] login and link it with your github,
  - [x] find your repo,
  - [x] Deploy...
    As simple is that...
