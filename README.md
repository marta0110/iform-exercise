# iform-exercise
that's a IForm exercise



Frontend autumn 2018 
Form exercise



  
Styled form
Your task is to create a form for signing up to a fictional site. The form should ask for name, requested user-name, email, phone as well as subscription type.
The important part is the UX - the user must never be in doubt as to whether a field is required or optional, if it is correctly filled in or not, and if any fields are missing before submitting the form.
You are not allowed to use any JavaScript - only HTML and CSS.
Requirements
The form must have these fields:
Full name (required): A full name, preferably first AND last name, maybe more
User name (required): A string of 5 to 10 lowercase letters, only a-z allowed
Email (required): A valid email-address 
Phone (optional): A danish phone-number with or without +45
Subscription (required): A selection between Free, Cheap and Expensive (one
An “agree to terms and conditions” checkbox (required)
A Sign-up button that submits the form
Layout
A suggested layout could look like this:

But you are free to layout and design the form however you choose! Make the user friendliness your priority! 
Interactivity / feedback
Must means that it is an absolute requirement. Should means that it is a request, that you should try to fulfill.
The user must be told if a field is required or optional.
When the user enters data into a field, there should be immediate feedback about whether the data is valid or invalid.
If the user hasn’t entered data into a field yet, it should not be marked as invalid.
The user should be made aware of all missing required fields before (or just when) pressing “sign up” – not just the first one.
The user should be told if the form as a whole is valid or not, without having to press the “sign up”
Suggested process
We will do these steps in class – not as solutions to the exercise, but as small demonstrations of the technology required – follow the same process, and life will be sweet!
Design your layout as a wireframe, and draw a grid over it
Build the resulting HTML for a partially filled form (with required and validated info-symbols), and make the CSS for the grid.
Split the grid into subgrids - HTML and CSS-wise
Style the inputs that are required (ugly red background-color is always a good start)
Now insert the required-symbol (*) using CSS rather than HTML
Then insert valid and invalid marks using the same technique
Now, fix it so empty fields doesn’t get valid/invalid-marks
Make the sign-up-button look different, when the form is invalid
After that, make additional niceities, like:
Make the field change color, if the user leaves it in an invalid state
Make all invalid fields “light up”, if the user tries to submit the form.
Make animations and cool effects!

