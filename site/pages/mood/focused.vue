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
                        Focused
                        <b-img class="icon" src="/icons/focused.png" />
                    </h1>
                </b-col>
            </b-row>

            <b-row align-h="center" class="mt-4">
                <b-col cols="8" class="description">
                    <p>Vitamin K and folate both help to sustain cell growth, specifically in the brain. Both have been shown to increase cognitive function including focus, clarity and memory.</p>
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
                        <li>Spinach</li>
                        <li>Brussel Sprouts</li>
                        <li>Blueberries</li>
                        <li>Broccoli</li>
                        <li>Oranges</li>
                        <li>Orange Juice</li>
                        <li>Celery</li>
                        <li>Kale</li>
                        <li>Asparagus</li>
                        <li>Cranberries</li>
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
