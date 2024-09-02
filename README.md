# WebDevUdemy
Web dev Udemy practice- study notes



## Important List

| Important List                                               |
| ------------------------------------------------------------ |
| Difference checker - https://www.diffchecker.com/            |
| https://colorhunt.co/ --- to choose our website colors       |
| RGB mixer - https://www.csfieldguide.org.nz/en/interactives/rgb-mixer/ -- to get your own colors |
| Custom fonts - Fonts.google.com                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |
|                                                              |



## HTML-CSS commands

need to do from Section 6-- 

### HTML

!DOCTYPE html

HTML

HEAD

META

TITLE

LINK, REL, HREF

BODY

H1, H2, H3

IMG, file paths

P - paragraph 

OL, LI

Class , Value

id

STYLE (internal styling)

External CSS

a href 

! hit enter - to get boilerplate



```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Spanish Vocabulary</title>
    <link rel="stylesheet" href="./style.css" />      <!-- External -->
    <style>
      h1 {
        color: red;
      }
    </style>
  </head>
    
  <body>
     <h1>Colors</h1>
    <h2>Learn the colors in Spanish!</h2>
<img src="./assets/images/red.png" alt="red" />
      <li class="note" value="2">Class selectors target elements based on the value of the class attribute.</li>
      <li class="note" id="id-selector-demo" value="3">ID selectors target elements based on the value of the id
      attribute.</li>
      
<h3><a href="./public/MyMovieRanking.html">Movie Ranking Project</a></h3>
    <img
      src="./assets/images/myMovieRankingScreenshot.png"
      height="200"
      alt="Movie ranking project"
    />
     <img src="./../Folder1/fish.png" alt="Fish" />     <!-- File path -->
```





### CSS

#id (selector)

font-weight

height, width

.class (selector)

margin-left

margin-top

list-style-position

color

background-color

attribute selector - li[value="4"]

html (selector)

inline





```css
5.4 ColorVocabProject\style.css

#red {
  color: red;
}
.color-title {
  font-weight: normal;
}
img {
  height: 200px;
  width: 200px;
}

ol {
  margin-left: -40px;
  margin-top: -20px;
  list-style-position: inside;
}

li[value="4"] {
  color: blue;
}

 <h1 style="color: blue">Style Me in Blue!</h1>   <!-- Inline -->

      body {
        background-color: antiquewhite;
      }

```







|                       |
| --------------------- |
|                       |
|                       |
|                       |
|                       |
| 5.4 ColorVocabProject |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |
|                       |













## Section 1- Front-end Web development



1 - What you will get in this course

2-3-4 download & software install

Course syllabus in Section 1 folder - 2023+Web+Dev+Syllabus.pdf

12+Rules+to+Learn+to+Code+[2nd+Edition]+2022.pdf

Visual code Extensions

- Live preview 
- Prettier
- vscode-icons







### 5. How does Internet Actually work?

#### Submarine cables map

Under ocean cables 

https://www.submarinecablemap.com/

ISP , dns server , 

web server , client 



### 6. How does Websites Actually work?



3 types of files.

![image-20240219180946392](Images/image-20240219180946392.png)



Prank your friends ! 

Play & change text ! 

Aria-label - 6:11 



#### Inspect 



![image-20240219180310578](Images/image-20240219180310578.png)

![image-20240219180336229](./Images/image-20240219180336229.png)





![image-20240219180454276](./Images/image-20240219180454276.png)



### Done

my note to say i am done.



## Section 2- Introduction to HTML

​	

### 11. What is HTML

#### inventor of Web1

Sir Tim Berners-Lee - who created 1st website. inventor of internet.

#### Hypertext



Click 1 doc to 1 go to another - hyper links

#### Mark Up - 

Done through HTML tags

#### HTML tags

 

![image-20240224231322981](./Images/image-20240224231322981.png)







![image-20240224231505768](./Images/image-20240224231505768.png)



#### done



### 12. How to download course resources



### 13. The HTML Heading Elements 



#### Resources

2.1 Heading Element 

##### docs

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements

how to extract zip files from windows and mac.



![image-20240224233106750](./Images/image-20240224233106750.png)





![image-20240224233143988](./Images/image-20240224233143988.png)

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements









#### exercise

WebDevUdemy\2.1 Heading Element\index.html

#### Done



![image-20240304002428179](./Images/image-20240304002428179.png)

### 14. HTML Paragraph Elements



#### Exercise

WebDevUdemy\2.2 Paragraph Element\index.html







#### Lorem Ipsum

www.lipsum.com

Latin classical literature by famous author Cicero. 2000 yrs old. been in use in print indistry even since 1500s. when they did not have placeholder text they would put this.



![image-20240224235914920](./Images/image-20240224235914920.png)



![image-20240224235922183](./Images/image-20240224235922183.png)





![image-20240224235947304](./Images/image-20240224235947304.png)







#### done 



### 15. Self Closing Tags



#### Horizontal Rule element



![image-20240225000357344](./Images/image-20240225000357344.png)



#### Break element



![image-20240225001633022](./Images/image-20240225001633022.png)







#### Exercise 

WebDevUdemy\2.3 Void Elements\index.html

```html
<h1>William Blake</h1>

<p>
  17 south molton street <br \ />
  London<br \ />
  W1K 5QT<br \ />
  UK
</p>

<hr \ />

<p>
  William Blake (28 November 1757 – 12 August 1827) was an English poet,
  painter, and printmaker. Largely unrecognised during his life, Blake is now
  considered a seminal figure in the history of the poetry and visual art of the
  Romantic Age. What he called his "prophetic works" were said by 20th-century
  critic Northrop Frye to form "what is in proportion to its merits the least
  read body of poetry in the English language".[2] His visual artistry led
  21st-century critic Jonathan Jones to proclaim him "far and away the greatest
  artist Britain has ever produced".[3] In 2002, Blake was placed at number 38
  in the BBC's poll of the 100 Greatest Britons.[4] While he lived in London his
  entire life, except for three years spent in Felpham,[5] he produced a diverse
  and symbolically rich collection of works, which embraced the imagination as
  "the body of God"[6] or "human existence itself".[7]
</p>

<p>
  Although Blake was considered mad by contemporaries for his idiosyncratic
  views, he is held in high regard by later critics for his expressiveness and
  creativity, and for the philosophical and mystical undercurrents within his
  work. His paintings and poetry have been characterised as part of the Romantic
  movement and as "Pre-Romantic".[8] In fact, he has been said to be "a key
  early proponent of both Romanticism and Nationalism".[9] A committed Christian
  who was hostile to the Church of England (indeed, to almost all forms of
  organised religion), Blake was influenced by the ideals and ambitions of the
  French and American revolutions.[10][11] Though later he rejected many of
  these political beliefs, he maintained an amiable relationship with the
  political activist Thomas Paine; he was also influenced by thinkers such as
  Emanuel Swedenborg.[12] Despite these known influences, the singularity of
  Blake's work makes him difficult to classify. The 19th-century scholar William
  Michael Rossetti characterised him as a "glorious luminary",[13] and "a man
  not forestalled by predecessors, nor to be classed with contemporaries, nor to
  be replaced by known or readily surmisable successors".[14]
</p>

```





![image-20240304001549585](./Images/image-20240304001549585.png)

#### Difference Checker

https://www.diffchecker.com/

#### Done 





### 16. [Project] Movie Ranking



#### Exercise 

WebDevUdemy\2.4 Movie Ranking Project\index.html

```html
<!-- Write your code below -->
<h1>The Best Movies According to Chuck</h1>
<h2>My top 3 movies of all-time</h2>
<hr />

<h3>Jurassic Park</h3>
<p>
  love Speilberg's creativity here and its amazing to see something that could
  be as real as what's made in the movie if this were to have happened
</p>

<h3>The Matrix</h3>
<p>love the idea of us being in a Video game and movie is very well done</p>

<h3>Bourne Series</h3>
<p>
  I love this series as its very gripping and Matt Damon's character is very
  suitable
</p>
```





![image-20240304001456525](./Images/image-20240304001456525.png)





#### Done





### 17. How to Ace this Course







## Section 3- Intermediate HTML



### 18. The List Element



#### Unordered List

![image-20240225011109516](./Images/image-20240225011109516.png)







##### example - fbi top10

https://www.fbi.gov/wanted/topten



![image-20240503235754727](./Images/image-20240503235754727.png)

![image-20240225011350036](./Images/image-20240225011350036.png)





#### Exercise

WebDevUdemy\3.0 List Elements\index.html

```html
<h1>Angela's Cinnamon Roll Recipe</h1>

<h2>Ingredients</h2>

<h3>For the dough:</h3>
<ul>
  <li>¾ cup warm milk</li>
  <li>2 ¼ teaspoons yeast</li>
  <li>¼ cup granulated sugar</li>
  <li>1 egg plus 1 egg yolk</li>
  <li>¼ cup butter</li>
  <li>3 cups bread flour</li>
</ul>

<h3>For the filling:</h3>
<ul>
  <li>2/3 cup dark brown sugar</li>
  <li>1 ½ tablespoons ground cinnamon</li>
  <li>¼ cup butter</li>
</ul>

<h2>Instructions</h2>
<ol>
  <li>Mix the milk with the yeast, sugar, eggs.</li>
  <li>Melt the butter and add to the mixture.</li>
  <li>
    Add in the flour and mix until combined into a dough. Knead the dough for 10
    minuites.
  </li>
  <li>
    Transfer the dough into a large bowl and cover with plastic wrap. Leave it
    somewhere to rise for 2 hours.
  </li>
  <li>
    After the dough has doubled in size, roll it out into a large rectangle.
  </li>
  <li>Melt the butter for the filling and mix in the sugar and cinnamon.</li>
  <li>
    Spread the filling onto the dough then roll the dough into a swiss roll.
  </li>
  <li>Cut the roll into 3cm sections and place flat into a baking tray.</li>
  <li>
    Pre-heat the oven to 350F or 180C, then bake the rolls for 20-25min until
    lightly brown.
  </li>
</ol>
```



![image-20240304001357477](./Images/image-20240304001357477.png)





#### Done





### 19. Nesting and Indentation



### Nested lists



#### exercise

WebDevUdemy\3.1 Nesting and Indentation\index.html





```html
<!-- Write your code below -->
<ul>
  <li>A</li>
  <li>B</li>
  <ol>
    <li>B1</li>
    <li>B2</li>
    <ul>
      <li>B2a</li>
      <ul>
        <li>B2aa</li>
        <ki>B2ab</ki>
      </ul>
      <li>B2b</li>
      <li>B2c</li>
    </ul>
    <li>B3</li>
    <ol>
      <li>B31</li>
      <li>B32</li>
    </ol>
  </ol>
  <li>C</li>
</ul>
```







![image-20240304001259747](./Images/image-20240304001259747.png)

#### done



### 20. Anchor Elements



#### Anchor element

https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a

##### href

Anchor element allows hyperlinks



![image-20240225021958062](./Images/image-20240225021958062.png)



![image-20240225022023189](./Images/image-20240225022023189.png)

##### syntax, multiple attributes

![image-20240225022030726](./Images/image-20240225022030726.png)









##### Global attributes

https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes



##### draggable

![image-20240225022201672](./Images/image-20240225022201672.png)





#### Exercise 



Documents\GitHub\WebDevUdemy\3.2 Anchor Elements\index.html

```html
<h1>My top 5 Favourite Websites</h1>
<!-- Write your code below -->

<ol>
  <li><a href="https://www.udemy.com">Udemy - learn what you love</a></li>
  <li><a href="https://dayone.me/">Day One - great journalling tool</a></li>
  <li><a href="https://chat.openai.com/">ChatGpt</a></li>
  <li>
    <a href="https://plutonomicon.github.io/plutarch-plutus/README"
      >Cardano Blockchain - Plutarch</a
    >
  </li>
  <li>
    <a href="https://www.patreon.com/InvestAnswers/posts"
      >Crypto/Ai investment perpectives</a
    >
  </li>
</ol>

<p>Part 2 - start list from 5</p>
<ol start="5">
  <li><a href="https://www.udemy.com">Udemy - learn what you love</a></li>
  <li><a href="https://dayone.me/">Day One - great journalling tool</a></li>
  <li><a href="https://chat.openai.com/">ChatGpt</a></li>
  <li>
    <a href="https://plutonomicon.github.io/plutarch-plutus/README"
      >Cardano Blockchain - Plutarch</a
    >
  </li>
  <li>
    <a href="https://www.patreon.com/InvestAnswers/posts"
      >Crypto/Ai investment perpectives</a
    >
  </li>
</ol>
<p>Part 3 - test draggable 5</p>
<a draggable="true"
      >Cardano Blockchain - Plutarch</a



```



![image-20240504001011953](./Images/image-20240504001011953.png)







#### Done



### 21. Image Elements



#### img tag



![image-20240228212927480](./Images/image-20240228212927480.png)

#### alt attribute

![image-20240228212951700](./Images/image-20240228212951700.png)



#### SilkTide

SilkTide toolbar to listen to Alt reading attribute

Seems like its asking to login and also no free user email registration.



#### Exercise

Documents\GitHub\WebDevUdemy\3.3 Image Elements\index.html

```html
<h1>I am a Dog Person</h1>

<!-- Kitten image URL -->
<!-- https://raw.githubusercontent.com/appbrewery/webdev/main/kitten.jpeg
 -->

<!-- Puppy image URL -->
<img
  src="https://raw.githubusercontent.com/appbrewery/webdev/main/puppy.gif"
  alt="Dog searching in sand near beach"
/>

```







#### Done



### 22. [Project] Birthday Invite

#### Exercise - 

Documents\GitHub\WebDevUdemy\3.4 Birthday Invite Project\index.html

```html
<h1>It's My Birthday</h1>
<h2>On the 9th of December</h2>
<!-- Example image URL -->
<img
  src="https://raw.githubusercontent.com/appbrewery/webdev/main/birthday-cake3.4.jpeg"
  alt="nice purple cake with candles"
/>
<h3>What to bring:</h3>

<ul>
  <li>Lot of booze :)</li>
  <li>Chicken Biriyani</li>
  <li>Fun vibe</li>
</ul>

<h3>This is where you need to go:</h3>
<!-- Example Google Maps Link -->
<a
  href="https://www.google.com/maps/@35.7040744,139.5577317,3a,75y,289.6h,87.01t,0.72r/data=!3m6!1e1!3m4!1sgT28ssf0BB2LxZ63JNcL1w!2e0!7i13312!8i6656"
>
  Google Map</a
>

```



#### done



### 23. Tip from Angela - Habit building



### 24. Monthly App Brewery newsletter

signed up.



## Section 4 - Multi-Page Websites



### 25. Computer File Paths

Relative & absolute file paths

./ is current directory

#### Exercise

Documents\GitHub\WebDevUdemy\4.0 File Paths\Folder0\index.html



```html
<h1>All the Animals</h1>
<h2>Rabbit:</h2>
<img src="./rabbit.png" alt="Rabbit in grass" />
<h2>Cat:</h2>
<img src="./Folder3/cat.png" alt="Cat" />
<h2>Dog:</h2>
<img src="./../dog.png" alt="Dog" />
<h2>Fish:</h2>
<img src="./../Folder1/fish.png" alt="Fish" />
<h2>Bird:</h2>
<img src="./../Folder1/Folder2/bird.png" alt="Bird" />

```



#### done



![image-20240809172515452](./Images/image-20240809172515452.png)







### 26. What are Webpages?



#### multi-page 

![image-20240229130701502](./Images/image-20240229130701502.png)





#### Exercise

