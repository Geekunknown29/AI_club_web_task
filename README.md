<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-image: linear-gradient(to left, rgba(177, 23, 131, 0.752), rgb(0, 0, 0));
            
        }
        body{
            background-color:rgba(0, 0, 0, 0.636);
        }
        #forback{
            background-image: url("https://th.bing.com/th/id/R.08de08c5e1488dff26c48025ac47753b?rik=Jpd%2f9fC2%2fjyUPA&riu=http%3a%2f%2fwallpapercave.com%2fwp%2fduL56wg.jpg&ehk=ezfcDBWpnHmX53SnDU0pjy5a7XeAlXb0On4PVdXZM5k%3d&risl=&pid=ImgRaw&r=0");
            background-size:cover;
            background-repeat: no-repeat;
            width: 100%;
            height: 100% ;
        }
        #hero {
            margin: 0;
            padding: 100px;
            background-color: rgba(71, 6, 106, 0.053);
            color: whitesmoke;
            
            align:left;
            

        }
        .heading {
            background-color: rgba(249, 144, 202, 0.019);
            background-position:center;
            text-align:unset;
            font-size: 50px;
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            text-shadow: 1px 1px 2px rgba(250, 0, 8, 0.951), 0 0 1em rgba(244, 121, 6, 0.879), 0 0 0.2em rgb(255, 18, 212);
            color:rgb(0, 0, 0);
            font-size:5vw;
            animation: blink 38s infinite;
            
        }

        @keyframes blink {
            0%, 50% {
                opacity: 1;
            }
            25%, 75% {
                opacity: 0;
            }

        }
        #texthead{
            background-color:rgba(0, 0, 0, 0.111);
            font-style:italic;
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif
        }

        .navbar {
            background-color: #1815155a;
            padding: 10px;
        }

        .navbar ul {
            display: flex;
            justify-content: space-around;
        }

        .navbar ul li {
            display: inline;
        }

        .navbar ul li a {
            color: rgba(248, 243, 216, 0.578);
            text-decoration: none;
            padding: 10px 20px;
        }

        .navbar ul li a:hover {
            background-color: #23151c76;
            border-radius: 4px;
        }
        
        #aboutus{
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:white;
            background-color:rgba(44, 2, 2, 0.258)
            

        }
        .about_head{
            color:blanchedalmond;
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: 4vw;
           
            text-transform: uppercase;
            text-decoration-thickness: 3px;
            text-decoration-color: rgba(245, 227, 214, 0.888);
            text-shadow: 1px 1px 2px rgba(154, 233, 142, 0.401), 0 0 1em rgba(244, 121, 6, 0.44), 0 0 0.2em rgba(169, 30, 3, 0.418);
            font-size: 4em;
            color: rgba(251, 233, 35, 0.868);
            animation: blink 2s infinite;
            
        }

        @keyframes blink {
            0%, 50% {
                opacity: 1;
            }
            25%, 75% {
                opacity: 0;
            }

        }


        #events {
            padding: 50px;
            text-align: center;
            font-family:Verdana, Geneva, Tahoma, sans-serif;
        }

        #events h2 {
            margin-bottom: 20px;
        }

        .event-cards {
            display: flex;
            justify-content:center;
            flex-wrap:wrap;
        }

        .card {
            background: #0000007d;
            padding: 20px;
            margin: 10px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        #upcoming{
            background-color:rgba(69, 85, 88, 0.564);
            color:rgba(243, 169, 225, 0.99)
        }
        #past{
            background-color:rgba(79, 53, 94, 0.564);
            color:rgba(226, 219, 95, 0.84)
        }
        .text{
            font-family:Verdana, Geneva, Tahoma, sans-serif
        }

        .event_time{
            text-decoration:dotted;
            text-decoration: underline;
            text-decoration-thickness:1px;
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:black;
            text-shadow: 1px 1px 2px rgba(245, 112, 116, 0.437), 0 0 1em rgb(223, 19, 185), 0 0 0.2em rgba(221, 177, 0, 0.152);
        }
        .event_name{
            color:rgba(130, 249, 215, 0.662);
            font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-shadow: 1px 1px 2px rgba(13, 229, 249, 0.938), 0 0 1em rgb(151, 109, 251), 0 0 0.2em rgba(38, 225, 132, 0.5);
            text-decoration:underline;
            text-decoration-thickness:1px;
            text-decoration-color: rgba(80, 230, 69, 0.807);
            
        }


        footer {

            background-color: #f9deb819;
            color: white;
            padding: 20px;
            text-align: center;
        }



    footer {
                background-color: #f1ebe821;
                color: white;
                padding: 20px;
                text-align: center;
            }
            .footer-content p {
                margin: 10px 0;
                display: inline;
            }
            .social-links {
                display: inline;
                padding: 0;
                text-align: center;
            }
            .social-links li {
                display: inline;
                margin: 0 10px;
            }
            .social-links li a {
                color: white;
                text-decoration: none;
            }
            #resources{
                color:bisque;
                background-color:rgba(64, 2, 17, 0.285);
            }
            .re_head{
                color:#fcaa80e3;
                font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                text-shadow: #470cf9ef;
                font-size: 3vw;
            }

            .text{
                color:rgba(229, 255, 0, 0.832);
                text-shadow: 1px 1px 2px rgba(228, 188, 10, 0.266), 0 0 1em rgba(251, 109, 196, 0.359), 0 0 0.2em rgba(35, 144, 233, 0.216);
                text-decoration:underline;
                text-decoration-thickness:1px;
                text-decoration-color: rgba(71, 1, 66, 0.807);
            }
            .re_head{
                color:#000000e3;
                font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                
                text-shadow: 1px 1px 2px rgba(251, 0, 255, 0.89), 0 0 1em rgba(235, 9, 141, 0.501), 0 0 0.2em rgba(205, 85, 0, 0.797);
                font-size: 3.5vw;
            }


            .x{
                background-color:rgb(157, 52, 106);
            }
            .logo{
                padding:20px;
                margin:20px;
                width:145px;
                height:200px;
                
                display:inline;
                
            }
            .join-container {
                color:white;
                display: flex;
                flex-direction: column;
                align-items: center;
                text-align: center;
                list-style:none;
            }

            .join_link {
                margin-top: 10px; 
                list-style: none;
                color:rgb(0, 217, 255);
                text-shadow: 1px 1px 2px rgba(251, 0, 255, 0.89), 0 0 1em rgba(246, 133, 199, 0.53), 0 0 0.2em rgba(245, 134, 55, 0.797);
                
            }
            .join-list {
                list-style: none; 
                padding: 0;      
                margin: 0;       
            }
            #join_us{
                background-color:rgba(46, 5, 78, 0.134);
                height:175px;
            }

 
            
    </style>
