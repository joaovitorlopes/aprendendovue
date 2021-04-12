<template>
    <div>
        <b-col>
            <b-card
                :title="nome"
                style="max-width: 20rem;"
                class="mb-2"
                border-variant="primary"
                header="Primary"
                header-bg-variant="primary"
                header-text-variant="white"
                align="center"
                img-src="https://picsum.photos/600/300/?image=25"
                img-alt="Curso de Vue.JS"
                img-top
                tag="article"
            >
                <b-card-text>
                    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Blanditiis, laudantium eos id iure natus recusandae fugit eveniet sint provident rerum quis, autem alias velit suscipit ullam cum, deserunt consequuntur mollitia.
                </b-card-text>
                <b-button variant="primary">Inscrever-se</b-button>
            </b-card>
        </b-col>
    </div>
</template>

<script>
export default {
    props: {
        nome: {
        type: String,
        required: true,
        }
    },
};
</script>