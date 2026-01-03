<head>
    <title>Photography ∙ Noah Elazar</title>
</head>

<div class="photography">
    <nav>
        <a class="main-name" href="/">Noah Elazar</a>
        <div class="spacer"></div>
        <a class="nav-link" href="/projects">Projects</a>
        <a class="nav-link selected" href="/photography">Photography</a>
        <a class="nav-link" href="/elazar-cv.pdf" target="_blank">CV</a>
    </nav>

    <div class="gallery">
        <div class="content column">
            <h2>Photography</h2>
            <img 
                src="photography/000249870002.jpg"
                alt="A nighttime scene of a building, in the foreground is a sign reading 'CLOSED'
                illuminated in red."
            >
            <img
                src="photography/000249860024.jpg"
                alt="A view of an empty cafe through a window. Tables, chairs, and a counter are illuminated
                by natural light pouring in through windows on the opposite side."
            >
            <img
                src="photography/000320530035.jpg"
                alt="A scene of a living room, with various objects scattered around. Bright white light comes
                from a pair of windows, and a chair in the center of the scene has a basket sitting on it, with
                a red hat poking out."
            >
            <div class="side-by-side">
                <div>
                    <img
                        src="photography/000401780026.jpg"
                        alt="A scene of a river running alongside a road, winding through a rocky valley."
                    >
                </div>
                <div>
                    <img
                        src="photography/000320530001.jpg"
                        alt="A scene of a bathroom. Soft light from a window with the blind closed illuminates
                        a hanging towel, and some toothbrushes sitting on the counter."
                    >
                </div>
            </div>
            <img
                src="photography/000249860037.jpg"
                alt="A set of windows outside of a building. The windows are reflecting a number of buildings.
                Inside the building, industrial shelves and a painting of a man can be seen."
            >
            <img
                src="photography/000249870038.jpg"
                alt="A single, orange light illuminates the side of a building at night. The only part of the
                building that is visible is a grid of windows outlined by silver frames."
            >
            <img
                src="photography/000401780029.jpg"
                alt="Three buildings against a blue sky with white clouds. The first building, barely visible
                on the left, is a square, brown, brick building. The second building is the Willis Tower in
                Chicago, a black, blocky skyscraper with white antennas. The final building, on the right,
                is a shiny glass building with wavy sides and a sign that reads 'BMO.'"
            >
            <div class="side-by-side">
                <div>
                    <img
                        src="photography/000666380013.jpg"
                        alt="A grayscale scene of an electrical pole, with wires stretching across the frame.
                        A branch of a tree can be seen across the top of the scene."
                    >
                </div>
                <div>
                    <img
                        src="photography/000249860023.jpg"
                        alt="A view of an industrial area, with a tan building behind a green domed structure.
                        Two white cars can be seen at the front."
                    >
                </div>
            </div>
            <img
                src="photography/000267540031.jpg"
                alt="Beams of light spill across a night scene, emanating from a church. Trees and a couple
                of road signs are outlined by the bright light."
            >
            <img
                src="photography/000320520022.jpg"
                alt="An eerie green light illuminates a foggy night, where the tops of houses and buildings can
                be seen. A row of Christmas lights runs along the edge of one roof."
            >
            <img
                src="photography/000320530026.jpg"
                alt="The front of a shuttered storefront. A large sign across the front is split into two halves.
                One half, in red, reads 'FRIEDRICH'S MODERN DRY CLEANING,' while the other half, in blue, reads
                'ELECTRIC MAID COMMUNITY EXCHANGE.'"
            >
        </div>
    </div>
</div>

<style lang="scss">
    .photography {
        width: 100%;
    }

    nav {
        background-color: var(--color-light);
    }

    .gallery {
        display: flex;
        flex-direction: column;
    }

    img {
        max-width: 100%;
        max-height: 100%;
        width: auto;
        height: auto;
    }

    .side-by-side {
        width: 1000px;
        display: flex;
        flex-direction: row;
        gap: 20px;
    }
</style>