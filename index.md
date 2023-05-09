---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h2>About</h2>

Hi, I'm Vinay Gupta, a **masters student in Computer Science at USC**. Video games hold a special place in my heart, and I recently (or perhaps, finally!) switched my career focus to game development!

This site hosts my personal portfolio of endeavours in game development. If you're interested to connect, please contact me using the options in the footer below :)

<h2 class="space-on-top">Top projects</h2>

<div class="quick-links-container">
    <a class="card" href="/projects#stealth-system">
        <img src="/media/StealthSystemThumbnail.gif" />
        <h3>Stealth System</h3>
        <p>Engine / Gameplay components for cover interaction, stealth and AI!</p>
    </a>
    <a class="card" href="/projects#sci-fi-spaceship-controller">
        <img src="/media/FlightControllerThumbnail.gif" />
        <h3>Sci-Fi Spaceship Controller</h3>
        <p>Passion project inspired by the Banshee from Halo.</p>
    </a>
    <a class="card" href="/games#alter-ego">
        <img src="/media/AlterEgoThumbnail.gif" />
        <h3>Alter Ego</h3>
        <p>Manage clones in this puzzle-platformer with 30+ levels!</p>
    </a>
</div>

<h2 class="space-on-top">How does my prior experience help?</h2>

<div class="two-column-cards">
    <div>
        <h3>Low-level (2 years)</h3>
        {% include chip.html tag="C++" %}
        {% include chip.html tag="OOP" %}
        {% include chip.html tag="Multithreading" %}
        {% include chip.html tag="SIMD" %}
        <p>I shipped features for the 5G protocol stack that runs frame-to-frame, using <strong>multithreaded event-driven architecture</strong> and SIMD processing - similar to games!</p>
    </div>
    <div>
        <h3>Tools (2 years)</h3>
        {% include chip.html tag="Python" %}
        {% include chip.html tag="GUI" %}
        {% include chip.html tag="MVVM" %}
        {% include chip.html tag="CI/CD" %}
        {% include chip.html tag="Perforce" %}
        <p>Keen on improving things around me and aiding productivity, I've created impact using test <strong>automation workflows</strong>; GUI & CLI utilities; data analysis; and more!</p>
    </div>
</div>

I realize that many of these skills can translate to game development - but more than anything, I'm eager to learn and grow further!

{% include button.html type="primary" content="View Resume" url="https://drive.google.com/file/d/1tvfX61oePzo92PQj2EFezm4rxI0i5ztQ/view?usp=sharing" %}
