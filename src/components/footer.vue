<template>
    <footer class='cm-footer'>
        <slot />
    </footer>
</template>

<style lang='scss'>
.cm-footer {
    flex: 0 0 auto;
    color: var(--cm-footer-color);
    margin-top: 24px;
    padding-top: var(--cm-footer-padding);
    padding-bottom: var(--cm-footer-padding);
    background-color: var(--cm-footer-background-color);
    border-top: 1px solid var(--cm-footer-border-color);

    .cm-container {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
}
</style>