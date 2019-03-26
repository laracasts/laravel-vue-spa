<template>
    <div>
        <h1 class="font-normal text-3xl text-grey-darkest leading-none mb-8">
            Full Logo
        </h1>

        <!-- Original Logo -->
        <div class="mb-12">
            <picture
                style="height: 382px;"
                class="block shadow rounded-lg flex items-center justify-center mb-6"
            >
                <img src="/images/logo.svg" alt="logo" />
            </picture>

            <div class="flex justify-between items-center">
                <p>Original logo on <strong>white</strong> background</p>

                <a href="/images/logo.svg" class="button">logo.svg</a>
            </div>
        </div>

        <!-- Negative Logo With Accent -->
        <div class="mb-12">
            <picture
                style="height: 382px;"
                class="block shadow rounded-lg flex items-center justify-center mb-6 bg-blue"
            >
                <img src="/images/negative-logo.svg" alt="logo" />
            </picture>

            <div class="flex justify-between items-center">
                <p>
                    Negative logo with accent on
                    <strong>dark</strong> background
                </p>

                <a href="/images/negative-logo.svg" class="button">
                    negative-logo.svg
                </a>
            </div>
        </div>

        <!-- Pure Negative Logo -->
        <div>
            <picture
                style="height: 382px;"
                class="block shadow rounded-lg flex items-center justify-center mb-6 bg-black"
            >
                <img src="/images/pure-negative-logo.svg" alt="logo" />
            </picture>

            <div class="flex justify-between items-center">
                <p>Pure negative logo on <strong>dark</strong> background</p>

                <a href="/images/pure-negative-logo.svg" class="button">
                    pure-negative-logo.svg
                </a>
            </div>
        </div>
    </div>
</template>

<script>
export default {};
</script>
