---
layout: project
title: ApplyUp
subtext: "Created as a part of USC's premier product incubator, LavaLab, the goal was to create and pitch an MVP to venture capitalists and investors within 10-weeks. By working alongside a product manager ([João Aguiar de Souza](https://www.linkedin.com/in/joao-aguiar-de-souza/)) and two developers ([Jason Chen](https://www.linkedin.com/in/jsn-chn/), [Sanjana Ilango](https://www.linkedin.com/in/sanjana~ilango/)), ApplyUp was created!"


image: applyup_one.gif
video: 
role: Product Designer
product: "ApplyUp is a tool that seamlessly fills, tracks and perfects your job applications in seconds."
timeframe: 10-weeks
timeline:
tools: "Figma"
---

<div class="row mb-4 align-items-center">
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 40px">
        <h3 id="intro"> PART 1: GENERATIVE RESEARCH </h3>
        <h2 id="mainhead align-items-left" style="padding-top:20px"> The Problem </h2>
        <p id="redtext"> Job applications suck. </p>
        <p>They are time consuming, repetitive, and simply boring. The process involves manually entering the same info multiple times; most of these actions can be automated and streamlined to increase efficiency.</p>
        <h2 id="mainhead align-items-left" style="padding-top:60px"> The Current Landscape</h2>
        <p>for Job and Internship Seekers</p>
    </div>
    <div class="myrow">
        <div id="hide" class="mycol">
            <p id="stats">Up to 75%</p>
        </div>
        <div id="hide" class="mycol">
            <p>of job applications are weeded out by ATS or applicant tracking systems before ever seen by a human.</p>
        </div>
    </div>
    <div class="myrow">
        <div id="hide" class="mycol">
            <p id="stats">21 - 80<br>applications</p>
        </div>
        <div id="hide" class="mycol">
            <p>is how many an individual should submit to have highest probabiliy of receiving a job offer.</p>
        </div>
    </div>
    <div class="myrow">
        <div id="hide" class="mycol">
            <p id="stats">30 - 60<br>minutes</p>
        </div>
        <div id="hide" class="mycol">
            <p>is the average amount of time most people prefer to spend on an application.</p>
        </div>
    </div>
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 40px">
        <h2 id="mainhead align-items-left" style="padding-top:20px">User Interviews</h2>
        <p>To gain a deeper understanding of the problems people face while submitting a
        job application online, I conducted user interviews with 10 college students and
        5 graduates.There were 4 main painpoints:</p>
    </div>
    <img src="img/ApplyUpPain.png" style="padding-top: 15px; padding-left:14px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 20px">
        <h2 id="mainhead align-items-left" style="padding-top:30px">Our Solution</h2>
        <p>A web tool, starting as a Chrome extension for now, that <b><i>seamlessly recognizes</i></b> job application forms, <b><i>auto-completes</i></b> the most relevant fields, <b><i>customizes </i></b>cover letters and resumes, and <b><i>tracks submitted applications</i></b>.</p>
    </div>
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 20px">
        <h3 id="intro"> PART 2: INITIAL IDEATION </h3>
        <p>By consolidating everything I learned about the current job application landscape through user interviews, market research and first hand experience, I began ideating a possible solution.</p>
        <h2 id="mainhead align-items-left" style="padding-top:20px"> User Journey </h2>
        <img src="img/ApplyUpIdeaOne.png" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
        <h2 id="mainhead align-items-left" style="padding-top:60px">Mid Fidelity Sketches & Screens</h2>
        <img src="img/applyUpIdeation.png" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
    </div>
    <img src="img/AppUpScreens.png" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
</div>

