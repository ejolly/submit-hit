# Mturk Dummy Submit

Single html form submit to use with creating and testing external HITs. All it does is provide the bare minimum to submit a hit:  
- The assignment Id parsed from the URL
- A dummy hidden field because external submission requires at least one other POST parameter

When you create an external HIT for testing on Mturk, just use the Netlify URL: https://testmturksubmit.netlify.app/

It will render in the iframe when a Worker accepts the HIT, and the form will automatically populate with the assignment ID. Just press 'Submit' and it should work fine!