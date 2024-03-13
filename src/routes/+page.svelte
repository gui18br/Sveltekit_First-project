<script>
   const lista = [
    {nome: 'João', idade: 23},
    {nome: 'Ana', idade: 32},
    {nome: 'Andre', idade: 29},

]
</script>


<h1>Meu site</h1>


{#each lista as {nome, idade}}
    <p>{nome} tem {idade}</p>
{/each}

