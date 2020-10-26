<script>
const date = new Date().getFullYear()

    $: setTimeout(()=> {
        return date
    }, 1000)
</script>

<footer class="fixed-bottom bg-dark w-100 text-center py-2 text-light rounded-top">
    Dans Le Bon Sens &copy; - 
    {date}
</footer>