Documents\GitHub\WebDevUdemy\4.1 WebPages\index.html

```html
<h1>Welcome to My Website!</h1>
<!-- Add an image of yourself that links to the about page -->
<a href="./public/about.html">
  <img src="./assets/images/mypics001.jpg" width="400" height="700" />
</a>
<hr />
<!-- Add a link to your contact me page here -->
<a href="./public/contact.html">Contact Me</a>
```



about.html

```html
<h1>About Me</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque sem tellus, sagittis non odio nec, interdum
  elementum lacus. Ut ac justo eget risus sollicitudin fringilla sed ut leo. Ut condimentum elit nec fermentum lobortis.
  Quisque tincidunt quam nec tincidunt ullamcorper. Integer vitae pretium justo. In placerat volutpat pellentesque.
  Etiam
  gravida quam vitae odio pulvinar imperdiet. Vivamus venenatis gravida purus sit amet aliquet. Ut in nibh sed quam
  laoreet lacinia. Cras cursus ut dui vitae posuere. Vivamus volutpat urna vitae odio fringilla placerat. Nulla vel
  rhoncus sapien. Phasellus at interdum enim.</p>

<p>Curabitur elementum sagittis mollis. In porta nec quam ut semper. Nulla volutpat neque quis lacus mattis eleifend.
  Phasellus et congue odio. Mauris tristique, nisl quis porttitor porttitor, tortor ante mattis ex, at dictum tortor
  dolor
  ut sem. Nullam nec libero non ex porta vulputate a eu sapien. In nec bibendum mauris. Fusce iaculis lectus vel magna
  laoreet gravida.</p>

<p>Donec euismod vestibulum arcu, a blandit metus mattis ultrices. Integer quis hendrerit justo. Maecenas sed tempor mi.
  Fusce egestas urna leo. Mauris viverra sem sed libero egestas, volutpat aliquet magna porta. Quisque id diam sed ipsum
  interdum sollicitudin id quis augue. Donec congue nisl nec massa ornare imperdiet quis quis odio. Etiam ut volutpat
  nisl. Vestibulum hendrerit justo nibh, eget consequat magna fermentum finibus. Pellentesque et urna fringilla, rutrum
  neque in, varius leo. Vestibulum efficitur id massa eget pellentesque.</p>
```



contact.html

```html
<h1>Contact Me</h1>
<p>Tel: +123456789</p>
<p>Email: me@gmail.com</p>
<p>Address:</p>
<p>
  123 North Street<br />
  Some City<br />
  Some Country <br />
</p>
```













#### done



### 27. The HTML Boilerplate



#### !Doctype 

which version its written in 

![image-20240229195557549](./Images/image-20240229195557549.png)





![image-20240229195645852](./Images/image-20240229195645852.png)



#### html

root of the document - everything else goes within this.

has lang for language. more for screen readers.



![image-20240229195803023](./Images/image-20240229195803023.png)



#### head element

not displayed but important info but not content.

##### meta 

tag for character set.

![image-20240229195941788](./Images/image-20240229195941788.png)

##### title

![image-20240229200049961](./Images/image-20240229200049961.png)

![image-20240229200109823](./Images/image-20240229200109823.png)



##### Example - 

View Page source



![image-20240229200405297](./Images/image-20240229200405297.png)

![image-20240229200226719](./Images/image-20240229200226719.png)

![image-20240504111446386](./Images/image-20240504111446386.png)

##### Body element

 



All the content goes here.

Meat of the body.

![image-20240229200718621](./Images/image-20240229200718621.png)



#### ! Hit 

enter to get boilerplate

\WebDevUdemy\Test\testBoilerPlate.html



### 28. [Project] Portfolio Website



#### project

Documents\GitHub\WebDevUdemy\4.3 HTML Porfolio Project\index.html

```html
<!-- TODO 1: Create the HTML Boilerplate -->

<!-- TODO 2: Add Your previous projects' HTML into the public folder -->

<!-- TODO 3: Take screenshots of your project previews and add the images to the images folder -->

<!-- TODO 4: Add titles/subtitles etc. -->

<!-- TODO 5: Add a link to the project pages -->

<!-- TODO 6: Add images to show the project previews
HINT for TODO 6: You can use the height attribute set to 200 to make the image smaller:
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#attr-height -->

<!-- TODO 7: Add the Contact Me and About Me page links -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Chakravarti's Portfolio</title>
  </head>
  <body>
    <h1>Chakravarti Raghavan's Portfolio</h1>
    <h2>I am a Web3 Enthusiast</h2>
    <hr />
    <h3><a href="./public/MyMovieRanking.html">Movie Ranking Project</a></h3>
    <img
      src="./assets/images/myMovieRankingScreenshot.png"
      height="200"
      alt="Movie ranking project"
    />
    <h3><a href="./public/MyBdayInvite.html">Birthday Invite Project</a></h3>
    <img
      src="./assets/images/myBdayScreenshot.png"
      height="200"
      alt="Bday Invite project"
    />
    <hr />
    <a href="./public/about.html">About Me </a>
    <a href="./public/contact.html"> Contact Me</a>
  </body>
</html>

```





MyMovieRanking.html

```html
<!-- Write your code below -->
<h1>The Best Movies According to Chuck</h1>
<h2>My top 3 movies of all-time</h2>
<hr />

<h3>Jurassic Park</h3>
<p>
  love Speilberg's creativity here and its amazing to see something that could
  be as real as what's made in the movie if this were to have happened
</p>

<h3>The Matrix</h3>
<p>love the idea of us being in a Video game and movie is very well done</p>

<h3>Bourne Series</h3>
<p>
  I love this series as its very gripping and Matt Damon's character is very
  suitable
</p>
```





MyBdayInvite.html

```html
<h1>It's My Birthday</h1>
<h2>On the 9th of December</h2>
<!-- Example image URL -->
<img
  src="https://raw.githubusercontent.com/appbrewery/webdev/main/birthday-cake3.4.jpeg"
  alt="nice purple cake with candles"
/>
<h3>What to bring:</h3>

<ul>
  <li>Lot of booze :)</li>
  <li>Chicken Biriyani</li>
  <li>Fun vibe</li>
</ul>

<h3>This is where you need to go:</h3>
<!-- Example Google Maps Link -->
<a
  href="https://www.google.com/maps/@35.7040744,139.5577317,3a,75y,289.6h,87.01t,0.72r/data=!3m6!1e1!3m4!1sgT28ssf0BB2LxZ63JNcL1w!2e0!7i13312!8i6656"
>
  Google Map</a
>

```



about.html

```html
<h1>About Me</h1>
<p>Web3 developer, Blockchain technologies, Crypto, Cardano, Plutus, Plutarch, Lucid Offchain.</p>

<p>
  <ul>
<li>Writing Smart contracts on Cardano Blockchain using Plutus apps, Plutarch and offchain using Lucid</li>
<li>Experience in Python Web3, Smart contracts Solidity with Remix, deploying NFT smart contract with Streamlit UI. </li>
<li>Understanding of Blockchains, BIP-39, 44 etc standards, mnemonic phrases, private keys, hash, SHA-256, cryptography, digital wallets, Digital signature, how encryption works. </li>
<li>Worked with Geth, Ganache, Metamask wallets, Kovan testnets, Faucets.</li>
<li>Worked with Python Web3 to interact with Smart contract, send transactions, gas estimates, Bit transactions, mint NFTs, approve, transfer tokens through python. </li>
<li>Used OpenZepplin Libraries.</li>
<li>Worked with Infura API using Python to connect to Kovan Testnet. </li>
<li>Interacted with etherscan through Python to get stats.</li>
<li>Worked with Chainlink Oracles data feeds.</li>
<li>Worked with Piñata IPFS to store NFT pics and get the IPFS numbers to mint. </li>
<li>Generated AI pics for NFT from pre-trained models of Style Transfer. </li>
</ul>
</p>

<p>check some of my projects @
  <a href="https://github.com/rchak007"> My Github - https://github.com/rchak007</a> </p>
```





contact.html

```html
<h1>Contact Me</h1>
<p>Tel: +123456789</p>
<p>Email: me@gmail.com</p>
<p>Address:</p>
<p>
  123 North Street<br />
  Some City<br />
  Some Country <br />
</p>
```





#### done







### 29. How to Host Your Website for Free with GitHub

https://rchak007.github.io/html-portfolio/



https://rchak007.github.io/html-portfolio/

created this website on GitHub.

Documents\GitHub\WebDevUdemy\4.3 HTML Porfolio Project\index.html



steps - 

1) Create a repo - 
   1) https://github.com/rchak007/html-portfolio
   2) add Readme
2) Add Files - Upload files 
   1) From local desktop - index.html should be in Home page code. Spelling with case etc should be exactly index.html
3) Commit Changes
4) Go to Settings -> Pages -> Change Branch from `none` to `main`. Then Save.
5) Refresh and at the top you should have "Your site is live at https://rchak007.github.io/html-portfolio/" Could take some time - 1 to 10 mins.













![image-20240504113107417](./Images/image-20240504113107417.png)



![image-20240504113205962](./Images/image-20240504113205962.png)







![image-20240504113229106](./Images/image-20240504113229106.png)





![image-20240504113412862](./Images/image-20240504113412862.png)





![image-20240504113456197](./Images/image-20240504113456197.png)





![image-20240504113618932](./Images/image-20240504113618932.png)





![image-20240504113733525](./Images/image-20240504113733525.png)





![image-20240504113759851](./Images/image-20240504113759851.png)



![image-20240504113837578](./Images/image-20240504113837578.png)









### 30. Introduction to Capstone Projects



### 31. Instructions to Capstone Project 1

https://www.udemy.com/course/the-complete-web-development-bootcamp/learn/lecture/37330378#notes



Documents\GitHub\WebDevUdemy\Capstone Project 1\index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Resume</title>
  </head>
  <body>
    <h1>Chakravarti Raghavan</h1>
    <img src="./assets/images/myResumePic2.png" height="200" />
    <h2>Summary</h2>
    <p>I am a Web3 Enthusiast</p>
    <hr />
    <h2>Education</h2>
    <ul>
      <li>
        <a
          href="https://www.linkedin.com/school/missouri-university-of-science-and-technology/"
        >
          Missouri University of Science and Technology</a
        >
        Masters in Computer Science 1993-97
      </li>
      <li>
        <a href="https://www.jntuh.ac.in/">
          Jawaharlal Nehru Technological University</a
        >
        Bachelors in Computer Science 1989-93
      </li>
    </ul>
    <hr />
    <h2>Featured Projects</h2>
    <a href="https://github.com/rchak007/decentralSeedRecover">
      Decentralized Seed Phrase Recovery using Cardano Blockchain</a
    >
    <br />
    <br />
    <img
      src="./assets/images/decentralizedSeedScreenshot.png"
      height="200"
      width="300"
    />
    <br />
    <br />
    <a href="https://github.com/rchak007/PlutarchCrowdFunding">
      CrowdFunding in Cardano Blockchain using Plutarch</a
    >
    <br />
    <br />
    <img
      src="./assets/images/crowdFundScreenshot.png"
      height="200"
      width="300"
    />

    <br />
    <br />
    <a href="https://github.com/rchak007/governmentDaoICP">
      Government DAO in Internet Computer blockchain</a
    >
    <br />
    <br />
    <img src="./assets/images/daoScreenshot.png" height="200" width="300" />
    <br />
    <h2>Skills</h2>
    <ul>
      <li>Plutus/Plutarch/Lucid for Cardano</li>
      <li>Solidity for Ethereum</li>
      <li>Motoko for ICP</li>
      <li>Python Web3</li>
      <li>Typescript Web3</li>
      <li>Haskell</li>
    </ul>
    <h2>Other</h2>
    <ul>
      <li><a href="./public/hobbies.html">My Hobbies</a></li>
      <li><a href="./public/contacts.html">Contact Me</a></li>
    </ul>
  </body>
</html>
```



hobbies.html

```html
<h1>My Hobbies</h1>
<ol>
  <li>Hot yoga</li>
  <li>Salsa dancing</li>
  <li>Financial investing/Trading in Stocks and Crypto</li>
</ol>
```



contacts.html

```html
<h1>My Contact Details</h1>
<br />
<p>Los Angeles</p>
<p>Phone: 123456789</p>
<p>Email: rchak1@aol.com</p>
```







https://rchak007.github.io/onlineResume/





#### done







## Section 5 - Introduction to CSS





### 32. Why do we need CSS?



#### Marc Andreessen - mosaic inventor and Netscape

https://en.wikipedia.org/wiki/Marc_Andreessen

**Marc Lowell Andreessen** (born July 9, 1971) is an American businessman and [software engineer](https://en.wikipedia.org/wiki/Software_engineer). He is the co-author of [Mosaic](https://en.wikipedia.org/wiki/Mosaic_(web_browser)), the first widely used [web browser](https://en.wikipedia.org/wiki/Web_browser) with a graphical user interface; co-founder of [Netscape](https://en.wikipedia.org/wiki/Netscape); and co-founder and general partner of [Silicon Valley](https://en.wikipedia.org/wiki/Silicon_Valley) venture capital firm [Andreessen Horowitz](https://en.wikipedia.org/wiki/Andreessen_Horowitz). He co-founded and later sold the [software company](https://en.wikipedia.org/wiki/Software_company) [Opsware](https://en.wikipedia.org/wiki/Opsware) to [Hewlett-Packard](https://en.wikipedia.org/wiki/Hewlett-Packard). Andreessen is also a co-founder of [Ning](https://en.wikipedia.org/wiki/Ning_(website)), a company that provides a platform for social networking websites and an inductee in the [World Wide Web Hall of Fame](https://en.wikipedia.org/wiki/World_Wide_Web_Hall_of_Fame). Andreessen's net-worth is estimated at $1.7 billion.



#### CSS creator - Håkon Wium Lie

https://en.wikipedia.org/wiki/H%C3%A5kon_Wium_Lie

**Håkon Wium Lie** (born July 26, 1965) is a [Norwegian](https://en.wikipedia.org/wiki/Norwegians) web pioneer, a standards activist, and the chairman of YesLogic, developers of [Prince](https://en.wikipedia.org/wiki/Prince_(software)) CSS-based PDF rendering software.[[1\]](https://en.wikipedia.org/wiki/Håkon_Wium_Lie#cite_note-howcome-1)[[2\]](https://en.wikipedia.org/wiki/Håkon_Wium_Lie#cite_note-liehome-2) He is best known for developing [Cascading Style Sheets](https://en.wikipedia.org/wiki/CSS) (CSS) while working with [Tim Berners-Lee](https://en.wikipedia.org/wiki/Tim_Berners-Lee) and [Robert Cailliau](https://en.wikipedia.org/wiki/Robert_Cailliau) at [CERN](https://en.wikipedia.org/wiki/CERN) in 1994. He was the [Chief Technology Officer](https://en.wikipedia.org/wiki/Chief_Technology_Officer) of [Opera Software](https://en.wikipedia.org/wiki/Opera_(company)) from 1998 until the browser was sold to new owners in 2016.[[3\]](https://en.wikipedia.org/wiki/Håkon_Wium_Lie#cite_note-3)[[2\]](https://en.wikipedia.org/wiki/Håkon_Wium_Lie#cite_note-liehome-2)



#### her Website

just shows HTML vs what happens when adding CSS to it as is.

https://appbrewery.github.io/just-add-css/





### 33. How to add CSS



#### 3 types

![image-20240302100900865](./Images/image-20240302100900865.png)





#### Inline 



![image-20240302100939899](./Images/image-20240302100939899.png)





![image-20240302101049200](./Images/image-20240302101049200.png)





#### global attribute `style`

Global attribute style- available to all tags.

![image-20240302101246697](./Images/image-20240302101246697.png)





#### Internal



Inline add only when its very specific and not to use everywhere.

instead Internal is better.

![image-20240302101455447](./Images/image-20240302101455447.png)



##### selector

![image-20240302101559073](./Images/image-20240302101559073.png)





![image-20240302101834484](./Images/image-20240302101834484.png)











#### External

Most common



![image-20240302101940117](./Images/image-20240302101940117.png)







#### Summary 

![image-20240302102056047](./Images/image-20240302102056047.png)





#### Exercise

Documents\GitHub\WebDevUdemy\5.1. Adding CSS\index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Adding CSS</title>
  </head>

  <body>
    <h1>Three Methods of Adding CSS</h1>
    <!-- Create 3 Links to The 3 Webpages: inline, internal and external -->
    <a href="./inline.html">Inline CSS page</a> <br />
    <a href="./internal.html">Internal CSS page</a> <br />
    <a href="./external.html">External CSS pages</a>
  </body>
</html>
```



