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
                    <li class="nav-item ps-3 pe-2">
                        <button class="btn btn-primary" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasScrolling" aria-controls="offcanvasScrolling">Tutte</button>
                    </li>
                    <li class="nav-item ps-3 pe-2">
                       <a href="http://">Continua a fare acquisti</a>
                    </li>
                    <li class="nav-item ps-3 pe-2">
                       <a href="http://">Amazon Basics</a>
                    </li>
                    <li class="nav-item ps-3 pe-2">
                       <a href="http://">Offerte</a>
                    </li>
                    <li class="nav-item ps-3 pe-2">
                       <a href="http://">Acquista di nuovo</a>
                    </li>
                </ul>

                <div class="offcanvas offcanvas-start" data-bs-scroll="true" data-bs-backdrop="false" tabindex="-1" id="offcanvasScrolling" aria-labelledby="offcanvasScrollingLabel">
                    <div class="offcanvas-header">
                        <h5 class="offcanvas-title" id="offcanvasScrollingLabel">PROVA</h5>
                        <button type="button" class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
                    </div>
                    <div class="offcanvas-body">
                        <p>Try scrolling the rest of the page to see this option in action.</p>
                    </div>
                </div>

            </div>
        </div>
    </nav>
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

  
</style>