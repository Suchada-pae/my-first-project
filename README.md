I am Suchada Rotjanathamrong. I am a mentor online programe student.
This website is designed and created as a part of a student project in software development. 
The project is about building a website for a given client by using the user-centric frontend development. 
My client is The Script which is well-known as an Irish rock band. And this is the website created for them.  
The majority of the codes I have written and some I took from the outsources which was adapted and applied to fit into my project. 

When you go to my website, what you are going to see is my home page which contains:

1. A picture of the latest album of the Script "Freedom Child" that I added on at the top of the page in a header area.


To make the image at the top of the page as a logo, I used these codes running on html:
        <header class="contain-fluid">
            <div class="row">
                <div class="col-md-12 logo"></div>
            </div>
        </header>

And these codes running okn css:

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
    
    
2. A navigation menu


To make the nav menu, I used these codes on html:
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
                            <a href="blog.html" class="nav-bar uppercase">Blog</a>
                        </li>
                        <li class="col-xs-6 col-sm-2 col-md-2 ui-menu-color-about menuitem">
                            <a href="about.html" class="nav-bar uppercase">About</a>
                        </li>
                    </ul>
                </div>
                
And these codes running on css: 

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


3. The content of the section area on home page which contains:

    - A heading "THE SCRIPT", to make the heading appeared on my site; I used these codes running on html:
            
            <!--content-->
                <div class="row bg-color-thescript">
                    <div class="col-xs-12 col-sm-12 col-md-12">
                        <h1 class="uppercase sub-heading">The Script</h1>
                    </div>
                    
    And to make the heading "THE SCRIPT" appeared on the screen with uppercase, used these codes running on css: 

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

            
            
    - The brief story of the Script appeared on my site, I used these codes running on html:
    
    
                <div class="col-xs-12 col-sm-12 col-md-12 heading-content">
                    <p class="inline-block"><img src="https://images.sk-static.com/images/media/profile_images/artists/465363/huge_avatar" class="home-image" alt="the Script" align="left" width="300" height="410">The Script is a famous rock band, where originally come from Dublin, Ireland. At the beginning of <span class="phase-line">the Script</span>, the band was formed by guitarist <span class="phase-line">Mark Sheehan</span> and vocalist <span class="phase-line">Danny O'Donoghue</span> in 1996.
                    The band received a success in their home country and desired to go worldwide. However, they did not go so far as they expected, so that the two musicians decided to go to Los Angeles and worked there as producers, where they wrote and produced songs for singers and bands such as 
                    <span class="phase-line">Britney Spear</span>, <span class="phase-line">Boy II Men</span> and <span class="phase-line">TLC</span>.
                    After spending several years in Los Angeles, they moved back to Ireland where they found <span class="phase-line">Glen Power</span> to joy the band as a drummer.<br> 
                    
                    <br>The band released the first debut album in August 2008 by Phonogenic Records. The most popular singles of <span class="phase-line">"the Script"</span> album that made them become famous in both the UK and America were<span class="phase-line">"The Man Who Can't Be Moved"</span> and <span class="phase-line">"Breakeven"</span>.
                    After their first albums, the band has released next four albums: <span class="phase-line">"Science & Faith"</span> in 2010, <span class="phase-line">"#3"</span> in 2012, <span class="phase-line">"No sound without Silence"</span> in 2014 and the latest one from last year <span class="phase-line">"Freedom Child"</span>. 
                    Not only those songs became successful, some of their singles could go to the top charts in the UK, America and Asia as well, such as <span class="phase-line">"Hall of Fame"</span>, <span class="phase-line">"Superheros"</span>, <span class="phase-line">"Rain"</span> and <span class="phase-line">"Written in the Scars"</span>.<br>
                    
                    <br>Nowadays, <span class="phase-line">the Script</span> is globally well-known as an Irish rock band and has a lot of fans around the world.
                    It is said that <span class="phase-line">the Script</span> is one of the rock bands has made a significant success of their career according to the numbers of selling the records and the tickets tour. 
                    </p><br>
                </div>


And these codes on css: 

    - I used these codes to set an image at the left hand site of the story of the Script:

            .inline-block img {
                float: left;
                width: 200px;
                height: 250px;
                margin-right: 30px;
            }
                
    - added these codes to set the position, size and color of the letters:

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
    - added this code to set blue color on some words in the texts:
            .phase-line {
                font-size: 14px;
                letter-spacing: 1px;
                color: #9999ff;
            }