inline.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Inline</title>
  </head>

  <body>
    <h1 style="color: blue">Style Me in Blue!</h1>
  </body>
</html>
```



internal.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Internal</title>
    <style>
      h1 {
        color: red;
      }
    </style>
  </head>

  <body>
    <h1>Style Me in Red!</h1>
  </body>
</html>

```



external.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>External</title>
    <link rel="stylesheet" href="./style.css" />
  </head>
  <body>
    <h1>Style Me in Green</h1>
  </body>
</html>
```





style.css

```css
h1 {
  color: green;
}

```



![image-20240303234924214](./Images/image-20240303234924214.png)





![image-20240303234934156](./Images/image-20240303234934156.png)



![image-20240303234945035](./Images/image-20240303234945035.png)



![image-20240303234955978](./Images/image-20240303234955978.png)















#### done



### 34. CSS Selectors



#### Element Selector

![image-20240302103441065](./Images/image-20240302103441065.png)



#### Class Selector



![image-20240302103514079](./Images/image-20240302103514079.png)



#### ID selector

![image-20240302103536144](./Images/image-20240302103536144.png)



#### Attribute Selector



![image-20240302103602348](./Images/image-20240302103602348.png)



![image-20240302103650125](./Images/image-20240302103650125.png)



https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li





#### Exercise

Documents\GitHub\WebDevUdemy\5.3 CSS Selectors\index.html

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Selectors</title>
  <link rel="stylesheet" href="./style.css" />
</head>

<body>
  <h1>CSS Selectors</h1>
  <h2>Applying CSS to Different Parts of HTML</h2>
  <!-- TODO 1: Set the CSS for all paragraph tags to "color: red" -->
  <p class="note">1. The element selector targets elements based on their HTML tag name.</p>

  <ol>
    <!-- TODO 2: Set the CSS for all elements with a class of "note" to "font-size: 20px" -->
    <li class="note" value="2">Class selectors target elements based on the value of the class attribute.</li>

    <!-- TODO 3: Set the CSS for the element with an id of "id-selector-demo" to "color: green" -->
    <li class="note" id="id-selector-demo" value="3">ID selectors target elements based on the value of the id
      attribute.</li>

    <!-- TODO 4: Set the CSS for the li elements that have the "value" attribute set to "4" to have "color: blue" -->
    <li class="note" value="4">Attribute selectors target elements based on their attributes and values.</li>

    <!-- TODO 5: Set all elements to have "text-align: center" -->
    <li class="note" value="5">The universal selector targets all elements.</li>
  </ol>
</body>

</html>
```





```css
ol {
  margin-left: -40px;
  margin-top: -20px;
  list-style-position: inside;
}

/* Write your CSS below, don't change the rules above. */
p {
  color: red;
}
.note {
  font-size: 20px;
}
#id-selector-demo {
  color: green;
}
li[value="4"] {
  color: blue;
}
html {
  text-align: center;
}
```









![image-20240303234608112](./Images/image-20240303234608112.png)



#### Done



###  35. [Project] Color Vocab Website



#### project

Documents\GitHub\WebDevUdemy\5.4 ColorVocabProject\index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Spanish Vocabulary</title>
    <link rel="stylesheet" href="./style.css" />
  </head>

  <body>
    <h1>Colors</h1>
    <h2>Learn the colors in Spanish!</h2>
    <h2 class="color-title" id="red">Rojo</h2>
    <img src="./assets/images/red.png" alt="red" />

    <h2 class="color-title" id="blue">Azul</h2>
    <img src="./assets/images/blue.png" alt="blue" />

    <h2 class="color-title" id="orange">Anaranjado</h2>
    <img src="./assets/images/orange.png" alt="orange" />

    <h2 class="color-title" id="green">Verde</h2>
    <img src="./assets/images/green.png" alt="green" />

    <h2 class="color-title" id="yellow">Amarillo</h2>
    <img src="./assets/images/yellow.png" alt="yellow" />
  </body>
</html>

<!-- 
TODOs
IMPORTANT: You should not need to make ANY CHANGES to index.html
All code should be written in your CSS file.

1. Create a CSS file and incorporate it as an external stylesheet.
2. Use CSS to style each of the color titles to meaning. 
Hint: Use the id to help if you don't know the words in spanish.
3. Use CSS to change all the color titles to have "font-weight: normal;"
4. Use CSS (not HTML) to make all the images 200px heigh and 200px wide. 
Hint: 
https://developer.mozilla.org/en-US/docs/Web/CSS/height
https://developer.mozilla.org/en-US/docs/Web/CSS/width
-->

```

```css
#red {
  color: red;
}
#blue {
  color: blue;
}
#orange {
  color: orange;
}
#green {
  color: green;
}
#yellow {
  color: yellow;
}
.color-title {
  font-weight: normal;
}
img {
  height: 200px;
  width: 200px;
}
```





![image-20240303234419304](./Images/image-20240303234419304.png)





#### done



### 36. Tip from Angela



### 37. Join the Student community

report issue.

https://docs.google.com/forms/d/e/1FAIpQLSeZewm5WSjfb_VfOdkQCQpdunWl9FeIQlVhdYjSYK5fvM_fcw/viewform



## Section 6 - CSS Properties





### 38. CSS Colors





![image-20240302152741362](./Images/image-20240302152741362.png)



#### Named colors documentation

https://developer.mozilla.org/en-US/docs/Web/css/named-color



#### Important - color hunt	

https://colorhunt.co/

![image-20240302151714384](./Images/image-20240302151714384.png)





3rd one can be background. 1st one H1 and 2nd one h2.

#### Hex codes



#### RGB Mixer

https://www.csfieldguide.org.nz/en/interactives/rgb-mixer/



#### Exercise 

Documents\GitHub\WebDevUdemy\6.0 CSS Colors\index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Colors</title>
    <style>
      /* Write your CSS code here. */
      /* 1. Make the background of the webpage "antiquewhite"
    2. Make the h1 "whitesmoke"
    3. Make the background of the h1 "darkseagreen"
    4. Make the h2 #FAF8F1
    5. Make the background of the h2 "#C58940" */
      body {
        background-color: antiquewhite;
      }
      h1 {
        color: whitesmoke;
        background-color: darkseagreen;
      }
      h2 {
        color: #faf8f1;
        background-color: #c58940;
      }
    </style>
  </head>

  <body>
    <h1>Hello</h1>
    <h2>World</h2>
  </body>
</html>

```



![image-20240303234045496](./Images/image-20240303234045496.png)



#### done



### 39. Font Properties





#### Font Size

![](./Images/image-20240302153439313.png)





#### Pixel vs Point



![image-20240302153616042](./Images/image-20240302153616042.png)

#### MS Word - points

Word uses Points 



#### 1em 1rem

![image-20240303152723393](./Images/image-20240303152723393.png)

​	

Recommend only REM & not EM



![image-20240303152943374](./Images/image-20240303152943374.png)







![image-20240303152952769](./Images/image-20240303152952769.png)



![image-20240811163207873](./Images/image-20240811163207873.png)

#### Font Size task

just play around to see how `em` and `rem` affects etc.

Documents\GitHub\WebDevUdemy\6.1 Font properties\font-size.html



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Font-Size</title>
    <style>
      #pixel {
        font-size: 20px;
      }

      #point {
        font-size: 20pt;
      }

      #em {
        font-size: 1em;
      }

      #rem {
        font-size: 1rem;
      }

      footer {
        font-size: 12pt;
      }

      html {
        font-size: xx-large;
      }
    </style>
  </head>

  <body>
    <p id="pixel">1 Pixel is 1/96 of an Inch</p>
    <p id="point">1 Point is 1/72 of an Inch</p>
    <footer>
      <p id="em">1em is 100% the size of the parent element</p>
      <p id="rem">1rem is 100% the size of the root element</p>
    </footer>
  </body>
</html>
```







![image-20240303233742982](./Images/image-20240303233742982.png)







#### font Weight

normal or bold

![image-20240303153837918](./Images/image-20240303153837918.png)



![image-20240303153854260](./Images/image-20240303153854260.png)



#### font-family

![image-20240303153944736](./Images/image-20240303153944736.png)

#### backup generic font family

Helvetica is mac typeface. So it may not be there on all computers so we have generic backup.

Sans serif - has edges at right angle on the bottom and edges.

if it has feet or decorations at edges its serif type.



![image-20240303154012646](./Images/image-20240303154012646.png)





![image-20240303154040221](./Images/image-20240303154040221.png)





put in double quotes if font family has space.

![image-20240303154323512](./Images/image-20240303154323512.png)





#### Custom font



##### Fonts.google.com



Choose whatever fonts you want.

and when you click on the Oswald for example it inside can show different Font Weights. Sometimes you can choose by font weight or here it chose all those as a whole on its own.







![image-20240303224342505](./Images/image-20240303224342505.png)



![image-20240303224310396](./Images/image-20240303224310396.png)







![image-20240303224259783](./Images/image-20240303224259783.png)



then go to the ICON on right top - View Selected Families.

Shows the couple i selected.

Then click on `Embed code1`

![image-20240303224200487](./Images/image-20240303224200487.png)





##### Embed Code and CSS

Then copy the the code.

This will go in `<link>` element inside the `<head>` ususally.

then the CSS can go into your styling and use those classes if need be.



![image-20240303224137676](./Images/image-20240303224137676.png)







##### task to do for custom font



Documents\GitHub\WebDevUdemy\6.1 Font properties\font-family.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Font Family</title>
    <style>
      .merriweather-light {
        font-family: "Merriweather", serif;
        font-weight: 300;
        font-style: normal;
      }

      .merriweather-regular {
        font-family: "Merriweather", serif;
        font-weight: 400;
        font-style: normal;
      }

      .merriweather-bold {
        font-family: "Merriweather", serif;
        font-weight: 700;
        font-style: normal;
      }

      .merriweather-black {
        font-family: "Merriweather", serif;
        font-weight: 900;
        font-style: normal;
      }

      .merriweather-light-italic {
        font-family: "Merriweather", serif;
        font-weight: 300;
        font-style: italic;
      }

      .merriweather-regular-italic {
        font-family: "Merriweather", serif;
        font-weight: 400;
        font-style: italic;
      }

      .merriweather-bold-italic {
        font-family: "Merriweather", serif;
        font-weight: 700;
        font-style: italic;
      }

      .merriweather-black-italic {
        font-family: "Merriweather", serif;
        font-weight: 900;
        font-style: italic;
      }
      /* // <uniquifier>: Use a unique and descriptive class name */
      /* // <weight>: Use a value from 200 to 700 */
      .oswald-example {
        font-family: "Oswald", serif;
        font-optical-sizing: auto;
        font-weight: 200;
        font-style: normal;
      }

      #helvetica {
        font-family: Helvetica, sans-serif;
      }

      #arial {
        font-family: Arial, sans-serif;
      }

      #serif {
        font-family: serif;
      }

      #sans-serif {
        font-family: sans-serif;
      }

      #cursive {
        font-family: cursive;
      }

      #monospace {
        font-family: monospace;
      }

      #fantasy {
        font-family: fantasy;
      }
    </style>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Merriweather:ital,wght@0,300;0,400;0,700;0,900;1,300;1,400;1,700;1,900&family=Oswald:wght@200..700&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <h1 class="oswald-example">Font family size</h1>
    <h2>heading 2 Font family size</h2>
    <h2 class="oswald-example">heading 2 Font family size</h2>
    <h2 class="merriweather-black-italic">heading 2 Font family size</h2>
    <p id="helvetica">Helvetica</p>
    <p id="arial">Arial</p>
    <p id="serif">Serif</p>
    <p id="sans-serif">Sans Serif</p>
    <p id="cursive">Cursive</p>
    <p id="monospace">Monospace</p>
    <p id="fantasy">Fantasy</p>
  </body>
</html>
```





![image-20240303233858644](./Images/image-20240303233858644.png)

#### text-align

![image-20240303230114457](./Images/image-20240303230114457.png)

#### Exercise 6.1

No Exercise 6.2

Documents\GitHub\WebDevUdemy\6.1 Font properties\index.html



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS Properties</title>
    <style>
      html {
        font-size: 30px;
      }
      body {
        background-color: cornflowerblue;
        color: white;
        font-size: 18px;
      }

      /* Don't change the CSS above, add Your CSS below */
      .coral {
        color: coral;
      }
      #fontSize {
        font-size: 2rem;
      }
      #fontWeight {
        font-weight: 900;
      }

      /* <uniquifier>: Use a unique and descriptive class name */
      /* <weight>: Use a value from 400 to 700 */

      .caveat-1 {
        font-family: "Caveat", cursive;
        font-optical-sizing: auto;
        font-weight: 400;
        font-style: normal;
      }
      #textAlign {
        text-align: right;
      }
    </style>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Caveat:wght@400..700&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <h1>Important CSS Properties</h1>
    <p class="coral">Color</p>
    <p id="fontSize">Font Size</p>
    <p id="fontWeight">Font Weight</p>
    <p class="caveat-1">Font Family</p>
    <p id="textAlign">Text Align</p>

    <!-- TODOs
  1. Change the color of <p>Color</p> to "coral" color.
  2. Change the font size of <p>Font Size</p> to 2X the size of the root font size.
  3. Change the font weight of <p>Font Weight</p> to 900.
  4. Change the font family of <p>Font Family</p> to the Google font Caveat with regular (400) font weight.
  Link: https://fonts.google.com/specimen/Caveat
  5. Change the <p>Text Align</p> to right align.
  6. Change the the root (html element) font size to 30px -->
  </body>
