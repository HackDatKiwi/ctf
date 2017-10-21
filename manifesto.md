# CTF Manifesto


In this document, we intend to explain some points for CTF organizers. It is our accumulated experience over 10 years of running local and global CTFs, participating in thousands of others CTFs in person or online, and learning in the process.


## Challenges

People do CTFs for multiple reasons. Our polls show that the most common reasons are to "Learn new hacking skills" and to "Have fun while doing something technical", with an emphasis on former.

If people just wanted to have fun, they'd watch a movie or play video games. If they just wanted to learn, they'd watch tutorials or read books. They want to learn cool things in a competitive environment working as a team. If you want to give them a good experience, then you have to fascilitate for these metrics.

### No puzzles

People are not there to guess your puzzles. They are not there to throw themselves at a blank webpage until they find your obscure URL and hack you. They are not ants.

Sure if you create a full-puzzle challenge, those who solve it will be happy. But there would be no correlation between technical skills and results, and thus you'd only appease the persistent user rather than the technical user.

Don't do puzzles. A little puzzle is OK, particularly when it's very limited in scope and the user knows exactly what he needs to do, but more than that is not.

Puzzles are also a sign of non-technical challenge designers. If you are not in the cutting-edge of security, your challenges will be known by others. They will be easily. You'd resort to puzzles to make them hard. You are making them hard by hiding them, not by making them challenging. And players notice that. They realize that you are not good, and thus your CTF is not good. They will leave with a sour taste in their brain-mouths.

So don't do puzzles. You are not making a good CTF with puzzles. If you can't think of creative challenges, then just don't run a CTF. You don't have to, if it's not fun and educating.

### Educate people

If you create typical SSRF challenges, some are gonna solve it, some are not. Some of those who are unable to solve it might learn, but they'd be negligible. You are not teaching anyone anything, those who know it will enjoy themselves and those who don't will be pissed, not knowing what they don't know.

However, if you create a new means of exploiting SSRF, or even SQL Injection, with some creative new technique, then you're teaching that to people. Everybody would love that, assuming they figure it out and solve it.

### Clearly state the purpose

Yes, we realize that in a CTF, the goal is to hack the appliaction. But the distinction is, in the real world, you know what you want to get out of a hacking attempt. You want the users. You want the data. You know what you want, you are not just randomly trying to hack a system, without even knowing what you want.

State what the goal of the challenge is. You don't have to be imperative, don't explain the steps, but explain the goals. "This is a web application in which we need to obtain administrative access". That's good. So now they know breaking authentication is the ultimate goal.

### Provide as much source-code as possible

In real-world scenarios, source code is usually not available. We all get that. But in real-world scenarios, nobody hacks 25 systems in 48 hours. 

People can't figure out the complete behavior of the black-box system. Either provide the source-code upfront, or make your challenge in a way that source-code can be leaked (error messages, other creative means).

It's OK and fun to have some black-box functionality, but limited in scope and completely known to the user that they have to reverse engineer the behavior and then break the system.

Reading source code is educational. People love to read code and figure out bugs. They love to understand the system, then try to figure out its quirks. They find things in your source code that you couldn't even think or dream of.

### Don't separate the source code from the challenge

If you want your challenge source code to be available, add a few lines inside the challenge to leak itself. Don't put a separate file as the source code.

Why? Because you'd patch the challenge in the middle of the CTF, and then forget to patch the separate source code, just confusing the users.

True, you need some parts of a challenge to be hidden. Flag is one of them. Some of the logic is one of them. Put them in a separate file, and don't let your leaking mechanism leak them. But don't duplicate your files, that's a recipe for disaster.

### Use different technologies

Part of the learning process is seeing different languages, different coding styles, different vulnerabilities. If limited people designs challenges, their imprint will be all over everything. They think the same, they code the same. Create things outside yours, and your users comfort zone. They'll love it.

## The CTF

### High availability

### No AJAX!

### Lightweight portal

### Teams

### Scoreboard

### Writeup



