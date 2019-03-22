<template>
    <div>
        <h1 class="font-normal text-3xl text-grey-darkest leading-none mb-6">
            Colors
        </h1>

        <div class="mb-16">
            <p class="mb-8">Primary - Blue, White, Dark Grey</p>

            <div class="flex">
                <div class="text-center mr-8">
                    <div
                        class="rounded-full bg-blue shadow w-18 h-18 mb-3"
                    ></div>
                    <p class="text-xs">#328AF1</p>
                </div>

                <div class="text-center mr-8">
                    <div
                        class="rounded-full bg-white shadow w-18 h-18 mb-3"
                    ></div>
                    <p class="text-xs">#FFF</p>
                </div>

                <div class="text-center">
                    <div
                        class="rounded-full bg-black shadow w-18 h-18 mb-3"
                    ></div>
                    <p class="text-xs">#222222</p>
                </div>
            </div>
        </div>

        <div class="mb-16">
            <p class="mb-8">Secondary - Category Colors & Accents</p>

            <div class="flex">
                <color-range
                    from="#EC454F"
                    to="#F44881"
                    name="Laravel"
                ></color-range>

                <color-range
                    from="#637BFF"
                    to="#21C8F6"
                    name="PHP"
                ></color-range>

                <color-range
                    from="#50A88D"
                    to="#6EDCC4"
                    name="Testing"
                ></color-range>

                <color-range
                    from="#E59D3E"
                    to="#F19A1A"
                    name="JavaScript"
                ></color-range>

                <color-range
                    from="#8465E5"
                    to="#AA76B9"
                    name="Tooling"
                ></color-range>
            </div>
        </div>

        <div>
            <p class="mb-8">Icons</p>

            <div class="flex">
                <div class="text-center mr-8">
                    <div
                        class="rounded-full shadow w-18 h-18 mb-3 bg-grey-dark"
                    ></div>
                    <p class="text-xs">#78909C</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import ColorRange from './ColorRange';

export default {
    components: {
        ColorRange
    }
};
</script>
