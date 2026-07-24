<script lang="ts">
    let { page }: { page: "home" | "projects" | "photography" } = $props();

    let dialog: undefined | HTMLDialogElement = $state();
</script>

<div class="desktop">
    <nav>
        <a class={["main-name", page === "home" ? "selected" : ""]} href="/">Noah Elazar</a>
        <div class="spacer"></div>
        <a class={["nav-link", page === "projects" ? "selected" : ""]} href="/projects">Projects</a>
        <a class={["nav-link", page === "photography" ? "selected" : ""]} href="/photography">Photography</a>
        <a class="nav-link" href="/elazar-cv.pdf" target="_blank">CV</a>
    </nav>
</div>

<div class="mobile">
    <nav>
        <a class="main-name selected" href="/">Noah Elazar</a>
        <div class="spacer"></div>
        <button class="nav-link" onclick={() => dialog?.showModal()}>Menu</button>
    </nav>
</div>

<dialog bind:this={dialog}>
    <div class="menu-body">
        <div class="menu-close-div">
            <button class="nav-link menu-close" onclick={() => dialog?.close()}>Close</button>
        </div>
        <nav class="vertical">
            <a class={["nav-link", page === "home" ? "selected" : ""]} href="/">Home</a>
            <a class={["nav-link", page === "projects" ? "selected" : ""]} href="/projects">Projects</a>
            <a class={["nav-link", page === "photography" ? "selected" : ""]} href="/photography">Photography</a>
            <a class="nav-link" href="/elazar-cv.pdf" target="_blank">CV</a>
        </nav>
    </div>
</dialog>

<style lang="scss">
    dialog {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        width: 100%;
        height: 100%;
        max-width: none;
        max-height: none;
        margin: 0;
        border: none;
        background-color: var(--color-light);
    }

    .menu-body {
        margin: 30px;
    }

    .menu-close-div {
        display: flex;
        flex-direction: row-reverse;
    }

    .menu-close {
        margin-left: auto;
    }

    nav.vertical {
        display: flex;
        flex-direction: column;
        gap: 20px;
        justify-content: left;
        align-items: normal;
    }

    nav.vertical > a {
        font-size: 30px;
    }
</style>