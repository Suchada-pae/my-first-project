# Keep in touch with The Script 

<img width="361" alt="screen shot 2018-06-25 at 13 11 25" src="https://user-images.githubusercontent.com/37799063/41863892-0ba7c084-78a0-11e8-8176-21347f5b106c.png">



Built this website for all fans of the Script. The Script is the famous Irish rock band which has followers on
social media nearly 10 millions.
This website is alternative choice for the audiences who admire and would like to stay in touch with the band. 

# Motivation

Created the website to allow all fans following movements of the Irish rock band, such as news, concerts tour 
and the popular singles etc.
And the website also has the brif history of The Script for the new followers. 

# Usage

Go to this link: [The Script](https://thescript-cloned2-cloned-suchadarot.c9users.io)

The website contains:

    - The Home page provides a short story for The Script.
    - The Music page provides the most 10 popular songs of The Script from the first album til now.
    - The Event page provides the schedule of The Script concerts tour, which let users accessing the official
      website for purchasing tickets.
    - The About page provides the biography of each The Script member.
    - The Contact page provides an email for leaving a comment. 
    
    As mentioned earlier, this is not an official website of The Script. 
    Therefore, some pages on this website hold external resources which could be changed at any time.
    
# Purposes of building this website

This website was created for an educational project in Software Development to have an understanding of building a website
by using User Centric Frontend:

- to understand of how to run html and css 
- to adopt and apply knowledge of UX design
- to be able to build a website by using User Centric Frontend
- to know how to use responsive web design
- to learn more about how colours have effect on a website
- to have an understanding of how to use command line interface
- to have an understanding of how to use Git and GitHub for version control

# Reasons 

When you go to my website, what you are going to see:

## 1. Home Page which contains:

   ### 1.1 Header area on Home page:
    
   #### - Logo
   
You can see a picture of the latest album of the Script "Freedom Child" in which I added it on at the top of
the website page in the header area as a logo. I chose this picture because I realize that when the fans
of the Script see this picture, they would know right away that this website belongs to the Script, Irish rock band.

- To make this appear on the screen; I used this code on html:

        <header class="contain-fluid">
            <div class="row">
                <div class="col-md-12 logo"></div>
            </div>
        </header>

- These codes running on css to control the position and size of the image:

        header {
            margin: 0;
        }
    
        .logo {
            background: url("../images/album1.jpg");
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            width: 100%;
            min-height: 400px;
            transition: all .5s ease-in-out;
            -moz-o-transition: all .5s ease-in-out;
            -webkit-o-transition: all .5s ease-in-out;
        }
      
    
#### - A navigation menu
        
I divided my website into 5 categories which is comprised of home, music, event, about and contact pages. 
For more details of each page, I will explain later. As you can see on the website, the color of the
nav bar that I picked is blue color(#3AACD1). The reason for my chosen color for the nav bar is I would like to make 
the color of each part on the website has the same tone of color which match with the logo picture.

-To make the nav menu, I used these codes on html:

            <!--navigation menu-->
                <div class="row bg-color-nav">
                    <ul id="nav" class="list-inline clearfix">
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-home menuitem">
                            <a href="index.html" class="nav-bar uppercase">Home</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-music menuitem">
                            <a href="music.html" class="nav-bar uppercase">Music</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-contact menuitem">
                            <a href="blog.html" class="nav-bar uppercase">Event</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-about menuitem">
                            <a href="about.html" class="nav-bar uppercase">About</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-about menuitem">
                            <a href="contact.html" class="nav-bar uppercase">Contact</a>
                        </li>
                    </ul>
                </div>
                
- These codes running on css: 

         #nav {
            margin: 0;
        }

        #nav li {
            padding: 0;
        }


        .menuitem {
            height: 50px;
            text-align: center;
            padding: 0;
        }

        .menuitem a {
            width: 100%;
            text-decoration: none;
            color: #3AACD1;
            height: 50px;
            font-size: 17px;
            font-weight: 400;
            padding-top: 10px;
        }

        .hvr-fade:hover {
            background-color: #00124d;
            height: 50px;
        }


### 1.2 Section area on Home page:

#### - A heading on the section area "THE SCRIPT"
        
I used "THE SCRIPT" as a heading on the section area on Homepage because I thought this would be easier to start with
the Script story which might be helpful for the new followers who do not know about the band and would like to know
more about who they are and what they do. 

- To make the heading appearing on my site; I used these codes running on HTML:
            
            <!--content-->
                <div class="row bg-color-thescript">
                    <div class="col-xs-12 col-sm-12 col-md-12">
                        <h1 class="uppercase sub-heading">The Script</h1>
                    </div>
                    
                    
- To make the heading "THE SCRIPT" appearing on the screen with uppercase and font with "Exo" sans-serif, I used these 
codes running on CSS: 

            h1 {
                margin-top: 30px;
                margin-bottom: 10px;
            }

            .uppercase {
                text-transform: uppercase;
            }
            
            .sub-heading {
                font-family: "Exo", sans-serif;
                text-align: center;
                font-size: 50px;
                font-weight: 300;
                color: #ffffff;
            }

            
            
