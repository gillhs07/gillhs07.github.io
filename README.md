# WAPH-Web Application Programming and Hacking

## Instructor: Dr. Phu Phung

## Student

**Name**: Arpit Gill

**Email**: [gillhs@mail.uc.edu](mailto:gillhs@mail.uc.edu)

**Short-bio**: I like burritos and coding or something.

![Arpit's headshot](https://media.licdn.com/dms/image/v2/D4E03AQH418VjrmMFMQ/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1705716772295?e=1782345600&v=beta&t=V7v5TDKy3m32QgZhzkaH9ITBnJDCEx7vFnlne-wLKy8){width=150px}

## Project overview

Project folder link: https://github.com/gillhs07/gillhs07.github.io

Website link: https://gillhs07.github.io/

This project allowed me to learn about coding a front-end website. I was able to learn basic HTML, Javascript, and CSS. I also learned more modern frameworks, including the Jquery and Alpine for javascript and bootstrap for css. I also learned more about "under the hood" stuff that I don't really think about when using a website, like using cookies and using APIs. The end result was a decent looking portfolio website incorporating many different things that we've learned in the class.

## Tasks

### Non-technical requirements

I started off my project by picking out a boostrap template that I liked. This became the core of my webpage. I took the template and then changed around things as I needed to and kept that template in mind going forward, reusing components and ideas and not deviating much from how the template structured things. This allowed me to keep a clean looking page with consistent code and not radically change how the template looked. 

The page tracker was a lot simpler than I thought it would be to implement. I simply went to the flagcounter website, proceeded with a few steps, and then pasted the code inside my code. I then had an issue with it not displaying properly and eventually realized it was because my adblocker was blocking the contents from displaying, so after pausing the adblocker for my page everything worked as intended.

### General requirements

I took the template I'd copied and then added my personal details. I kept the template mostly the same when doing this but the big thing I changed was making my headshot centered instead of on the right like it was on the template. I thought it looked better because a really large photo on the right side looked weird and a really small one looked unbalanced.

I was able to add a button to the navbar at the top linking to the waph.html page that I had added to the repo..

### Technical requirements

I used Alpine and Jquery to implement the clocks, email, and guess age functionality. I would have just gone with Jquery but since we had to use another one I went with Alpine because I heard it was easy and its lightweight enough to just import with a script tag like Jquery and not needing additional install (which is why I didn't go with React).

I added the APIs and kept them pretty similar to the stuff we made in lab. I just had to change how they were implemented in the page to stay in line with the bootstrap template. For the graphic API I went with the dog api because there was no sign up or anything like that and I don't know I just liked the idea of a cute dog picture on the site.

The Javascript cookie functionality was probably the only difficult part of this lab because I haven't experiemented with that at all before. I went mostly with whatever I saw online to guide me in making the cookie and modifying it to track the last time the person visited the site.