4. A link to go back to the top of the home page:

        html:
    
         <!--back to top-->
                <div class="row bg-color-back-to-top">
                   <div class="col-xs-12 col-sm-12 col-md-12">
                        <a href="#" class="nav-bar lowercase">back to top</a>
                   </div> 
                </div>
            </div>

        css:
        
        .bg-color-back-to-top .nav-bar {
            float: right;
            margin-right: 40px;
            font-family: "Exo", sans-serif;
            letter-spacing: 1.5px;
            font-size: 13px;
        }

    
5. A footer:

    - Privacy Policy & ©2018 All musics- All Rights Reserved:
    
        <footer class="contain-fluid">
            <div class="row footer-details">
                <!--copyrights-->
                <div class="col-xs-6 col-sm-6 col-md-6 right-menu">
                    <a class="privacy-policy color" href="images/p2.pdf" target="_blak")><span class="uppercase general-sub">Privacy Policy</span></a>
                    <p class="copy-all-music">©2018 All musics- All Rights Reserved</p>
                </div>

    - And these codes on css: 

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
        
   - added this code to change the color on a link of privacy policy on the left-hand side of the footer:

        .right-menu .privacy-policy:hover {
            color: #337ab7;
        }

        
        
    - Symbols of social medias (Facebook, Twitter and Instagram) at the right hand side:
    
            html
            
            <div class="col-xs-6 col-sm-6 col-md-6 footer-symbol">
                    <a target="_blank" href="https://www.facebook.com/thescript/"><i class="fa fa-facebook" aria-hidden="true"></i></a>
                    <a target="_blank" href="https://www.instagram.com/thescriptofficial/"><i class="fa fa-instagram" aria-hidden="true"></i></a>
                    <a target="_blank" href="https://twitter.com/thescript"><i class="fa fa-twitter" aria-hidden="true"></i></a>
                </div>
    
            css
            
            .footer-details .fa {
                float: right;
            }
            
            .footer-symbol i {
                margin: 10px;
                margin-right: 20px;
            }
    
            .footer-details span:hover {
                color: #ccff33;
            }
            
            .fa {
                padding-right: 15px;
            }


Second page of my website is music page which contains top 10 singles:

1. At the top of music page is the same as the home page which has the logo and the nav menu, You can see all the codes that present at the home page. 


2. Section of music page contains the 10 Youtube videos of the Script:

        html codes of heading "THE TOP 10 SINGLES:
             <!--heading-->
                <div class="row bg-singles">
                    <div class="col-xs-12 col-md-12 section-heading">
                        <h1 class="uppercase sub-heading-singles">The Top 10 Singles</h1>
                    </div>        
                </div>    
        
        css codes of heading "THE TOP 10 SINGLES:
        
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

        
   html codes of the list of "THE TOP 10 SINGLES: 
        
        
            <!--top 10 songs-->
                <div class="row col-md-12 songs">
                    <div class="section-sub-heading">
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/gS9o1FAszdk" controls frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/vOKOamXsXYE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>                       
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                             <iframe src="https://www.youtube.com/embed/CPEBN2dVNUY" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>        
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/SGlkwKA-t_4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/KMihKmoYfe8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/QV62YRpIeUA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/-iA-MHxa8C8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/WIm1GgfRz6M" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/ho9xM9n2USA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                        <div class="col-xs-12 col-sm-6 col-md-6 menu-songs">
                            <iframe src="https://www.youtube.com/embed/mk48xRzuNvA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
                        </div>
                    </div>   
                </div>
        
        
        css codes of the list of "THE TOP 10 SINGLES:
        
        
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
    
3. A link of back to the top
4. A footer



Third page is Blog:

1. At the top of music page is the same as the home page which has the logo and the nav menu, You can see all the codes that present at the home page. 


2. the Section of Blog page contains:

    - A heading "BLOG":
    
        html:
        <!--blog-->
                <div class="row event-news">
                    <div class="col-xs-12 col-md-12 bg-heading-news">
                        <h1 class="uppercase sub-heading">Blog</h1>
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
        
    - A sub-heading "Tour":
    
        html:
        <!--tour-->
                <div class="row event-news-2">
                    <div class="col-md-12 bg-news">
                        <h2 class="news-event">Tour</h2>
                        
        css:
        .news-event {
            margin-top: 50px;
            margin-bottom: 50px;
            text-align: center;
            color:#0000ff;
        }
    
    - Two flashlights between the sub-heading (Tour):
    
        only on css:
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
        
    - A table of ticket tours:
    
                        html:
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
                            
                            
                        css:
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
                            
        - Ticket buttons in the table:
                

   html:        
                                                                
    <button type="button" class="btn btn-warning">Ticket</button>
        
                            
    css:
        button {
            display: block;
            margin-right: 30px;
         }

                        
    - A heading "NEWS":
    
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