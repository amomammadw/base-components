<template>
    <div class="bg-brand-500 w-fit">
        Custom Button

        <button v-bind="$attrs">
            <slot />
        </button>
    </div>
</template>
