<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "AppTitle",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <div class="container my-5">
        <div class="row">
            <div class="col-4 offset-4 text-center">
                <span>Ciao mondo</span>
                <h1 class="my-3">La mia prima app con <span class="text-bg-primary">Vite!</span></h1>
                <p>Hello world</p>
            </div>
        </div>
    </div>
</template>