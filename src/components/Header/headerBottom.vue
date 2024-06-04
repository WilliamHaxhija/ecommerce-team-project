<script>

    export default {
        name: 'headerBottom'
    }

</script>

<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid align-items-center text-white">
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item ms-3 me-2">
                        <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasScrolling" aria-controls="offcanvasScrolling">Tutte</button>
                    </li>
                    <li class="nav-item ms-3 me-2">
                       <a href="http://">Continua a fare acquisti</a>
                    </li>
                    <li class="nav-item ms-3 me-2">
                       <a href="http://">Amazon Basics</a>
                    </li>
                    <li class="nav-item ms-3 me-2">
                       <a href="http://">Offerte</a>
                    </li>
                    <li class="nav-item ms-3 me-2">
                       <a href="http://">Acquista di nuovo</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="offcanvas offcanvas-start" data-bs-scroll="true" data-bs-backdrop="false" tabindex="-1" id="offcanvasScrolling" aria-labelledby="offcanvasScrollingLabel">
        <div class="offcanvas-header">
            <h5 class="offcanvas-title" id="offcanvasScrollingLabel"> <i class="fa-solid fa-user ms-2"></i> Benvenuto (nome utente)</h5>
            <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"><i class="fa-solid fa-xmark text-white fs-4"></i></button>
        </div>
        <div class="offcanvas-body">
            <div class="row ms-2 pt-2 border-bottom border-secondary">
                <ul>
                    <li class="mb-3 fw-bold">Bisogno di aiuto?</li>
                    <li><a href="http://">Visualizza o traccia un ordine</a></li>
                    <li><a href="http://">Costi e modalità di spedizione</a></li>
                    <li><a href="http://">Amazon Prime</a></li>
                    <li><a href="http://">Restituisci o sostituisci articoli</a></li>
                    <li><a href="http://">Riciclo</a></li>
                </ul>
            </div>
            <div class="row ms-2 mt-2 pt-2 border-bottom border-secondary ">
                <ul>
                    <li class="mb-3 fw-bold">Bisogno di aiuto?</li>
                    <li><a href="http://">Visualizza o traccia un ordine</a></li>
                    <li><a href="http://">Costi e modalità di spedizione</a></li>
                    <li><a href="http://">Amazon Prime</a></li>
                    <li><a href="http://">Restituisci o sostituisci articoli</a></li>
                    <li><a href="http://">Riciclo</a></li>
                </ul>
            </div>
            <div class="row ms-2 mt-2 pt-2">
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
</template>

<style scoped lang="scss">
   nav{
        background-color:#252f3f !important;

        li{
            a{
                text-decoration: none;
                color: white;
            }

            &:hover{
                border: 1px solid white;
            }
        }

        li:nth-child(1){
            &:hover{
                border: none;
            }
        }   
    }

    .offcanvas-header{
        background-color: #141920;
        color: white;
    }

    .offcanvas-body{

        li{
            list-style-type: none;
            line-height: 30px;

            &:hover{
                background-color: grey;
            }
            a{
                text-decoration: none;
                color: black;
            }

        }

        li:nth-child(1){
            &:hover{
                border: none;
            }
        }
    }

  
</style>