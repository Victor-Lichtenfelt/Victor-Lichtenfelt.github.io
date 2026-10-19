<h1> Victor Lichtenfelt's Simple Portfolio </h1>

<hr>

<h2> Professional Self Evaluation </h2>
		
<p>
Overall, the program of Computer Science here at SNHU has been massively helpful in the development of ability to code and structure that code for projects in a varied amount of applications, including app development and full-stack development in addition to a class on AI production. More importantly then that, it has trained general software development skills, including a familiarity with the use of databases, an ability to create and use complex data structures and algorithms, along with an awareness of security procedure and testing of code.
</p>

<p>
Security is likely my toughest challenge, though still learned via the help of the professors at SNHU in the classes Software Security (2025 Sep-Oct) and Secure Coding (2026 May-Jun) respectively, along with general help in other classes, have been helpful in getting my mind around the concept. While I likely would rely on libraries, I can confidently say I know the differences between and reasons to use hashes vs encryption (and public-key vs private key, along with the homomorphic encryption), and the respective use cases of them, with hashing being used for cases where recovery is unimportant or undesired in order to guarantee similarity (such as with passwords and download verification) and proper ciphers do encryption in a manor that is reversible in some way (such as data storage).
</p>

<p>
Software engineering and database work may be the opposite, as the Intro to Struct Database Env (2025 Mar-Apr) and Full-Stack Development I (2026 Jun-Aug) all antiquated me with Databases and so to a minor degree so did Mobile Architecture and Programming (2026 Jan-Mar) and Client/Server Development (2026 Mar-Apr), though those classes was more on the software engineering Side, and Full-Stack Development was arguably just as effective in teaching that skill. Other classes that also improved software engineering skills include every other computer science class, but special mentions include Comp Graphic and Visualization (2026 Jan-Mar) as well as Systems Analysis and Design (2025 Jun-Aug), which while beaten by the classes that also focused on databases in learning about the code that keeps process together, were good for getting an idea of the processes, Comp Graphic and Visualization at a more low-level application of code and Systems Analysis and Design was good at giving a high level view.
</p>

<p>
Data structures and algorithms are done in every single class. From text adventure games made in Introduction to Scripting (2024 Oct-Dec), all the way up to and including data reflection of database qualities in Full-Stack Application Development, development of small AI models in Current Emerging Trends in Computer Science (2026 Mar-Apr) as well as state machines and smaller algorithms for traits such as bit hacks and memory saving in Emerging Sys Arch & Tech (2026 May-Jun). Along with time spent on personal development with sites like LeetCode, I should be able to be effective in creating the required tools and storage containers in code development.
</p>

<p>
Communicating with stakeholders and collaborating in a team environment are the ones that are currently not filled with on the job experience, but as much as school can prepare it has prepared for this. Systems Analysis and Design mentioned the social element, but Software Development Lifecycle (2025 May-Jun) was done, and every class so far has had both discussion with fellow classmates; in addition, communication with teachers when problem were had involving either understanding or what was asked, and have been able to be addressed. In addition, Systems Analysis and Design (2025 Jun-Aug) also mentioned some of the elements involved in communicating with others.
The chosen artifact of the full-stack development travlr application was selected because it ultimately has the most immediate and primary ability to show use, as the additions of an authorization system, filtering options, and swapping out the in use database for another all contribute to a system that easily displays a number of the skills mentioned earlier in the project, including database use, awareness of security, and a modicum of data structures ability primarily seen in the database class.
</p>

<p>
The travlr application consists of three major sub-folders containing an admin side angular application (app_admin), a customer facing simple static site (app_server), and a database interfacing api (app_api). Improvements and changes focused on the app_admin and app_api side.
</p>

<hr>
<h1> Full-Stack Site and Improvements/Changes </h1>
<hr>

<h2> Full-Stack Application </h2>

<p>
I created, as part of the CS 465: Full-Stack Development, a site using the MEAN stack, that can be seen on branch module-7. It contains an admin portal, a web API for database interaction, and a static front page. These all used a lot of different tools in order to make, including Angular, MongoDB, Express and NodeJS in order to get setup. The website's admin page was able to support the creation of, editing, and viewing of trips in addition to basic authorization via having a user login page and database with user login details. It uses trips to reflect a travel website, and has a number of traits that match that use.
</p>
<p>
This class, and therefore the creation of the full-stack website, was done in July-August 2026. As such, it shows recent ability to work with databases, engineer software, use algorithms and data structures to make a functional product. It even shows some security concepts with the authentication though it clearly leaves room for improvement on those principles without even a hint of authorization. This is why it was chosen as the focus of all improvements, as it reliably has all the elements to make improvements to. The primary emphasis of the improvements and changes was to the admin portal and the web API for database interaction, and the static front page was left as it originally was. This was due to the more data oriented side of most changes, such as swapping out the used database.
</p>

<h4>
The Initial Project (without enhancements):
</h4>
<p>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/module7">Module 7 Branch of Full-Stack Development</a>
</p>

<hr>
<h2> Informal Code Review </h2>