</html>
```



![image-20240303233921531](./Images/image-20240303233921531.png)





#### Done







### 40. Inspecting CSS



#### Developer tools or inspect

Chrome developer console or right click. & inspect

https://appbrewery.github.io/just-add-css/





![image-20240304002610555](./Images/image-20240304002610555.png)





#### Elements tab & style section





##### select an element button

you can then select Visually

![image-20240304002952881](./Images/image-20240304002952881.png)





#### style section



![image-20240304003115013](./Images/image-20240304003115013.png)







when you select `h2` in the style tab shows what styling has been applied to it.



![image-20240304003241046](./Images/image-20240304003241046.png)







#### Example - 

i can see what button and color etc and temporarily change it to PINK

![image-20240304003608936](./Images/image-20240304003608936.png)





![image-20240304003657929](./Images/image-20240304003657929.png)







#### automatic pre-loaded CSS

there is lot of automatic pre-loaded CSS.



when yours is in conflict with automatic one then they will appear in scratched (the automatic ones)

![image-20240304004417509](./Images/image-20240304004417509.png)





#### CSS file

when you do your own CSS it even tells which file its coming from.

![image-20240304004505746](./Images/image-20240304004505746.png)





in this example there was no style.css but as we see its Internal styling and external file.

![image-20240304004938552](./Images/image-20240304004938552.png)



#### Create styling

![image-20240304013948233](./Images/image-20240304013948233.png)





when yours is in conflict with automatic one then they will appear in scratched (the automatic ones)

how do you know final what is applied - 

#### Computed tab

ChatGpt- When inspecting a web page and looking at the elements in the "Elements" tab of the browser's developer tools, the "Computed" tab provides information about the computed styles of the selected element. This tab **<u>shows the final styles that are applied to the element after considering all CSS rules, inheritance, and browser defaults.</u>**

Here's what you can expect to see in the "Computed" tab:

1. **Computed Styles**: This section displays a list of CSS properties and their computed values for the selected element. These computed styles take into account all CSS rules that apply to the element, including styles inherited from parent elements and any browser default styles.
2. **Cascade**: The "Cascade" section shows the cascade of CSS rules that apply to the selected element, including the source (inline, user agent, author, etc.) and specificity of each rule. This helps you understand which CSS rules are influencing the computed styles of the element.
3. **Box Model**: The "Box Model" section provides information about the dimensions and positioning of the element, including its content area, padding, border, margin, width, height, and positioning properties (such as `position`, `top`, `left`, etc.).
4. **Typography**: If applicable, the "Typography" section may display information about font-related properties such as `font-family`, `font-size`, `line-height`, `font-weight`, `font-style`, etc.
5. **Color and Background**: Information about the color and background properties of the element, including `color`, `background-color`, `background-image`, `background-repeat`, `background-position`, etc.

By inspecting the computed styles in the "Computed" tab, you can gain insight into how CSS rules are affecting the appearance and layout of elements on the web page. This can be useful for debugging layout issues, understanding CSS specificity, and optimizing styles for performance and consistency.





![image-20240304014505241](./Images/image-20240304014505241.png)





As you can see it also tells the rules sequence and how it has 2 rem which is 60 px. 

![image-20240504190508683](./Images/image-20240504190508683.png)



#### More Tools -> CSS Overview





![image-20240304014655348](./Images/image-20240304014655348.png)



then select `Capture overview`

![image-20240304014744702](./Images/image-20240304014744702.png)



#### Colors used

shows all the background colors, color used etc.

![image-20240304014903228](./Images/image-20240304014903228.png)



#### Fonts used

You can even check the Font being used.

![image-20240304015007924](./Images/image-20240304015007924.png)







#### Media Queries used

![image-20240304015128793](./Images/image-20240304015128793.png)



#### practice 

https://appbrewery.github.io/css-inspection/



You can go to Computed or just from styles you can get these.



#### done



### 41.The CSS Box Model - Margin, Padding and Border



#### Border

Pixel or percentages

Border- thickness style color



![image-20240305174319365](./Images/image-20240305174319365.png)



#### border-width

![image-20240305174351522](./Images/image-20240305174351522.png)





#### padding

![image-20240305174437706](./Images/image-20240305174437706.png)



#### margin



![image-20240305174516111](./Images/image-20240305174516111.png)





![image-20240305174545472](./Images/image-20240305174545472.png)







#### summary1

![image-20240305174620522](./Images/image-20240305174620522.png)





#### Task

you can play a bit here

https://appbrewery.github.io/box-model/

![image-20240305174755347](./Images/image-20240305174755347.png)





you can increase margin here and you see below image it increased.



![image-20240305175047717](./Images/image-20240305175047717.png)





more changes:



![image-20240305175152868](./Images/image-20240305175152868.png)





#### Summary2

![image-20240305175243666](./Images/image-20240305175243666.png)



#### div element

![image-20240305175345145](./Images/image-20240305175345145.png)







![image-20240305175425626](./Images/image-20240305175425626.png)





#### Pesticide Extension



![image-20240305175441402](./Images/image-20240305175441402.png)





##### hovering on element

![image-20240305175543485](./Images/image-20240305175543485.png)

##### CTRL key

You have to hold down CTRL key.

![image-20240305175908212](./Images/image-20240305175908212.png)





#### Exercise 6.3

No Exercise 6.2

Documents\GitHub\WebDevUdemy\6.3 CSS Box Model\index.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS Box Model</title>
    <style>
      /* Write your CSS code here */
      div {
        height: 200px;
        width: 200px;
      }
      p {
        display: block;
        margin-block-start: 0px;
        margin-block-end: 0px;
        margin-inline-start: 0px;
        margin-inline-end: 0px;
      }
      body {
        display: block;
        margin-block-start: 0px;
        margin-block-end: 0px;
        margin-inline-start: 0px;
        margin-inline-end: 0px;
      }
    </style>
  </head>

  <body>
    <div
      style="
        background-color: cadetblue;
        padding: 20px;
        border: 10px solid black;
      "
    >
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at
        sapien porttitor urna elementum lacinia. In id magna pulvinar, ultricies
        lorem id, vehicula elit. Aliquam eu luctus nisl, vitae pellentesque
        magna. Phasellus dolor metus, laoreet ac convallis sit amet,
        efficitursed dolor.
      </p>
    </div>
    <div
      style="
        background-color: gold;
        border: 20px solid black;
        border-width: 20px 10px;
        margin-left: 260px;
      "
    ></div>
    <div
      style="
        background-color: indianred;
        border: 10px solid black;
        margin-left: 40px;
      "
    ></div>

    <!-- TODOs:
1. Create 3 Boxes using the div element.
2. Set their sizes to 200px heigh by 200px wide.
3. Set different background colors for each of the boxes (I used cadetblue, gold and indianred).
4. Add a paragraph <p> element into the first div and add the following words:
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam at sapien porttitor urna elementum lacinia. In
    id magna pulvinar, ultricies lorem id, vehicula elit. Aliquam eu luctus nisl, vitae pellentesque magna. Phasellus
    dolor metus, laoreet ac convallis sit amet, efficitur sed dolor.
5. Set the 1st div to have 20px padding all around with a black 10px border.
6. Fix the style of the <p> element to remove all margins.
Hint: Use the CSS inspector in Chrome.
7. Set the 2nd div to have a 20px border on top and bottom and 10px border left and right. (See goal image)
8. Set the 3rd div to have a 10px border 
9. Set the margins for the divs so that each box corner touches the other. (See the goal image)
-->
  </body>
</html>
```







![image-20240508113119549](./Images/image-20240508113119549.png)

















### 42. [Project] Motivational Poster Website



#### project

Documents\GitHub\WebDevUdemy\6.4 Motivation Meme Project\index.html

i did differently but solution is better.

Also text you can align center, but image you just make width=100% so it fills the Div.

The hint in exercises is good, plus other important stuff - 

- center a div by giving it a width of 50% and a margin-left of 25%
- image to have a width of 100% so it fills the div
- text-transform: uppercase;

```html
<!-- 
  TODO: Create a motivational post website.
Style it how ever you like. 
Look at the goal image for inspiration.
But it must have the following features:
1. The main h1 text should be using the Regular Libre Baskerville Font from Google Fonts:
  https://fonts.google.com/specimen/Libre+Baskerville
2. The text should be white and background black.
3. Add your own image into the images folder inside assets. It should have a 5px white border.
4. The text should be center aligned.
5. Create a div to contain the h1, p and img elements. Adjust the margins so that the image and text are centered on the page. 
  Hint: You horizontally center a div by giving it a width of 50% and a margin-left of 25%.
  Hint: Set the image to have a width of 100% so it fills the div. 
6. Read about the text-transform property on MDN docs to make the h1 uppercase with CSS.
  https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform 
-->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:ital,wght@0,400;0,700;1,400&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="./style.css" />
  </head>
  <body>
    <div class="topDivClass">
      <div class="imageDivClass">
        <img src="./assets/images/daenerys.jpeg" class="imageClass" />
      </div>
      <div class="textClass">
        <h1 class="libre-baskerville-regular">That special Moment</h1>
        <p>When you find the perfect avocado at the supermarket</p>
      </div>
    </div>
  </body>
</html>


---- Solution body ---
<body>

  <div class="poster">
    <img class="motivation-img" src="./assets/images/daenerys.jpeg" src="daenerys with egg" />
    <h1>That Special Moment</h1>
    <p>When you find the perfect avocado at the supermarket</p>
  </div>
</body>
```







Documents\GitHub\WebDevUdemy\6.4 Motivation Meme Project\style.css



```css
.libre-baskerville-regular {
  font-family: "Libre Baskerville", serif;
  font-weight: 400;
  font-style: normal;
}

.libre-baskerville-regular-italic {
  font-family: "Libre Baskerville", serif;
  font-weight: 400;
  font-style: italic;
}

.libre-baskerville-bold {
  font-family: "Libre Baskerville", serif;
  font-weight: 700;
  font-style: normal;
}

body {
  color: white;
  background-color: black;
}
.imageDivClass {
  border: 5px solid white;
}
.textClass {
  text-align: center;
}
.topDivClass {
  margin-left: 25%;
  width: 50%;
  margin-right: 25%;
  margin-top: 3%;
}
.imageClass {
  width: 100%;
}
h1 {
  text-transform: uppercase;
}


---- SOLUTION CSS
body {
  background-color: black;
}
h1 {
  text-transform: uppercase;
  font-size: 3rem;
}

.poster {
  width: 50%;
  margin-left: 25%;
  margin-top: 100px;
  color: white;
  font-family: "Libre Baskerville", serif;
  text-align: center;
}

.motivation-img {
  border: 5px solid white;
  width: 100%;
}

```



```
git remote set-url origin https://huggingface.co/spaces/rchak007/BackTester.git

```



#### done







## Section 7 - Intermediate CSS 





### 43. The Cascade - Specificity and Inheritance

Summary for Cascade rules.

![image-20240307222609153](./Images/image-20240307222609153.png)







![image-20240508221037662](./Images/image-20240508221037662.png)



Will be blue here since its later;



![image-20240508221118450](./Images/image-20240508221118450.png)



2nd `li` - `style` takes precedence over `class` which takes over `li`

3rd `li` - `.Three` is class so takes pr	ecedence over just `li`



![image-20240508221602036](./Images/image-20240508221602036.png)



#### exercise 7.0

Documents\GitHub\WebDevUdemy\7.0 CSS Cascade\index.html

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>CSS Cascade</title>
  <link rel="stylesheet" href="./style.css">
</head>

<body>
  <div id="outer-box" class="box">
    <div class="box">
      <p>Yellow Text</p>
      <div class="box inner-box">
        <p class="white-text">White Text</p>
      </div>
    </div>
    <div class="box">
      <p>Yellow Text</p>
      <div class="box inner-box">
        <p class="white-text">White Text</p>
      </div>
    </div>
  </div>
</body>

</html>
```





Documents\GitHub\WebDevUdemy\7.0 CSS Cascade\style.css

```css
/* Don't change the existing CSS. */

.box {
  background-color: blue;
  padding: 10px;
}

p {
  color: yellow;
  margin: 0;
  padding: 0;
}

/* my changes */
.inner-box {
  /* this has to be below .box to work due to specificity rules */
  background-color: red;
}
.inner-box p {
  /* could have done .white-text class */
  color: white;
}
#outer-box {
  background-color: purple;
}


------------- SOLUTION - 
#outer-box {
  background-color: purple;
}

.box {
  background-color: blue;
  padding: 10px;
}

.inner-box {
  background-color: red;
}

p {
  color: yellow;
  margin: 0;
  padding: 0;
}

.white-text {
  color: white;
}
```



![image-20240308141821834](./Images/image-20240308141821834.png)







#### order important

since .box and .inner-box are both classes the order is important since both classes are used.

```html
      <div class="box inner-box">
        <p class="white-text">White Text</p>
      </div>
```

![image-20240813111554044](./Images/image-20240813111554044.png)



#### done



### 44. Combining CSS Selectors





#### Combine class and paragraph

![image-20240308161045279](./Images/image-20240308161045279.png)



#### group selectors with comma , 

![image-20240308161137402](./Images/image-20240308161137402.png)





#### child

![image-20240308161546898](./Images/image-20240308161546898.png)





![image-20240308161616654](./Images/image-20240308161616654.png)







#### descendent

![image-20240308161802934](./Images/image-20240308161802934.png)





#### chaining



![image-20240308162238036](./Images/image-20240308162238036.png)





##### Order - element first

element has to go first



![image-20240308162335285](./Images/image-20240308162335285.png)





#### Combining combiners



 ![image-20240308162559362](./Images/image-20240308162559362.png)







#### exercise

was earlier tasks - 

Documents\GitHub\WebDevUdemy\7.1 Combining Selectors\index.html

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <title>Combining CSS Selectors</title>
  <link rel="stylesheet" href="./style.css">
</head>

<!-- Don't change any of the HTML code! -->

<body>
  <h1>To Do List</h1>
  <h2>Monday</h2>
  <div class="box">
    <p class="done">Do these things today!</p>
    <ul class="list">
      <li>Wash Clothes</li>
      <li class="done">Read</li>
      <li class="done">Maths Questions</li>
    </ul>
  </div>

  <ul>
    <p class="done">Other items</p>
  </ul>
  <p>The best preparation for tomorrow is doing your best today.</p>

</body>

</html>
```





\Documents\GitHub\WebDevUdemy\7.1 Combining Selectors\style.css



```css
/* Write your code here: */
h1,
h2 {
  color: blueviolet;
}
.box > p {
  color: firebrick;
}

/* .list {
    color: blue;
} */

/* also works */
/* div li {
  color: blue;
} */
.box li {
  color: blue;
}

/* Chaining */
li.done {
  color: seagreen;
}

/* combining combiner */
ul > p.done {
  font-size: 0.5rem;
}
```





![image-20240308163056526](./Images/image-20240308163056526.png)



#### done





### 45. CSS Positioning



#### 4 positions

![image-20240308221912264](./Images/image-20240308221912264.png)

#### Default is Static

left 50px and top 50px does not matter for Static - it will ignore and just start immediate after previous element - thats why its greyed out.

![image-20240511110539390](./Images/image-20240511110539390.png)

![image-20240308222121285](./Images/image-20240308222121285.png)



#### play task



https://appbrewery.github.io/css-positioning/



So the below left and top are fixed for all boxes. Here you see 5 divs with different classes. and `style.css` and in the css it defines static, relative, etc.

```
  left: 50px;
  top: 50px;
```



then it uses the descendent method actually - 



```
.static .box {
  position: static;
  left: 50px;
  top: 50px;
}

.relative .box {
  position: relative;
  left: 50px;
  top: 50px;
}
```



![image-20240510224816343](./Images/image-20240510224816343.png)

![image-20240510224705405](./Images/image-20240510224705405.png)



Static just goes to next position below the `top: 50pm` text.



##### View with Pesitcide

![image-20240308222639183](./Images/image-20240308222639183.png)



![image-20240308222958963](./Images/image-20240308222958963.png)



#### Relative

Relative to only its own position;







![image-20240308223352918](./Images/image-20240308223352918.png)

![image-20240511110504895](./Images/image-20240511110504895.png)



relative from itself (which was Static) now moves left 50 and top 50.



![image-20240308223429963](./Images/image-20240308223429963.png)





#### Absolute

important distinction - only the ancestor that is positioned matter. So i have few ancestors but that did not use Position relative then it will just to use the top left corner just like in this example she gave.



![image-20240308223549329](./Images/image-20240308223549329.png)





when no nearest ancestor then goes takes position from top left of webpage.



![image-20240308223622606](./Images/image-20240308223622606.png)















