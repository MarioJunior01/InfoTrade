<template>
    <div class="card bg-base-100 w-96 shadow-sm p-10">
        <figure class="w-full h-64">
            <img :src="produto.imagem" :alt="produto.nome" class="object-cover w-full h-full">
        </figure>
        <div class="card-body">
            <h2 class="card-title">
                {{ produto.nome }}
            </h2>
            <p> {{ produto.descricao }}</p>
            <div class="card-actions justify-end">
                <div class="badge badge-outline">{{ produto.categoria }}</div>
                <div class="badge badge-outline">{{ produto.preco }}</div>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: "Card",
    props: {
        produto: {
            id: Number,
            nome: String,
            imagem: String,
            descricao: String,
            preco: Number,

        },

    }

}
</script>