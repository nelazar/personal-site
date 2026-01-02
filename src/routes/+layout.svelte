<script lang="ts">
    import type { LayoutProps } from "./$types";
    import "$lib/style/global.scss";

    let { children }: LayoutProps = $props();
</script>

<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Libre+Bodoni:ital,wght@0,400..700;1,400..700&display=swap" rel="stylesheet">
</head>

{@render children()}

<footer>
    <p>© 2025 Noah Elazar</p>
</footer>