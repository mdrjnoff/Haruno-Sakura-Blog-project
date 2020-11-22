# Haruno-Sakura-Blog-project
Dr. Haruno Sakura's site

<!DOCTYPE html>
  <html lang="en-US">
  <head>
    <!-- Have a good day <3 You who is reading right now ;) -->  
    <meta charset="UTF-8">
    <title>Mini blog project</title>
  </head>
  
  <body>
    <header>
    <!-- header start -->
    <div><button onclick="topFunction()" id="myTopBtn" title="Go to top">Back to top</button>
         <img alt="" class="img-circle" src="https://code.sololearn.com/Icons/Avatars/0.jpg">
         <p>Sakura Haruno</p>
    </div>
    <!-- header end -->
    
    <!-- Lil' presentation section start -->
    <div class="section">
        <h1><span>Who am I ?</span></h1>
        <p>Hey! I'm Sakura <b><i>Haruno</i></b>, the strongest kunoichi from Konoha.I started learning coding after the fourth ninja war. It was a globale ninja alliance against Kabuto, Akatsuki and other dickheads (oops) in order to kinda save the whole world from his freedom. Since then, I had a beloved daughter. Not gonna say much more, I would not spoil you in case you haven't seen it ;)
        </p>
            <p class="quote">"Declare variables, not war"</p>
        </div>
    <!-- lil' presentation section end -->
    
    <!-- My Ninja Schedule section start -->
    <div class="section">
        <h1><span>My Ninja Schedule</span></h1>
        <table>
            <tr>
                <th><br /></th>
                <th>Day</th>
                <th>Mon</th>
                <th>Tue</th>
                <th>Wed</th>
                <th>Thu</th>
                <th>Fri</th>
            </tr>
            <tr>
                <th>Morning</th>
                <td>8-9h</td>
                <td class="selected">Learn</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th><br /></th>
                <td>9-10h</td>
                <td></td>
                <td class="selected">Practice</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th><br /></th>
                <td>10-11h</td>
                <td></td>
                <td></td>
                <td class="selected">Play</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th><br /></th>
                <td>11-12h</td>
                <td></td>
                <td></td>
                <td></td>
                <td class="selected">Code</td>
                <td></td>
            </tr>
            <tr> <!-- Space separating morning from afternoon schedule -->
                <td><br/></td>
            </tr> 
            <tr>
                <th>Afternoon</th>
                <td>13-14h</td>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td class="selected">Discuss</td>
            </tr>
            <tr>
                <th><br /></th>
                <td>14-15h</td>
                <td></td>
                <td class="selected">Practice</td>
                <td></td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th><br /></th>
                <td>15-16h</td>
                <td></td>
                <td></td>
                <td class="selected">Play</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <th><br /></th>
                <td>16-17h</td>
                <td></td>
                <td></td>
                <td></td>
                <td class="selected">Code</td>
                <td></td>
            </tr>
        </table>
    </div>
    <!-- My Schedule section end -->
        
        
    <!-- My Skills section start -->
    <div class="section">
        <h1><span>My Skills ranked according to my priorities of learning</span></h1>
        <ol>
            <li>HTML<br />
                <progress min="0" max="100" value="60"></progress>
            </li>
            <li>CSS<br />
                <progress min="0" max="100" value="10"></progress>
            </li>
            <li>JavaScript<br />
                <progress min="0" max="100" value="8"></progress>
            </li>
            <li>Python<br />
                <progress min="0" max="100" value="10"></progress>
            </li>
            <li>C# (C sharp)<br />
                <progress min="0" max="100" value="4"></progress>
            </li>
        </ol>
    </div>
    <!-- My Skills section end -->
        
        
         <!-- Media section start -->
        <div class="section">
            <h1><span>My Media</span></h1>
            <iframe height="150" width="300" src="https://www.youtube.com/embed/Q6_5InVJZ88" allowfullscreen frameborder="0"></iframe>
        </div>
        <!-- Media section end -->
        
        <!-- Form section start -->
       <div class="section">
            <h1><span>Wanna contact me ?</span></h1>
            
            <svg class="face" height="100" width="100">
                <circle cx="50" cy="50" r="50" fill="#FDD835"/>
                <circle cx="30" cy="30" r="10" fill="#FFFFFF"/>
                <circle cx="70" cy="30" r="10" fill="#FFFFFF"/>
                <circle cx="30" cy="30" r="5" fill="#000000"/>
                <circle cx="70" cy="30" r="5" fill="#000000"/>
                <path d="M 30 70 q 20 20 40 0" stroke="#FFFFFF" stroke-width="5" fill="none" />
            </svg>
                 
            <form action="URL" method="GET">
                <input name="name" placeholder="Your name" type="text" required /><br/>
                <input name="email" placeholder="Your adress mail" type="email" required /><br/>
                <textarea name="message" placeholder="What you want to say to me :)" required ></textarea>
                <input type="submit" value="SEND" class="submit" />
            </form>
        </div>
        <!-- Form section end -->
        
        <!-- Contacts section start -->
        <div class="section" id="contacts">
            <h1><span>Or, follow me ?</span></h1>
            <div>
                <a href="https://www.sololearn.com/" target="_blank">
                    <img alt="Thegr3yg1rl" src="https://www.sololearn.com/Uploads/icons/sololearn.png" />
                </a>
            </div>
        </div>
        <!-- Contacts section end -->
        
        <div class="copyright">
            &copy; 2019 My Blog. All rights reserved.
        </div>
    </header>
  </body>
 </HTML>