#### - The story of the Script on the section area on Home page:
   
I mentioned the story of the Script on the home page because it is a good place to tell the story to both new and regular
followers to know how the band has the significant success in music industry. 

   
- I used these codes running on HTML:
    
    
          <div class="col-xs-12 col-sm-12 col-md-12 heading-content">
               <p class="inline-block>
                 <imgsrc="https://images.skstatic.com/images/media/profile_images/artists/465363/huge_avatar"
          class="home-image" alt="the Script" align="left" width="300" height="410">The Script is a famous rock band,
          where originally come from Dublin, Ireland. At the beginning of <span class="phase-line">the Script</span>,
          the band was formed by guitarist <span class="phase-line">Mark Sheehan</span> and vocalist <span class=
          "phase-line">Danny O'Donoghue</span> in 1996.
               
               The band received a success in their home country and desired to go worldwide. However, they did not go
         so far as they expected, so that the two musicians decided to go to Los Angeles and worked there as producers,
         where they wrote and produced songs for singers and bands such as <span class="phase-line">Britney Spear</span>,
         <span class="phase-line">Boy II Men</span> and <span class="phase-line">TLC</span>.
               
               After spending several years in Los Angeles, they moved back to Ireland where they found 
         <span class="phase-line">Glen Power</span> to joy the band as a drummer.<br> 
                    
              <br>The band released the first debut album in August 2008 by Phonogenic Records. The most popular 
         singles of <span class="phase-line">"the Script"</span> album that made them become famous in both the UK and
         America were<span class="phase-line">"The Man Who Can't Be Moved"</span> and <span class="phase-line">"Breakeven"
         </span>.
              
              After their first albums, the band has released next four albums: <span class="phase-line">"Science & Faith"
         </span> in 2010, <span class="phase-line">"#3"</span> in 2012, <span class="phase-line">"No sound without Silence"
         </span> in 2014 and the latest one from last year <span class="phase-line">"Freedom Child"</span>. Not only those
         songs became successful, some of their singles could go to the top charts in the UK, America and Asia as well,
         such as <span class="phase-line">"Hall of Fame"</span>, <span class="phase-line">"Superheros"</span>,
         <span class="phase-line">"Rain"</span> and <span class="phase-line">"Written in the Scars"</span>.<br>
                    
              <br>Nowadays, <span class="phase-line">the Script</span> is globally well-known as an Irish rock band and
         has a lot of fans around the world. It is said that <span class="phase-line">the Script</span> is one of the
         rock bands has made a significant success of their career according to the numbers of selling the records and
         the tickets tour.</p><br>
         </div>


- These codes running on css: 

   - Used these codes to set an image at the left hand site beside the story of the Script:

            .inline-block img {
                float: left;
                width: 200px;
                height: 250px;
                margin-right: 30px;
            }
                
   - Added these codes to set the position, size and color of the letters:

            .heading-content {
                margin-top: 10px;
                margin-left: 30px;
                margin-right: 70px;
                padding-right: 80px;
                display: block;
                text-align: left;
                font-size: 14px;
                letter-spacing: 1px;
            }
            
   - Added this code to set the blue color to emphasize some words in the texts:
   
            .phase-line {
                font-size: 14px;
                letter-spacing: 1px;
                color: #9999ff;
            }

#### - A link "back to top" used to go back to the top of the page
    
I created the link "back to top" on each page because some pages provide loads of information which would make the length
of the page a bit longer than users expect. Therefore, I thought that without the link "back to top" might let the users
use a scrolling bar too much, and this might be able to lead the users having a bad experience of accessing the website.
   
- These codes running on html:
    
         <!--back to top-->
                <div class="row bg-color-back-to-top">
                   <div class="col-xs-12 col-sm-12 col-md-12">
                        <a href="#" class="nav-bar lowercase">back to top</a>
                   </div> 
                </div>
            </div>

   
 - These codes running on css:
  
   - To control size and font of the link "back to top":
        
         .bg-color-back-to-top .nav-bar {
            float: right;
            margin-right: 40px;
            font-family: "Exo", sans-serif;
            letter-spacing: 1.5px;
            font-size: 13px;
        }
  
  
  - To control color and hover of the link "back to top"; I used CSS Bootstrap:
  
            a:hover {
                color: #23527c;
            }
            
            
            
### 1.3 A footer on Home page:

#### - Privacy Policy & ©2018 All musics- All Rights Reserved:
  
