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
                        Relaxed
                        <b-img class="icon" src="/icons/relaxed.png" />
                    </h1>
                </b-col>
            </b-row>

            <b-row align-h="center" class="mt-4">
                <b-col cols="8" class="description">
                    <p>Tryptophan is an amino acid found in many protein-rich foods. Tryptophan plays a large role in the production of serotonin in the brain. An increase in serotonin in the brain can reduce anxiety and calm the nervous system.</p>
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
                        <li>Eggs</li>
                        <li>Oats</li>
                        <li>Tofu</li>
                        <li>Pumpkin Seeds</li>
                        <li>Turkey</li>
                        <li>Mushrooms</li>
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

.heading {
    margin-top: 5rem;
}

.light-green {
    background-color: #CFE9D7;
}

.description {
    margin-left: 0;
    padding-right: 3rem;
}

.icon {
    width: 10%;
}
</style>
