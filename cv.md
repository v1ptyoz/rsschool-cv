# Aleksandr Khrabrov
Junior JS-developer
___
**Contacts:**
1. E-mail: [v1ptyoz@gmail.com](mailto:v1ptyoz@gmail.com)
2. Telegram: [@khrabrovav](https://t.me/khrabrovav)
___
## About me
Hello everyone! As your understood - my name is Aleksandr, and I'm a junior JS-developer.
Programming has a most important place in my life. I like to automate everything in my work.
Also, I like to write a programming code. So, I'm learning some programming languages for five years.
But, only with a Javascript I decided to change my life and become a programmer.
Next, I'll tell you about my skills and projects.
___
## Skills
Now, my skills in **HTML**, **CSS** are very well.
I know about semantic in **HTML**, and trying to use special semantic tags in my work.
In **CSS** I know about boxing model, positioning, vendor-prefixes for different browsers and so on and so forth.
Also, I know about instruments, which help us to write less code, or do our coding process more nice.
I talk about HTML template engines like **PUG**, about CSS preprocessors, like **SASS** and **LESS** and more other instruments,
like **gulp** and **webpack**, with its rich plugins' library.

In native Javascript I know all about variables, functions, classes, hoisting and built-in methods for any variables.
Of course, it is too many methods and no way to remember all of it.
But with a practice all of it is automatically remember.
Also, I know about Document Object Model and browser events.
Of course, I know about some libraries like JQuery.
But I don’t like jQuery. Why we are using it, if there is we can write more expressively code with ES6?

And of course, I know some graphic editors, like Photoshop and Corel Draw,
and instruments for layout and design, like Figma and Sketch.
Also, In my work I'm using GIT and Visual Studio Code editor and PHPStorm IDE.
___
## My projects
###### All of my projects can be found [on my GitHub](https://github.com/v1ptyoz/). Here is one of them.
[Tabs on JS](https://github.com/v1ptyoz/JSTabs).

It is a small library for tabs on your site. Let's look to my code:
* First, the *info* variable is a wrapper for all tabs. As you see, *tab* and *tabcontent* are collections for a
  tab, where we're clicking and content, which will be showing after click. So, you need elements with classes: *info-header-tab*,
  *info-header* and *info-tabcontent*. Or you can use your own classes, just renamed it in the code.
    ```javascript
    let tab = document.querySelectorAll(".info-header-tab"), 
        info = document.querySelector(".info-header"),
        tabContent = document.querySelectorAll(".info-tabcontent");
    ```
* Before next step, you need CSS-classes with name *show* and *hide*.
  In my project this classes has code:
  ```css
    .hide {
       display: none;
    }
    .show {
       display: block;
    }
    ```
* Then we are hide all content in all tabs and showing only first tab via function *hideTabContent*.
  ```javascript
    function hideTabContent(a) {
        for (let i = a; i < tabContent.length; i++) {
        tabContent[i].classList.remove("show");
        tabContent[i].classList.add("hide");
        }
    }
    hideTabContent(1);
  ```
* The function *showTabContent* just toggle *show* class. I won't describe it here.
* Finally, using event delegation, I am create a click handler.
  ```javascript
  info.addEventListener("click", function(event) {
  let target = event.target;
  if (target && target.classList.contains("info-header-tab")) {
      for(let i = 0; i < tab.length; i++) {
          if (target == tab[i]) {
              hideTabContent(0);
              showTabContent(i);
              break;
              }
          }
      }
  });
    ```
More project [on my GitHub](https://github.com/v1ptyoz/)
___
## Courses
I really love to study. Last year I'm ending courses "HTML and CSS Basics" and "Web development for beginners"
with a top rate. Now, I am studying on the Rolling Scope School and planning to finish it on top rating.
___
## Languages
1. Russian - native
2. English - B1+ (as I think). When I wrote text for this site, I am using translator just five or seven times.