I added Privacy Policy because I thought this policy is very important for the web developers to protect their work
and also to protect users' right in which allow them to know about the website, such as what the web is, 
who wrote and the risks of browsing the web and so on. And inside of the privacy policy link, I also wrote policy
information for all users.
  
  
- These codes running on html:
    
         <footer class="contain-fluid">
            <div class="row footer-details">
                <!--copyrights-->
                <div class="col-xs-6 col-sm-6 col-md-6 right-menu">
                    <a class="privacy-policy color" href="images/p2.pdf" target="_blak")>
                    <span class="uppercase general-sub">Privacy Policy</span></a>
                    <p class="copy-all-music">©2018 All musics- All Rights Reserved</p>
                </div>


- These codes running on css: 

    - These codes used to set up background color of the footer with the gray color(#525252). I picked this color because 
    I always see the majority of the websites have the gray color on a footer area, which this can be considered as a
    unique color for the footer area.
    
    
            footer {
                background-color: #525252;
                color: #fafafa;
                min-height: 70px;
                padding-top: 15px;
                padding-left: 25px;
                padding-bottom: 15px;
            }

            .term-of-service {
                padding-right: 13px;
            }

            .privacy-policy {
                color: #ffffff;
                margin: 10px;
                padding: 0;
            }

            .copy-all-music {
                font-family: "Exo", sans-serif;
                font-size: 11px;
                margin-top: 7px;
                letter-spacing: 1px;
                text-transform: capitalize;
                float: left;
            }

            .general-sub {
                font-family: "Exo", sans-serif;
                margin-top: 7px;
                margin-right: 0;
                letter-spacing: 1px;
                text-transform: capitalize;
                float: left;
            }
            
        
   - Added this code to change the color on the link of privacy policy on the left-hand side of the footer area:

            .right-menu .privacy-policy:hover {
                color: #337ab7;
            }

        
        
 #### - Symbols of social medias (Facebook, Twitter and Instagram) at the right hand side:
    
   - These codes running on html:
            
            <div class="col-xs-6 col-sm-6 col-md-6 footer-symbol">
                    <a target="_blank" href="https://www.facebook.com/thescript/">
                        <i class="fa fa-facebook" aria-hidden="true"></i></a>
                    <a target="_blank" href="https://www.instagram.com/thescriptofficial/">
                        <i class="fa fa-instagram" aria-hidden="true"></i></a>
                    <a target="_blank" href="https://twitter.com/thescript">
                        <i class="fa fa-twitter" aria-hidden="true"></i></a>
            </div>
    
  - These codes running on css:
  
    - To control the position of social media links:
            
            .footer-details .fa {
                float: right;
            }
            
            .footer-symbol i {
                margin: 10px;
                margin-right: 20px;
            }
            
            .fa {
                padding-right: 15px;
            }
            
   - Added this code to change the color on the link of social media links:        
    
            .footer-details span:hover {
                color: #ccff33;
            }
            
            


## 2. Music page which contains:


For logo, nav bar, link "back to top" and footer, they used the same codes as mentioned on the Home page. 


### 2.1 The section area of Music page contains:

#### - A heading "THE TOP 10 SINGLES"

I used "THE TOP 10 SINGLES" as a heading on Music page because I would like to add the most popular songs of the Script,
which are the official videos, according to the numbers of viewing the videos from users and the comments that
have been written on subscribe on Youtube website. 


- HTML codes of heading "THE TOP 10 SINGLES":

             <!--heading-->
                <div class="row bg-singles">
                    <div class="col-xs-12 col-md-12 section-heading">
                        <h1 class="uppercase sub-heading-singles">The Top 10 Singles</h1>
                    </div>        
                </div>    
        
        
 - CSS codes of heading "THE TOP 10 SINGLES:
        
            .section-heading {
                background-color: #000000;
            }
            
            h1 {
                margin-top: 30px;
                margin-bottom: 10px;
            }

            .uppercase {
                text-transform: uppercase;
            }
            
            .sub-heading {
                font-family: "Exo", sans-serif;
                text-align: center;
                font-size: 50px;
                font-weight: 300;
                color: #ffffff;
            }

        
  #### - 10 Youtube videos 
  
  
  - HTML codes of the list of "THE TOP 10 SINGLES: 
        
        
            <!--top 10 songs-->
                <div class="row col-md-12 songs">
                    <div class="section-sub-heading">
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/gS9o1FAszdk" controls frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/vOKOamXsXYE" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>                       
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                             <iframe src="https://www.youtube.com/embed/CPEBN2dVNUY" frameborder="0" 
                             allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>        
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/SGlkwKA-t_4" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/KMihKmoYfe8" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/QV62YRpIeUA" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/-iA-MHxa8C8" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/WIm1GgfRz6M" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/ho9xM9n2USA" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/mk48xRzuNvA" frameborder="0" 
                            allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                    </div>   
                </div>
        
        
- CSS codes of the list of "THE TOP 10 SINGLES:
        
        
            .songs {
                margin: auto;
                padding-left: 30px;
                background-color:#08151F;
            }

         @media(min-width: 1200px)
             .menu-songs iframe {
                width: 516px;
                height: 315px;
                margin: 50px;
                background-color: #08151F;
                display: inline-block;
       
            }
    
            .bg-singles {
                width: 100%;
                background-color: #08151F;
            }
        
         @media(min-width: 679px) and (max-width: 1119px)
            /*----music----*/ 
            .songs iframe {
                padding: 50px;
            }


## 3. Event page which contains:

For logo, nav bar, link "back to top" and footer, they used the same codes as mentioned on the Home page. 


#### - A heading "Event"

Used the "Event" as a heading on Event page, the reason is that I wanted the page holding the information
about concerts tour where the fans can go through the ticket links to purchase the tickets, and the page also 
provides some news of the Script for the past two years.

- HTML codes:

            <!--blog-->
                <div class="row event-news">
                    <div class="col-xs-12 col-md-12 bg-heading-news">
                        <h1 class="uppercase sub-heading">Blog</h1>
                    </div> 
                </div> 
        
- CSS codes:        
     
        .sub-heading {
            font-family: "Exo", sans-serif;
            text-align: center;
            font-size: 50px;
            font-weight: 300;
            color: #ffffff;
        }
        

##### - A sub-heading "Tour":
    
- HTML codes:
            
            <!--tour-->
                <div class="row event-news-2">
                    <div class="col-md-12 bg-news">
                        <h2 class="news-event">Tour</h2>
                    </div>
                </div>
                
                
- CSS codes:

        .news-event {
            margin-top: 50px;
            margin-bottom: 50px;
            text-align: center;
            color:#0000ff;
        }
    

##### - Two blue lines between the sub-heading (Tour):
    

I build the two lines between the sub-heading "Tour" because I wanted to separate the two areas between the list
of concerts tour and the Script's news from each other. Because this would make page neat and legible. 
    
  - only on css:
  
 
        h2 {
            overflow: hidden;
            text-align: center;
        }


        h2:before,
        h2:after {
            background-color: #000099;
            content: "";
            display: inline-block;
            height: 10px;
            position: relative;
            vertical-align: middle;
            width: 50%;
            -webkit-animation-name: headline; 
            -o-animation-name: headline;
            -webkit-animation-duration: 1s;
            -o-animation-duration: 1s;
            animation-name: headline;
            animation-duration: 1s;
            animation-iteration-count: infinite;
  
        }


        h2:before {
            right: 0.7em;
            margin-left: -50%;
        }


        h2:after {
            left: 0.7em;
            margin-right: -50%;
        }
        
        
##### - A table of ticket tours:
   
Created a table to contain the informaiton of the Script's concern tour which is hold days, places and ticket links. 

- HTML codes:
                           
                          <table style="width:100%">
                                <table class="table table-condensed">
                                    <tr>
                                        <th>Date</th>
                                        <th>Place</th>
                                        <th>Ticket</th>
                                     </tr>
                                    <tr>  
                                        <td>June 7</td>
                                        <td>Thetford forest, suffolk, UK</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                    </tr>
                                     <tr>
                                        <td>June 9</td>
                                        <td>Caribana Festival, Crans-Pres'-Celigny, Switzerland</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                     <tr>
                                        <td>June 9</td>
                                        <td>Caribana Festival, Crans-Pres'-Celigny, Switzerland</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                     <tr>
                                        <td>June 10</td>
                                        <td>Forum, Milan, Italy</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                     <tr>
                                        <td>June 11</td>
                                        <td>Padova, Palageox, Italy</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                     <tr>
                                        <td>June 14</td>
                                        <td>Westonbirt Arboretum, Tetbury, UK</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                     <tr>
                                        <td>June 16</td>
                                        <td>Pinkpop, Netheland</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                     <tr>
                                        <td>June 21</td>
                                        <td>Open Air Theatre, Scarborough, UK</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                     <tr>
                                        <td>June 22</td>
                                        <td>Isle of Wight Festival, Newport, UK</td>
                                        <td><a href="http://www.thescriptmusic.com/home">
                                            <button type="button" class="btn btn-warning">Ticket</button></a></td>
                                     </tr>
                                </table>      
                            </table> 
                            
                            
- CSS codes to set up the position, font-size, and color of the letter:
 
 I set a position of the news on the left side of the image just to make the content look nicely. The font is white to
 contrast dark blue background color.

                        th {
                            text-align: left;
                            padding: 10px;
                            width: 200;
                            letter-spacing: 2px;
                            font-size: 20px;
                            font-weight: 500;
                            color: #ffffff;
                        }

                        td {
                            letter-spacing: 1px;
                            font-size: 12px;
                            color: #ffffff;
                        }
                        
                        .table-condensed {
                            border-style: solid;
                            border-color:  #ff0000;
                            border-width: 2px;
                            width: 60%;
                            margin: auto;
                            }
                            
                        
##### - Ticket buttons in the table:

These buttons would be helpful for all users to purchase the tickets if they want. And the buttons with the orange color 
could be seen easily when it is on dark background color.
                
- HTML codes:        
                                                                
     <button type="button" class="btn btn-warning">Ticket</button>
        
                            
 - CSS codes:
        button {
            display: block;
            margin-right: 30px;
         }

                        
                  
##### - A heading "NEWS":


    
        html:
            <!--news-->
                    <div class="row event-news-3">
                        <div class="col-xs-12 col-md-12 bg-news">
                            <h2 class="news-event">News</h2>
                        </div>
                    </div>
                    
        css:
        
        .sub-heading {
            font-family: "Exo", sans-serif;
            text-align: center;
            font-size: 50px;
            font-weight: 300;
            color: #ffffff;
        }
    
    - The list of the Script news:
    
        html:
        <div class="row event-news-4">
                        <div class="col-md-12 bg-news-section-2">
                            <img src="https://s1.ticketm.net/img/tat/dam/a/91f/dc2396de-dfc4-47f6-bf9d-d11876c1691f_516261_CUSTOM.jpg" class="news-image-2"></img>
                            <div class="news-list">
                              <a href="https://www.rte.ie/entertainment/music-reviews/2017/0901/901498-the-script-freedom-child" target="_blank" class="news-freedom"/>News of Freedom Child album</a></p>
                              <a href="https://www.bbc.co.uk/programmes/p05pl98z" target="_blank" class="news-freedom"/>The Script performed live on BBC Radio 2 Room</a></p>
                              <a href="https://twitter.com/thescript" target="_blank" class="news-freedom"/>News of the Script on Twitter</a></p>
                              <a href="https://twitter.com/thescript/status/1002241934134530053" target="_blank" class="news-freedom"/>The Script Summer Tour</a></p>
                            </div>
                        </div>
                    </div>
                    
        css:
        .news-list a {
            color: #ffffff;
            line-height: 2.0;
            padding-left: 30px;
        }

        .event-news,
        .event-news-2,
        .event-news-3,
        .event-news-4 {
             background-color: #08151F;
        }
        
    - A picture of the Script on the left hand side:
        
   html:
        <img src="https://s1.ticketm.net/img/tat/dam/a/91f/dc2396de-dfc4-47f6-bf9d-d11876c1691f_516261_CUSTOM.jpg" class="news-image-2"></img>

   css:
    
    .bg-news-section-2 img {
        margin-left: 50px;
        margin-bottom: 30px;
    }    
        
3. A link of back to the top
4. A footer


The last page of my site is About:

1. Logo
2. Navigation menu

3. The section of the biography of the Script:

    - A heading "BIOGRAPHY OF THE SCRIPT":
    
        html:
        <!--about-content menu-->
                <div class="row bg-color-thescript">
                    <div class="col-xs-12 col-sm-12 col-md-12">
                        <h1 class="uppercase sub-heading">Biography of the Script</h1>
                    </div>
                </div>

        css:
        .sub-heading {
            font-family: "Exo", sans-serif;
            text-align: center;
            font-size: 50px;
            font-weight: 300;
            color: #ffffff;
        }

    - biography of Danny with a border:
    
    html:
    
    <!--danny-->
                <div class="row danny-content">
                    <div class="col-xs-12 col-sm-12 col-md-12 about-content">
                        <img src="https://i.pinimg.com/originals/94/9a/0f/949a0f52374c4921b060c11023f0bd36.jpg" class="about-image"></img>
                            <a href="https://en.wikipedia.org/wiki/Danny_O%27Donoghue" target="_blank" class="donoghue-content"><h3>Danny O'Donoghue</h3></a>
                                <p class="inline-block-about">Danny O'Donoghue is a Dubliner who was born in the family of whom father was a member of <span class="phase-line">The Dreams</span> Shay O'Donoghue, and mother Ailish O'Donoghue.
                                Before he became a lead single in The Script, he used to form a band called  <span class="phase-line">Mytown</span> with his intimate friend, Mark Sheehan.  
                                And they received the moderate success in their home country but later on; they decided  to work as producers in Los Angeles for a few years and went back to Dublin where recruited Glen Power as a drummer.
                                The Script was formed in 2001 and released the first album called <span class="phase-line">"The Script"</span>. The debut album had the significant success in Ireland and went on to the UK and America.
                                Since 2008, the script has released next four albums which have been sold worldwide.</p> 
                    </div>
                </div>
                
    css:
    
        .about-image {
            width: 300px;
            min-height: 300px;
            margin-right: 50px;
        }
        
        .about-content,
        .about-content-2,
        .about-content-3 {
            padding-left: 40px;
            padding-right: 50px;
            margin-bottom: 50px;
            line-height: 2.0;
            letter-spacing: 1px;
            color: #ffffff;
        }
        
        .about-content .inline-block-about {
            margin-left: 30px;
            margin-right: 20px;
        }
        
        h3 {
            text-align: center;
        }


    - biography of Mark with a border:


 html:
           <!--mark-->
                <div class="row mark-content">
                    <div class="col-xs-12 col-sm-12 col-md12 about-content-2">
                        <img src="http://images.gibson.com/Lifestyle/2013/mark-sheehan_1.jpg" class="about-image-2"></img>
                            <a href="https://thescriptbible.wordpress.com/biography/mark-sheehan/" target="_blank" class="mark-content"><h3>Mark Sheehan</h3></a>
                             <p class="inline-block-about">Mark Sheehan was born on 29 October 1981 in Mount Brown, Dublin. 
                             His father named Marc Anthony Sheehan. Danny and  Mark have been friends since they were 12 years old. 
                             He and Danny used to play music as a boyband <span class="phase-line">MyTown</span>. Not only, Danny, that worked in Los Angeles, but Mark also went there. 
                             When they moved back to Dublin, they formed <span class="phase-line">the Script</span> together. 
                             After that he married Rina Sheehan, and he has three children named Cameron, Avery, and Lil.</p> 
                    </div>         
                </div>
                
css:
        .about-content,
        .about-content-2,
        .about-content-3 {
            padding-left: 40px;
            padding-right: 50px;
            margin-bottom: 50px;
            line-height: 2.0;
            letter-spacing: 1px;
            color: #ffffff;
        }
        
        .about-content-2 .inline-block-about {
            margin-left: 30px;
            margin-right: 20px;
        }
        
        
        - biography of Glen
        
    html:
    <!--glen-->
                <div class="row glen-content">
                    <div class="col-xs-12 col-sm-12 col-md-12 about-content-3">
                        <img src="https://www.famousbirthdays.com/headshots/glen-power-3.jpg" class="about-image-3"></img>
                            <a href="https://thescriptbible.wordpress.com/biography/glen-power/" target="_blank" class="glen-content"><h3>Glen Power</h3></a>
                             <p class="inline-block-about">Glen Power is one of <span class="phase-line">the Script</span> members. He had started his career before he joined the Script. 
                             His father was a singer, however; the most inspired person that made him interested in the music industry was his mother. 
                             He and his other band members have achieved many awards, such as <span class="phase-line">the Best Album and Best Irish Band Award at the 2009 Meteor Ireland Music Awards</span>. 
                             He has married and has a son named Luke.</p> 
                    </div>         
                </div>
                
    css:
        .about-content,
        .about-content-2,
        .about-content-3 {
            padding-left: 40px;
            padding-right: 50px;
            margin-bottom: 50px;
            line-height: 2.0;
            letter-spacing: 1px;
            color: #ffffff;
        }

        .about-content-3 .inline-block-about {
            margin-left: 30px;
            margin-right: 20px;
        }


- Hover


/*-----------navigation bar-------------*/

.hvr-fade:hover {
    background-color: #00124d;
    height: 50px;
}

/*----------------footer---------------*/

.right-menu .privacy-policy:hover {
    color: #337ab7;
}

/*----------------blog page-------------*/

ul .news-freedom:hover {
    color: #337ab7;
}

.news-list a:hover {
    color: #337ab7;
}


- Color

.bg-color-menuitem {
    background: #80b3ff;
}

.bg-color-thescript,
.danny-content,
.mark-content,
.glen-content,
.bg-color-back-to-top,
.section-heading {
    background-color: #08151F;
}

.bg-color-nav {
    background-color: #0B3177;
}

- These codes running on css to make the home page work on tablet and desktop screens:

As you would see pixels of a desktop screen, I set 1200px instead of 992px. 
The reason is that on About page I created a border covered a picture and texts of biography of each member of The Script. 
At that time, when I checked the screen which is less than 1000px, the border of each bigraphy did not appear on the screen.
On the other hand, the borders appeared on the big screen only; although I did try to change the size of the border but it still did not work either.
If I wanted it worked, I had to reduce the size of the border a lot like 500px, which was too small and it did not look nice on both table and desktop.
Therefore, I chose the desktop screen(1200px) to have the borders instead of neither tablet nor mobile screens.

    @media(min-width: 1200px) {
    
    .col-md-12 {
        width: 100%;
    }
    
    /*----home page----*/
    
    .bg-color-menuitem {
        padding-left: 100px;
    }
    
    .heading-content .home-image {
        width: 300px;
        height: 300px;
        margin-bottom: 20px;
        margin-right: 30px;
    }
    
    .inline-block {
        margin-top: 30px;
        margin-bottom: 30px;
        padding-right: 70px;
        padding-left: 30px;
        display: inline-block;
        text-align: left;
        font-size: 14px;
        letter-spacing: 1px;
        color: #ffffff;
    }
    
    
    /*----music page----*/
    
    .menu-songs iframe {
        width: 516px;
        height: 315px;
        margin: 50px;
        background-color: #0B3177;
        display: inline-block;
       
    }
    
    .bg-singles {
        width: 100%;
        background-color: #0B3177;
    }
    
    
 
     /*----blog page----*/
    
    table {
        margin-left: 300px;
        margin-top: 30px;
    }
    
    .bg-news-section-2 {
        margin-top: 30px;
        margin-left: 100px;
        padding-left: 100px;
    }
    
    .news-list {
        text-align: left;
        padding-top: 50px;
        padding-left: 70px;
        letter-spacing: 1px;
    }
    
    .news-freedom {
        color: #4d4dff;
        line-height: 2.0;
        padding-left: 80px;
    }
    
    .news-image-2 {
        margin-bottom: 70px;
        margin-left: 30px;
        float: left;
    }
    
    
    /*----about page----*/    
    
    .about-content {
        border: 10px solid transparent;
        box-sizing: content-box;
        padding: 30px;
        margin-bottom: 50px;
        margin: 40px;
        margin-left: 100px;
        border-image-repeat: round;
        border-image: url("../images/border.png") 45;
        -webkit-border-image: url("../images/border.png") 45; 
        -o-border-image: url("../images/border.png") 45;
        -moz-border-image: url("../images/border.png") 45;
        border-image-outset: 10px 10px;
        width: 1000px;
        height: 400px;
    }
    
    .about-content-2 {
        border: 10px solid transparent;
        border-spacing: 50px;
        box-sizing: content-box;
        padding: 30px;
        padding-bottom: 50px;
        margin-left: 200px;
        margin-top: 70px;
        border-image-repeat: round;
        border-image: url("../images/border.png") 45;
        -webkit-border-image: url("../images/border.png") 45; 
        -o-border-image: url("../images/border.png") 45;
        -moz-border-image: url("../images/border.png") 45;
        border-image-outset: 10px 10px;
        width: 1000px;
        height: 370px;
    }
    
    .about-content-3 {
        border: 10px solid transparent;
        box-sizing: content-box;
        padding: 30px;
        margin-bottom: 100px;
        margin: 70px;
        margin-left: 50px;
        border-image-repeat: round;
        border-image: url("../images/border.png") 45;
        -webkit-border-image: url("../images/border.png") 45; 
        -o-border-image: url("../images/border.png") 45;
        -moz-border-image: url("../images/border.png") 45;
        border-image-outset: 10px 10px;
        width: 1000px;
        height: 320px;
    }
    
    .donoghue-content,
    .mark-content,
    .glen-content {
        padding-left: 50px;
        padding-right: 50px;
    }
    
    .about-image {
        float: left;
    }
    
    .about-image-3 {
        float: left;
        margin-right: 30px;
    }
    
    .about-image-2 {
        float: right;
        margin-left: 30px;
    }
    
    /*----Footer----*/ 
    
    .right-menu {
        font-size: 12px;
        font-family: "Exo", sans-serif;
        margin-top: 10px;
    }
    
    .right-menu span {
        font-size: 13px;
        color: #ffffff;
        margin-right: 13px;
        margin-left: 13px;
        padding-right: 10px;
        border-right: 3px solid #ffffff;
    }
    
    .right-menu p {
        font-size: 13px;
        margin-right: 13px;
        margin-left: 13px;
        padding-right: 10px;
    }
    
    .footer-symbol i {
        margin: 10px;
        margin-right: 20px;
    }
    
    .footer-details span:hover {
        color: #ccff33;
    }
}


@media(min-width: 679px) and (max-width: 1119px) {
    
    .col-sm-12 {
        width: 100%;
    }
    
    /*----about----*/ 

    p .inline-block-about {
        text-align: justify;
        
    }
    
    .about-content img {
        float: left;
        margin-right: 30px;
    }
    
    .about-content-2 img {
       float: right;
       margin-left: 30px;
    }
    
    .about-content-3 img {
        float: left;
        margin-right: 30px;
    }
    
    /*----music----*/ 
    
    .songs iframe {
        padding: 50px;
    }
    
    /*----blog----*/ 
    
    .bg-news-section-2 img {
        float: left;
    }
    
    /*----footer----*/ 
    
     .right-menu {
        font-size: 13px;
        margin-top: 18px;
        font-family: "Exo", sans-serif;
        text-align: center;
    }
    
    .right-menu a {
        font-size: 11px;
        padding-left: 10px;
    }
    
    .privacy-policy span {
        margin-left: 10px;
    }
    
    .right-menu .copy-all-music {
        margin-left: 3px;
    }
    
    .footer-symbol i {
       float: right;
       padding-top: 20px;
       padding-right: 30px;
    }
}




These codes that are from other websites which have been used on html for this project: 

1. Bootstrap
   Used this code to make a table on html  

    <table class="table table-condensed">



2. Copied from Code institute material to building a navigation menu.
                

                <div class="row bg-color-nav">
                    <ul id="nav" class="list-inline clearfix">
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-home menuitem">
                            <a href="index.html" class="nav-bar uppercase">Home</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-music menuitem">
                            <a href="music.html" class="nav-bar uppercase">Music</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-contact menuitem">
                            <a href="blog.html" class="nav-bar uppercase">Blog</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-about menuitem">
                            <a href="about.html" class="nav-bar uppercase">About</a>
                        </li>

3. Copied from Code institute material to building a navigation menu


                <div class="col-xs-6 col-sm-6 col-md-6 footer-symbol">
                    <a target="_blank" href="https://www.facebook.com/thescript/"><i class="fa fa-facebook" aria-hidden="true"></i></a>
                    <a target="_blank" href="https://www.instagram.com/thescriptofficial/"><i class="fa fa-instagram" aria-hidden="true"></i></a>
                    <a target="_blank" href="https://twitter.com/thescript"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                </div>


 
These codes are from other websites which have been used on css for this project: 

1. Used these codes to create a pattern of border on the About page which I changed:
    - changed the value of box-sizing to be content-box
    - changed a picture of border on -webkit-border-image: url("../images/border.png"),
      -o-border-image: url("../images/border.png") and border-image: url("../images/border.png")
    - swaped border-image: url("../images/border.png") to the top of -webkit- and -o- so that the code would work on Apple screens 
    -  added width: 1000px and height: 400px;
    -  added padding: 30px, margin-bottom: 50px, margin: 40px and margin-left: 100px
    
.about-content {
        border: 10px solid transparent;
        box-sizing: content-box;
        padding: 30px;
        margin-bottom: 50px;
        margin: 40px;
        margin-left: 100px;
        border-image: url("../images/border.png");
        -webkit-border-image: url("../images/border.png"); 
        -o-border-image: url("../images/border.png"); 
        border-image-repeat: round;
        border-image-outset: 10px 10px;
        width: 1000px;
        height: 400px;
    }
    
    .about-content-2 {
        border: 10px solid transparent;
        border-spacing: 50px;
        box-sizing: content-box;
        padding: 30px;
        padding-bottom: 50px;
        margin-left: 200px;
        margin-top: 70px;
        border-image: url("../images/border.png");
        -webkit-border-image: url("../images/border.png"); 
        -o-border-image: url("../images/border.png"); 
        border-image: url("../images/border.png");
        border-image-outset: 10px 10px;
        width: 1000px;
        height: 370px;
    }
    
    .about-content-3 {
        border: 10px solid transparent;
        box-sizing: content-box;
        padding: 30px;
        margin-bottom: 100px;
        margin: 70px;
        margin-left: 50px;
        border-image: url("../images/border.png");
        -webkit-border-image: url("../images/border.png"); 
        -o-border-image: url("../images/border.png"); 
        border-image-repeat: round;
        border-image-outset: 10px 10px;
        width: 1000px;
        height: 320px;
    }

2. Used these codes to create a logo which is from the User-centric frontend development module which I changed:
    - changed background
    - changed background-size 
    - added width: 100%
    - added min-height 
    
.logo {
    background: url("../images/album1.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    min-height: 400px;
    transition: all .5s ease-in-out;
    -moz-o-transition: all .5s ease-in-out;
    -webkit-o-transition: all .5s ease-in-out;
}

3. Used these animation codes to create flashlights on the Blog page which I changed:
    - changed background-color and @keyframes 
    - changed display 
    - changed height:10px
    - changed name of animation to headline
    - changed the duration of animation faster
    - changed animation-iteration-count to be infinite
h2 {
  overflow: hidden;
  text-align: center;
}
h2:before,
h2:after {
  background-color: #000099;
  content: "";
  display: inline-block;
  height: 10px;
  position: relative;
  vertical-align: middle;
  width: 50%;
  -webkit-animation-name: headline; 
  -o-animation-name: headline;
  -webkit-animation-duration: 1s;
  -o-animation-duration: 1s;
  animation-name: headline;
  animation-duration: 1s;
  animation-iteration-count: infinite;
  
}
@-webkit-keyframes headline {
    from {
        background-color: #000099;
        
    }
    to {
        background-color: #ffff00;
        
    }
}
@keyframes headline {
    from {
        background-color: #000099;
        
    }
    to {
        background-color: #ffff00;
        
    }
}
h2:before {
  right: 0.7em;
  margin-left: -50%;
}
h2:after {
  left: 0.7em;
  margin-right: -50%;
}
   

    For the rest I have written. As you can see on the html page, I still used some class names the same as shown on the materials.
The reason is that it makes me remember what is all about, however; all the details inside I changed and added new values and new codes to create
something that was suitable for my site.  

  
# Built with

- [Cloud 9](https://www.aws.amazon.com/cloud9/?origin=c9io)
- [Adobe XD](https://www.adobe.com/products/xd.html)
    
    
# Credits and Related links

- [Ticketmaster](https://www.ticketmaster.ie)
- [The Script Official](https://www.thescriptmusic.com)
- [Youtube](https://www.youtube.com)
    


# License

MIT © [Suchada Rotjanathamrong](www.linkedin.com/in/suchada-rotjanathamrong-205735110)


   
