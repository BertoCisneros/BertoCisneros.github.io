## AI Pair Programmer Breakdown
Coding CoPilots like GitHub CoPilot, TabNine, and Kite are tools developers can use that automate the coding process. These tools use artificial intelligence to autocomplete your code based on your projects existing code, context given by commented code, and public or stored code from its users. In this blog I will be focusing on GitHub CoPilot.

The AI Programmer with the most notoriety by far has been **GitHub CoPilot**. On June 29th, 2021, GitHub announced a technical preview of the CoPilot. What GitHub CoPilot aims to achieve is to "help you write code faster and with less work". The tool is available for a direct install as a plug-in/extension into your choice of one of its many compatible IDE's but you will not have access to the tool as there is a waitlist (use the link in sources if interested), but once approved you can sign in with your GitHub account to have access. It is currently free as it’s only a technical preview, but GitHub plans to release a full paid version in the future.

### OpenAI
GitHub CoPilot is powered by OpenAI Codex which is a descendant and improvement of GPT-3. GPT-3 is a neural network machine learning model using internet data to generate diferent types of text. One example of its uses have been to write blog posts. A college student used GPT-3 to write this blog post [Feeling unproductive? Maybe you should stop overthinking.](https://adolos.substack.com/p/feeling-unproductive-maybe-you-should?s=r). Also, OpenAI has had 1 billion dollars funded by Microsoft and was Co-Founded by Elon Musk. 

### My Experience
I actually enrolled in the Github CoPilot waitlist months ago and have had a few days to play around with the tool at the time of writing this blog. Take my experience though with a grain of salt as I’ve had limited time with the tool and I'm a student and don't currently have a developer position with an employer. 

I tested the CoPilot in two ways. 

First, I began working on one of my incomplete projects which happened to be a website. This project has been built up by a framework and has thousands of LOC and a decent amount of work done on it. So, I assumed that would be enough context for me to experience the CoPilot, but I was wrong. The issue was that I was working with html and although GitHub CoPilot states that it can be used for a wide range of languages and frameworks; it does work better with certain ones. HTML is not one of the languages it works well with. Even though there was plenty of context, it did a poor job of suggesting much that was useful outside of making a button or other small insights. Which I’m not complaining because HTML isn't my forte and it can be tedious, but in this context the CoPilot was basically a step above auto complete features that exist.

Second, I decided to test the CoPilot with one of the languages it excels in, and I chose python. I have almost no experience with python, but I could understand it enough to do some very easy leetcode/interview coding questions. So, to test I began going through different leetcode problems on varying difficulty to see what it could do. I would take the question prompt and paste it into my IDE and comment it all out. All I needed to do next was make a relevant function name and **boom** it gave me a full function to use if I just hit `tab`. I tried this on varying degrees of difficulty, and it usually accepted the answer with all testcases leetcode had for the prompt. One thing to note is as the prompts got harder, it was pretty difficult to decipher what the function was doing but it usually worked.

Does that mean I can write python code? Apparently, I can. 

Can I consider myself a python dev? Definitely not. 

## Should Developers Fear or Embrace the CoPilot
With the emergence of this new tool, it begs to ask several questions.

- **Will this make me more efficient as a developer?**

There is a common narrative amongst developers that a big part of being an efficient developer is being an efficient 'googler'. While we must admit that googling itself can be too much of a crutch at times, it is often much faster to look on stack overflow for a quick fix. Not every line of code or function needs to be given 100% of your attention and years of refined coding skill. Some things just need to barely get the job done and that’s fine. Stack overflow and other sites help to serve that exact purpose, but here's where it starts to get a little bit different with these AI CoPilot's. At times working with this tool did feel like too much of a crutch. With resources like stack overflow, they at least cultivate the process of reading other people's code or explanation's and you can walk away with a better understanding of why your code failed to work. With the CoPilot you are spoon fed entire functions at a time. These functions can be complex and hard to understand but sure enough, it usually works. 

On one hand you could say you accomplished your tasks for the day that much faster, which isn't that efficiency is all about? **But** on the other hand you walk away not really learning anything. So, in the long run, you as a developer are not becoming more efficient and refining your skills because the tool can be too much of a crutch. 

- **Has AI begun to work its way into replacing jobs of developers?**

When it comes to certain industries, AI has taken on the role of the boogeyman coming to take jobs. An obvious example of this is Wal-Mart's move to self-checkouts over cashiers. "Retail has lost more than 140,000 jobs since January 2017 and is still declining despite strong growth in nearly every other sector and a historically-low unemployment rate" (BizJournals.com). With that many jobs lost, it is a pretty serious concern, but should developers be worried? A key point of these tools is right in the name, **CO**-pilot. For what the tool is right now, it cant be operated without a developer being the pilot and choosing what code is useful from the CoPilots suggestions. But, with the AI heavy hitter that is OpenAI then who knows wwhat could happen in the coming decades. 

- **Is my private code safe since the AI will be learning from it?**

I believe this question will be one that will be the most prevalent in the coming years. GitHub CoPilot does use telemetry which is the process of recording and saving the code you write(in this context). The GitHub CoPilot page gives the usually speel about data that most comanies give in that its stored, secure, and only has human eyes on it when necessary. 

There is one concerning answer GitHub offered from FAQ about privacy. 

> Does GitHub Copilot ever output personal data?
Because GitHub Copilot was trained on publicly available code, its training set included public personal data included in that code. From our internal testing, we found it to be extremely rare that GitHub Copilot suggestions included personal data verbatim from the training set. In some cases, the model will suggest what appears to be personal data – email addresses, phone numbers, access keys, etc. – but is actually made-up information synthesized from patterns in training data. For the technical preview, we have implemented a rudimentary filter that blocks emails when shown in standard formats, but it’s still possible to get the model to suggest this sort of content if you try hard enough.

While it is rare, it is possible to have personal data appear. With this, I wonder if CoPilot is something employers would forbid there developers to use. It doesn't really seem worth the risk. 

- **Will it always write good quality code?**

The answer to this one is simple. No. It can provide impressive results but it doesnt always work in rare cases provides gibberish. 

## Conclusion

In conclusion, I honestly think GitHub CoPilot is a really cool concept and could be extremely useful. Just like with anything in life, it would need to be used with moderation. You can't really blame the tool because you use it too much and get lazy. On the otherhand, I do think it could be a big concern for students. If I would have had this tool as a freshman or sophomore, a lot of my assignments would have been much easier and I would have been worse off for it. All the AI pair programmers are still in their infancy but it will be exciting to see how they grow, and I doubt it will be without controversy. 

### Sources
[GitHub CoPilot](https://copilot.github.com)

[TabNine](https://www.tabnine.com)

[Kite](https://www.kite.com)

[BizJournals - Self-checkouts contribute to retail jobs decline](https://www.bizjournals.com/bizwomen/news/latest-news/2019/04/self-checkouts-contribute-to-retail-jobs-decline.html?page=all)

[Feeling unproductive? Maybe you should stop overthinking.](https://adolos.substack.com/p/feeling-unproductive-maybe-you-should?s=r)


