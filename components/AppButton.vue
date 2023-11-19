<template>
    <div class="bg-red-800">
        Custom Button

        <button v-bind="$attrs">
            <slot />
        </button>
    </div>
</template>
