<template>
    <div class="navbar bg-base-160 shadow-sm">

        <div class="navbar-start">
            <div class="dropdown">
                <div tabindex="0" role="button" class="btn btn-ghost btn-circle">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24"
                        stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                            d="M4 6h16M4 12h16M4 18h7" />
                    </svg>
                </div>
                <ul tabindex="-1"
                    class="menu menu-sm dropdown-content bg-base-100 rounded-box z-1 mt-3 w-52 p-2 shadow">

                    <li><a href="./PaginaApresentacao.vue">Homepage</a></li>

                    <li tabindex="0">
                        <a>
                            Categorias
                            <svg class="fill-current" xmlns="http://www.w3.org/2000/svg" width="12" height="12"
                                viewBox="0 0 24 24">
                                <path d="M8.59 16.59L13.17 12 8.59 7.41 10 6l6 6-6 6z" />
                            </svg>
                        </a>
                        <ul class="p-2 bg-base-100 rounded-box">
                            <li><a>Placa Mãe</a></li>
                            <li><a>Processadores</a></li>
                            <li><a>Memória RAM</a></li>
                            <li><a>Placas de Vídeo</a></li>
                            <li><a>PC</a></li>
                            <li><a>Perifericos</a></li>
                            <li><a>Impressoras</a></li>
                        </ul>
                    </li>
                </ul>

            </div>
        </div>
        <div class="navbar-center">
            <a class="btn btn-ghost text-xl">InfoTrade</a>
            <img src="/src/assets/img/logo_.svg" alt="InfoTrade Logo" class="h-10" </div>

        </div>
</template>

<script>


export default {
    name: "Header",

}
</script>