### AirBnB clone - Web static

<p align="center">
    <img [AirBnB clone - Web static] src="">
</p>

----------

# <p align="center">AirBnB clone - Web static</p>

----------

## ➤ Menu:

* [➤ Description]()
* [➤ Console]()
  * [➤ Install]()
  * [➤ Execute]()
* [➤ Files description]()
* [➤ Tests]()
* [➤ Commands]()
* [➤ Resources]()
* [➤ General]()
* [➤ Requirements]()
* [➤ Authors]()
* [➤ License]()

----------

## ➤ Description:



----------

## ➤ Resources:
Read or watch:

* [Learn to Code HTML & CSS (until “Creating Lists” included)](https://intranet.hbtn.io/rltoken/9P868D9X6hKF-iPeuTjUMA)
* [Inline Styles in HTML](https://intranet.hbtn.io/rltoken/3w80rVNNceP13m7D52ma3Q)
* [Specifics on CSS Specificity](https://intranet.hbtn.io/rltoken/miNTDX58opEBx0EbOWPySw)
* [CSS SpeciFishity](https://intranet.hbtn.io/rltoken/sOpKz-qSh9sD3tEcidcgDw)
* [Introduction to HTML](https://intranet.hbtn.io/rltoken/Jrc0YlYYAry_aRJBZB5v2Q)
* [CSS](https://intranet.hbtn.io/rltoken/mq0A1qZJs8J0SE5xyxODzg)
* [MDN](https://intranet.hbtn.io/rltoken/8AWCJcUwO2UK5FFUb7G-iw)
* [center boxes](https://intranet.hbtn.io/rltoken/CWYMpBgaImw4SPgfibG2eQ)

----------

## ➤ General:

* What is HTML
* How to create an HTML page
* What is a markup language
* What is the DOM
* What is an element / tag
* What is an attribute
* How does the browser load a webpage
* What is CSS
* How to add style to an element
* What is a class
* What is a selector
* How to compute CSS Specificity Value
* What are Box properties in CSS

----------

## ➤ Requirements:

**General**

* Allowed editors: vi, vim, emacs
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should be W3C compliant and validate with W3C-Validator
* All your CSS files should be in styles folder
* All your images should be in images folder
* You are not allowed to use !important and id (#... in the CSS file)
* You are not allowed to use tags img, embed and iframe
* You are not allowed to use Javascript
* Current screenshots have been done on Chrome 56 or more.
* No cross browsers
* You have to follow all requirements but some margin/padding are missing - you should try to fit as much as you can to screenshots

**More Info**

![Concepts](https://s3.eu-west-3.amazonaws.com/hbtn.intranet.project.files/concepts/74/hbnb_step1.png)

----------
<details>
<summary> ➤ Tasks:</summary>

### 0. Inline styling

Write an HTML page that displays a header and a footer.

Layout:

* Body:
 * no margin
 * no padding
* Header:
 * background color #FF0000 (red)
 * height: 70px
 * width: 100%

* Footer:
 * background color #00FF00 (green)
 * height: 60px
 * width: 100%
 * text Holberton School center vertically and horizontally
 * always at the bottom at the page

* Requirements:

* You must use the header and footer tags
* You are not allowed to import any files
* You are not allowed to use the style tag in the head tag
* Use inline styling for all your tags

![medias](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/939d6b9448e63776610d05d2226aa8985209ee4d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240315%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240315T084513Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0891bb3792eae5d917daaa6c6c1ed7eef99e51ccc1659e08aa4b6cdf886f74d4)


Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 0-index.html
Please review your task manually with the following checklist
 
### 1. Head styling

Write an HTML page that displays a header and a footer by using the style tag in the head tag (same as 0-index.html)

Requirements:

* You must use the header and footer tags
* You are not allowed to import any files
* No inline styling
* You must use the style tag in the head tag

The layout must be exactly the same as 0-index.html

Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 1-index.html

Please review your task manually with the following checklist

### 2. CSS files

Write an HTML page that displays a header and a footer by using CSS files (same as 1-index.html)

Requirements:

* You must use the header and footer tags
* No inline styling
* You must have 3 CSS files:
 * styles/2-common.css: for global style (i.e. the body style)
 * styles/2-header.css: for header style
 * styles/2-footer.css: for footer style

The layout must be exactly the same as 1-index.html

Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 2-index.html, styles/2-common.css, styles/2-header.css, styles/2-footer.css

Please review your task manually with the following checklist

### 3. Zoning done!

Write an HTML page that displays a header and footer by using CSS files (same as 2-index.html)

Layout:

* Common:
 * no margin
 * no padding
 * font color: #484848
 * font size: 14px
 * font family: Circular,"Helvetica Neue",Helvetica,Arial,sans-serif;
 * icon in the browser tab

* Header:
 * background color: white
 * height: 70px
 * width: 100%
 * border bottom 1px #CCCCCC
 * logo align on left and center vertically (20px space at the left)

* Footer:
 * background color: white
 * height: 60px
 * width: 100%
 * border top 1px #CCCCCC
 * text Holberton School center vertically and horizontally
 * always at the bottom at the page

Requirements:

* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 3 CSS files:
 * styles/3-common.css: for the global style (i.e body style)
 * styles/3-header.css: for the header style
 * styles/3-footer.css: for the footer style

Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 3-index.html, styles/3-common.css, styles/3-header.css, styles/3-footer.css, images/

![Zoning done!](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/101096090ff2b87a86083d61789d597774400d5d.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240315%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240315T084513Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d2d8d473cfa75f34fe4b8f78e61b7c6551a8ad297ecf04c9553c258c35b7d146)

Please review your task manually with the following checklist

### 4. Search!

Write an HTML page that displays a header, footer and a filters box with a search button.

Layout: (based on 3-index.html)

* Container:
 * between header and footer tags, add a div:
  * class name: container
  * max width 1000px
  * margin top and bottom 30px - it should be 30px under the bottom of the header (screenshot)
  * center horizontally

* Filter section:
 * tag section
 * class name filters
 * inside the .container
 * background color white
 * height: 70px
 * width: 100% of the container
 * border 1px #DDDDDD with radius 4px

* Button search:
 * tag button
 * text Search
 * inside the section filters
 * font size: 18px
 * background color #FF5A5F
 * text color #FFFFFF
 * height: 48px
 * width: 20% of the section filters
 * no borders
 * border radius: 4px
 * center vertically and at 30px of the right border
 * change opacity to 90% when the mouse is on the button

* Requirements:

* You must use: header, footer, section, button tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 4 CSS files:
 * styles/4-common.css: for the global style (body and .container styles)
 * styles/3-header.css: for the header style
 * styles/3-footer.css: for the footer style
 * styles/4-filters.css: for the filters style

* 4-index.html won’t be W3C valid, don’t worry, it’s temporary

![Search!](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/0fc91d5d4d62955575dc65a93d9823cf4dc72133.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240315%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240315T084513Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8a731dfa0b35e9e1476ca2e4e9c7ae0477416af3bc03fc56f6f45f7a73f4df1d)

Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 4-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/4-filters.css, images/

Please review your task manually with the following checklist

### 5. More filters

Write an HTML page that displays a header, footer and a filters box.

Layout: (based on 4-index.html)

* Locations and Amenities filters:
 * tag: div
 * classname: locations for location tag and amenities for the other
 * inside the section filters (same level as the button Search)
 * height: 100% of the section filters
 * width: 25% of the section filters
 * border right #DDDDDD 1px only for the first left filter
 * contains a title:
  * tag: h3
  * font weight: 600
  * text States or Amenities
 * contains a subtitle:
  * tag: h4
  * font weight: 400
  * font size: 14px
  * text with fake contents

* Requirements:

* You must use: header, footer, section, button, h3, h4 tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 4 CSS files:
 * styles/4-common.css: for the global style (body and .container styles)
 * styles/3-header.css: for the header style
 * styles/3-footer.css: for the footer style
 * styles/5-filters.css: for the filters style

![More filters](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/63600f1cf5fad5711e6ebba03421fe980d498ec5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240315%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240315T084513Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=dc865e7bc756c95f27153ad95eafe398be708543b6cf8c2103b18c12083bee1b)

Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 5-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/5-filters.css, images/

Please review your task manually with the following checklist

### 6. It's (h)over

Write an HTML page that displays a header, footer and a filters box with dropdown.

Layout: (based on 5-index.html)

* Update Locations and Amenities filters to display a contextual dropdown when the mouse is on the filter div:
 * tag ul
 * classname popover
 * text should be fake now
 * inside each div
 * not displayed by default
 * color #FAFAFA
 * width same as the div filter
 * border #DDDDDD 1px with border radius 4px
 * no list display
 * Location filter has 2 levels of ul/li:
  * state -> cities
  * state name must be display in a h2 tag (font size 16px)

Requirements:

* You must use: header, footer, section, button, h3, h4, ul, li tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 4 CSS files:
 * styles/4-common.css: for the global style (body and .container styles)
 * styles/3-header.css: for the header style
 * styles/3-footer.css: for the footer style
 * styles/6-filters.css: for the filters style

 ![It's (h)over(1)](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/2fc49432137a0f660dedf3fd4b3d86449a72bc53.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240315%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240315T084513Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a229ac05b38c64ba0020cebe422cc933cfc739dcce42cc7a49d6cd18b68e13bc)
 
 ![It's (h)over(2)](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/5aa1d0291e579abd8fc9876af9b9d089147268e2.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240315%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240315T084513Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=38d4171cafeecde9a0d662180bee5414669b0065bdcfed1e481c42ebc69d8ff9)

Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 6-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, images/

Please review your task manually with the following checklist

### 7. Display results

Write an HTML page that displays a header, footer, a filters box with dropdown and results.

Layout: (based on 6-index.html)

* Add Places section:
 * tag: section
 * classname: places
 * same level as the filters section, inside .container
 * contains a title:
  * tag: h1
  * text: Places
  * align in the top left
  * font size: 30px
 * contains multiple “Places” as listing (horizontal or vertical) describe by:
  * tag: article
  * width: 390px
  * padding and margin 20px
  * border #FF5A5F 1px with radius 4px
  * contains the place name:
   * tag: h2
  * font size: 30px
  * center horizontally

Requirements:

* You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 5 CSS files:
 * styles/4-common.css: for the global style (i.e. body and .container styles)
 * styles/3-header.css: for the header style
 * styles/3-footer.css: for footer style
 * styles/6-filters.css: for the filters style
 * styles/7-places.css: for the places style


Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 7-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, styles/7-places.css, images/

Please review your task manually with the following checklist

### 8. More details

Write an HTML page that displays a header, a footer, a filter box (dropdown list) and the result of the search.

Layout: (based on 7-index.html)

Add more information to a Place article:

* Price by night:
 * tag: div
 * classname: price_by_night
 * same level as the place name
 * font color: #FF5A5F
 * border: #FF5A5F 4px rounded
 * min width: 60px
 * height: 60px
 * font size: 30px
 * align: the top right (with space)

* Information section:
 * tag: div
 * classname: information
 * height: 80px
 * border: top and bottom #DDDDDD 1px
 * contains (align vertically):
  * Number of guests:
   * tag: div
   * classname: max_guest
   * width: 100px
   * fake text
   * icon
  * Number of bedrooms:
   * tag: div
   * classname: number_rooms
   * width: 100px
   * fake text
   * icon
  * Number of bathrooms:
   * tag: div
   * classname: number_bathrooms
   * width: 100px
   * fake text
   * icon
* User section:
 * tag: div
 * classname: user
 * text Owner: <fake text>
 * Owner text should be in bold
* Description section:
 * tag: div
 * classname: description

Requirements:

* You must use: header, footer, section, article, button, h1, h2, h3, h4, ul, li tags
* No inline style
* You are not allowed to use the img tag
* You are not allowed to use the style tag in the head tag
* All images must be stored in the images folder
* You must have 5 CSS files:
 * styles/4-common.css: for the global style (i.e. body and .container styles)
 * styles/3-header.css: for the header style
 * styles/3-footer.css: for the footer style
 * styles/6-filters.css: for the filters style
 * styles/8-places.css: for the places style

 ![More details](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/9/f47a405fccad371100ff9665dae9b3a84a471e62.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20240315%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20240315T084513Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=165e5c3c4dcbdeb49f9e8abb13b75c458063654937d191cec6c837a797867b65)


Repo:

* GitHub repository: holbertonschool-AirBnB_clone
* Directory: web_static
* File: 8-index.html, styles/4-common.css, styles/3-header.css, styles/3-footer.css, styles/6-filters.css, styles/8-places.css, images/

</details>

----------

## ➤ Authors:

<p align="center">
<a href="https://github.com/amandinekemp">
 <img src="https://github.com/Khadaassi/holbertonschool-AirBnB_clone/raw/main/logo_github.png?raw=true" />
</a> 
<p align="center">Amandine Kemp</p>

----------

## ➤ License:
This project is subject to the MIT license. For detailed information on the conditions of this license, please consult the [LICENSE](https://github.com/Khadaassi/holbertonschool-AirBnB_clone/blob/main/LICENSE) file included in the project.