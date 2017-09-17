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
                        Happy
                        <b-img class="icon" src="/icons/happy.png" />
                    </h1>
                </b-col>
            </b-row>

            <b-row align-h="center" class="mt-4">
                <b-col cols="8" class="description">
                    <p>Foods with high vitamin B6 can improve mood, as vitamin B6 increases production of serotonin. Some research has shown that low levels of serotonin could lead to depression and regular serotonin levels regulates happiness and mood.</p>
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
                        <li>Chickpeas</li>
                        <li>Potatoes</li>
                        <li>Chicken</li>
                        <li>Turkey</li>
                        <li>Sweet Potatoes</li>
                        <li>Bananas</li>
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