this since has no ancestor with Relative position goes from top left corner. has ancestors but they dont have relative. Thats why goes to top left corner to use top and left from there.



![image-20240308224103663](./Images/image-20240308224103663.png)







when i added style for that ancestor - then it shifts.

![image-20240308224812855](./Images/image-20240308224812855.png)









Below - ancestors of the div green box. since ancestors none of them have position relative set m, green box went off of the top left corner webpage.



![image-20240308225008509](./Images/image-20240308225008509.png)

![image-20240308225100107](./Images/image-20240308225100107.png)



![image-20240308225348407](./Images/image-20240308225348407.png)



#### Z-index

3rd dimension - which goes on top of which



![image-20240309085246556](./Images/image-20240309085246556.png)







now green box is behind others - as we set z-index = -1;



![image-20240309085321939](./Images/image-20240309085321939.png)





#### Fixed

![image-20240309085423489](./Images/image-20240309085423489.png)



#### position , margin, border, padding



![image-20240309085506789](./Images/image-20240309085506789.png)





#### exercise



Documents\GitHub\WebDevUdemy\7.2 CSS Positioning\index.html



```html
<!DOCTYPE html>
<html>
  <head>
    <title>CSS Positioning Exercise</title>
    <style>
      /* Write your code here */
      .blue-box {
        background-color: blue;
        position: relative; /* could be absolute or fixed too in this case */
        top: 200px;
        left: 200px;
        width: 500px;
        height: 300px;
      }
      .red-circle {
        background-color: red;
        position: absolute;
        top: 150px; /* or can be 50% too */
        left: 250px; /* or can be 50% too */
        width: 200px;
        height: 200px;
        border-radius: 50%;
      }
    </style>
  </head>

  <body>
    <div class="blue-box">
      <div class="red-circle"></div>
    </div>
  </body>
</html>
```







![image-20240309090918219](./Images/image-20240309090918219.png)





#### circle

##### border-radius 50%

![image-20240309090345624](./Images/image-20240309090345624.png)



![image-20240309090409599](./Images/image-20240309090409599.png)





#### Important - div

will not show unless you add width and height.







### 46. [Project] CSS Flag



#### Painting with CSS - crazy

![image-20240309093154419](./Images/image-20240309093154419.png)









#### Simpsons in CSS



![image-20240309093230158](./Images/image-20240309093230158.png)





#### project



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>CSS Flag Project</title>
    <style>
      /* Write your CSS Code here */
      body {
        margin: 0 0 0 0;
      }
      p {
        margin: 0 0 0 0;
      }
      .flag {
        width: 900px;
        height: 600px;
        background-color: rgb(206, 17, 38);
        margin: 0 0 0 0;
        position: relative;
      }

      /* Blue middle */
      .flag > div {
        background-color: rgb(0, 40, 104);
        /* width: 100px; */
        height: 300px;
        width: 900px;
        position: absolute;
        top: 25%;
      }

      /* Circle  */
      .flag > div > div > p {
        position: absolute;
        background-color: rgb(255, 255, 255);
        border-radius: 50%;
        width: 200px;
        height: 200px;
        left: 350px;
        top: 50px;
        font-size: 70px;
        color: black;
        text-align: center;
      }

      .flag > p {
        color: white;
        font-size: 70px;
        text-align: center;
        position: relative;
        top: 5%;
      }
    </style>
  </head>

  <!-- 
  IMPORTANT! Do not change any HTML
Don't add any classes/ids/elements 
Use what you know about combining selectors 
and CSS specificity instead.
Hint 1: The flag is 900px by 600px and the circle is 200px by 200px.
Hint 2: You can use CSS inspection to get the colors from
https://appbrewery.github.io/flag-of-laos/
-->

  <body>
    <div class="flag">
      <p>The Flag</p>
      <div>
        <div>
          <p>of Laos</p>
        </div>
      </div>
    </div>
  </body>
</html>

```

​	



![image-20240310153438298](./Images/image-20240310153438298.png)



#### done



### 47. Tip from Angela- nothing easy is worth doing











## Section 8 - Advanced CSS 





### 48. CSS Display



#### span



#### Default display is block

#### display inline

![image-20240310154412684](./Images/image-20240310154412684.png)









##### Default to content size

you cant set height and width;

see - Documents\GitHub\WebDevUdemy\8.0 CSS Display\spantest.html

```html
    <p class="test">Just some random <span> spanTest2</span> here</p>
    <p class="test3">Just some random <span> spanTest2</span> here</p>

```

![image-20240310154657941](./Images/image-20240310154657941.png)





#### Inline-block

![image-20240310155220640](./Images/image-20240310155220640.png)







#### none

disappears;



#### link to play

https://appbrewery.github.io/css-display/





#### Exercise



Documents\GitHub\WebDevUdemy\8.0 CSS Display\index.html

```html
<!DOCTYPE html>
<html>
  <!-- 
  TODO
1. By changing only the display property of the CSS make all 3 squares line up horizontally like in goal1 image.
2. Change only the display property to make all 3 squares line up vertically like in goal2 image. 
-->

  <head>
    <title>CSS Display Property Example</title>
    <style>
      p {
        color: white;
      }

      .red {
        display: inline-block;
        width: 200px;
        height: 200px;
        background-color: red;
      }

      .green {
        display: inline-block;
        width: 200px;
        height: 200px;
        background-color: green;
      }

      .blue {
        display: inline-block;
        width: 200px;
        height: 200px;
        background-color: blue;
      }
    </style>
  </head>

  <body>
    <h1>CSS Display Property</h1>
    <p class="red">Red Paragraph</p>
    <p class="green">Green Paragraph</p>
    <p class="blue">Blue Paragraph</p>
  </body>
</html>

```









Documents\GitHub\WebDevUdemy\8.0 CSS Display\index2.html

```html


<!DOCTYPE html>
<html>
  <!-- 
  TODO
1. By changing only the display property of the CSS make all 3 squares line up horizontally like in goal1 image.
2. Change only the display property to make all 3 squares line up vertically like in goal2 image. 
-->

  <head>
    <title>CSS Display Property Example</title>
    <style>
      p {
        color: white;
      }

      .red {
        display: block;
        width: 200px;
        height: 200px;
        background-color: red;
      }

      .green {
        display: block;
        width: 200px;
        height: 200px;
        background-color: green;
      }

      .blue {
        display: block;
        width: 200px;
        height: 200px;
        background-color: blue;
      }
    </style>
  </head>

  <body>
    <h1>CSS Display Property</h1>
    <p class="red">Red Paragraph</p>
    <p class="green">Green Paragraph</p>
    <p class="blue">Blue Paragraph</p>
  </body>
</html>

```





#### own exercise Span

Documents\GitHub\WebDevUdemy\8.0 CSS Display\spantest.html

![image-20240511190512494](./Images/image-20240511190512494.png)



### 49. CSS Float





00:24 - Wrap text around element - float

00:38 - Do this diff size blocks (did that actually under own exercise)

00:51 - Try a Div & assign float to it & keep IMG & p for text (later in exercise we did anyways)

02:32 - Example

5:14 - Footer clear left

5;16 - Clear

5:25 - Clear

6:08 - Practice float on Div too; not just image (already kind of did it)

6:19 - Clear both (we do this in exercise)

6:24 - Clear:both  (we do this in exercise)

6:32 - Exercise- done.

11:11 - Float is not used in this way anymore

11:30 - Only use when you wrap text around image





#### Own exercise

 to have inline blocks like newspaper format - (0:38 secs)

Documents\GitHub\WebDevUdemy\8.1 CSS Float\test1.html

```html
<!DOCTYPE html>
<html>


  <head>
    <title>CSS Display Property Example</title>
    <style>
      p {
        color: black;
      }
      h1 {
        display: inline-block;
        background-color: yellow;
        width: 350px;
        height: 250px;
      }
      .block1 {
        display: inline-block;
        background-color: aqua;
        width: 200px;
        height: 100px;
      }
      .block2 {
        display: inline-block;
        background-color: bisque;
        width: 150px;
      }
    </style>
  </head>

  <h1>CSS Display Property</h1>
  <p class="block1">Block1 Paragraph</p>
  <p class="block2">Block2 Paragraph</p>
</html>
```



![image-20240511195623207](./Images/image-20240511195623207.png)



was mimicking diff block size like below in above exercise.

![image-20240511195701978](./Images/image-20240511195701978.png)















#### float

##### right



![image-20240513133315229](./Images/image-20240513133315229.png)



#### clear

![image-20240513133416204](./Images/image-20240513133416204.png)



#### clear: both

#### Only use when you wrap text around image

usually used in this way mostly.









#### Exercise 

Documents\GitHub\WebDevUdemy\8.1 CSS Float\index.html

```html
<!DOCTYPE html>
<html lang="en">
  <!-- TODO
1. Make both paragraph elements wrap around the image.
2. Use Float to move the cat div to the left and the dog div to the right.
3. Use clear to make the footer go below both the cat and dog div. -->

  <head>
    <meta charset="UTF-8" />
    <title>CSS Float</title>
    <style>
      div {
        display: inline-block;
        width: 40%;
      }

      p {
        font-size: 2em;
      }

      .cat {
        background-color: aquamarine;
      }
      .cat img {
        float: left;
      }

      .dog {
        background-color: coral;
        float: right;
      }
      .dog img {
        float: left;
      }

      footer {
        text-align: center;
        background-color: blueviolet;
        clear: both;
      }
    </style>
  </head>

  <body>
    <div class="cat">
      <h2>CatCSS</h2>

      <img src="cat.jpeg" alt="cat in a box" />
      <p class="first-paragraph">
        Nap all day cat dog hate mouse eat string barf pillow no baths hate
        everything but kitty poochy. Sleep on keyboard toy mouse squeak roll
        over. Mesmerizing birds. Poop on grasses licks paws destroy couch
        intently sniff hand. The dog smells bad gnaw.
      </p>
    </div>
    <div class="dog">
      <h2>DogCSS</h2>
      <img src="dog.jpeg" alt="dogs in a box" />
      <p class="second-paragraph">
        Heckin good boys and girls long woofer big ol wow very biscit long
        woofer heck what a nice floof, long doggo noodle horse vvv very taste
        wow. Very taste wow many pats aqua doggo he made many woofs pupperino,
        puggo doing me a frighten.
      </p>
    </div>

    <footer>Copyright. This is the footer</footer>
  </body>
</html>

```





![image-20240513132728501](./Images/image-20240513132728501.png)





### 50. Responsive Websites





2:09 - 4 responsive ways to

3;24 Media Query

4:47 - Display grid

7:54 - Grid small summary

7:59 - Try this as is as small exercise

10:49 - How to do 2 of them - do as exercise

11:24 - Flex box summary

12:00 - Try this on your own with some Div in flex & some not etc & see what happens

14:03 - Bootstrap built on top of flex box -

14:17 - 12 part

15:49 - Responsiveness built in & styles

16:20 - Good. One to do again

17:36 - Exercise





#### 4 responsive ways

2:09 - 4 responsive ways to

![image-20240513133758385](./Images/image-20240513133758385.png)







#### Media Query

3;24 Media Query

we will look deeper in next lesson. 

![image-20240513133846962](./Images/image-20240513133846962.png)





#### display Grid

4:47 - Display grid

##### grid-template-columns

##### grid-template-rows



![image-20240514222722307](./Images/image-20240514222722307.png)



![image-20240514222932097](./Images/image-20240514222932097.png)





##### gap 

##### grid-column Span



##### Grid Summary

7:54 - Grid small summary

![image-20240514223144236](./Images/image-20240514223144236.png)



##### Own exercise

7:59 - Try this as is as small exercise - from above code

Documents\GitHub\WebDevUdemy\Test\test50-01-CSS-Grid.html

```html
<html>
  <head>
    <style>
      .grid-container {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-template-rows: 100px 200px 200px;
        gap: 30px;
      }
      .first {
        grid-column: span 2;
        background-color: bisque;
      }
      .card {
        background-color: blue;
      }
    </style>
  </head>

  <body>
    <div class="grid-container">
      <div class="first"></div>
      <div class="card"></div>
      <div class="card"></div>
      <div class="card"></div>
      <div class="card"></div>
    </div>
  </body>
</html>
```



![image-20240514224833742](./Images/image-20240514224833742.png)



Since we use `grid` its auto responsive.



![image-20240514224851843](./Images/image-20240514224851843.png)



Grid applies to 2D layout with rows and columns

#### CSS Flex

##### 1D layout

Grid applies to 2D layout with rows and columns then Flex is good at 1D layout.



![image-20240516134434816](./Images/image-20240516134434816.png)





##### display: flex

##### flex:1



![image-20240516135246922](./Images/image-20240516135246922.png)



10:49 - How to do 2 of them - do as exercise







##### Flex in column direction too



##### No Fixed width

since its not fixed width and is more %age of total width, it will easily be responsive when web page width changes. 



##### own exercise.



Documents\GitHub\WebDevUdemy\Test\test50-02-CSS-Flex.html



```html
<html>
  <head>
    <style>
      .flex-container {
        display: flex;
      }

      .card {
        background-color: blue;
        border: 30px solid white;
        height: 100px;
        flex: 1;
      }
      .first {
        flex: 2;
      }
      .second {
        flex: 0.5;
      }
    </style>
  </head>

  <body>
    <div class="flex-container">
      <div class="first card"></div>
      <div class="second card"></div>
      <div class="card"></div>
      <div class="card"></div>
    </div>
    <!-- my additions -->
    <div class="flex-container">
      <div class="first card"></div>
      <div class="second card"></div>
      <div class="card"></div>
      <div class="card"></div>
    </div>
  </body>
</html>
```









![image-20240516143746911](./Images/image-20240516143746911.png)









#### Bootstrap framework



Its framework because its external and not built into CSS like grid and flexbox.

We bring in other people's code.

whole bunch of classes have been defined. lot of styling is automatically applied.

its built on FlexBox.

12 div system. 12 columns.





![image-20240516144242991](./Images/image-20240516144242991.png)







#### exercise

was only to check it out. nothing to do.

Documents\GitHub\WebDevUdemy\8.2 Responsiveness\index.html























### 51. Media Queries



0:41 - Syntax

3:32 - More conditions

5:33 - Screen not recommended .. but also print similar

5:47 - Docs	

6:29 - Exercise

8:25 - Simulation of different devices from chrome

8:37 - Devices chrome



#### Syntax

![image-20240514175242247](./Images/image-20240514175242247.png)





#### Combine - more conditions

3:32 - More conditions

![image-20240514175323604](./Images/image-20240514175323604.png)



#### Screen / Print

5:33 - Screen not recommended .. but also print similar

Screen not recommended .. but also print similar

![image-20240514175452531](./Images/image-20240514175452531.png)





#### Docs

5:47 - Docs

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries



#### Exercise

6:29 - Exercise

Documents\GitHub\WebDevUdemy\8.3 Media Query\index.html

```html
<!DOCTYPE html>
<html lang="en">
  <!-- 
TODO: Change the background color for each device
[lightsalmon] Mobile Devices: 319px — 480px
[powderblue] iPads and Tablets: 481px — 1200px
[limegreen] Laptops: 1201px — 1600px
[seagreen] Desktops: 1601px and more
-->

  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1, minimum-scale=1"
    />
    <title>Media Query</title>
    <style>
      @media (min-width: 1601px) {
        body {
          background-color: seagreen;
        }
      }
      @media (min-width: 1201px) and (max-width: 1600px) {
        body {
          background-color: limegreen;
        }
      }
      @media (min-width: 481px) and (max-width: 1200px) {
        body {
          background-color: powderblue;
        }
      }
      @media (min-width: 319px) and (max-width: 480px) {
        body {
          background-color: lightsalmon;
        }
      }
    </style>
  </head>

  <body></body>
