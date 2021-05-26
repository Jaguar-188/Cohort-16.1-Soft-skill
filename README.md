# Browser Rendering

* ## Concepts or technologies to be known :

    1. #### HTML
    2. #### CSS
    3. #### JS
    4. #### DOM/CSSOM

    ### The explanation is as follows :

    1. #### HTML :
        +  HTML is a **HyperText Markup Language** which is consists of **markup symbols**.
        +  The markup symbols tell the browser that how it should render the page.
        +  It is a **front-end technology**.
        [https://www.w3schools.com/html/html_intro.asp](https://www.w3schools.com/html/html_intro.asp)
        + Currently HTML has version of 5 i.e **HTML5**.
    
    1. #### CSS :
        +  CSS is a **Cascading StyleSheet**.
        +  They are used to give styles to the HTML page as like **font**, **color**. 
        +  The main purpose is to design the pages according to the **customer's requirements**.
        +  It is responsible for the **look** and **feel** of the web page.
        [https://www.tutorialspoint.com/css/what_is_css.htm](https://www.tutorialspoint.com/css/what_is_css.htm)
        +  Currently CSS has version of 3 i.e **CSS3**

    1. #### JS :
        +  JS is a kind of **scripting language** that can be used on both **client-side** as well as **server-side**.
        +  JavaScript makes the web page more **interactive**.
        +  Most of the browsers uses JavaScript as their **primary language**.
        [https://skillcrush.com/blog/javascript/](https://skillcrush.com/blog/javascript/)
        +  JavaScript has it's own library called **JQUERY** which contains the different functions that makes it more interactive.

    1. #### DOM / CSSOM :
        +  DOM is a **Document Object Model** / **CSS Object Model** is a kind of parser that is used to parse the HTML and XML documents.
        +  The CSS Object Model creation it’s generated like the DOM but with some differences.

        ![N|Solid](https://miro.medium.com/max/376/1*jL3O3J4KmXBMh1zULLwGgA.png)
<br>
  

* ## Mechanism :

    ### The explanation is as follows :

    +  A browser is one that renders the web page from the **remote server** as per the request of the end-user. 
    +  We generally write the code by using the syntax that can be understandable by us but the computer knows the **binary     language** or you can say it accepts the data in terms of **bytes**. 
    +  The intermediate software converts the human understandable data into **machine understandable data**. So, that machine can process the request. 
    +  The bytes of data is first converted into **characters** and then they are converted into **tokens**. 
    +  The first part is the **browser engine** which acts as **middleware** between the **end-user** and the **rendering engine**. 
    +  It takes request from user to further part which is rendering engine whose primary task is to **display** or **execute** the HTML pages. 
    +  This **rendering engine is different for different browsers** like **Firefox uses Gecko** or **Chrome uses Webkit**  or **opera uses Blink** etc. 
    +  The next part **networking** is used to connect to the internet through the **protocol HTTPS**. 
    +  The next part is **JavaScript interpreter** which is used to render the **javascript coding**. 
    +  Most of the browsers uses **javascript as their primary language**. 
    +  The **web address** e.g [https://example.com](https://example.com) recieved from user is first converted into **ip address** e.g 
    **192.168.1.1** by using **DNS server** and then it travels over the internet to search for where it belongs. 
    +  After searching, the **server will serve the respective web page for the ip address**. 
    +  The rendering engine will recieve it and then **creates a DOM tree**. 
    +  After that it creates a rendering tree by using **CSS files** and DOM tree. 
    +  Rendering tree will then displays the web page as per the **positions**, **layout** written in the file. 
    +  Then user will get the web page that he is accessing.

        [https://youtu.be/5VEDjg9zGEk](https://youtu.be/5VEDjg9zGEk)
<br>

* ## Architecture 

    ![N|Solid](https://miro.medium.com/max/624/1*srfAe9f1ryMc3qoMOASmhg.png)
    