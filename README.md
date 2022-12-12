
# Horiseon - Improving Website Accessibility  
![](https://img.shields.io/badge/html-HTML5-orange?logo=html5)
![](https://img.shields.io/badge/css-CSS3-%231572B6)
![](https://img.shields.io/w3c-validation/html?style=plastic&targetUrl=https%3A%2F%2Fsenseilein.github.io%2Fchallenge1-horiseon%2F)

## Description

### What is it about?
Horiseon is a marketing agency providing social solution services. They are specialized in search engine optimization, online reputation management and social media marketing.

They requested a review of their website in order to:
1. improve the accessibility aspect of the website
2. refactor the code base

### Why is web accessibility important?

- **Inclusion** Web accessibility ensures that people with disabilities can access a website using assistive technologies (such as video captions, screen readers, and braille keyboards).   
- **Wed positioning** Accessible sites are better positioned in search engines like Google.   
- **Business** It also helps companies avoid litigation that can occur when people with disabilities cannot access their website.

## Usage

### User story

```
AS A marketing agency  
I WANT a codebase that follows accessibility standards   
SO THAT our own site is optimized for search engines
```

```
WHEN I open the web page,   
THEN I can clearly identify its structure using assistive technologies. 

WHEN I click on a link,  
THEN I'm redirected to its associated target.

WHEN I can't see an image,  
THEN I can have access to an alternative text.

```

### Acceptance Criteria
It's done when:  
[] The HTML document includes a `<meta>` description with a `content` attribute.  
[] All the tags are replaced by more appropriate semantic tags when available.  
[] HTML elements follow a logical structure independent of styling and positioning.  
[] Heading elements fall in sequential order.  
[] All non-decorative images and icons contain a descriptive `alt` attribute.  
[] All decorative images and icons contain an `alt` attribute set to an empty string.  
[] All links (anchor `<a>` tags) include a `href` attribute.  
[] All links function correctly.  
[] Application's CSS selectors and properties are consolidated and organized to follow semantic structure.  
[] HTML and CSS files are properly commented.  

### Mock-Up
The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](Assets/01-html-css-git-challenge-demo.png)
 
**Note**: This layout is designed for desktop viewing.

## Technology used
- HTML  
- CSS

**What I've learnt**
- I discovered more `<meta>` and semantics tags to improve the positioning of the web application.  
- I was able to incorporate some CSS variables, providing more readability to the code.

**Suggestions for improvement**
- Review code colour contrast  
- Make the website responsive so that it can be accessed from different platforms

## Installation
No installation needed

## Credits
- This project was made as part of a coding assignment with [Trilogy Education Services](https://skillsforlife.edx.org/?utm_source=govuk)   
- [W3C](https://validator.w3.org/) for markup and CSS validity  
- Useful website for accessibility related info by [CanAdapt Solutions](https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html)

## License 
© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
