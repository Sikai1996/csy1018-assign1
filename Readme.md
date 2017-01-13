Assignment	1:	Web	Development
Student Name: Sikai He
Student Number: 16429428
URL: Sikai1996.github.io/csy1018-assign1
Date: 13/01/2017



This is that the university student from Year 1 who have finished Web Development assignment. Web design need to use html and css. And we need to use some free website like unsplash. Before when I was in web design, I design good plan first. Because I'm a little forgot the content of the class. I open the first Flexbox Froggy in learning again. Then I started to make my own web page. First of all, I fix the basic framework according to class what I have learned.

I designed the home page first. We need to put our name and photo in the page and some links. I put the background image first. I open the ppt from nile and learn how to do it. It showed strange in the beginning because the picture is quite big.  I put the background size into 1366px 768px first. It worked. But I still changed in the end. It is not easy to put our photo on the page. In the beginning, I met some problems because I cannot put my photo on the background image. I try to fix it. Finally I put
Html: <main class="container">


    <nav class="information">
    <h1>I am Sikai He</h1>

      <p>
          <a href="cv.html">CV</a>
        </p>
      <p>
           <a href="bio.html">Biography</a>
        </p>
         <p>
           <a href="contact.html">Contact</a>
         </p>
  </nav>


<img src="image/happy.jpg"
      alt="photograph"
      width="300"
      height="300"
      class="pic"/>
</main>

Css: body{
 background-image: url("../image/picture.jpg");
   max-height: 50%;
   max-width: 50%;
   background-size: cover;
   background-position: center;
   position: relative;
   margin: 0;
   top: 0;
   flex-direction:column;
   justify-content: center;
   text-align: center;
   align-items: center;
   align-self: center;
}
.pic{
display:flex;
position:relative;
justify-content:center;
margin-top:auto;
left:200px;
}
And fix it. But is still have some problems. I am not sure about how to put word into the center of the page. Like this: .information{
  display:flex;
  flex-direction:column;
  padding:20px 60px;
  margin:0 auto;
  color:black;
  justify-content:center;
  justify-content: space-around;
  align-items: center;
  align-items: stretch;
  align-self: center;
  box-shadow: inset  0 0 0 2px;
}.

When i finish home page, I started cv.html. I need to write something about myself. This is not hard for me. Because I do not put many things in this page. But I cannot put the content into the center of the page either. The bio page and contact page are the same like cv page. I just put my information in the page. It is not very hard for me. I know how to use html and css to create a website.

This is my cv code.
body{
 background-image: url("../image/hi.jpg");
 max-height: 50%;
 max-width: 50%;
 background-size: cover;
 background-position: center;
 position: relative;
 margin: 0;
 top: 0;
 flex-direction:column;
 justify-content: center;
 text-align: center;
 align-items: center;
 align-self: center;
}
.container{
  font-family:arial;
  display:block;
  align-items:center;
  color:white;
  align-items: stretch;
  align-self: center;
 justify-content: center;
 position:relative;
}
Not sure where is wrong because it only display on the left of the page. When I met this problems, I search in google. I know the HTML5. And I get some information about the code. When I still have questions, I use youtube. I found some tutorials about html and css. It is quite useful for me.
Perhaps I do website look more humble now. But its basic architecture has been established.