<p>
It wouldn't do, however, to just make code at random in the hopes of making progress. Team members need to know what is expected, and stakeholders need to be communicated with. As such, in order to allow for a degree of showing how these enhancements were choosen, here is a code review, turned into two respective YouTube videos. They provided a view of what files were expected to be changed, and the expectations met.
</p>


<h3> Video Part 1: </h3>
<a href="https://www.youtube.com/hvHnSBYK3-I">Code Review Part 1 </a>
<iframe width="560" height="315" src="https://www.youtube.com/embed/hvHnSBYK3-I?si=dJztw549TtSVQn4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<h3> Video Part 2: </h3>
<a href="https://www.youtube.com/zb2CByZkPEs">Code Review Part 2 </a>
<iframe width="560" height="315" src="https://www.youtube.com/embed/zb2CByZkPEs?si=jnNymLvpPC9MY0Zb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<hr>

<h2> Improving Software Design and Engineering </h2>

<p>
I made a simple authorization system on the admin side, containing an admin role and allowing trips to have authors and editors, allowing for those to be the only people that viewed their respective trips if not set to public (or if the user is an admin, they can see all available trips). This shows not just an improvement in software design by adding a new part of the filtering process, but also a dedication to security by saving and checking roles and permissions on the database side rather then with the user.
</p>
<p>
I learned more about almost all libraries involved, including mongoDB and it’s ability to support several different types of query, and the lean command to make reading data from the database a good bit clearer. I learned more about how angular displays the website, and how to use and communicate information with a checkbox on top of the date entry and text box that all the other inputs used. I even learned more about Javascript itself, how to check objects and arrays for certain traits and manage async functions calls
</p>

<h3> Video Link: </h3>
<a href="https://www.youtube.com/rZ3KlZvjpN0">Software Design and Engineering </a>

<h3> Related Files: </h3>
<h4>Initial:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/module7">Module 7 Branch of Full-Stack Development</a>
<h4>Early Improvement:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update1">Update 1 Branch of Full-Stack Development</a>
<h4>Early Improvement Notes:</h4>
<p> See "Narrative Software Design and Engineering (Victor Lichtenfelt).docx" </p>
<h4>Current Variation:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update4">Update 4 Branch of Full-Stack Development</a>
<hr>

<h2> 
Improving Algorithms and Data Structures 
</h2>
<p>
I made a single page that allowed sorting by date. However, I felt the best showing for algorithms and data structures was not this intended change, as it somewhat was undercut instead by the proper creation of authorization and the database data structure. While the addition of an advance query page shows some promise, what shows more were the pipeline algorithms, which while simple were able to easily make quick work and separate the respective jobs that were expected fairly easily. Verification of the necessary qualities for the respective authorization an account has while none the less having other proper querying information.
</p>
<p>
I learned more angular tools in order to allow easier connection between components, so that the controls could be a separate section from the list that shows the trips that correspond to the query. I much more thoroughly understood the controls for querying the MongoDB database, and can be much more certain I’m getting the intended results from it. I understand html queries better, choosing post for these advanced queries due to the ability to take data through form means whereas get cannot.
</p>

<h3> Video Link: </h3>
<a href="https://www.youtube.com/Ohg6HwEJ_K4">Improving Algorithms and Data Structures</a>


<h3> Related Files: </h3>
<h4>Initial:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update1">Update 1 Branch of Full-Stack Development</a>
<h4>Early Improvement:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update2">Update 2 Branch of Full-Stack Development</a>
<h4>Early Improvement Notes:</h4>
<p> See "Narrative Algorithms and Data Structures (Victor Lichtenfelt).docx"</p>
<h4>Current Variation:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update4">Update 4 Branch of Full-Stack Development</a>


<hr>
<h2> 
Improving Databases
</h2>
<p>
I switched the database from a freeform MongoDB to a MySQL database. This shows an ability to work with non-relational databases as well as with relational databases, and switch how data is stored between them in order to use the respective intended structures. I performed joins on tables in order to replicate the more freeform initial relationship made to support the first version of the authorization system. Overall, databases are understandable and able to be shown performing major queries.
</p>
<p>
Overall, I feel that I learned quite a bit about how to utilize the MySQL default library, along with how to produce code for simplifying interaction with the database. The element I talked about earlier, where database interaction also showed great strides in data structures, was shown here. I had to quickly change from the mysql library to mysql2, since mysql2 actually had the ability to use the new password system.
</p>

<h3> Video Link: </h3>
<a href="https://www.youtube.com/K3Xqhxw5zA0">Improving Databases</a>

<h3> Related Files: </h3>
<h4>Initial:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update2">Update 2 Branch of Full-Stack Development</a>
<h4>Early Improvement:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update3">Update 3 Branch of Full-Stack Development</a>
<h4>Early Improvement Notes:</h4>
<p> See "Narrative Databases (Victor Lichtenfelt).docx"</p>
<h4>Current Variation:</h4>
<a href="https://github.com/Victor-Lichtenfelt/cs465-fullstack/tree/update4">Update 4 Branch of Full-Stack Development</a>