</head>
<body>
    <div id = 'forback'>
        <nav class = 'navbar'>
            <ul>
                <li> <a href = #aboutus> About Us </a></li>
                <li> <a href = #events> Events </a></li>
                <li> <a href = #footer-content> Contact Us </a></li>
                <li> <a href = #join> Join Us </a></li>
            </ul>
        </nav>
        <section class="logo">
            <image src = "https://vitbhopal.ac.in/wp-content/uploads/2022/02/VIT-Bhopal-Logo.png" alt="aiclub logo", height="70px">
            <image src = "https://aivitb.com/images/club_logo.png" alt="ai club logo" height="70px">
        </section>
        <div id="hero">
            <pre class="heading">"We Exist 
          To Alter 
                 The Reality"</pre>
            <div id = 'texthead'>
                <p> AI club, the one thing you must take part into.
                    this club features some of the most briliants minds to some hands on tasks and supports the solving of some universal problem.
                    here the knowledge meets wisdom to create some revoluionary stuff.
                </p>
                <br>
                <br>
                <hr>
                
                <br>
                <br>
                </div>
        </div>
    </div>
    <br>
    <hr>
    <br>
    <div  id = 'aboutus'>
        <h2 class="about_head"><blink>About Us :</blink-182></h2>

    
                <br>
                <p>Welcome to the AI Club at VIT Bhopal University—a dynamic group of students united by a shared passion for Artificial Intelligence. Our goal is to create a space where learners of all levels can come together, explore the endless possibilities of AI, and turn innovative ideas into reality.

                    Whether you're new to AI or an experienced developer, we offer something for everyone. From hands-on workshops and coding challenges to insightful talks and collaborative projects, the AI Club is the perfect place to grow your skills and stay ahead of the curve. We believe in learning by doing, and we encourage our members to dive into real-world applications of AI.
                    
                    More than just a club, we’re a community—driven by curiosity, creativity, and a desire to push the boundaries of technology. Join us on this journey to shape the future through AI!</p>
    </div>        
    <section id="events">
        <div id="upcoming">
            <h2 class="event_time">Upcoming Events</h2>
            <p>Wonder how we create the new geniuses? Check out our major events:</p>
            <div class="event-cards">
                <div class="card">
                    <h3 class="event_name">HackExchange</h3>
                    <p>Get ready for a one-of-a-kind hackathon experience where innovation, collaboration & mentorship come together
                         as one. Brainstorm groundbreaking ideas, shape project prototypes under expert guidance & stand a chance to claim the grand prize of 2500.
                          💸 This is your moment to stretch your limits, unleash your creativity & pave the
                         way for the future of AI. Up for the challenge? 💪🏻Then join us on this intellectual adventure and let's co-create the future.
                    </p>
                </div>
                <div class="card">
                    <h3 class="event_name">Visterra</h3>
                    <p>Exciting News Unveiled! Join us for “Visterra” - a hands-on project session on CNNs led by our dynamic core team members Punit Kaushik,
                         Sarfaraj Ansari, and Kshitij Dalvi! 🤖✨ Dive into the world of object detection, create your ML model, deploy it as a web app using
                          Streamlit and GitHub, and boost your resume for those dream internships! 🚀
                         Save the date - December 15, 9:30 AM to 1:30 PM. Don’t miss out on this incredible learning opportunity! 
                         📆 #VisterraEvent.</p>
                </div>
                <div class="card">
                    <h3 class="event_name">GENESIS</h3>
                    <p> Exciting news! Introducing Genesis - a 2-day online event, featuring a workshop on NLP with Rishit Chugh and a podcast on Projects and Going Abroad with 
                        Kumar Prakhar. Mark your calendars for 24th and 25th Nov ‘23. Knowledge,
                         inspiration, and networking await! 🌐🔗 REGISTRATION IS ABSOLUTELY FREE! Link in Bio! #aiclub #vitb #nlp #chatgpt #gpt</p>
                </div>
            </div>
        </div>
        <br>
        <hr>
        <br>
        
        <div id="past">
            <h2 class="event_time">Check Out Our Past Events:</h2>
            <div class="event-cards">
                <div class="card">
                    <h3 class="event_name">AIconic</h3>
                    <p>📢🤖 Get Ready to Conquer AIConic: The Ultimate Coding Hunt! 🏆🔥

                        📅 Date: 26th July 2023
                        🏛️ Venue: VIT Bhopal Auditorium
                        ⏰ Time: 10:00am – 6:00pm
                        
                        Join us for an unforgettable AI adventure at AIConic! 🚀
                        
                        🌟 Embrace the opportunity to learn from the best, Mr. Rahul Mishra - the Expert in Generative AI and Head of Growth at Concept Campus! 🧠💼
                        
                        Participate in a mind-bending coding treasure hunt and test your AI skills! 💻
                        
                        🔍 Unleash the potential of Artificial Intelligence and secure your spot now!
                        
                        🤖🗝️ Don't miss out on this epic event by registering/p>
                </div>
                <div class="card">
                    <h3 class="event_name">Spring Bootcamp</h3>
                    <p>💡Are you ready to take your programming skills to the next level and make your vacations count?

                        🏁3 Days - 2 Projects 1 Live Podcast
                        
                        🌸 *Spring Bootcamp* is here!
                        Attend hands-on learning sessions that will help you build these Internship-ready skills on AIML & Web development:
                        
                        👉ML
                        👉Kaggle
                        👉Python
                        👉Jupyter Notebook
                        👉UI/UX
                        👉HTML
                        👉CSS
                        👉Java Script
                        👉API fetching
                        👉Github
                        
                        💰You get all this for flat ₹99. Offer valid only till 10 March '23
                        
                        *FREE* for existing members of the AI Club.
                        
                        📚Learn directly from top MNC professionals and gain practical knowledge. Tune in for internship-placement guidance from one of VIT Bhopal's highly successful alumnus - Rohan Sarkar, who received an offer of *35LPA+*.
                        
                        📌Mark your calendars for three action-packed days on learning and networking and get ready to elevate your skills to the next level!
                        
                        📝Here is the event schedule:
                        March 10th: Last date for early bird registration
                        
                        March 16th: Build an AIML-based model.
                        
                        March 17th: Create a web dev project.
                        
                        March 18th, 2 PM–4 PM: Discord podcast on placement and internship guidance, with a particular focus on the AIML domain.
                        </p>
                </div>
                <div class="card">
                    <h3 class="event_name">Tech digest</h3>
                    <p>Unlock the power of AI and change perceptions with The Tech DAIgest! Our mission is to make AI accessible to all. Join us on this exciting 
                        journey and dive into the limitless possibilities! 🔍 Magazine Link in bio! #AIaccessibility #TechNews
                         #TheTechDAIgest #ai #ml #aiclub #vitb</p>
                </div>
            </div>
        </div>
    </section>

  
    <hr>
    <section id="resources">
        <h3 class = "re_head">RESOURCES </h3>
        <div class="blog">
            <pre class="text">
                    Do you know the way we think?
                        Do you know the way a normal person think?
                            You want to know about latest tech news or latest updates?</pre>
            <section class="blog_index">
                <p>Dive into a world of insightful articles, thought-provoking discussions, and the latest updates. Our blog is
                     dedicated to providing in-depth analysis and perspectives on a wide range of topics, from current events and social issues to education
                     , technology, and personal growth. Whether you're looking to stay informed, get inspired
                    , or explore new ideas, we've got something for everyone. Join our community of curious minds and start
                     exploring!
                </p>
           </section> 
            <ul style="list-style: none; display: flex; align-items: center;">

                <li style="margin-right: 10px;">Check out our blogs here:</li>
            
                <li>
                    <a href="https://medium.com/ai-club-vit-bhopal" >
                        <img src="https://th.bing.com/th/id/R.0927581e090202c04ec490d9e9d68277?rik=pzybfJ6sStS7bg&riu=http%3a%2f%2fpluspng.com%2fimg-png%2fmedium-logo-vector-png-medium-icon-white-on-black-1600.png&ehk=91i%2fAjWf0ygUFD5xar3qWmp3S6LDpeopRUGpuWcRw58%3d&risl=&pid=ImgRaw&r=0" alt="Medium logo" height="50px">
                    </a>
                </li>

            </ul>
        </div>
    </section>

    <br>
    <br>
    <br>
    <br>


    <div id ="join">
        <section id='join_us'>
            <div class="join-container">
                <p>
                    Do you want to be part of the revolution?
                    Do you find yourself as the person who wants to bring change in society?
                    Do You love ai?
        
                    Join our team 
                    be a team member from society!!!
                </p>
                <div id="footer-content">
                    
                    <ul class="join-list">
                        <li><p>To join our team click the glowing text:</p></li>
                        <li class="join_link"><a href="https://aivitb.com/">JOIN US</a></li>
                    </ul>
                </div>
            </div>
        </section>
    </div>
    
    
</body>
<br>
<br>
<hr>
<br>
<br>
<footer>
    <div id="footer-content">
        <p>AI Club | Empowering the future with AI. Learn, collaborate, and innovate.</p>
        <ul class="social-links">
            <li><a href="https://twitter.com/aiclub"><img src="https://cdn.icon-icons.com/icons2/4029/PNG/512/twitter_x_new_logo_square_x_icon_256075.png" alt="Twitter X logo" width="70px" ></a></li>
            <li><a href="https://www.instagram.com/aiclub.vitb/"><img src="https://th.bing.com/th/id/OIP.jIjxU37e3484oqVvsn71IQHaHa?rs=1&pid=ImgDetMain" alt="Instagram logo" width="40px", height = 40x></a></li>
        </ul>
    </div>
</footer>
</html>
