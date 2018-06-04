# feedback

A simple tool for providing side-by-side feedback (a split screen with your app on the left and a notes page on the right).
The idea is that you've just created a wonderful new app or feature and you want to solicit feedback. Rather than 
giving people a link to your app and asking them to email feedback to you or go to some other site to provide 
feedback, give them a single link that loads your app (ideally directly to the page to be reviewed) on the left and 
a text page for feedback on the right. If you include some basic directions at the top of your notepad, users can 
quickly evaluate the app and drop in any comments along the way. You get instant feedback and can turnaround changes as 
you cross things off the notepad.

Just direct people to `https://bmamlin.github.io/feedback/?left={left}&right={right}&title={title}`, where:

* `left` = address of page to show in the left pane

* `right` = address of page to show in the right pane

* `title` = optional title for the feedback page

For example:

[https://bmamlin.github.io/feedback/?left=https://deanhume.github.io/beer/&right=https://beta.etherpad.org/p/feedback&title=Feedback%20demo](https://bmamlin.github.io/feedback/?left=https://deanhume.github.io/beer/&right=https://beta.etherpad.org/p/feedback&title=Feedback%20demo)

For an improved experience, send the URL through a shortener and give people a short link, like:

[http://maml.in/Ya3Pi](http://maml.in/Ya3Pi)