</html>
```









#### Simulate different devices

8:25 - Simulation of different devices from chrome

8:37 - Devices chrome



![image-20240514181027901](./Images/image-20240514181027901.png)









### 52. Project - Web Design Agency Website



Dimensions:

Next hub max - 1280 x 800

Nest Hub - 1024 x 600

Samsung Galaxy A51/71 - 412 x 914

Ipad Pro - 1024 x 1366	

Iphone Max pro - 430 x 932









#### My Solution

Documents\GitHub\WebDevUdemy\Test\8.4 Web Design Agency Project\index.html



Need to reDo again once -



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Agency</title>
    <link rel="stylesheet" href="./style.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <div class="main">
      <img class="logo" src="./assets/images/logo.png" alt="logo" />
      <h1>We are a <span class="span">Creative</span> Design Agency</h1>
      <div class="flex-container">
        <div class="left card">
          <img
            class="tile-image"
            src="./assets/images/beautiful.jpg"
            alt="hand and flower in water"
          />
          <h2 class="card-title">Beauty</h2>
          <p>
            We strive to create the most beautiful websites for all your needs.
            Working closely with you to design and develop an amazing website
            for your business.
          </p>
        </div>

        <div class="right card">
          <img
            class="tile-image"
            src="./assets/images/construction.jpg"
            alt="metal structure"
          />
          <h2 class="card-title">Construction</h2>
          <p>
            Built by our team of professional developers, we ensure the most
            rigourous and modern websites. Built from scratch using HTML and
            CSS. Only the best for you.
          </p>
        </div>
      </div>
    </div>
    <footer>
      <p>Create. Develop. Design.</p>
    </footer>
  </body>
</html>

```



Documents\GitHub\WebDevUdemy\8.4 Web Design Agency Project\style.css

```css
@media (min-width: 768px) {
  body {
    font-family: "Poppins", sans-serif;
    margin: 50px 50px 0 50px;
    background-color: #faf9f6;
    display: flex;
    flex-direction: column;
    min-height: 95vh;
  }
  .flex-container {
    display: flex;
  }
  .card {
    flex: 1;
  }
  .main {
    flex: 1;
  }

  .tile-image {
    float: left;
    width: 40%;
    height: 85%;
    margin-right: 5%;
  }
  h1 {
    font-size: 5rem;
    width: 100%;
  }
  p {
    width: 90%;
  }
}

@media (max-width: 767px) {
  body {
    font-family: "Poppins", sans-serif;
    margin: 50px 50px 0 50px;
    background-color: #faf9f6;
    display: flex;
    flex-direction: column;
    min-height: 95vh;
  }

  .main {
    flex: 1;
  }

  .tile-image {
    width: 100%;
    height: 100%;
    margin-right: 5%;
  }
  h1 {
    font-size: 5rem;
    width: 100%;
    font-size: 56px;
  }
}

.span {
  color: navy;
}

/* h2 {
  margin-left: 20px;
} */

footer {
  text-align: right;
  color: midnightblue;
}

```





#### From Solution



Documents\GitHub\WebDevUdemy\8.4 Web Design Agency Project\solution.html

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Agency</title>
    <link rel="stylesheet" href="./solution.css" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <div class="main">
      <img class="logo" src="./assets/images/logo.png" alt="logo" />
      <h1>
        We are a <span class="creative">Creative</span> <br />Design Agency
      </h1>
      <div class="left card">
        <img
          class="tile-image"
          src="./assets/images/beautiful.jpg"
          alt="hand and flower in water"
        />
        <h2 class="card-title">Beauty</h2>
        <p class="card-text">
          We strive to create the most beautiful websites for all your needs.
          Working closely with you to design and develop an amazing website for
          your business.
        </p>
      </div>

      <div class="right card">
        <img
          class="tile-image"
          src="./assets/images/construction.jpg"
          alt="metal structure"
        />
        <h2 class="card-title">Construction</h2>
        <p>
          Built by our team of professional developers, we ensure the most
          rigourous and modern websites. Built from scratch using HTML and CSS.
          Only the best for you.
        </p>
      </div>
    </div>
    <footer>
      <p>Create. Develop. Design.</p>
    </footer>
  </body>
</html>

```





Documents\GitHub\WebDevUdemy\8.4 Web Design Agency Project\solution.css

```css
body {
  font-family: "Poppins", sans-serif;
  margin: 50px 50px 0 50px;
  background-color: #faf9f6;
  display: flex;
  flex-direction: column;
  min-height: 95vh;
}
.main {
  flex: 1;
}

h1 {
  font-size: 5rem;
}

footer {
  text-align: right;
  color: midnightblue;
}

.tile-image {
  height: 200px;
  float: left;
  margin-right: 50px;
}

.card {
  width: 45%;
}

.left {
  float: left;
}

.right {
  float: right;
}

.creative {
  color: midnightblue;
}

@media (max-width: 680px) {
  .logo {
    width: 100px;
  }

  h1 {
    font-size: 3.5rem;
    text-align: center;
  }

  .card {
    width: 100%;
    display: block;
    margin-bottom: 30px;
    text-align: justify;
  }

  .card img {
    margin-bottom: 10px;
    width: 100%;
    display: inline;
    object-fit: cover;
  }
}

```





##### Technique

used Float left and right on the left and right div classes. 

And inside when 1st one <img> starts float again. 

This above is for full size,

For smaller size - they made it 100% width.





![image-20240520213607056](./Images/image-20240520213607056.png)



![image-20240520213625955](./Images/image-20240520213625955.png)







### 53. Tip from Angela - how to deal with Procrastination



## Section 9 - FlexBox



### 54. Display: Flex



1:38 - Table

2:09 - No no for styling - only if real table is needed

4:52 - 2005-2010 - floats were used

5:31 - Float when to use

6:41 - Flex; can do easily do layout
Gap ;

7:36 - Display - good advice

8:12 - Good summary

8:23 - Now flex

8:52 - Now this in flex box

9:37 - Default 100%width

10:02 - In-line flex













#### Table

1:38 - Table

they used to use HTML for tables before. still is in use in modern times.   And use only if you really need table.

but dont use for styling .

![image-20240520220213657](./Images/image-20240520220213657.png)





2:09 - No no for styling - only if real table is needed



#### Inline Block 

then they used this for layouts. there are problems with this too.



![image-20240520220336799](./Images/image-20240520220336799.png)





#### Another inflexible way 

Absolute - 

just illustrating evolution. even this it NOT ideal and inflexible. not responsive.

![image-20240520220448362](./Images/image-20240520220448362.png)





#### Float 

2005-2010 - floats were used for layout.

![image-20240520220847338](./Images/image-20240520220847338.png)



4:52 - 2005-2010 - floats were used



too hacky. hard to fix.

![image-20240820140030734](./Images/image-20240820140030734.png)



5:31 - Float when to use



##### Float when to use

![image-20240520221040039](./Images/image-20240520221040039.png)

dont use float for layout.





https://saijogeorge.com/css-puns/



![image-20240820135138811](./Images/image-20240820135138811.png)

#### Flexbox

incredibly easy to use

wrap it in a container.

##### display: flex

6:41 - Flex; can do easily do layout

##### Gap ;

![image-20240520221426974](./Images/image-20240520221426974.png)

7:36 - Display - good advice

this flex is not like inline-block, block etc.. need to think of this totally separately.

8:12 - Good summary

##### w/o flex

![image-20240520221713036](./Images/image-20240520221713036.png)

8:23 - Now flex



![image-20240520221749289](./Images/image-20240520221749289.png)



##### with flex

8:52 - Now this in flex box - it will ignore block display properties now.

so in Div it will show all its content as its width, so its not necessarily same as other columns.

![image-20240520221804768](./Images/image-20240520221804768.png)



9:37 - Default 100%width

flex will give whole page width. 

![image-20240520221902469](./Images/image-20240520221902469.png)



##### Inline-flex

10:02 - In-line flex

when you do this inline flex then you dont get full width now.

![image-20240820140901567](./Images/image-20240820140901567.png)





#### Exercise



GitHub\WebDevUdemy\9.0 Display Flex\index.html

just arrange the vertical to horizontal.

using gap or 1 rem.





```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Column Layout Methods</title>
  <style>
    p {
      padding: 0;
      margin: 0;
      font-weight: 700;
    }

    li {
      list-style: none;
    }

    .container {
      padding: 10px;
      background-color: gold;
    }
    /* added this  */
    .container {
      display: flex;
      gap: 10px;
    }

  </style>
</head>

<body>
  <div class="container">
    <p>Page Layout Methods</p>

    <li><a href="./html-table.html">HTML Table</a></li>
    <li><a href="./inline-block.html">Inline-Block</li>
    <li><a href="./absolute-position.html">Absolute Positioning</li>
    <li><a href="./float.html">Float</li>
    <li><a href="./flex.html">Flexbox</li>

  </div>
</body>

</html>
```

![image-20240820141410120](./Images/image-20240820141410120.png)



### 55. Flex Direction



Row and Column layouts



default - Block and inline block. go from top to bottom.

Flex - its like container into the Row.



#### Flex Direction

because of Flex direction. Default direction is Row.

Think how next item is stacked onto other. Its like rows.

you are setting the Main axis. Left to right.



Cross Axis - vertical - top to bottom.





![image-20240820172537092](./Images/image-20240820172537092.png)



now main axis top to bottom. Cross axis is left to right.

#### flex-basis: 100px;

Has to be on the Child and not container.

if its larger basis - it will set width if its Row. 



#### Exercise - 

9.1-Flex-Direction\9.1 Flex Direction\index.html

change it to vertical. height is 100px.

##### display: inline-flex;

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Flex Direction</title>
    <!-- HINT:
  https://developer.mozilla.org/en-US/docs/Web/CSS/Universal_selectors
  https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Combinators 
  -->
    <style>
      .container {
        color: white;
        border: 5px solid gold;
        display: flex;
        flex-direction: column;
        /* width: 50px; */
        display: inline-flex;
      }
      div > div {
        flex-basis: 100px;
      }

      /*
Select all the elements that are the direct
children of the .container class.
    */

      .red {
        background-color: #eb4d4b;
      }
      .orange {
        background-color: #f0932b;
      }
      .yellow {
        background-color: #f6e58d;
      }
      .green {
        background-color: #6ab04c;
      }
      .blue {
        background-color: #4834d4;
      }
      .indigo {
        background-color: #30336b;
      }
      .purple {
        background-color: #be2edd;
      }
    </style>
  </head>

  <body>
    <div class="container">
      <div class="red">Red</div>
      <div class="orange">Orange</div>
      <div class="yellow">Yellow</div>
      <div class="green">Green</div>
      <div class="blue">Blue</div>
      <div class="indigo">Indigo</div>
      <div class="purple">Purple</div>
    </div>
  </body>
</html>

```





![image-20240820174523097](./Images/image-20240820174523097.png)

#### done



### 56. Flex Layout



default

#### order: 0;



![image-20240820215136711](./Images/image-20240820215136711.png)



![image-20240820215254217](./Images/image-20240820215254217.png)



#### order

![image-20240820215332223](./Images/image-20240820215332223.png)





default:

#### flex-wrap: nowrap;







#### flex-wrap: wrap;

![image-20240820215448663](./Images/image-20240820215448663.png)



This is property on the parent.

![image-20240820215525937](./Images/image-20240820215525937.png)



5:49

#### demo

https://appbrewery.github.io/flex-layout/



#### justify-content: flex-start;

Flex start





![image-20240821180937415](./Images/image-20240821180937415.png)





#### justify-content: flex-start;

![image-20240821220230221](./Images/image-20240821220230221.png)



#### justify-content: center

![image-20240821220319243](./Images/image-20240821220319243.png)





#### justify-content: space-between

![image-20240821220408779](./Images/image-20240821220408779.png)



#### align-items: flex-start;

#### height: 70vh;    (viewport height)



![image-20240821220925971](./Images/image-20240821220925971.png)





![image-20240821221414174](./Images/image-20240821221414174.png)







#### demo - 

https://appbrewery.github.io/flex-layout/

try different options here - align-items: stretch

12;36

Works better no wrap for some of the align items

![image-20240821221507672](./Images/image-20240821221507672.png)





#### align-self

on the item and not container



![image-20240821221636837](./Images/image-20240821221636837.png)





#### cheat sheet (IMP)

https://css-tricks.com/snippets/css/a-guide-to-flexbox/



#### Align content

Align content only works w wrap



17:09

#### froggy game

 https://appbrewery.github.io/flexboxfroggy/



this below link very imp to learn to play to know how to place them.

https://appbrewery.github.io/flex-layout/





##### level 4



![image-20240822100654895](./Images/image-20240822100654895.png)

![image-20240822100639253](./Images/image-20240822100639253.png)

​	

##### level 5 

![image-20240822100725550](./Images/image-20240822100725550.png)



![image-20240822100917484](./Images/image-20240822100917484.png)



##### level 6

![image-20240822100959337](./Images/image-20240822100959337.png)







![image-20240822101023670](./Images/image-20240822101023670.png)



##### Level 7

![image-20240822101059641](./Images/image-20240822101059641.png)





![image-20240822101301553](./Images/image-20240822101301553.png)







##### Level 8

![image-20240822101323834](./Images/image-20240822101323834.png)



![image-20240822101744159](./Images/image-20240822101744159-1724347064757-1.png)





##### level 9

![image-20240822101815446](./Images/image-20240822101815446.png)





![image-20240822101942171](./Images/image-20240822101942171.png)





##### level 10

![image-20240822102005824](./Images/image-20240822102005824.png)



![image-20240822102137929](./Images/image-20240822102137929.png)



##### level 11



![image-20240822103907594](./Images/image-20240822103907594.png)





![image-20240822103954084](./Images/image-20240822103954084.png)



##### Level 12

![image-20240822104011603](./Images/image-20240822104011603.png)





![image-20240822104132930](./Images/image-20240822104132930.png)





##### level 13



![image-20240822110544957](./Images/image-20240822110544957.png)



![image-20240822110643100](./Images/image-20240822110643100.png)



##### Level 14



![image-20240822110721444](./../EncodeBootcamps/Gizathon/image-20240822110721444.png)





![image-20240822110747982](./Images/image-20240822110747982.png)





##### level 15

![image-20240822110812907](./Images/image-20240822110812907.png)



![image-20240822110840622](./Images/image-20240822110840622.png)





##### level 16

![image-20240822110945804](./Images/image-20240822110945804.png)



![image-20240822111019760](./Images/image-20240822111019760.png)



##### level 17



![image-20240822112020774](./Images/image-20240822112020774.png)



![image-20240822112001026](./Images/image-20240822112001026.png)



##### level 18

![image-20240822112059245](./Images/image-20240822112059245.png)



![image-20240822112144784](./Images/image-20240822112144784.png)





##### level 19

![image-20240822112356529](./Images/image-20240822112356529.png)





![image-20240822112529465](./Images/image-20240822112529465.png)



##### level 20

same as above but only 1 line seems like; 

![image-20240822112548653](./Images/image-20240822112548653.png)



![image-20240822112645306](./Images/image-20240822112645306.png)



##### level 21

![image-20240822112829110](./Images/image-20240822112829110.png)



![image-20240822113258321](./Images/image-20240822113258321.png)



##### level 22



![image-20240822113325883](./Images/image-20240822113325883.png)





![image-20240822113347949](./Images/image-20240822113347949.png)



##### level 23

