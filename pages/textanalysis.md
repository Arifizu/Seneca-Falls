# Speeches and Newspaper articles relating to suffrage
### The Process
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;First, I located some newspapers handily sourced from archives & newspapers.com. From there, I scraped the sites to get a plain text version that can be analyzed by Orange. After the webscrape, the data was collected and input into a fairly massive excel document so I could analyze everything at once. After cleaning up a few "unusable" entries via filter (usually an offhand mention of the word "woman" that would come up in a search but bear no relevance to suffrage or rights). An idea of all the processing and work that goes into work like this can be shown below. This is a screen shot of my workflow in Orange3.

![Title Image]({{ site.baseurl }}/assets/images/orange.PNG "Work made easy thanks to Orange3")

---

### The Result
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The visualizations posted here are the result of the research and scrape. While traditional research would allow me to hone in on a single subject like a person or a location, the strength of digital techniques is that I can clear large swathes of metaphorical ground so long as the sources are digitized or composed in a way that can be analyzed by a program. While I only used four sources plus the *Declaration*, in a project with no time constraints, or at the very least, more time and archival work, a larger sample of data can be gathered.

---

### Sentiments
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Setting out, I wanted to get the sentiments of a few articles and pair it with the Stanton address to see what a computer would determine is either in support of, or against women's rights. Once all the information is compiled, we can process the text and see what the computer believes are the dividing lines. In order to read this, consider 0 a neutral point, 1 in support of, and -1 in opposition to. Orange3 successfully identified the topic as something to do with Women and scored the articles accordingly. Interestingly enough, a computer can't detect sarcasm, so the *Oneida Whig* article comes up as fairly close to a 1.

![Title Image]({{ site.baseurl }}/assets/images/sentiment.PNG "Sarcasm undetected")

---

### Clustering
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Another technique in text processing we can use is called clustering, where an AI attempts to not only determine sentiment, but classify entries together in order to determine their relevancy to eachother. In the image below, you'll see three clusters created by Orange3. The *Oneida Whig* article is a sarcastic response to the *Declaration*, so naturally the program detected that it was referring to the *Declaration* and paired them together regardless of connotation. The *North Star* article by Frederick Douglass supports women's rights without mentioning the *Declaration*, because, as Douglass mentioned in the article, he did not want to "mar" its efficacy. Therefore, it was placed with the only other document that did not mention the *Declaration* and still supported women's rights, which is the Stanton address. Finally, the Mechanic's advocate article was noted by the program to be negative and was seperated as such.

![Title Image]({{ site.baseurl }}/assets/images/cluster.png "Sarcasm still undetected. Putting in a patent for a Sarcasm-bot.")

---

### Word Cloud
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Word Clouds actually provide no real insight or value to an academic work. They're usually a novelty and can't prove anything yet still appeal to people as some kind of technical marvel. Before I generated the following word cloud I guessed that the center would contain "woman","man", "rights", and "power" and I was unsurprised at the result. But for posterity's sake, here's a word cloud.

![Title Image]({{ site.baseurl }}/assets/images/cloud.png "Were you surprised, though?")




---
{% include nav.html %}
---
