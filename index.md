---
layout: base.njk
title: Home
---

<section id="home" class="hero">
    <h1>Itasca Runners Club</h1>
    <p>A "social" group with a "running" problem!</p>
    <a href="#about" class="button">Learn More</a>
</section>

<section id="about">
    <div class="about-content">
        <div class="about-image">
             <img src="/assets/about-club.avif" alt="Group of runners">
        </div>
        <div class="about-text">
            <h2>About The Club</h2>
            <p>The Itasca Runners Club was formed in 2005, bringing together local runners with varying abilities and with a common interest in running. The club has approximately 30 active members. We welcome new recruits or people visiting from out of town who just want to meet up with a friendly group to run with.</p>
            <a href="#contact" class="button secondary">Get in Touch</a>
        </div>
    </div>
</section>

<section id="runs">
    <h2>Run With Us</h2>
    
    <div class="runs-content">
        <div class="run-type">
            <h3>Saturday</h3>
            <img src="/assets/saturday-run.avif" alt="Saturday run route map">
            <p>The Itasca Runners Saturday morning run starts at <a href="https://www.fullabeans.com/">Fulla Beans Cafe</a> (corner of Irving Park Road and Walnut Street in Itasca). The run begins at 7:00AM.</p>
            <p>The course is essentially an "out and back" run with a small loop at the turnaround (at about the 2-1/2 mile mark). The complete run measures about 5.1 miles long. There are several convenient areas to shorten the run when desired.</p>
            <p>After finishing, most stay for a while at a local breakfast place for stretching, liquids, and conversation!</p>
        </div>
        <div class="run-type">
            <h3>Weekdays</h3>
            <img src="/assets/weekday-run.avif" alt="Weekday run route map">
            <p>Tuesday and Thursday mornings, members out running, generally follow this course.</p>
            <p>There is no real starting point to this run, people just meet up at different points depending on where they live in town. The basic course is a "lollipop" with the loop on the north side of town and is about 4.5 miles long. Most runners start at the intersection of Catalpa Ave. and Bryn Mawr Ave. at around 6:00AM.</p>
        </div>
    </div>
</section>

<section id="oktoberfast">
    <h3>The Annual Itasca Oktoberfast 5K Run</h3>
    <p><em>"Well done Itasca runners, you guys really know how to put on a race" - Past Race Participant</em></p>
    <p>Itasca Runners Club's organizes a 5K run / walk every year in the fall. The chip-timed race follows a fast and scenic neighborhood route through Itasca, Illinois, with a downhill finish into Usher Park.</p>
    <p>For more information and to register, check out the <a href="https://www.itascaoktoberfast5k.org">race website</a>.</p>
</section>

<section id="contact">
    <img src="/assets/contact.avif" alt="Runners stretching">
    <h2>Contact Us</h2>
    <form name="contact" method="POST" data-netlify="true">
        <input type="text" name="name" placeholder="Name" required>
        <input type="email" name="email" placeholder="Email" required>
        <input type="text" name="subject" placeholder="Subject">
        <textarea name="message" placeholder="Type your message here..." rows="4"></textarea>
        <button class="button secondary" type="submit">Submit</button>
    </form>
</section>

