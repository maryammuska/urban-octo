# urban-octo

User Story:

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria:

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title




Added comments throughout doc

<!-- Changes I maded on the HTML document;-->

For <head>:
- replaced "website" with Horiseon line 7

For <header>
- replaced <div> with headers on line 12
- added href to  <a href ="#Hori-seo-n">Hori<span class="seo">seo</span>n</a> line 14
- changed <div> on line 16 to <nav>

Hero Section
- changed  <div class="hero"></div> to  <section class="hero"></section> 

Search Engine Optimization Section
- changed <div class="content"> to <section class="content">
- changed  <div class="search-engine-optimization"> to  <article class="search-engine-optimization">
- changed  <div id="online-reputation-management"> to  <section id="online-reputation-management">
- changed <div id="social-media-marketing"> to <section id="social-media-marketing">
- added "alt" to images 
- changed  <div class="benefits"> to <section class="benefits">
- changed <div class="footer"> to <section class="footer">

<!--Changes I made on the CSS-->

- added font-family: Helvetica, Arial, sans-serif; to Body {}
- added to .header h1 {
    font-weight: bold;
    color: #ffffff;
    margin: 0;
    display: inline;

- changed .header div { } to .header nav 
- changed .header div ul { } to .header nav ul
- changed .header div ul li { } to .header nav ul li
- changed .header nav { font-size } to 23px 
- changed width of .content to 70% to mimic the mockup 
- changed width of .benefits to 25% to mimic the mockup

<!--include screenshot of website along with link-->

file:///Users/maryamhaidar/Desktop/UCB/Files/urban-octo/index.html


<!--for images make sure to have alt -->




