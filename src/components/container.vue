<template>
    <div class='cm-container'>
        <slot />
    </div>
</template>

<style lang='scss'>
.cm-container {
    width: 100%;
    display: flex;
    margin-right: auto;
    margin-left: auto;
    padding-right: var(--cm-container-padding);
    padding-left: var(--cm-container-padding);
}

@media (min-width: 640px) {
    .cm-container {
        max-width: calc(640px - var(--cm-container-padding) * 2);
    }
}

@media (min-width: 768px) {
    .cm-container {
        max-width: calc(768px - var(--cm-container-padding) * 2);
    }
}

@media (min-width: 1024px) {
    .cm-container {
        max-width: calc(1024px - var(--cm-container-padding) * 2);
    }
}

@media (min-width: 1280px) {
    .cm-container {
        max-width: calc(1280px - var(--cm-container-padding) * 2);
    }
}

@media (min-width: 1536px) {
    .cm-container {
        max-width: calc(1536px - var(--cm-container-padding) * 2);
    }
}
</style>