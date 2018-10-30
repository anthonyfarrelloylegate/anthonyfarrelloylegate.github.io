# README
** (2 minutes to read) **

In my previous blog post [Git me out of here - writing with Markdown](http://ramblingsofanthony.blogspot.com/2018/09/git-out-of-here-writing-simple-readmes.html) we looked at Git and discussed how Git & GitHub has changed the way we code and are now changing the way we document our code. Our documentation can now be closer to the code than it has ever been before.  

I was about to dive in and start documenting but where to start? Given the options what should I use? What do I write into a GitHub README file, when to use the WIKI feature on GitHub; what is the difference between GitHub Pages and Jekyll.  What is the difference between Jekyll, GitBook and other Static Site Generators (SSG’s) like VuePress and Hugo. Which static site generator do you choose if any at all.


**For today’s blog** let’s start with the humble README file that you see on GitHub; what it is, why they are an absolute necessity, and how to craft them well.


**In my next blog,** I will look at the rise in popularity of Static Site generators (SSG’s). The rise of SSG’s has highlighted the enthusiasm for ready-made tooling that allows users to focus on content leaving boilerplate code to be auto-generated through declarative statements.  I will show how these tools integrate with GitHub allowing GitHub to host compelling sites.


## The humble README

You may be waiting to write your README until your project is finished. This is a mistake.  Try a different approach and write as much of your README as you can before you start your project. Like the agile process of [TDD](https://en.wikipedia.org/wiki/Test-driven_development) surely we should also move to readme driven development for our repo’s.   The readme should be the single most important document in your codebase, write it early as you would with your design documentation; writing it first is the proper thing to do.


A README is your readers first and possibly only look into your repository. I would say that the lack of a README is a powerful red flag, or a poorly structured or lengthy README is indicative of a poor quality component.  You must care about people’s time, your README must allow the reader to scan your readme page and in a just few seconds the reader should get the gist of your project. Once scanned the reader may then take a little more time to read your page properly. When crafting your readme do not spend too much time on bikeshedding (Parkinson's law of triviality) trivial items when more crucial matters require attention.


#### Cognitive funneling

Good rules of thumb for your readme include dividing your readme into a number of short sections. The following are good candidates; Project Name & short description, Install, Usage, API, Examples, Contribute, other sections might include e.g. a License section, Known Issues, Useful links, Release process.


The ordering of the above was not chosen at random. The ordering here is referred to as "cognitive funneling" where the start of the README contains board project description, and moving deeper down into the funnel presents more specific details for the reader who is interested enough in your work to keep reading your readme. Finally, the bottom can be reserved for details only for those intrigued by the deeper context of the work (background, credits, biblio, advanced features etc.).


By taking the time and making your README files uniform across the org, you can also give the impression that your sample apps (Git repos) are well thought out and collaborative as opposed to one-off efforts.


## References

https://github.com/noffle/art-of-readme - By Stephen Whitmore

https://whatis.techtarget.com/definition/Parkinsons-Law -  By Cyril Northcote Parkinson "Work expands so as to fill the time available for its completion"

https://en.wiktionary.org/wiki/bikeshedding - Don't waste time on trivial things with crucial matters outstanding, "Parkinsons Law of Triviality"

https://github.com/IBM-Cloud/repo-guidelines - IBM Cloud repository guidelines

http://tom.preston-werner.com/2010/08/23/readme-driven-development.html  - Readme driven development By Tom Preston-Werner (founder of GitHub)
