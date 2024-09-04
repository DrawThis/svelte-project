<script>
    import MiComponente from "./MiComponente.svelte";
</script>

<h1>Mi titulo del proyecto</h1>

<h2>
    Hablando del país:
</h2>

<p>Los paises que se mencionan son:</p>

<MiComponente pais = Colombia capital = Bogotá ciudad = Medellin />

<style>
    * {
        text-align: center;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    h1 {
        color: red;
        font-weight: 700;     
    }

</style>
