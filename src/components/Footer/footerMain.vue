<script>

    export default {
        name: 'footer'
    }

</script>

<template>
    <section id="footer">
        <div class="container py-5 mt-5">
            <div class="row text-white">
                <div class="col">
                    <ul>
                        <li class="mb-3 fw-bold">Per conoscerci meglio</li>
                        <li><a href="http://">Opportunità di lavoro</a></li>
                        <li><a href="http://">Informazioni su amazon</a></li>
                        <li><a href="http://">Sostenibilità</a></li>
                        <li><a href="http://">AGCM</a></li>
                        <li><a href="http://">Amazon Science</a></li>
                    </ul>
                </div>
                <div class="col">
                    <ul>
                        <li class="mb-3 fw-bold">Guadagna con Amazon</li>
                        <li><a href="http://">Vendi su Amazon</a></li>
                        <li><a href="http://">Vendi su Amazon Business</a></li>
                        <li><a href="http://">Vendi su Amazon Handmade</a></li>
                        <li><a href="http://">Costruisci e proteggi il tuo marchio</a></li>
                        <li><a href="http://">Diventa affialiato</a></li>
                    </ul>
                </div>
                <div class="col">
                    <ul>
                        <li class="mb-3 fw-bold">Metodi di pagamento</li>
                        <li><a href="http://">Metodi di pagamento</a></li>
                        <li><a href="http://">Convertitore di Valuta Amazon</a></li>
                        <li><a href="http://">Buoni Regalo</a></li>
                        <li><a href="http://">Ricarica online</a></li>
                        <li><a href="http://">Ricarica in cassa</a></li>
                    </ul>
                </div>
                <div class="col">
                    <ul>
                        <li class="mb-3 fw-bold">Bisogno di aiuto?</li>
                        <li><a href="http://">Visualizza o traccia un ordine</a></li>
                        <li><a href="http://">Costi e modalità di spedizione</a></li>
                        <li><a href="http://">Amazon Prime</a></li>
                        <li><a href="http://">Restituisci o sostituisci articoli</a></li>
                        <li><a href="http://">Riciclo</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped lang="scss">
    #footer{
        background-color:#141920;

        ul{
            list-style-type: none;

            li{
                line-height: 30px;
                
                a{
                    text-decoration: none;
                    color: white;
                    cursor: pointer;
                }
            }
        }
    }

</style>