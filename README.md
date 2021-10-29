# Email-Template

You’ve just been assigned to code an Email Template by your Project Manager, and you have no idea where to start. If you are put in this unfortunate position, you should first ask if you can simply use an already established email service, which includes support. If that proves to be fruitless, you will have to write your own. Writing email templates gets frustrating fast due to its incompatibility with CSS and the inconsistency between Email clients such as Gmail vs. Outlook.

CSS Incompatibility

The first step with dealing with CSS incompatibility is to break the cardinal rule of front-end development completely; you have to inline-style your CSS code. I can feel your contempt for me right now, but it’s the only way to guarantee your styling is rendered properly. 

Tables          

When creating the layout for the HTML code, you want to be displayed in the Email, use tables. Outlook doesn’t support flexbox or float, so if you want a grid that aligns together, your best bet is a table.

For example; if you wanted a grid displaying four NBA teams under a header that said Teams and you wanted to achieve this with just DIVs, it wouldn’t display properly in an Email template even though it would render in Web Browsers.

Buttons

Everyone knows how essential Calls-To-Actions are for Emails; how else would you drive user traffic to your desired URL. It’s preferable to programmatically create buttons as opposed to using images because it allows changes to be made more easily. However, getting buttons to display correctly on Outlook is exceptionally frustrating. This cope snippet below works perfectly fine on Gmail but looks completely off in Outlook:
