<template>
<div class="container">
    <div class="row">
        <div class="col-sm-3">
            <div id="cardsec">
                <b-card
                    title="Eventos"
                    img-src="https://picsum.photos/600/300/?image=25"
                    img-alt="Image"
                    img-top
                    tag="article"
                    style="max-width: 20rem;"
                    class="mb-2"
                >
                    <b-button-toolbar aria-label="Toolbar with button groups and dropdown menu">
                        <b-dropdown class="mx-1" right text="Esta Semana">
                        <b-dropdown-item>Segunda</b-dropdown-item>
                        <b-dropdown-item>Terça</b-dropdown-item>
                        <b-dropdown-item>Quarta</b-dropdown-item>
                        <b-dropdown-item>Quinta</b-dropdown-item>
                        <b-dropdown-item>Sexta</b-dropdown-item>
                        </b-dropdown>
                    </b-button-toolbar>
                </b-card>
            </div>
        </div>

         <div class="col-sm-3">
            <div id="cardsec">
                <b-card
                    title="Projetos em Aberto"
                    tag="article"
                    style="max-width: 20rem;"
                    class="mb-2"
                >
                    <b-card-text>
                     <h2>12</h2>
                    </b-card-text>

                </b-card>
            </div>
        </div>

        <div class="col-sm-3">
            <div id="cardsec">
                <b-card
                    title="Quantidade de Imagens"
                    img-src="https://picsum.photos/600/300/?image=25"
                    img-alt="Image"
                    img-top
                    tag="article"
                    style="max-width: 20rem;"
                    class="mb-2"
                >
                    <b-card-text>
                    <h2>250</h2>
                    </b-card-text>

                    <div class="progress">
                        <div class="progress-bar" role="progressbar" style="width: 25%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">25%</div>
                    </div>
                   
                </b-card>
            </div>
        </div>

        <div class="col-sm-3">
            <div id="cardsec">
                <b-card
                    title="Acessos a share"
                    img-src="https://picsum.photos/600/300/?image=25"
                    img-alt="Image"
                    img-top
                    tag="article"
                    style="max-width: 20rem;"
                    class="mb-2"
                >
                    <b-card-text>
                    <h2>08</h2>.
                    </b-card-text>

                </b-card>
            </div>
        </div>

    </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
#cardsec {
  max-width: 15rem;
}
</style>