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
                        Awake
                        <b-img class="icon" src="/icons/awake.png" />
                    </h1>
                </b-col>
            </b-row>

            <b-row align-h="center" class="mt-4">
                <b-col cols="8" class="description">
                    <p>Vitamin B12 is a B vitamin that helps to produce red blood cells which transport oxygen in the body. Glucose can then be converted to energy more easily. As well, thiamin and riboflavin also aid in energy metabolism. Eating foods with high vitamin B12 could increase overall energy.</p>
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
                        <li>Milk</li>
                        <li>Cheese</li>
                        <li>Greek Yogurt</li>
                        <li>Sunflower seeds</li>
                        <li>Spinach</li>
                        <li>Almonds</li>

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
