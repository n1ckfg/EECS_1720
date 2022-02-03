# EECS_1720

commits made while instructing EECS 1720 - Building Interactive Systems (winter 2022) (course @York University, Canada)

---

## what's new

### As of `post-lecture` Feb 3

A reminder that all code developed and demoed during class will be updated in the folder `live_code` available in this repo. Note that it will be `live` so you can copy-paste immediately, but that the content itself might be organized or rearrange after lecture.

The code will remain in `live_code` until the next lecture - at which point it will be moved to the `Content_by_Topic` and `Content_by_Week` folders so that our `live_code` folder can be emptied and ready for the next lecture's code content.

**Specifically:** video files of any live code will be made available ASAP (I have to wait for zoom to send me a 'recording is ready' notification - then I can grab, edit if needed, and share the file). Videos will be available either directly from zoom (if there is no need to edit) otherwise they can be found in our Lecture_Videos drive and/or eClass

---

### As of Feb 3

1. In response to feedback from our questionnaire content will now be arranged by both:
   - Topic
   - Week
   
   The content will be the same - just organized differently, so, depending on your preference, you can look content up by topic (python, JavaScript, lecture notes etc.) or by week (follows the course syllabus regarding content)

2. I have also added some clarification in past files regarding what is for advanced students and not for those just starting. Moving forward I will indicate during lecture and in any lecture notes where the content diverges and depending on if we are doing a `deeper dive` or `just starting`, you will know within what context we are working and can tune out or tune in accordingly (but keep playing with the code in either case!). 
   - Digital Media is always a mix of people often with large differences in kind and type of knowledge and experience
   - it is _expected_ that you will have different skills
   - it is _expected_ that you will learn at different paces
   - you are expected to improve _as compared to yourself_ (and not other students!)

3. Since we are now all setup with repo's and have some familiarity working with code files and folders - lectures will start exploring, in much more detail, the aspects of `sound`, `image`, and `interaction` _directly into `live code` examples_ where students are expected to follow along `actively`. This process will be worked from both processing.py (python mode in processing v3) and carried into JavaScript with p5.js. This will let us compare the codes, and, because of the direct connection to the processing framework, both languages will maintain very similar structure, function names, and reference points. Now we can start exploring the underlying patterns in our code's logic, output, and general form. 

4. We will generally always see content within a processing context, so processing.py / python mode in the `PDE` (recall: [P]rocessing [D]evelopmet [E]nvironment) when working with python, and p5.js when working with JavaScript. When working through code in the p5.js context, any `index.html` files required for the JavaScript examples will be identical other than changing the name of the `sketch.js` file if we are using more than one. Any libraries will be provided or direct instructions on how to load or add them will be mentioned.

5. We will at times develop (individual pace) both `python` and `JavaScript` content outside of `processing`. Some of our python exploring will be done as individual `.py` files, and more and more of our JavaScript exploring will be extended beyond p5.js.

---

### As of Jan 27

Files and folders are updated.

1. docs/ contains
   - our `.md` files that you should _probably (definitely)_ look at

2. JavaScript/ contains
   - ~~extension sample code (Lab 1)~~
   - three working examples of where to `JavaScript-in-HTML`

3. processing/ contains
   - p5js/
     - stand-alone local browser example
   - python-mode/
     - python version of supplied p5js example

4. misc/ contains
   - some additional `txt` files for installation help (incomplete for all `OS` but will be updated when and if we need to)
   - an `img` folder to collect found content (don't worry if it's important it won't stay in the misc folder)
   - weekly updates otherwise not found in `docs/`
     - (where those `.md` files that _you should probably look at_ reside)

5. demos/ contains
   - extension sample code (Lab 1)
     - with `HTML`
     - with `HTML` _and_ `JavaScript`

---

### Old (and maybe no longer relevant)

- live content will be cleaned, edited, and described in logfile and code comments each week
- don't worry about the GitHub CLI (command line interface) files.. we will look at git and/or gh during Week 2
- it's there if you're interested though

> course syllabus with updated due dates is now available
>>
> browser extension demo is in .. extension-demo/
>>
>> Be sure to check additional info in extension-debugINFO.md
>>
>> recall the different ways to -> chrome://extensions or about:addons
>> more in-depth version will be in .. more-extension-demo/
>>
> python mode for processing is in PYTHON/
>>
>> you should have already installed processing from 1710 - if not instructions are in the folder
>> for now we will run and edit python sketches from within the Processing Development Environment (PDE)
>>
> p5js for processing is in P5JS/
>> this is a bit more work to set up as we will run our own http-servers
>> for now you can copy the sketch code into the p5.js editor on the website and start playing around
>> if you really want to get into the self-serve .. there are some instructions included in the folder

---
---

## If you are interested

This README file is formatted with [Markdown](https://www.markdownguide.org/basic-syntax/) :)

---

### Occasionally I update these web references

(but web references are often only added to our `.md` files found in `docs/`)

- (yes the `.md` files _you should probably look at_)

<https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax>

<https://github.github.com/gfm/>

<https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github>

<https://www.theserverside.com/answer/Git-fork-vs-clone-Whats-the-difference>

<https://py.processing.org/tutorials/gettingstarted/>

<https://p5js.org/get-started/>

<https://github.com/processing/p5.js/wiki/Local-server>
