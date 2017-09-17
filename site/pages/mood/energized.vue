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
                        Energized
                        <b-img class="icon" src="/icons/energized.png" />
                    </h1>
                </b-col>
            </b-row>

            <b-row align-h="center" class="mt-4">
                <b-col cols="8" class="description">
                    <p>Carbohydrates provide the body with energy. Foods with complex carbohydrates take longer for the body to break down, meaning a slow release of energy that can be sustained for longer periods of time.</p>
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
                        <li>Oats</li>
                        <li>Yams</li>
                        <li>Sweet Potatoes</li>
                        <li>Potatoes</li>
                        <li>Whole wheat bread</li>
                        <li>Spinach</li>
                        <li>Peas</li>
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
