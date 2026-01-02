<div class="projects">
    <nav>
        <a class="main-name" href="/">Noah Elazar</a>
        <div class="spacer"></div>
        <a class="nav-link selected" href="/projects">Projects</a>
        <a class="nav-link" href="/photography">Photography</a>
        <a class="nav-link" href="/elazar-cv.pdf" target="_blank">CV</a>
    </nav>

    <div class="projects-list">
        <div class="content column">
            <h2>Projects</h2>
        </div>
        <div class="content column">
            <h3>Retweets and Ideal Points: Political Ideology on Twitter/X</h3>
            <div class="content row">
                <div class="blurb">
                    <p class="justify">
                        For my senior Honors thesis, I developed a quantitative measure of political ideology
                        using social media as a source of data.
                        I applied dimensionality reduction to a matrix of retweets from users on Twitter/X to
                        members of Congress, generating numbers for the location of each politician on a
                        two-dimensional ideological spectrum.
                        I found that my score strongly correlated with the existing, established measures of
                        political ideology, such as DW-NOMINATE, suggesting that it is an effective alternative.
                        However, as my score is based on social media, a more flexible source of data than those
                        used by the existing measures, my score has utility in situations where the existing
                        measures cannot be applied, such as in local politics or with small campaigns.
                    </p>
                </div>
                <div class="visual">
                    <img
                        src="/projects/twt-score.png"
                        alt="A scatterplot displaying the ideological coordinates for members of Congress given
                            by my project. Democrats, in blue, are clustered to the left, 
                            while Republicans, in red, are distributed to the right."
                        width="500" height="375"
                    />
                </div>
            </div>
            <div></div>
            <h3>Socio-Spatial Disparities in Access to Driver Education for Teens</h3>
            <div class="content row">
                <div class="blurb">
                    <p class="justify">
                        I utilized advanced spatial analysis techniques to measure the relationship
                        between proximity to driver training centers (DTCs), locations where individuals can
                        go to receive their driver's education, and traffic citations.
                        This work developed
                        from past research demonstrating that drivers who recieve their license after age 17,
                        when the requirement to attend driver training is dropped in many states, are actually
                        less safe than younger drivers who attend driver training.
                    </p>
                    <p class="justify">
                        I first applied a routing algorithm, similar to Google Maps, to identify how long it
                        would take for anyone in the study area to driver to the nearest DTC.
                        From there, I used point-pattern anlysis and Ripley's K-function to statistically
                        analyze the spatial relationship between those travel times and the distribution of
                        traffic citations.
                        We found that there was a significant relationship, although the nature of that
                        relationship was less clear.
                        I also assisted in developing the conference presentation for this work.
                    </p>
                    <p class="italic">
                        Davidson, Joshua H., Noah Elazar, Sangeetha Ramanuj, and Megan S. Ryerson. 2025.
                        “Socio-Spatial Disparities in Access to Driver Education for Teens.”
                        In preparation, to be submitted summer 2026.
                        Presented at 2025 American Association of Geographers Annual Meeting. Detroit, MI.
                    </p>
                </div>
                <div class="visual">
                    <img
                        src="/projects/driver-education.png"
                        alt="A map of Montgomery County, MD, shaded darker to indicate places where travel times
                        to driver training centers are longer. The locations of driver training centers are marked
                        with black dots. The dots are clustered in the center and southeast of the county, and the
                        longest travel times are in the west and north."
                        width="500" height="310"
                    />
                </div>
            </div>
            <div></div>
            <h3>Rust Shocks</h3>
            <div class="content row">
                <div class="blurb">
                    <p class="justify">
                        As an NSF REU student at Carnegie Mellon University, I measured the impact of a
                        layoff from Mozilla on the ecosystem of open-source developers for the Rust programming
                        language.
                        Mozilla was heavily involved in the development of the language, and continued to support
                        many of the software packages for Rust following the open-sourcing of the language.
                        They laid off a significant percentage of their developers in 2021, leading to concerns
                        about the future of the Rust ecosystem.
                        I downloaded billions of commits from Rust packages, and used qualitative and quantitative
                        means to identify some of the laid off developers in the commit records.
                        I applied regression discontinuity design (RDD) and ended up discovering that not only
                        did the overall ecosystem not face a significant decline in commits, but even the laid
                        off developers continued contributing at a similar rate following the event.
                    </p>
                </div>
                <div class="visual">
                    <img
                        src="/projects/rust-shocks.png"
                        alt="A line graph showing the average commits per month for packages in the Rust ecosystem.
                        The packages are broken into control and treatment groups, where the treatment group represents
                        any package with greater than five percent of commits from developers who were laid off.
                        While there is some decline following the layoff, it is minimal, and there is almost no difference
                        between the treatment and control groups."
                        width="500" height="340"
                    />
                </div>
            </div>
            <div></div>
            <h3>Empirically Measuring the Mobility Outcomes of New Equity-Oriented Transit</h3>
            <div class="content row">
                <div class="blurb">
                    <p class="justify">
                        In 2019, Philadelphia's SEPTA transit system introduced a new bus line connecting two
                        low-income neighborhoods previously underserved by transit.
                        We used a sample, based on surveys conducted on SEPTA buses, of commutes between these
                        two neighborhoods to analyze the change to real people's mobility with the introduction
                        of this new line.
                        I pulled bus schedules using the General Transit Feed Specification (GTFS), and mapped
                        out the routes for each individual, as well as the routes between each possible origin
                        and destination pair.
                        From there, I calculated the mobility scores for each person before and after the
                        introduction of the new bus line.
                        We demonstrated a significant improvement in mobility for these neighborhoods overall
                        given this new line.
                    </p>
                    <p class="italic">
                        Davidson, Joshua H., Noah Elazar, Sophia Ungar, and Megan S. Ryerson. 2023.
                        “Empirically Measuring the Mobility Outcomes of New Equity-Oriented Transit.”
                        In preparation, to be submitted January 2026.
                        Presented at 2023 East Lakes Division-American Association of Geographers Annual Meeting.
                        Oregon, OH.
                    </p>
                </div>
                <div class="visual">
                    <img
                        src="/projects/urban-mobility.png"
                        alt="A set of density plots showing the personal mobility index of individuals surveyed
                        before and after the introduction of a new bus SEPTA bus line. The plots are separated by
                        percentile of travel distance, and show that regardless of the distance of travel,
                        the mobility of individuals increased following the new bus line."
                        width="500" height="340"
                    />
                </div>
            </div>
            <div></div>
            <h3>Parsing Congressional Hearing Transcripts</h3>
            <div class="content row">
                <div class="blurb">
                    <p class="justify">
                        Professor Jenny Garcia at Oberlin College studies the words that members of Congress
                        use in their speeches in hearings.
                        She was looking for a way to speed up the manual process of going through hearing
                        transcripts and labeling each speech with its speaker.
                        I developed a Python script that would read each file and recognize the patterns that
                        indicated the speakers, breaking up the text and storing each speech in a SQLite database.
                        After laying out the intial system to parse transcripts, I went back through and tweaked
                        it to handle the countless typos and slight variations in formatting for each different
                        Congressional committee.
                    </p>
                </div>
                <div class="visual">
                    <img
                        src="/projects/hearing-transcripts.png"
                        alt="A screenshot of the heading of a congressional hearing transcript."
                        width="500" height="340"
                    />
                </div>
            </div>
            <div></div>
            <h3>Web Design for Difede Ramsdell Bender PLLC</h3>
            <div class="content row">
                <div class="blurb">
                    <p class="justify">
                        I was hired to redesign the <a href="https://drb-law.com" target="_blank">website</a> of 
                        boutique law firm Difede Ramsdell Bender PLLC.
                        I created a new logo and design language, and developed a modern website to reflect
                        the expansion of their firm.
                        I implemented the design using Wix, and set up mechanisms for the firm to easily
                        upload new content such as news articles and new projects.
                    </p>
                </div>
                <div class="visual">
                    <img
                        src="/projects/drb-law.png"
                        alt="A screenshot of the home page of drb-law.com, the website for Difede Ramsdell Bender
                        PLLC. It shows a building, with the logo of the firm and the navigation bar placed in the
                        sky above the building. Below it reads a heading 'Who We Are.'"
                        width="500" height="280"
                    />
                </div>
            </div>
        </div>
    </div>
</div>

<style lang="scss">
    .projects {
        width: 100%;
    }

    nav {
        background-color: var(--color-light);
    }

    .projects-list {
        display: flex;
        flex-direction: column;
    }

    .blurb {
        width: 100%;
        display: flex;
        flex-direction: column;
        gap: 10px;
    }
</style>