<div class="row mb-4 align-items-center">
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 40px">
        <h2 id="mainhead align-items-left" style="padding-top:20px"> Design Issues </h2>
        <p>After creating a preliminary render of our product, I gave it to 8 users for feedback on the existing user flow and design. There were 3 key issues:</p>
        <div class="container" style="padding-top:20px; padding-left:20px">
            <h4>1. Too Text Heavy</h4>
            <p style="padding-left:20px">With ApplyUp primarily a Chrome extension, there is already very little screen real estate for users to work with. Thus, a text-heavy approach with small words and menus will only burden them further and make the process more difficult.</p>
            <h4 style="padding-top:20px">2. Information in the Wrong Order</h4>
            <p style="padding-left:20px">Although users also have trouble tracking their job applications, their main concern as shown from the user interviews is the need to auto-fill fields. Thus, it does not make the most sense to prompt users with basic job information first; instead, role templates should be shown first.</p>
            <h4 style="padding-top:20px">3. Manual Input</h4>
            <p style="padding-left:20px">Instead of selecting the ‘Input Fields’ option, highlighting or typing the question and writing the answer, it would be more efficient for users to just write the correct answer in the actual application field and have the program automatically learn it.</p>
        </div>
    </div>
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 40px">
        <h3 id="intro"> PART 3: SECOND ITERATION </h3>
        <h2 id="mainhead align-items-left" style="padding-top:30px"> Ideation (Again) </h2>
        <p>This time, designing with <i><b>efficiency and accessibility in mind</b></i>.</p>
        <h2 id="mainhead align-items-left" style="padding-top:20px"> User Journey </h2>
        <img src="img/userJourney.png" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
        <h2 id="mainhead align-items-left" style="padding-top:60px">Interface Development</h2>
        <img src="img/Screens-02.png" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
    </div>
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 40px">
        <h3 id="intro"> PART 4: FINAL DELIVERABLES </h3>
        <h2 id="mainhead align-items-left" style="padding-top:30px"> Final Prototypes</h2>
        <img src="img/38.png" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
        <img src="img/applyup_one.gif" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
        <img src="img/applyuptwo.gif" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
        <img src="img/applyup_three.gif" style="padding-top: 15px; padding-bottom:2em" alt="Image" data-aos="fade-up" class="img-fluid">
    </div>
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 40px">
        <h2 id="mainhead align-items-left" style="padding-top:30px"> Design System </h2>
    </div>
    <img src="img/Screens-01.png" style="padding-top:15px; padding-bottom:1em; padding-left:15px" alt="Image" data-aos="fade-up" class="img-fluid">
    <div class="col-md-8" data-aos="fade-up" style="padding-top: 40px; padding-bottom: 5em">
        <h2 id="mainhead align-items-left" style="padding-top:30px"> User Flow</h2>
        <img src="img/applyup_four.png" style="padding-top: 15px; padding-bottom:1em" alt="Image" data-aos="fade-up" class="img-fluid">
        <h2 id="mainhead align-items-left" style="padding-top:30px; padding-bottom:20px"> Official Pitch Deck (static)</h2>
        <iframe src="img/ApplyUp.pdf" width="100%" height="600px"> </iframe>
    </div>

</div>



<div class="site-section pb-0">
    <div class="container">
        <div class="row justify-content-center text-center mb-4">
            <div class="col-5">
                <h3 class="h3 heading">More Works</h3>
            </div>
        </div>
        <div class="row" data-aos="fade-up" data-aos-delay="200">
            <div class="item rendering col-sm-6 col-md-4 col-lg-4 mb-4">
                <a href="halfway.html" class="item-wrap fancybox">
                    <div class="work-info">
                        <h3>Halfway There Van Frames</h3>
                        <span>3D Rendering</span>
                    </div>
                    <img class="img-fluid" src="img/misc_v2.png">
                </a>
            </div>
            <div class="item branding col-sm-6 col-md-4 col-lg-4 mb-4">
                <a href="caraxy.html" class="item-wrap fancybox">
                    <div class="work-info">
                        <h3>Caraxy</h3>
                        <span>Branding</span>
                    </div>
                    <img class="img-fluid" src="img/img_2.jpg">
                </a>
            </div>
            <div class="item design col-sm-6 col-md-4 col-lg-4 mb-4">
                <a href="history.html" class="item-wrap fancybox">
                    <div class="work-info">
                        <h3>History At Your Footsteps</h3>
                        <span>Design</span>
                    </div>
                    <img class="img-fluid" src="img/img_5.jpg">
                </a>
            </div>
        </div>
    </div>
</div>