# Entry 5: Learning Jekyll
##### 4/27/26

### Learning Jekyll

The tool that I chose to help me create my Freedom Project website is Jekyll, a static website generator that allows you to create posts or blogs and then add layouts or themes to these. Each of these will be in a home page where you can see them side by side (or vertically). In addition to this, Jekyll uses Yaml and Liquid as a way to process meta data and implement CSS to Markdown. During the time that I have spent learning Jekyll, I have used several sources and platforms in order to understand how to use Jekyll, why to use it, and for what. Often times, I would struggle understanding some of the videos that I watched or even trying to preview my code I would get stuck and make errors which would hold me back (if there is something wrong with the website then Jekyll won't allow you to preview the website), and yet, I was able to finish learning Jekyll which will allow me to create a website for my Freedom Project.

Below, I will go through what I did to learn Jekyll and what Blog posts, themes, Yaml, and Liquid are.


### Blog posts
Blog posts are websites where you can add projects, or information that you want people to see. Blog posts can also be used to create actual websites using Github. While I was learning Jekyll I watched [this video](https://www.youtube.com/watch?v=gsYqPL9EFwQ) from Giraffe Academy, which taught me how to create  blog posts.

Inside of my IDE I created a new blog post where I would tinker with Jekyll.

<!-- ![blog ss](imgs/blog-ss) -->



### Themes
Themes are pre-determined layouts that can make a blog post look a certain way depending on the preference of the person who's creating the website. In order to learn how to add themes and where to look for them I watched [this](https://www.youtube.com/watch?v=NoRS2D-cyko&t=211s) video.

After watching the video I added the _Minimal Mistakes_ theme to my website.

![theme ss](imgs/theme-ss)

### Liquid and Yaml
Yaml is a coding language that can be used as a substitute for JSON and XML. Liquid is a coding language that enables you to load your Yaml front matter into HTML.

As a way to learn both of these languages I decided to watch these videos:
* [Yaml tutorial](https://www.youtube.com/watch?v=BEki_rsWu4E&t=73s)
* [Introduction to liquid](https://www.youtube.com/watch?v=6pCdOh_I4EM&list=LL&index=10&t=1s)
* [variables](https://www.youtube.com/watch?v=nLJBF2KiOZw&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=13)


and used this website:
* [Idratherbewriting.com](https://idratherbewriting.com/documentation-theme-jekyll/mydoc_yaml_tutorial)

From these I learned that I can use Yaml to create variables and objects which can then be assesed by Liquid.

For instance, if the title of my website is Freedom Project, and I want to add an `h1` that says Freedom Project, I could type `{{ page.title }}` inside and `h1`. In this case, my front mater would contain the variable `title: Freedom Project` This would make the title show up as an `h1`, but if I want the title to only be capital letters, `{{ page.title | upcase}}`, if I only want the first 5 letters in the title to show, then `{{ page.title | upcase | truncate:8 }}`.

Using Liquid you can also be specific of where you want your variables to come from. Using `page.` (like we just did) means that the variables are coming from the "home" or the by default page, but if you want to use variables from the same post, or _layout_  you are in then you use `layout.`. Furthermore, if you want to use variables from your **_cofig.yaml** folder then you can use `site.`.

### Skills

As I learned my tool and wrote this blog I gained some skills that I know will definetely help me next year at school, and continue to help me for the rest of my life. The skils that I gained were learning on my own, working despite not feeling like it, and doing things wisely. Throughout all the time I've spent learning Jekyll, I have realized that everything I learned came from my own reaserch and my own tinkering. I didn't pay online lessons, or have someone teach me this tool. Instead I had to search information in websites and watch videos which were hard to understand so that I could then try what I learned in my Jekyll site. Additionally, I had to keep doing research and learning Jekyll despite feeling like giving up on it. It has been almost a whole month of me not feeling like doing any work and being mentally drained by my day to day life. As a result I found it very hard to stay consistent and not procrastinate, but I still did the reaserch, learned my tool, and wrote my blog. Finaly, because I have been occupied with many tasks and commitments, I've had to  be wise on what tasks to do, and when to do them. For instance, right now I'm typing my blog and after this I will move on to finishing my ELA homework because I know it is going to be a lot easier and less time consuming.


[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
