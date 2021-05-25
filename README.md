
Topic Name - Browser rendering

Question - How does a browser render HTML, CSS, JS to DOM? What is the mechanism behind it?


HTML - HTML is a HyperText Markup Language which is consists of markup symbols. The markup symbols tell the browser that how it should render the page. It is a front-end technology.

CSS - CSS is a Cascading StyleSheet. They are used to give styles to the HTML page as like font, color. The main purpose is to design the pages according to the customer's requirements.

JS - JS is a kind of scripting language that can be used on both client-side as well as server-side. JavaScript makes the web page more interactive.

DOM - DOM is a Document Object Model is a kind of parser that is used to parse the HTML and XML documents.

Mechanism -
             A browser is one that renders the web page from the remote server as per the request of the end-user. We generally write the code by using the syntax which can be understandable by us but the computer knows the binary language or you can say it accepts the data in terms of bytes. The intermediate software converts the human understandable data into machine understandable data. So, that machine can process the request. The bytes of data is first converted into characters and then they are converted into tokens. The first part is the browser engine which acts as middleware between the end-user and the rendering engine. It takes request from user to further part which is rendering engine whose primary task is to display or execute the HTML pages. This rendering engine is different for different browsers like Firefox uses Gecko or Chrome uses Webkit etc. The next part networking is used to connect to the internet through the protocol HTTPS. The next part is JavaScript interpreter which is used to render the javascript. Most of the browsers uses javascript as their primary language. The web address recieved from user is first converted into ip address by using DNS server and then it travels over the internet to search for where it belongs. After finding, the server will serve the respective web page for the ip address. The rendering engine will recieve it and then creates a DOM tree. After that it creates a rendering tree by using CSS files and DOM tree. Rendering tree will then displays the web page as per the positions, layout written in the file. Then user will get the web page that he is accessing.