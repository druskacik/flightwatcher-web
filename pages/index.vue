<template>
    <div class="home">
        <div class="home__description-and-form">
            <div class="home__description-and-form__element home__description-and-form__description--temp">
                <app-description />
            </div>
            <!-- <div class="home__description-and-form__element">
                <app-form />
            </div> -->
        </div>
    </div>
</template>
  
<script setup>

definePageMeta({ layout: 'default' });

useHead({
    title: 'Flight Watcher Bot',
    meta: [
        {
            name: 'keywords',
            content: 'cheap flights, flight tracking, flight notifications, flights search, notification bot',
        },
        {
            name: 'description',
            content: 'Flight Watcher Bot - get cheap flight notifications directly to your Telegram inbox.',
        },
    ],
});
</script>
  
<style scoped>
.home__description-and-form {
    display: flex;
    flex-direction: row;
}

/* .home__description-and-form__element {
    width: 50%;
} */

.home__description-and-form__description--temp {
    width: 70%;
}

@media screen and (max-width: 900px) {

    .home__description-and-form {
        flex-direction: column;
    }

    .home__description-and-form__element {
        width: 100%;
    }
}
</style>
  