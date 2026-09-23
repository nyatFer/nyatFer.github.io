# Decision log

Your methods section. About one page total.

Answer these as you go, not the night before it is due.
Specifics beat polish - a short honest answer is worth more than a long vague one.

Delete these instructions when you are done, or leave them. It does not matter.

---

## 1. What did you set out to build, and what changed?

What you wanted at the start, and what is actually live now.
Name one thing you dropped or added along the way, and why.

I wanted a personal page that introduces me and says the things I'm currently up to. What is actually live now is my name, a short introduction, my current projects/courses/hobbies, and my contact information. Something that I added along the way was my github link and university email because Claude suggested it and I thought it was a good idea.

---

## 2. A fork in the road

Name one real choice where you could have gone two ways.
Plain HTML or a framework. One page or several. Your own CSS or someone's template.
What goes on the front page and what does not.

Say which you picked, what the alternative was, and what you gave up by not taking it.

"There was no alternative" is not an answer. Find the fork.

So I wanted a robots.txt file. I could choose between blocking specific bots/scrapers such as search indexers but I decided on blocking all bots. I gave up search visibility. Now, my site shouldn't show up in search engines or AI training. That is the behavior I wanted and I hope bots respect my robots.txt file.

---

## 3. Where you overruled the agent

One time Claude suggested, wrote, or claimed something and you did not take it.

What did it do? How did you notice? What did you do instead?

If it genuinely never happened, say so plainly, and then say what you would have had to
check in order to notice. Being honest here costs you far less than a story you cannot
defend when you record your video.

I told it to put one of my projects in the site but it put it in past tense instead of present tense. When I noticed that in the localhost preview, I asked it how it thinks I should show that it is a current project. It gave me two choices to pick from. I decided on renaming the section to "Current projects" and changing the wording to present tense.

---

## 4. How you know it works

What check did you run, and what did it tell you?

Then the real question: **what would have made this check fail?**
A check that could not have failed is not a check.

Link to your `verification/` folder.

[verification/](verification/)
I ran a check to see if the fetch Claude got matches to a screenshot I took. The check was meant to see if index.html is at the proper place. The check passed because the screenshot and fetch matched. There would've been a page error or no content showing up if it failed.

---

## 5. What is still wrong

One thing on your own site that is not right, not finished, or that you do not
fully understand.

What would you do next, and how would you find out?

Something that isn't finished is my projects section. In the future, I'll add my past projects because right now it only shows my current projects. I would find out by making a list of my past projects and seeing what is not already on the site.
