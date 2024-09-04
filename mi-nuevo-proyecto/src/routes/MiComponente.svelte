<script>
    let {pais, capital, ciudad} = $props()
</script>

<p>
   una capital de <span>{pais}</span> es <span>{capital}</span> y una ciudad es <span>{ciudad}</span>
</p>

<style>
    * {
        text-align: center;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    span {
        color: blue;
    }
</style>
