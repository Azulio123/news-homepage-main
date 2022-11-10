## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Toggle the mobile menu (requires some JavaScript)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

1. Marking up everything with the appropriate tags
2. Working down by sections 
    a. Some sections needed to be pieced together, so this part of the process was ongoing and sometimes frustrating!
3. Implementing rows and columns using bootstrap (ongoing fiddling)
4. Applying the most superficial styles (fonts, colors, etc.)
5. Fine-tuning aspects
6. Continually fiddling to fit the eye-balled parameters of the project
7. Troubleshooting the offcanvas drawer navbar menu (I DID NOT have to use javascript)

### Built with

- Bootstrap
- HTML
- CSS
- Mobile First in practice (Although, sometimes I focused more on the desktop design despite knowing better)


### What I learned

Some HTML code I'm proud of:
It took a LONG time to figure out what menu I need to use and how to implement, and on top of that, figuring out the individual settings to override the default Bootstrap settings to get the menu just right.

   <!--   <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
      </button>
      <div class="offcanvas offcanvas-right" tabindex="-1" id="offcanvasRight" aria-labelledby="offcanvasRightLabel">
        <div class="offcanvas-header">
          <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>

      <ul id="drawer-list" class="navbar-nav ms-auto">
         
        <li class="nav-item">
            <a id="drawer-link" class="nav-link" href="#home">Home</a>
        </li>
        <li class="nav-item">
            <a id="drawer-link" class="nav-link" href="#new">New</a>
        </li>
        <li class="nav-item">
            <a id="drawer-link" class="nav-link" href="#home">Popular</a>
        </li>
        <li class="nav-item">
          <a id="drawer-link" class="nav-link" href="#trending">Trending</a>
      </li>
      <li class="nav-item">
        <a id="drawer-link" class="nav-link" href="#categories">Categories</a>
    </li>
    </ul>
      </div>
  </nav>
</div>-->
  

      CSS I am proud of (which is almost all of it):
      Figuring out how to get this to look nice in mobile view, which can be tricky. What is trickier is the breakpoints between desktop to tablet. Tablet view is NOT at all styled or dealt with. Please only view on desktop or mobile. Haha. The tablet-size view is ATROCIOUS. 
      
      I am most proud of the styling I did to fix the offcanvas navbar though. That is simply boring to look at though.
      
            @media only screen and (max-width: 650px) {
    body { 
        padding: 3%;
    }
    
    .main-pic {
        display: none;
    }
    .mobile-pic {
      display: block;  
    }

    footer {
        padding-top: 2em;
    }

    #home { 
        margin-bottom: 3em;
    }
    
    .trending-image {
        width: 12.625rem;
        height: 80%;
    }
}
</div>



### Continued development

2. I am still working on all of this being as accessible as possible. I still need the documentation on screen readers in order to implement them. I am still so confused about how it works that I will have to look at a guide for it.
2. Workflow could be improved. I still tend to go all over the place fixing one small thing and then moving to completely different part of the project and fixing that instead of going completely section by section.
3. Going Mobile first. I need to set up my workflow to focus on mobile view first and foremost.
4. Not messing with padding, margins, and other CSS centering parameters before implementing the skeleton and structure first. I wasted a lot of time getting things to not look like a hot mess by using CSS too quickly to get certain parts to center when their absence did that for me.            

### Useful resources

Bootstrap documentation!
            - I learned a lot about BS5 by reading more and messing around with individual settings. It is ALWAYS a good idea to really get into the nitty-gritty of a               library like this.


## Author

- Frontend Mentor - [@Azulio123](https://www.frontendmentor.io/profile/Azulio123)
- Dev.to - https://dev.to/lavenderliz

## Acknowledgments

My husband has been invaluable once again. He helps me break down problems and lends a hand with anything, even trying things that are outside of the scope of the project. What a chad.
