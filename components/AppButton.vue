<template>
    <div class="bg-red-800 w-fit">
        Custom Button

        <button v-bind="$attrs">
            <slot />
        </button>
    </div>
</template>
