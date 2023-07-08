<template>
    <div class="description">
        <div class="description__content">
            <h1>
                Flight Watcher Bot
            </h1>
            <p>
                Flight Watcher Bot is a Telegram bot you can use to get cheap flight notifications directly to your Telegram inbox.
                It's highly customizable and easy to use. You can set up notifications for any start city, any destination, any date.
            </p>
            <p>
                By default, the bot sends flight tips twice a day, in the morning and in the evening.
            </p>
            <p>
                To take part, all you need is a
                <a href="https://telegram.org/" target="_blank">
                    Telegram
                </a>
                app. To set up notifications, chat up with the bot at
                <a href="https://t.me/flight_watcher_bot" target="_blank">
                    https://t.me/flight_watcher_bot
                </a>
                and follow his instructions.
            </p>
            <div>
                <telegram-button />
            </div>
            <h1 class="description__content__header">
                About project
            </h1>
            <p>
                If you want to provide any feedback or suggestions, the fastest way to contact me is via Telegram:
                <a href="https://t.me/rdruska" target="_blank">
                    https://t.me/rdruska
                </a>
            </p>
        </div>
    </div>
</template>

<style scoped>

.description {
  padding: 2rem 0;
  text-align: left;
}

.description__content {
  width: 80%;
  margin: auto;
}

.description__content__header {
  margin-top: 3rem;
}

@media screen and (max-width: 600px) {

  .description__content {
    width: 90%;
  }

  .description__content__header {
    margin-top: 3.5rem;
  }

}

</style>