![image-20240822113505398](./Images/image-20240822113505398.png)



![image-20240822113607168](./Images/image-20240822113607168.png)





##### level 24



![image-20240822114400438](./Images/image-20240822114400438.png)





![image-20240822114334428](./Images/image-20240822114334428.png)



















### 57. Flex Sizing



#### Algo

![image-20240822132150964](./Images/image-20240822132150964.png)



start

![image-20240822132306691](./Images/image-20240822132306691.png)



4:35 

#### Shrink

min. content size

![image-20240822132402824](./Images/image-20240822132402824.png)





Good to know it goes to min content size



#### default behavior

5:32

Default behavior w/o anything else applied.

![image-20240822132527467](./Images/image-20240822132527467.png)







#### max-width

is length of text.

![image-20240822132709511](./Images/image-20240822132709511.png)



#### min-width

longest word.







#### width

6:24

manual width- 100px.



![image-20240822132835014](./Images/image-20240822132835014.png)





#### flex-basis

9:01

![image-20240823000947602](./Images/image-20240823000947602.png)



#### max and min width



![image-20240823001043642](./Images/image-20240823001043642.png)





11:35



![image-20240823001151260](./Images/image-20240823001151260.png)



#### width vs flex-basis

whichever is smaller looks like;

![image-20240823001323644](./Images/image-20240823001323644.png)



13:38



![image-20240823001449783](./Images/image-20240823001449783.png)





#### flex-grow, flex-shrink

14:38



![image-20240823001555437](./Images/image-20240823001555437.png)

if both are 0, then its almost like not even a flex box.



#### flex-grow

15:50

![image-20240823001704201](./Images/image-20240823001704201.png)





#### default setting

![image-20240823001750124](./Images/image-20240823001750124.png)

![image-20240823001842577](./Images/image-20240823001842577.png)





#### flex-basis default auto

18:24

![image-20240823001918423](./Images/image-20240823001918423.png)









#### flex-basis equal

18:46

![image-20240823002023347](./Images/image-20240823002023347.png)







#### shorthand

![image-20240823002119729](./Images/image-20240823002119729.png)





#### even shorter

19:31

![image-20240823002703767](./Images/image-20240823002703767.png)



#### flex:1, flex:2 ...

20:14

![image-20240823002814537](./Images/image-20240823002814537.png)



#### Exercise

20:34

its online.



https://appbrewery.github.io/flexbox-sizing-exercise/



```css
/* Write your CSS code below to make the blue items size, grow and shrink like the green ones.*/

.container {
  display: flex;
  justify-content: space-between; 

}
  
.container > * {
background-color: green;

}

.item1 {
flex-basis: 200px;
}

.item2 {

min-width: 200px; 
}

.item3 {

min-width: 400px;
}
```





##### solution

![image-20240823011739893](./Images/image-20240823011739893.png)



### 58. Project Pricing Table



GitHub\WebDevUdemy\9.4-FlexBox-PricingTableProject\index.html



#### Solution 

```html
<!DOCTYPE html>
<html>

<head>
  <title>Flexbox Pricing Table</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Sono:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Sono', sans-serif;
    }

    .pricing-container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      gap: 2rem;
    }

    .pricing-plan {
      flex: 1;
      max-width: 400px;
      padding: 20px;
      background-color: #f2f2f2;
      border-radius: 5px;
      text-align: center;
    }

    .plan-title {
      font-size: 24px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .plan-price {
      font-size: 48px;
      font-weight: bold;
      margin-bottom: 10px;
    }

    .plan-features {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    .plan-features li {
      margin-bottom: 20px;
    }

    .plan-button {
      padding: 10px;
      background-color: #ff6600;
      color: #fff;
      border-radius: 5px;
      border: none;
    }

    @media (max-width: 1250px) {
      .pricing-container {
        flex-direction: column;
        height: 100%;
      }
    }
  </style>
</head>

<body>
  <div class="pricing-container">
    <div class="pricing-plan">
      <div class="plan-title">Basic</div>
      <div class="plan-price">$11.99/month</div>
      <ul class="plan-features">
        <li>✅ 10GB Storage</li>
        <li>✅ 1 User</li>
        <li>🚫 Support</li>
      </ul>
      <button class="plan-button">Sign Up</a>
    </div>
    <div class="pricing-plan">
      <div class="plan-title">Standard</div>
      <div class="plan-price">$19.99/month</div>
      <ul class="plan-features">
        <li>✅ 50GB Storage</li>
        <li>✅ 5 Users</li>
        <li>✅ Phone &amp; Email Support</li>
      </ul>
      <button class="plan-button">Sign Up</a>
    </div>
    <div class="pricing-plan">
      <div class="plan-title">Premium</div>
      <div class="plan-price">$49.99/month</div>
      <ul class="plan-features">
        <li>✅ 100GB Storage</li>
        <li>✅ 10 Users</li>
        <li>✅ 24/7 Support</li>
      </ul>
      <button class="plan-button">Sign Up</a>
    </div>
  </div>

</body>

</html>
```





![image-20240826115746224](./Images/image-20240826115746224.png)



![image-20240826115733845](./Images/image-20240826115733845.png)











### 59. Angela Tips - Building a Programming Habit





### 60. Display: Grid





#### Flex vs Grid

![image-20240826132747455](./Images/image-20240826132747455.png)



2:33

![image-20240826132847811](./Images/image-20240826132847811.png)





![image-20240826132944801](./Images/image-20240826132944801.png)



#### Usage1

![image-20240826133032158](./Images/image-20240826133032158.png)





#### link demo - Grid vs Flex



https://appbrewery.github.io/grid-vs-flexbox

play with how it responsive it is etc.



##### differences



![image-20240826133328014](./Images/image-20240826133328014.png)







#### example1

7:26;

![image-20240826133409998](./Images/image-20240826133409998.png)





![image-20240826133508906](./Images/image-20240826133508906.png)







#### Exercise 

9:09



GitHub\WebDevUdemy\10.0-DisplayGrid\10.0 Display Grid\index.html

![image-20240826135130332](./Images/image-20240826135130332.png)



##### Important 

width: 800px; in the .container

since otherwise it occupies whole HTML. that's greater than the 800px;



w/o width it would look like below:



![image-20240826135206150](./Images/image-20240826135206150.png)





![image-20240826135251858](./Images/image-20240826135251858.png)







### 61. Grid Sizing



#### grid-template-rows and columns

##### Using px 

is not responsive.

![image-20240826135620978](./Images/image-20240826135620978.png)









##### Using REM

![image-20240826135755472](./Images/image-20240826135755472.png)

![image-20240826135809589](./Images/image-20240826135809589.png)



2:00



![image-20240826135835167](./Images/image-20240826135835167.png)









##### shortcut- grid-template

2:58

not recommended.

![image-20240826135917019](./Images/image-20240826135917019.png)











##### auto 

more responsive

![image-20240826140039632](./Images/image-20240826140039632.png)







![image-20240826140112411](./Images/image-20240826140112411.png)





##### auto row

auto row is different based on content.

Auto- diff for column & row meanings 

![image-20240826140145611](./Images/image-20240826140145611.png)



4:54

![image-20240826140237806](./Images/image-20240826140237806.png)



##### auto column

is responsive



#### demo

https://appbrewery.github.io/grid-sizing

play around. 

Fixed size and Auto size

![image-20240826140341666](./Images/image-20240826140341666.png)





#### Fractional sizing

![image-20240826140655076](./Images/image-20240826140655076.png)







##### small personal exercises

7:10 - 

Do these & see .. change content & see 

GitHub\WebDevUdemy\Test\test61-1.html

![image-20240826140752036](./Images/image-20240826140752036.png)





8:21

![image-20240826141427563](./Images/image-20240826141427563.png)



#### minmax

9:16

![image-20240826141536392](./Images/image-20240826141536392.png)



Responsive between 400 & 800 



#### Repeat 





![image-20240826141640385](./Images/image-20240826141640385.png)







11:29

![image-20240826141657611](./Images/image-20240826141657611.png)







#### row/column declaration > actual divs

![image-20240826141803457](./Images/image-20240826141803457.png)





#### more divs

12:56

![image-20240826141849927](./Images/image-20240826141849927.png)



5 - will be based on content.



#### Grid auto row 

if more div declared then it will continue the grid properties on it.

![image-20240826141931730](./Images/image-20240826141931730.png)

![image-20240826142716172](./Images/image-20240826142716172.png)





This gives 300px to new rows.



#### Demo 2



https://appbrewery.github.io/grid-sizing



do the other ones - fractional, MinMax, Repeat.



change properties from inspect and play around - or watch this part just for revision.

![image-20240826142120236](./Images/image-20240826142120236.png)







#### Grid chip from inspect 

on the inspect on the .grid-container - next to it it will show "grid" when we click on that we can some things about grid.

![image-20240826142900053](./Images/image-20240826142900053.png)







##### layout tab



![image-20240826143037945](./Images/image-20240826143037945.png)





for me its below the elements tab.

![image-20240826143214151](./Images/image-20240826143214151.png)



#### Exercise

17:04



https://appbrewery.github.io/grid-sizing

go to test.



##### solution - mine

```
/* Write your CSS code below to make the purple items size, grow and shrink like the green ones.*/

.grid-container {
        display: grid;
        grid-template-rows: 1fr 1fr 2fr ;
        grid-template-columns: auto 400px minmax(200px,500px);
        gap: 0px;
        grid-auto-rows: 50px;
}
```



##### solution-hers

![image-20240826230415394](./Images/image-20240826230415394.png)







### 62. Grid Placement 



#### Grid normal

![image-20240827001352004](./Images/image-20240827001352004.png)



#### Grid cell



![image-20240827001424056](./Images/image-20240827001424056.png)



#### Multiple grid cells

![image-20240827001453009](./Images/image-20240827001453009.png)











#### Good initial grid summary of past lesson 

![image-20240827001528544](./Images/image-20240827001528544.png)



#### Good summary Grid

![image-20240827001555425](./Images/image-20240827001555425.png)



#### Height / Width

Height . If it’s not there takes content. But width default takes full html width

![image-20240827001652387](./Images/image-20240827001652387.png)







#### behavior stacking

![image-20240827001745769](./Images/image-20240827001745769.png)





#### 3 rem -

#### gap

Basically gap in grid means as dont need to rely on padding margin etc to create that gap 





#### Exercise1

6:42

GitHub\WebDevUdemy\10.2-GridPlacement\10.2 Grid Placement\exercise1.html

##### solution

3 lines:

      /* Solution */
      display: flex;
      align-items: center;
      justify-content: center;







```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid Placement</title>
  <style>
    body {
      padding: 0;
      margin: 0;
    }

    .container {
      height: 100vh;
      display: grid;
      gap: 3rem;
      grid-template-columns: 1fr 1fr 1.5fr;
      grid-template-rows: 1fr 1fr;
    }

    .item {
      font-size: 5rem;
      color: white;
      font-family: Arial, Helvetica, sans-serif;
      background-color: blueviolet;
      
      /* Solution */
      display: flex;
      align-items: center;
      justify-content: center;
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="item cowboy">🤠</div>
    <div class="item astronaut">👨‍🚀</div>
    <div class="item book">📖</div>
  </div>
</body>

</html>
```





flex box provides one of the easier way to center.



![image-20240827003007161](./Images/image-20240827003007161.png)

#### grid-column: span 2



![image-20240827003322309](./Images/image-20240827003322309.png)



GitHub\WebDevUdemy\10.2-GridPlacement\10.2 Grid Placement\demo1.html





#### shows line number in inspect



![image-20240827003757518](./Images/image-20240827003757518.png)



 

![image-20240827003904932](./Images/image-20240827003904932.png)





##### click on Triangle.

![image-20240827003922964](./Images/image-20240827003922964.png)

its actually 2 sub properties and this was shortcut.



#### grid-column-start / grid-column-end



![image-20240827004038636](./Images/image-20240827004038636.png)





#### line count from rightside - last line in Grid

![image-20240827004209545](./Images/image-20240827004209545.png)







#### 2 to -1

helpful if we have lot of columns. or they created programmatically or some other automatic way.

![image-20240827004402796](./Images/image-20240827004402796.png)



##### another example

![image-20240827004612444](./Images/image-20240827004612444.png)







##### example 2

![image-20240827004654984](./Images/image-20240827004654984.png)



#### grid-column breakdown

15:33



![image-20240827004814396](./Images/image-20240827004814396.png)





#### ex another

GitHub\WebDevUdemy\10.2-GridPlacement\10.2 Grid Placement\demo2.html

span 2 here on astronaut does not have space to occupy 2 spaces - thats because we had only 3 columns defined

grid-template-columns: 1fr 1fr 1.5fr;

![image-20240827160537845](./Images/image-20240827160537845.png)









#### order 1



![image-20240827160702032](./Images/image-20240827160702032.png)



![image-20240827160738337](./Images/image-20240827160738337.png)





#### direction

![image-20240827160825523](./Images/image-20240827160825523.png)



#### exercise 2 - 

18:32





##### solution:



```html
        .astronaut {
        .....
        /* TODO: Make the astronaut box look like the goal2 image. */
        /* grid-column: span 2; */
        /* or */
        grid-column-start: 1;
        grid-column-end: 3;
```



full code 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Grid Placement</title>
    <style>
      body {
        padding: 0;
        margin: 0;
      }

      .container {
        height: 100vh;
        display: grid;
        gap: 3rem;
        grid-template-columns: 1fr 1fr 1.5fr;
        grid-template-rows: 1fr 1fr;
      }

      .item {
        font-size: 5rem;
        color: white;
        font-family: Arial, Helvetica, sans-serif;
        background-color: blueviolet;
        display: flex;
        align-items: center;
        justify-content: center;
      }

      .cowboy {
        background-color: #00b9ff;
        grid-column: span 2;
      }

      .astronaut {
        background-color: #03989e;
        order: 1;

        /* TODO: Make the astronaut box look like the goal2 image. */
        /* grid-column: span 2; */
        /* or */
        grid-column-start: 1;
        grid-column-end: 3;
      }
    </style>
  </head>

  <body>
    <div class="container">
      <div class="item cowboy">🤠</div>
      <div class="item astronaut">👨‍🚀</div>
      <div class="item book">📖</div>
    </div>
  </body>
</html>
```



![image-20240827161732550](./Images/image-20240827161732550.png)



##### solution2

![image-20240827174647672](./Images/image-20240827174647672.png)



#### shorthand

![image-20240827174722178](./Images/image-20240827174722178.png)





![image-20240827174758079](./Images/image-20240827174758079.png)





#### grid-area

but if 1 uses grid area - all others have to use grid area too.





#### exercise 3

##### solution

```html
      .book {
        background-color: #e58331;
        /* TODO: Make the book div look like 
      the goal3 image using grid-row. */
        grid-row-start: 1;
        grid-row-end: 3;
      }
```





##### Full code

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Grid Placement</title>
    <style>
      body {
        padding: 0;
        margin: 0;
      }

      .container {
        height: 100vh;
        display: grid;
        gap: 3rem;
        grid-template-columns: 1fr 1fr 1.5fr;
        grid-template-rows: 1fr 1fr;
      }

      .item {
        font-size: 5rem;
        color: white;
        font-family: Arial, Helvetica, sans-serif;
        background-color: blueviolet;
        display: flex;
        align-items: center;
        justify-content: center;
      }

      .cowboy {
        background-color: #00b9ff;
        grid-column: span 2;
      }

      .astronaut {
        background-color: #03989e;
        order: 1;
        grid-area: 2 / 1 / 3 / 3;
      }

      .book {
        background-color: #e58331;
        /* TODO: Make the book div look like 
      the goal3 image using grid-row. */
        grid-row-start: 1;
        grid-row-end: 3;
      }
    </style>
  </head>

  <body>
    <div class="container">
      <div class="item cowboy">🤠</div>
      <div class="item astronaut">👨‍🚀</div>
      <div class="item book">📖</div>
    </div>
  </body>
</html>

```



