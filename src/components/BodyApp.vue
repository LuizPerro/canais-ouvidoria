<template>
    <main class="container mx-auto p-8 lg:p-20">
        <div class="flex flex-col lg:flex-row">
            <!-- content -->
            <div class="w-full lg:w-1/2">
                <!-- title -->
                <h1 class="text-3xl text-gray-700">Canais de <span class="font-bold">Ouvidoria</span></h1>
                <div class="w-10 h-1 mt-3 bg-blue-300"></div>
                
                <!-- description -->
                <p class="w-full mt-5 text-gray-500 md:text-justify">
                    A ouvidoria é ligação entre o Município e o usuário de serviços públicos. 
                    Promove o controle da Administração Pública, provendo informações que são trazidas diretamente pelos cidadãos e que poderão subsidiar os aprimoramentos necessários à gestão dos órgãos e entidades. 
                </p>

                <!-- card container -->
                <div class="flex mt-10 gap-4">
                    <!-- cards -->
                    <a class="card" href="https://transparencia.pmmp.rj.gov.br/?serv=685" target="_blank" rel="noopener">
                        <i class="card-icon bi bi-headset text-5xl text-blue-400"></i>
                        <p class="card-title">Fale Conosco</p>
                    </a>
                    <a class="card" href="https://transparencia.pmmp.rj.gov.br/?serv=28" target="_blank" rel="noopener">
                        <i class="card-icon bi bi-info-circle"></i>
                        <p class="card-title">eSIC</p>
                    </a>
                </div>
            </div>

            <!-- image -->
            <div class="w-full lg:w-1/2">
                <img src="img/home-content.png" alt="" class="w-full">
            </div>
        </div>
    </main>
</template>

<style scoped>
    @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.1/font/bootstrap-icons.css");

    .card {
        @apply w-48 h-32 flex justify-center items-center;
        @apply border rounded-lg shadow-sm;
    }

    .card-icon {
        @apply text-4xl mr-2 text-blue-400;
    }

    .card-title {
        @apply mt-2 text-lg text-gray-700 font-semibold;
    }
</style>