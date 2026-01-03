<head>
    <title>Noah Elazar</title>
</head>

<div class="home">
    <div class="intro">
        <nav>
            <a class="main-name selected" href="/">Noah Elazar</a>
            <div class="spacer"></div>
            <a class="nav-link" href="/projects">Projects</a>
            <a class="nav-link" href="/photography">Photography</a>
            <a class="nav-link" href="/elazar-cv.pdf" target="_blank">CV</a>
        </nav>
    </div>

    <div class="separator accent"></div>

    <div class="bio">
        <div class="content row">
            <div class="headshot">
                <img src="/headshot.jpg" alt="A headshot of Noah Elazar" width="200" height="200" />
            </div>
            <div class="blurb">
                <p class="libre-bodoni-regular hello">
                    I'm Noah,
                </p>
                <p>
                    a researcher and software developer interested in studying the future of work and the impact of data on society.
                    I received my B.A. from Oberlin College in 2025 with High Honors and majors in Computer Science and Politics, a minor in Mathematics, and a concentration in Data Science.
                </p>
                <div class="separator"></div>
                <p>
                    I've developed a robust skillset in geospatial analysis and quantitative social science, and I'm adept at handling massive datasets.
                    In my undergraduate Honors project I explored a new methodology for quantitatively approximating political ideology using the relationships between politicians on Twitter/X.
                    My other undergraduate research included more than two years in a transportation-oriented data science lab, developing a software tool to parse congressional hearing transcripts,
                    and spending a summer as an NSF REU student at Carnegie Mellon University, where I studied the impact of a Mozilla layoff on open source software communities.
                </p>
                <div class="separator"></div>
                <p>
                    I am honored to have been recognized for my work as an undergraduate.
                    I was awarded Oberlin College's <a href="https://www.oberlin.edu/news/noah-elazar-wins-oberlins-2025-nexial-prize" target="_blank">2025 Nexial Prize</a>,
                    given to an outstanding science student with aspirations for pursuing interdisciplinary research.
                    I also received the Aaron Wildavsky Memorial Prize in Politics, awarded to an outstanding graduating senior specializing in American politics and public policy,
                    and the R.J. Thomas Prize for excellence as a computer science research assistant.
                </p>
                <div class="separator"></div>
                <p>
                    I'm currently contracting as a full-stack web developer, building a data analysis app for a political consulting firm.
                    I've also worked as a tutor, grader, web designer, and interned as a digital organizer for a campaign for mayor of Providence, RI.
                </p>
            </div>
        </div>
    </div>

    <div class="contact">
        <div class="content column">
            <h2>Contact</h2>
            <div class="contact-list">
                <p>
                    You can reach me at noahbelazar (at) gmail (dot) com or on <a href="https://www.linkedin.com/in/noah-elazar/" target="_blank">LinkedIn</a>.
                    You can find my code on <a href="https://github.com/nelazar" target="_blank">my Github account</a>.
                </p>
            </div>
        </div>
    </div>
</div>

<style lang="scss">
    .home {
        width: 100%;
    }

    .intro {
        position: relative;
        width: 100%;
        height: 60vh;
        background-image: url('/home-page-header.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
    }

    .bio {
        background-color: var(--color-lighter);
    }

    p.hello {
        font-size: 26px;
        color: var(--color-dark);
    }

    .contact {
        background-color: var(--color-light);
    }

    .contact-list {
        display: flex;
        flex-direction: column;
        gap: 10px;
    }
</style>