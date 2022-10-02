<script>
    import '../styles/global.css'
</script>

<header>

</header>

<main>
    <slot></slot>
</main>

<footer>
    <p>Copyright</p>
</footer>

<style>
header {
    display: flex;
    justify-content: center;
}
main {
    max-width: 800px;
    margin: 20px auto;
}
footer {
    text-align: center;
}
</style>