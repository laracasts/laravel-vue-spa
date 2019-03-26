<template>
    <div class="mr-8 flex flex-col items-center">
        <div
            class="rounded-full shadow w-18 h-18 mb-3"
            :style="
                `background-image: linear-gradient(to left, ${from}, ${to})`
            "
        ></div>

        <div class="flex justify-center mb-4">
            <div class="flex flex-col items-center mr-4">
                <div
                    class="rounded-full w-5 h-5 shadow mb-3"
                    :style="`background: ${to}`"
                ></div>

                <p class="text-xs" v-text="to"></p>
            </div>

            <div class="flex flex-col items-center">
                <div
                    class="rounded-full w-5 h-5 shadow mb-3"
                    :style="`background: ${from}`"
                ></div>

                <p class="text-xs" v-text="from"></p>
            </div>
        </div>

        <h5 class="uppercase text-2xs text-grey font-normal" v-text="name"></h5>
    </div>
</template>

<script>
export default {
    props: ['from', 'to', 'name']
};
</script>