##### solution 2

![image-20240827175247454](./Images/image-20240827175247454.png)







##### solution 3

![image-20240827175344365](./Images/image-20240827175344365.png)







#### grid - can overlay

grid allows to overlay - so here orange is sitting on top of blue





![image-20240827175627797](./Images/image-20240827175627797.png)





#### exercise - grid-garden

https://appbrewery.github.io/gridgarden



##### level 1

![image-20240827175944597](./Images/image-20240827175944597.png)





![image-20240827180017502](./Images/image-20240827180017502.png)







##### level 2

![image-20240827180045642](./Images/image-20240827180045642.png)



![image-20240827180136802](./Images/image-20240827180136802.png)





##### level 3

![image-20240827180205784](./Images/image-20240827180205784.png)





![image-20240827180230560](./Images/image-20240827180230560.png)



##### level 4

![image-20240827180308025](./Images/image-20240827180308025.png)



![image-20240827180422590](./Images/image-20240827180422590.png)





##### level 5

![image-20240827180519706](./Images/image-20240827180519706.png)







![image-20240827180534028](./Images/image-20240827180534028.png)





##### level 6

![image-20240827180600837](./Images/image-20240827180600837.png)



![image-20240827180711516](./Images/image-20240827180711516.png)





##### level 7



![image-20240828093509956](./Images/image-20240828093509956-1724862911417-1.png)





![image-20240828093558476](./Images/image-20240828093558476.png)



##### level 8



![image-20240828093629241](./Images/image-20240828093629241.png)



![image-20240828093712592](./Images/image-20240828093712592.png)





##### level 9

![image-20240828093751156](./Images/image-20240828093751156.png)



![image-20240828093824785](./Images/image-20240828093824785.png)



or - 

grid-column-start: span 3;

##### level 10

![image-20240828093921188](./Images/image-20240828093921188.png)







![image-20240828094040974](./Images/image-20240828094040974.png)



or

grid-column: 4 / 6;



##### level 11



![image-20240828094606084](./Images/image-20240828094606084.png)







![image-20240828094646321](./Images/image-20240828094646321.png)



or 

grid-column: 2 / span 3;









##### level 12

![image-20240828103011747](./Images/image-20240828103011747.png)



![image-20240828103040709](./Images/image-20240828103040709.png)



##### level 13

![image-20240828103625119](./Images/image-20240828103625119.png)





![image-20240828103811305](./Images/image-20240828103811305.png)





or - 

grid-row: 3 / span 3;



##### level 14



![image-20240828103842898](./Images/image-20240828103842898.png)







![image-20240828103915941](./Images/image-20240828103915941.png)



##### level 15

![image-20240828103942936](./Images/image-20240828103942936.png)





![image-20240828104043788](./Images/image-20240828104043788.png)





##### level 16

![image-20240828104108786](./Images/image-20240828104108786.png)



![image-20240828104254759](./Images/image-20240828104254759.png)



##### level 17

![image-20240828104330077](./Images/image-20240828104330077.png)







![image-20240828104443712](./Images/image-20240828104443712.png)



##### level 18





![image-20240828104806176](./Images/image-20240828104806176.png)





![image-20240828104507339](./Images/image-20240828104507339.png)



##### level 19



![image-20240828105025455](./Images/image-20240828105025455.png)

![image-20240828104836880](./Images/image-20240828104836880.png)



##### level 20



![image-20240828105242010](./Images/image-20240828105242010.png)





![image-20240828105228999](./Images/image-20240828105228999.png)



##### level 21

![image-20240828105330537](./Images/image-20240828105330537.png)





![image-20240828105447293](./Images/image-20240828105447293.png)



##### level 22

![image-20240828105508048](./Images/image-20240828105508048.png)



![image-20240828105606960](./Images/image-20240828105606960.png)





##### level 23

![image-20240828105732347](./Images/image-20240828105732347.png)



![image-20240828105914628](./Images/image-20240828105914628.png)



##### level 24

![image-20240828105938137](./Images/image-20240828105938137.png)





![image-20240828110119201](./Images/image-20240828110119201.png)

##### level 25

![image-20240828110146728](./Images/image-20240828110146728.png)



![image-20240828110259480](./Images/image-20240828110259480.png)



##### level 26

![image-20240828110321981](./Images/image-20240828110321981.png)



DID NOT ANSWER YET.



##### level 27



![image-20240828111006103](./Images/image-20240828111006103.png)



![image-20240828111659229](./Images/image-20240828111659229.png)





##### level 28

![image-20240828111924734](./Images/image-20240828111924734.png)





![image-20240828140308236](./Images/image-20240828140308236.png)







### 63. Project - Mondarian Painting



Dutch painter

![image-20240828143733596](./Images/image-20240828143733596.png)





![image-20240828143750023](./Images/image-20240828143750023.png)



$50.6 Million on auction





![image-20240828143822460](./Images/image-20240828143822460.png)







#### Solution 



##### Imp

body is flex ; that's a good trick that keeps the whole below stuff inside 1 container.



```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mondrian Project</title>
  <style>
    /* 
    Write your CSS here 
    Line Colour: #000
    White: #F0F1EC
    Red: #E72F24
    Black: #232629
    Blue: #004592
    Yellow: #F9D01E
    */
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      padding: 0;
    }

    .container {
      height: 748px;
      width: 748px;
      display: grid;
      background-color: #000;
      grid-template-columns: 320px 198px 153px 50px;
      grid-template-rows: 414px 130px 155px 22px;
      gap: 9px;
    }

    .item {
      background-color: #F0F1EC;
    }

    .red {
      background-color: #E72F24;
    }

    .white1 {
      grid-column: span 3;
    }

    .white2 {
      grid-row: span 2;
    }

    .white3 {
      grid-area: 2 / 2 / 4 /4
    }

    .blue {
      background-color: #004592;
      border-bottom: 10px solid #000;
    }

    .white4 {
      grid-row: span 2;
    }

    .yellow {
      background-color: #F9D01E;
    }

    .black {
      background-color: #232629;
    }
  </style>
</head>

<body>
  <!-- Write your HTML here -->

  <div class="container">
    <div class="item red"></div>
    <div class="item white1"></div>
    <div class="item white2"></div>
    <div class="item white3"></div>

    <div class="item blue"></div>
    <div class="item white4"></div>

    <div class="item"></div>
    <div class="item yellow"></div>
    <div class="item black"></div>
  </div>
</body>

</html>
```





## Section 11 - Bootstrap



### 64. What is Bootstrap



To do the notes





### 65. Bootstrap Layout



To do the notes



### 66. Bootstrap Components



we can design - Cards buttons carousals, navs etc.

1:20



#### Components

https://getbootstrap.com/docs/5.3/getting-started/introduction/

https://getbootstrap.com/docs/5.3/components/buttons/

![image-20240901103020921](./Images/image-20240901103020921.png)



#### named buttons



![image-20240901102849253](./Images/image-20240901102849253.png)



from the Website 

![image-20240901103055014](./Images/image-20240901103055014.png)



##### button exercise 

3:06

real simple one using bootstrap

![image-20240901102408777](./Images/image-20240901102408777.png)



##### cards exercise

https://getbootstrap.com/docs/5.3/components/card/



copy card code

![image-20240901104150849](./Images/image-20240901104150849.png)

we already did earlier - 

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bootstrap Components</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-aFq/bzH65dt+w6FI2ooMVUpc+21e0SRygnTpmBvdBgSdnuTN7QbdgL+OapgHtvPp"
      crossorigin="anonymous"
    />
    <style></style>
  </head>

  <body>
    <!-- <button class="btn btn-success">Ok</button>    --- did for exercise button simple one-->

    <div class="card" style="width: 18rem">
      <img src="./dog.jpg" class="card-img-top" alt="dog moving bod" />
      <div class="card-body">
        <h5 class="card-title">Card title</h5>
        <p class="card-text">
          Some quick example text to build on the card title and make up the
          bulk of the card's content.
        </p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
      </div>
    </div>
  </body>
</html>
```



![image-20240901104115358](./Images/image-20240901104115358.png)







#### Navs component

3;47

https://getbootstrap.com/docs/5.3/components/navbar/

Bootstrap nav bars are best designed i see.

##### Brand at top left

![image-20240901104346008](./Images/image-20240901104346008.png)



##### image and text

![image-20240901104420929](./Images/image-20240901104420929.png)



another area for nav bars is from examples

##### examples-> Snippets -> Header

![image-20240901104550081](./Images/image-20240901104550081.png)



4:54 

we will build Move It website.

1 page multiple sections website.

we will show how easy it is to build with bootstrap.



5:38

#### Move it Website creation



GitHub\WebDevUdemy\11.2+Bootstrap+Components\11.2 Bootstrap Components\index.html



##### copy nav

and paste in body in html.

![image-20240901110651465](./Images/image-20240901110651465.png)

after i paste i have this. 

![image-20240901111524499](./Images/image-20240901111524499.png)



Below is when is reduce window width.

##### Hamburger Menu

![image-20240901111817585](./Images/image-20240901111817585.png)



but its right now does not show anything.

we have 2nd link.

6:16

##### Scripting link

gives access to bootstrap java script code.

need to put right at the end before body closing tag.

![image-20240901112011069](./Images/image-20240901112011069.png)

6:51



![image-20240901112336384](./Images/image-20240901112336384.png)

##### Disabled

![image-20240901210730511](./Images/image-20240901210730511.png)



![image-20240901210755521](./Images/image-20240901210755521.png)



but we will get rid of this since we dont need it.



now we change to the text we need.

![image-20240901210905668](./Images/image-20240901210905668.png)

8:18



##### Navbar Brand

![image-20240901211209602](./Images/image-20240901211209602.png)

![image-20240901211245890](./Images/image-20240901211245890.png)

have to change this to "Move It"



```html
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
        <a class="navbar-brand" href="#">Move It</a>
```



##### image navbar Brand 

we can also have image for NavBar brand

![](./Images/image-20240901211516879.png)



although we dont use image. instead we will use SVG.



##### svg

https://icons.getbootstrap.com/

here you have all these icons as svg.

you can also search for them.

you can copy or download and use it.

![image-20240901211655341](./Images/image-20240901211655341.png)





![image-20240901211825657](./Images/image-20240901211825657.png)



![image-20240901212119646](./Images/image-20240901212119646.png)

```html
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <!-- <a class="navbar-brand" href="#">Navbar</a> -->
        <a class="navbar-brand" href="#">
          <img src="./box-seam.svg" alt="move it brand icon" height="30" /> Move
          It</a
        >
```

















To do the notes till - 11:24



11:34 - showing how much code is behind the bootstrap. 

![image-20240831172517272](./Images/image-20240831172517272.png)







Examples is really good area to take lot of pieces. and put in your website.

taking from centered hero.

#### centered hero example & build

https://getbootstrap.com/docs/5.3/examples/heroes/

![image-20240831172652007](./Images/image-20240831172652007.png)



Similar to what we want.

![image-20240831172842074](./Images/image-20240831172842074.png)



##### steps to copy

inspect & expand.

![image-20240831172926688](./Images/image-20240831172926688.png)



then hover your mouse over it so it highlights what we want.

![image-20240831172958596](./Images/image-20240831172958596.png)



then you copy that element.

![image-20240831173155704](./Images/image-20240831173155704.png)



copy just below our <nav> .

![image-20240831173245459](./Images/image-20240831173245459.png)



now our Move it site looks like below. 

![image-20240831173319963](./Images/image-20240831173319963.png)

we will fix the image.



![image-20240831173409578](./Images/image-20240831173409578.png)



we now put our moving-van.jpg instead.



![image-20240831173444234](./Images/image-20240831173444234.png) 

then we put our own text now.



![image-20240831173551122](./Images/image-20240831173551122.png)

now we are done with your website!



now move on to next section.

##### Next section

14:17



![image-20240831173622132](./Images/image-20240831173622132.png)



###### Features section

https://getbootstrap.com/docs/5.3/examples/features/



![image-20240831225133182](./Images/image-20240831225133182.png)



![image-20240831225213539](./Images/image-20240831225213539.png)

lot of these bootstrap stuff comes from Appla. looks similar.

###### hover and copy

![image-20240831225306368](./Images/image-20240831225306368.png)





![image-20240831225357834](./Images/image-20240831225357834.png)



###### copy element from Inspect

![image-20240831225449360](./Images/image-20240831225449360.png)







#### custom CSS

so when we copy the icons also don't look like the code we copied.

![image-20240901093341493](./Images/image-20240901093341493.png)



#### How do we know they added more to bootstrap

because all the default ones come from utilities.scss

![image-20240901093602633](./Images/image-20240901093602633.png)



but we have feature.css which is custom on top of bootstrap.

so that feature.css is custom file they created.

![image-20240901092941374](./Images/image-20240901092941374.png)



in this file below they added some custom features to make the icons looks a little diff.

![image-20240901093051172](./Images/image-20240901093051172.png)

so we need to copy that .feature-icon

![image-20240901093647076](./Images/image-20240901093647076.png)

![image-20240901093726916](./Images/image-20240901093726916.png)

17:00

now we get that squared more custom.

![image-20240901093737780](./Images/image-20240901093737780.png)



then next we do have svg part next.



#### svg 

can be installed many diff ways.

Download and put in your folder - like she did.

& access through IMG or SVg element.



alternatively you can copy HTML

![image-20240901094104101](./Images/image-20240901094104101.png)

###### Change svg from examples

18:33

![image-20240831230345342](./Images/image-20240831230345342.png)



###### sizing the icon

height=30



![image-20240831230519719](./Images/image-20240831230519719.png)



19:21 - chevron right svg;



![image-20240831230642011](./Images/image-20240831230642011.png)



replace this - 

![image-20240831230702328](./Images/image-20240831230702328.png)



20:00

#### exercise Carousel



#### Exercises - Move it website 





























































































































































## Install etc



### issue `code .`

`code .` does not work.



https://chat.openai.com/c/80b8284c-a90e-4914-b714-53ff4fb927a8

fixed when i comment out out Conda stuff.





```
..../Documents/GitHub
$ code .
node:internal/modules/cjs/loader:1132
  throw err;
  ^

Error: Cannot find module 'C:\Users\chuck.raghavan\AppData\Local\anaconda3\Library\c\Users\chuck.raghavan\AppData\Local\Programs\Microsoft VS Code\resources\app\out\cli.js'
    at Module._resolveFilename (node:internal/modules/cjs/loader:1129:15)
    at Module._load (node:internal/modules/cjs/loader:974:27)
    at f._load (node:electron/js2c/asar_bundle:2:13377)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:96:12)
    at node:internal/main/run_main_module:23:47 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}

Node.js v18.15.0


C:\Users\chuck.raghavan\AppData\Local\Programs\Microsoft VS Code\Code.exe .
```







![image-20240219175206622](Images/image-20240219175206622.png)





### Moved to X64 VS Code

Installed x64 since VS code on LL laptop was x32.



```
....Documents/GitHub/WebDevUdemy (main)
$ code --version
1.83.1
a6606b6ca720bca780c2d3c9d4cc3966ff2eca12
ia32

.../Documents/GitHub/WebDevUdemy (main)
$ code --version
1.86.2
903b1e9d8990623e3d7da1df3d33db3e42d80eda
x64


```



