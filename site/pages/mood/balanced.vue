<template>
    <div>
        <b-container fluid class="mt-5 pl-5 pb-5">
            <b-row>
                <b-col>
                    <b-button to="/mood">back</b-button>
                </b-col>
            </b-row>
            <b-row align-h="center" class="heading">
                <b-col cols="9">
                    <h1>
                        Balanced
                        <b-img class="icon" src="/icons/balanced.png" />
                    </h1>
                </b-col>
            </b-row>

            <b-row align-h="center" class="mt-4">
                <b-col cols="8" class="description">
                    <p>Omega-3 fatty acids supports function and structure of brain cells by building and repairing cell membranes. This contributes to overall brain health.</p>
                </b-col>
            </b-row>
        </b-container>

        <div class="light-green">
            <b-container class="pt-5 pb-5">
                <b-row>
                    <h3>Try including these in your meal</h3>
                </b-row>
                <b-row>
                    <ul>
                        <li>Salmon</li>
                        <li>Oysters</li>
                        <li>Flaxseeds</li>
                        <li>Chia Seeds</li>
                        <li>Walnuts</li>
                    </ul>
                </b-row>

            </b-container>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
h1,
h3,
p {
    font-family: Comfortaa;
}

.light-green {
    background-color: #CFE9D7;
}

.description {
    margin-left: 4rem;
    padding-right: 3rem;
}

.icon {
    width: 15%;
}
</style>
