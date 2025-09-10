<!-- 
### Core systems

**Topics covered**:
`procedural programming`
`manual memory management`
`boolean algebra`
`gate logic`
`memory`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`
`compilers`
`operating systems`
`network protocols`
`and more`

Courses | Duration | Effort | Additional Text / Assignments| Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--: | :--:
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alt](https://www.nand2tetris.org/)) | 6 weeks | 7-13 hours/week | - | C-like programming language | [chat](https://discord.gg/vxB2DRV)
[Build a Modern Computer from First Principles: Nand to Tetris Part II ](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | - | one of [these programming languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), From Nand to Tetris Part I | [chat](https://discord.gg/AsUXcPu)
[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week | - | Nand to Tetris Part II | [chat](https://discord.gg/wZNgpep)
[Computer Networking: a Top-Down Approach](http://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)| 8 weeks | 4–12 hours/week | [Wireshark Labs](http://gaia.cs.umass.edu/kurose_ross/wireshark.php) | algebra, probability, basic CS | [chat](https://discord.gg/MJ9YXyV)
👋 OS Course: https://ops-class.org/slides/

[[Video] CS 15-213 CMU Introduction to Computer Systems (CS:APP)](https://scs.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx#folderID=%22b96d90ae-9871-4fae-91e2-b1627b43e25e%22)

[[Video] Berkeley CS 162 Operating Systems](https://www.youtube.com/watch?v=hry_qqXLej8&list=PLRdybCcWDFzCag9A0h1m9QYaujD0xefgM)

[Operating Systems: Three Easy Pieces](https://pages.cs.wisc.edu/~remzi/OSTEP/)

Bradfield CS Software Systems: Behind the Abstractions

[[Video] Threading Tutorial #1 - Concurrency, Threading and Parallelism Explained & Python 3 Tutorial](https://www.youtube.com/watch?v=olYdb0DdGtM&list=PLzMcBGfZo4-lTUl-4m1-9Jk27Eulyrmkx&index=1)

MD5 COLLISIONS/PREIMAGE 1st 2nd: https://crypto.stackexchange.com/questions/1173/what-are-preimage-resistance-and-collision-resistance-and-how-can-the-lack-ther
A collision is, given a hash function, come up with two documents with the same hash, but you can control both documents. A (first) preimage attack if, given a hash function and just a hash (output), find the document (input). A (second) preimage attack is, given a hash function and one document, find another document with the same hash. 

MD5 collisions are totally broken and can be generated in seconds if you are allowed to control the contents of the 2 documents.

First and Second preimage attacks are still practically infeasible for MD5, and even the same for older hashing algorithms like MD4.
https://stackoverflow.com/questions/8860512/whats-the-difference-between-collision-resistance-and-preimage-resistance/8860704#8860704

in pre-image attack, you are only leaking the hash H to the attacker, whereas in the second-preimage attack you are giving away both message m and the result of H(m). In both cases, the attacker has to find message m prime which will produce the same hash.

Capacity to Ship Packages - Leetcode 1011 - Python
Neetcode
https://www.youtube.com/watch?v=ER_oLmdc-nw
I think its worth explaining why Binary Search actually works in this case, and the reason is that our "canShip" function is monotonic, which means if we found some weight that doesn't fit, it for sure means that every weight below that also won't fit, and same for if we found a weight that fits, no need to check any values above that weight.

Also there is no reason to set res = min(res, cap), it is enough to just set res = cap, since it will always update it if we entered that if, again because of the monotonic attribute.

https://lively-banoffee-a7bd63.netlify.app/#three this guy's ExpressPOS is nb

OS Course Lectures: https://ops-class.org/slides/
 -->
# Hello, I'm William 👋
## [Click to View My Personal Site](https://williamchan.surge.sh)
- 🤖 Programming since 2020.
- 🦢 I love aesthetic websites- I enjoy getting into the nitty gritty details of website design.
- 💻 Frequently using: `.py`, `.js`, `.jsx`, `.html`, `.css`

---
<!-- 
 Please ignore this messy page- it's for personal reference
# personal notes: main: 
ADD GIFS TO README for each project [Resource](https://josephcardillo.medium.com/how-to-add-gifs-to-your-github-readme-89c74da2ce47) use [gifcap](https://github.com/joaomoreno/gifcap)
1409 889 edge browser equal spacing capture cloudinary cdn

design a portfolio site like [this](https://bennymeier-media.vercel.app/projects)
-->
## My Web Projects
<!-- #### Crème de la crème (the good ones) -->
##### Solo Projects
- [Spotifree](https://spotifree.app/search), like spotify, beautiful UI and totally free and search any song; made w/ React, Redux
- [YoutubeDLNow](https://youtubedlnow.vercel.app/home), store and download any youtube video or audio, mp4 and mp3 files; made w/ React, Firebase, Node.js
- [CalendarThings](https://calendar-things.vercel.app/calendar), a sleek minimalistic calendar todo list; made w/ React, Firebase
- [Vanilla JS Calculator](https://wc2184.github.io/oldstuff/calc.html), just a calculator; made w/ Vanilla JS
- [SortAlg](https://wc2184.github.io/SortAlg), a sorting algorithm visualizer; made w/ Chart.js


##### Group Projects
- [MailMe](https://mailmeaa.herokuapp.com/), like mailchimp, send out any email and create email lists; made w/ React, Redux, Node, MongoDB
- [WorkOrPay](https://www.envariable.com/), Deposit money and set a goal, do it or we keep your money; made w/ React, Firebase, Node.js
<!-- 
- [WorkOrPay](https://www.workorpay.com/), Deposit money and set a goal, do it or we keep your money; made w/ React, Firebase, Node.js 
-->

##### My Other Work (just for fun, less time involvement)
- [Bitcoin Hash Target Calculator](https://wc2184.github.io/oldstuff//targetfinder/index.html), find how hard the latest bitcoin block mine was; made w/ Vanilla JS
- [Easy NYU Covid Screener](https://wc2184.github.io/oldstuff/pass.html), covid screener without needing to login; made w/ Vanilla JS
- [Vanilla JS Todo App](https://wc2184.github.io/oldstuff/todolist.html), simple todo list; made w/ Vanilla JS
- and [others... ](https://github.com/wc2184/wc2184.github.io)

<!-- 
#### Planned
- something basic, like a [qr code generator with a minimalist sleek ui](https://hovercode.com/)
- Design inspo: I want to do something like https://github.com/eightants/reddium/ real good something like this for a diff site 
- just an idea, scan qr code with phone then phone acts as a controller for the game that updates live on the browser. make a quick gif on the demo to show for recruiter  (STEVE KRUG DONT MAKE ME THINK)
- [Minimalist design inspo Makerpad.co](https://www.makerpad.co/)
- [AI Lecture](https://karpathy.ai/zero-to-hero.html)
- [Subarray vs Substring vs Subset vs Subsequence](https://quanticdev.com/algorithms/primitives/subarray-vs-substring-vs-subsequence-vs-subset/)
- [DP](https://quanticdev.com/algorithms/dynamic-programming/staircase-problems/)
-->
<!-- - ~~pdf uploader? leetcode spaced repit w/ seqeliz? workorpay in footnotes as abandoned. ecommerce site w/ stripe. fastapi python back~~ -->


<!-- - Not seeking job.
- 👀 My all time favorite language is JavaScript, and my favorite library/framework is React. 
- 🎖️ My main focus is frontend programming. 
- 🦢 I love aesthetic websites- I enjoy getting into the nitty gritty details of website design.
- 🥪 I also do backend programming with Node/Express, Firebase, and others... but I am most proficient in React. 

 ⏱️ Recently worked on: 
- 🔨 https://www.WorkOrPay.com (Mostly to learn how to build a full stack website)

  WorkOrPay lets you be held accountable to your goals by putting down money. Set goals. Form contracts. Pay the penalty if you fail. Accountability with dollars on the line. -->
<!---
wc2184/wc2184 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
