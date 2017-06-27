## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

### Getting started

**1.** Clone the repo to your local machine

**2.** Change to dist folder

**3.** Install ngrok here (install python before this if not installed )

**4.** Launch a local http server to test.

```
$ python -m SimpleHTTPServer
```

**5.** In the same directory, run  ```./ngrok http 8080```

**5.** Copy the public URL given by ngrok from the terminal window and paste it into your browser to view the site.


#### dist ####This folder contains optimized files
#### src ####This folder contains original files

### Part 1: Optimize PageSpeed Insights score for index.html

* Minified "style.css"
* Minified "perfmatters.js"
* Add "Async" attribute on all JS  script tags
* Removing print media attribute and addinng it externally.
* Optimize and resize images
* Minified index.html

### Part 2: Optimize Frames per Second in pizza.html

* Replace querySelector with getElementById
* Append elements to DocumentFragment first then finish by adding that to the DOM
* Resize and optimize pizza picture and remove style.height and style.width change
* Use requestAnimationFrame on scroll event
* Cut down amount of background pizzas from 200 to 36
* Optimized For loop with iterating in reverse order
* Optimizing Images, CSS and JS files
