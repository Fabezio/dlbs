<script>
const date = new Date().getFullYear()

    $: setTimeout(()=> {
        return date
    }, 1000)
</script>

<footer>
    {date}
</footer>