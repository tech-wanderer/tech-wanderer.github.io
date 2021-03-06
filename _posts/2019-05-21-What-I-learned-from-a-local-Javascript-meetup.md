---
published: true
---

I went to a local Javascript meetup this week. There were two talks: one on functional programming and the other on SVGs.

Below are some key things that I learned:

- There are different programming paradigms. The two that were emphasised the most in the talk were functional and procedural programming. Functional programming involves the use of "pure" functions. Pure functions are functions that will return the same output if they are given the same input. They are not changed by global or local states. Functional programming has all programming code within functions. Procedural programming is based around statements and follows a "top-down" approach. 

- Currying is a technique used in functional programming. Currying's namesake is Haskell Curry. It involves turning a function that can take multiple arguments into a series of nesting functions. 

- It is possible to create SVGs in html code. There were some very detailed SVGs shown. I created a rectangle and circle when I got home. I have included the code and an image of the browser output below. 

```html
<!DOCTYPE html>
<html>
        <svg>
                <rect height="200" width="450" fill="blueviolet" />    
        </svg>
        
        <svg>
                <circle cx="100" cy="100" r="50" fill="blue" />    
        </svg>
</html>
```

![]({{site.baseurl}}/images/SVGs in browser.JPG)

I hope to develop my understanding of programming paradigms and SVGs further in the future.
