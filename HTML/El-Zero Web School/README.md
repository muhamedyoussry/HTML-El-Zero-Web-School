<h1 align="center">HTML El Zero Web School</h1>


## My Notes
- HTML is hypertext markup language used to build the structure of the web.
- We can use single or double quotes for attribute values.
- Paragraph element is a block element (block elements have margin, padding, border, content dimensions)
- plain text is without any tags is inline elements
- there is two types of attributes: global attributes and element attributes
  - class, hidden is example of global attributes
  - src, alt is exmaple of image element attributes
- some formatting elements `<b> <em> <strong> <u> <i> <mark> <small> <del> <small> <ins> <sub> <sup>`
- `<a></a>` anchor tag is an inline element not block element, it has some attribute called target with the following values:
  -  "_blank" open a new page in a new tab
-  also anchor tag `<a>` have attribute called title that shows a title when you hover on the link
-  Span is an inline element to isolate a word with specific CSS or specific operations
-  `<hr>` is used to make a horizontal rule.
-  div is a container for other elements.
- a complete list of HTML entities in this [link](https://www.freeformatter.com/html-entities.html)
- semantic elements like nav, header, section, aside, article; this solution generated for the problem of many div tags and many classes.
- main elements in a website: header, navigation bar, aside, footer, section
- Audio type use comething called MIME type, you can get them from MDN website.
- in the `input` tag we have the required attribute to validate if the input is filled.
- `input` have many attributes like; readonly, disabled, autofocus, minlength, maxlength
- difference between checkbox and radio button in the input type.
- `select` element in HTML.
- `datalist` is a list element like the `select` element but in the `datalist` you can search by typing letters in the list.
-  


<h2 align="center">Assignment 1</h2>

### Q1 Answer
HTML is Hyper Text Markup Language.

### Q2 Answer
```HTML
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <title>
            Booky
        </title>
        <meta name="description" content="Book Store, you can search for books
            reviews and buy e-books or hard copy books" />
        <style>
            /* CSS Code to style our web page */ 
        </style>
        <script>
            /* Java script code */
        </script>
        <link rel="stylesheet" href="" />
    </head>
    <body>
        This is my first page
    </body>
</html>

```

### Q3 Answer
Question 01 => No
<br/>
Question 02 => Yes
<br/>
Question 03 => No
<br/>
Question 04 => No
<br/>

### Q4 Answer

```HTML
<!DOCTYPE html>
<html>
    <head>
        <!--
            meta character attribute is responsible for page character encoding,
            we use it to decalre that Arabic content could be used 
        -->
        <meta charset="UTF-8" />
        <!-- define a description of the web page -->
        <meta name="description" content="This is my bage desctipion" />
        <!-- define keywords for the search engine -->
        <meta name="keywords" content="Books, E-Books, Hard Copy Books" />
        <!-- define the author of a page -->
        <meta name="author" content="Mohamed Youssry" />
        <!-- Setting the viewport to make your website look good on all devices: -->
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>

    </body>
</html>
```


<h2 align="center">Assignment 2</h2>

### Q1 Answer
Question 01 => 
```HTML
<!DOCTYPE html>
```
Question 02 => Quirks mode
<br/>
Question 03 => No
<br/>
Question 04 => No
<br/>
Question 05 => define the headings
<br/>

### Q2 Answer
The Answer is No becaue we can use single or double quotes for attribute values, Also if it is a one word we can write it without any quotations.

### Q3 Answer
No

### Q4 Answer
No they are all the same, browsers do not read spaces or new lines.

### Q5 Answer
title   => global attribute
href    => element attribute
src     => element attribute
hidden  => global attribute
charset => element attribute
clas    => global attribute
id      => global attribute
type    => element attribute

### Q6 Answer
```HTML
<!DOCTYPE html>
<html lang="en">
    <head>
    </head>
    <body>
        <h1>
            Booky Store
        </h1>
        <p> Welcome to Booky Store, your store to search for books reviews and
            buy e-books or hard copy books.</p>
        <h2>
            History Books
        </h2>
        <hr>
        <h3>
            السيرة النبوية
        </h3>
        <p>
            كتاب عن حياة الرسول - صلي الله عليه و سلم -
        </p>
        <hr>
        <h3>
            قصص الأنبياء للشيخ مصطفي العدوي
        </h3>
        <p>
            كتاب عن الأنبياء الذين ضكرو في القرآن
        </p>
        <hr>
        <h3>
            قصص الصحابة
        </h3>
        <p>
            قصص عن أصحاب رسول الله - صلي الله عليه و سلم -
        </p>
        <hr>
        <h2>
            Skills Books
        </h2>
    </body>
</html>

```

<h2 align="center">Assignment 3</h2>

### Q1 Answer
```HTML
<!DOCTYPE html>
<html>

    <head>
        <title>
            Mohamed Youssry Profile
        </title>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta name="description" content="This is Mohamed Youssry profile that
            shows his education, skills, projects and contributions" />
    </head>
    <body>
        <h1> My Info </h1>
        <p> My name is : <b>Mohamed Youssry</b></p>
        <p> I am <strong>Aviable</strong> for hire</p>
        <p> My hour old price is <del>10$</del> And the New price is <mark>30$</mark></p>
        <p> visit my website from this link <a
                href="https://www.linkedin.com/in/mohamed-youssry/"
                target="_blank" title="Go to Youssry LinkedIn">Mohamed
                Youssry</a></p>
        <hr>
        <h1>
            Here is Some of My Clients
        </h1>
        <img src="https://via.placeholder.com/100/F00?text=Client 1" alt="">
        <img src="https://via.placeholder.com/100/0F0?text=Client 2" alt="">
        <img src="https://via.placeholder.com/100/00F?text=Client 3" alt="">
        <hr>
        <h1>My Skills</h1>
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript
                <ul>
                    <li>VueJs</li>
                    <li>ReactJs</li>
                    <li>Angular
                        <ol type="a" start="1">
                            <li>v.4.0</li>
                            <li>v5.0</li>
                            <li>v6.0</li>
                            <li>v7.0</li>
                            <li>v8.0</li>
                        </ol>
                    </li>
                    <li>Sevelte</li>
                </ul>
            </li>
            <li>Python</li>
        </ul>
    </body>
</html>
``` 


<h2 align="center">Assignment 4</h2>

### Question 1

```HTML
<!DOCTYPE html>

<html>
    <head>
        <title>Table Assignment</title>
    </head>
    <body>

        <table border="1" width=100%>
            <caption>Table Caption</caption>
            <thead>
                <tr>
                    <td>Group</td>
                    <td>Avatar</td>
                    <td>Name</td>
                    <td>E-mail</td>
                    <td>Character</td>
                    <td>Profile</td>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td rowspan="2">Ninja</td>
                    <td><img src="https://via.placeholder.com/60.png"></td>
                    <td>Osama Mohamed</td>
                    <td>o1@nn.sa <hr> o2@nn.sa</td>
                    <td>&copy;</td>
                    <td><a href="profile.com">Profile</a></td>
                </tr>
                <tr>
                    <td><img src="https://via.placeholder.com/60.png"></td>
                    <td>Shady Nabil</td>
                    <td>s@nn.sa</td>
                    <td>&trade;/td>
                    <td><a href="profile.com">Profile</a></td>
                </tr>
                <tr>
                    <td>Monsters</td>
                    <td><img src="https://via.placeholder.com/60.png"></td>
                    <td>Mohamed Ibrahim</td>
                    <td>m@nn.sa</td>
                    <td>&reg;</td>
                    <td><a href="profile.com">Profile</a></td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <td colspan="5">Total</td>
                    <td>3</td>
                </tr>
            </tfoot>
        </table>
    </body>
</html>
```

<h2 align="center">Assignment 5</h2>

### Question 1
Semantic elements: Header, nav, main, aside, figure, footer, figcaption, section, article.
[W3Schools semantic elements reference](https://www.w3schools.com/html/html5_semantic_elements.asp)

### Question 2
```HTML
<!DOCTYPE html>

<html>
    <head>
        <meta charset="UTF-8" />
        <title>Page Layout</title>
        <meta name="description" content="This is a test for a page layout" />
    </head>

    <body>
        <header>
            <h2>My Logo</h2>
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>Services</li>
                <li>Contact us</li>
            </ul>
        </header>
        <hr>
        <nav> Navigation Bar
            <ul>
                <li>Home</li>
                <li>Profile</li>
                <li>Settings</li>
                <li>About</li>
                <li>Contact us</li>
                <li>Log out</li>
            </ul>
        </nav>
        <hr>
        <section style="display: flex; flex-direction: row;">
            <section>
                <section style="text-align: center;">
                    <heading>Article 1</heading>

                    <article>
                        Lorem ipsum dolor sit amet consectetur, adipisicing
                        elit.
                        Quisquam
                        fuga alias, atque similique illo id soluta nesciunt
                        repellat
                        doloremque ea, quod vel ut deserunt quia aperiam fugiat
                        sequi
                        debitis a.
                    </article>
                    <img src="https://via.placeholder.com/150" alt="">
                </section>
                <hr>
                <section style="text-align: center;">
                    <heading>Article 2</heading>

                    <article>
                        Lorem ipsum dolor sit amet consectetur, adipisicing
                        elit.
                        Quisquam
                        fuga alias, atque similique illo id soluta nesciunt
                        repellat
                        doloremque ea, quod vel ut deserunt quia aperiam fugiat
                        sequi
                        debitis a.
                    </article>
                    <img src="https://via.placeholder.com/150" alt="">
                </section>
                <hr>
                <section style="text-align: center;">
                    <heading>Article 3</heading>

                    <article>
                        Lorem ipsum dolor sit amet consectetur, adipisicing
                        elit.
                        Quisquam
                        fuga alias, atque similique illo id soluta nesciunt
                        repellat
                        doloremque ea, quod vel ut deserunt quia aperiam fugiat
                        sequi
                        debitis a.
                    </article>
                    <img src="https://via.placeholder.com/150" alt="">
                </section>
                <hr>
            </section>
            <aside style="border:1px solid black; width: 30%;text-align:
                center;">
                Categories
            </aside>
        </section>

        <hr>
        <footer>
            &COPY; Copyright 2021 | Mohamed Youssry
        </footer>
    </body>
</html>
```

### Question 3 
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>
            Mohamed Youssry Profile
        </title>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    </head>
    <body>
        <audio controls autoplay loop>
            <source src="Page002_2.mp3" type="audio/mpeg">
            Your browser does not support this file
        </audio>
    </body>
</html>
```

### Question 4
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>
            Mohamed Youssry Profile
        </title>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    </head>
    <body>
        <video controls="true" width="400" poster="">
            <source src="stp_video.mp4" type="video/mp4">
            video is not supported
        </video>
    </body>
</html>
```

<h2 align="center">Assignment 6</h2>

### Question 1
```HTML
<!DOCTYPE html>

<html>
    <head>
        <meta charset="UTF-8" />
        <title>Form</title>
    </head>
    <body>
        <form action="test.py" method="POST">
            <div>
                <label>User Name</label>
                <br>
                <input name="username" type="text" required
                    placeholder="Username">
            </div>
            <hr>
            <div>
                <label for="">Password</label>
                <br>
                <input name="password" type="password" required
                    placeholder="Password">
            </div>
            <hr>
            <div>
                <label>Mobile Phone</label>
                <br>
                <input name="mobile" type="text" placeholder="+20100 123 (234)">
            </div>
            <hr>
            <div>
                <label>E-mail</label>
                <br>
                <input type="email" value="mo@gmail.com" required>
            </div>
            <hr>
            <div>
                <label>Subject</label>
                <br>
                <input type="text" placeholder="Inquiry, feedback, etc.">
            </div>
            <hr>
            <div>
                <input type="submit" value="Send Data">
                <input type="reset" value="Empty form">
            </div>
        </form>
    </body>
</html>
```


<p align="center"><h2>Assignment 7</h2></p>

### Question 1, 2, 3
```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>My form 2</title>
    </head>
    <body>
        <form action="form2.html" method="get">
            <div>
                <label for="tk">Token</label>
                <input id="tk" type="text" name="token"
                    value="b92f1fc2fce391ad7af633723afd3055" hidden>
            </div>
            <br>
            <div>
                <label for="email">Email</label>
                <input id="email" name="email" type="email" value="o@o.com"
                    readonly>
            </div>
            <br>
            <div>
                <label for="usname">Username</label>
                <input id="usname" name="username" type="text" minlength="5"
                    maxlength="20"
                    required placeholder="Your Name">
            </div>
            <br>
            <div>
                <input name="skill" id="ps" value="ps" type="checkbox" checked>
                <label for="ps">Problem Solving</label>
            </div>
            <br>
            <div>
                <input name="skill" id="lt" value="lt" type="checkbox">
                <label for="lt">Logical Thinking</label>
            </div>
            <br>
            <div>
                <input name="skill" id="as" value="as" type="checkbox">
                <label for="as">Advanced Search</label>
            </div>
            <br>
            <div>
                <input name="skill" id="analysis" value="analysis"
                    type="checkbox">
                <label for="analysis">Analysis</label>
            </div>
            <br>
            <div>
                <input name="skill" id="planing" value="planning"
                    type="checkbox">
                <label for="planing">Planing</label>
            </div>
            <br>
            <div>
                <input name="job" type="radio" id="fed" checked>
                <label for="fed">Front-End Developer</label>
            </div>
            <br>
            <div>
                <input name="job" type="radio" id="bed">
                <label for="bed">Back-End Developer</label>
            </div>
            <br>
            <div>
                <input name="job" type="radio" id="pm">
                <label for="pm">Project Manager</label>
            </div>
            <br>
            <div>
                <input name="job" type="radio" id="ba">
                <label for="ba">Business Analyst</label>
            </div>
            <br>
            <div>
                <input name="job" type="radio" id="sm">
                <label for="sm">Scrum Master</label>
            </div>
            <br>
            <label for="book">Choose Book: </label>
            <select name="job" id="book">
                <optgroup label="PHP">
                    <option value="php1" selected>v5.0</option>
                    <option value="php2">v7.0</option>
                    <option value="php3">v8.0</option>
                </optgroup>
                <optgroup label="Python">
                    <option value="php1">v2.0</option>
                    <option value="php2">v3.0</option>
                    <option value="php3">v3.9</option>
                </optgroup>
            </select>
            <hr>
            <textarea name="brief" id="brief" cols="30" rows="10"
                placeholder="Write Here What You to learn from programming"></textarea>
            <br>
            <br>
            <input type="submit" value="Send">
            <input type="reset" value="Empty">
        </form>
    </body>
</html>
```

<h2 align="center">Assignment 8</h2>

### Question 1, 2

```HTML
<!DOCTYPE html>

<html>

    <head>
        <title>File HTMl</title>
    </head>
    <body>
        <form action="file.html" method="get">
            <label for="">Search</label>
            <br> <br>
            <input type="search" placeholder="Enter A Search Word">

            <br> <br>
            <label for="">Upload</label>
            <br> <br>
            <input type="file">
            <br> <br>

            <label for="">URL</label>
            <br><br>
            <input type="url">
            <br> <br>
            
            <label for="">Date</label>
            <br><br>
            <input type="date">
            <br> <br>

            <label for="">Month</label>
            <br><br>
            <input type="month">
            <br> <br>

            <input type="reset" value="Empty">
            <input type="submit" value="Save">
        </form>
    </body>
</html>

```

### Question 3, 4 

```HTML
<!DOCTYPE html>
<html>
    <head>
        <title>File HTMl</title>
    </head>
    <body>
        <pre>
            <p>
                Hello Line One
                Hello Line Two
                Hello Line Three
                    Hello Line Four
            </p>
        </pre>
        <iframe src="https://elzero.org/" width="100%" height="500px"></iframe>
    </body>
</html>
```