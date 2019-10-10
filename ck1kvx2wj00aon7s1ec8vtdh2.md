## On managed blogs

I wrote  [my first blog post](https://medium.com/google-cloud/sentiment-analysis-of-comments-on-lhls-facebook-page-9db8b3a60eb3)  on Medium. I was about to write about the experience, but I realised that I did it already in  [my first post after moving off Medium](https://blog.jiayu.co/2018/04/my-new-blog/) .

Instead, I want to compare the experience of writing on Medium to my current workflow for posting to my statically-generated, self-hosted blog.

Writing on Medium was surprisingly frictionless. Enter your content into their WYSIWYG editor, hit publish, and your post is immediately up.

On the other hand, to create a new post on current blog, I need to start the  [Hugo](https://gohugo.io)  dev server and a browser to preview my work, and switch between the browser and the editor I'm writing my post in. When I'm done, I need to manually generate a timestamp for the post (I use `date --rfc-3339=seconds`), remove the draft flag and commit and push it to GitHub. This triggers a  [Netlify](https://www.netlify.com)  deployment, after which my post will be available. (Unless it's one of the few times I've forgotten to remove the draft flag, then I need to go back and make another commit.)

Despite how I find writing in Vim therapeutic, there's definitely more steps involved in blogging with a static site generator. Writing this post felt like a breath of fresh air. I didn't need to run a command in my terminal then visit localhost:1313 in my browser. I won't have to manually set the timestamp after I'm done writing. And I don't have to wait for CI to complete after I hit publish.

Nevertheless, I do think there's value in having a self-hosted blog, but I can still have that with self-hosted  [Ghost](https://ghost.org)  or Wordpress. Or I could use a headless CMS like  [Forestry](https://forestry.io)  or Contentful and continue having a statically-generated site. Perhaps I'll give those options a try someday.

In the meantime, I just wanted to try out this new site I came across.