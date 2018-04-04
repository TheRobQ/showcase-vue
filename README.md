TinyMCE in Vue
==================

This project is a simple proof of concept for setting up TinyMCE in Vue.
Check the [TinyMCE Vue Integration](https://www.tinymce.com/docs/integrations/vue/) documentation for more information.

Setting up this showcase
---------------------------

These instructions operate on the predicate of having access to a Unix shell on either MacOS or Linux.
If you're running a Windows system, these steps probably won't work for you.


1. Install the Node Package Manager (if you don't already have it).  
<https://nodejs.org/en/download/>
2. Clone this Git repository.  
`git clone https://github.com/idempotency/showcase.git`
3. Install the required dependencies through NPM.  
`cd showcase`  
`npm install`
4. Start the NPM server.  
`npm start`  

The showcase should then be accessible at `localhost:3000`.

Viewing the code
----------------

Most of the code directly responsible for this Vue App lives in `/src/App.js`. Feel free to modify and play with what's already there.

It's assumed that you have at least a rudimentary knowledge of Vue before you
start learning specifically how TinyMCE is implemented here.
