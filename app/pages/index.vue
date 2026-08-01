<template>
    <div :class="$style.chartWrap">
        <ClientOnly>
            <TradingViewChart symbol="NASDAQ:SOFI" interval="D" />
        </ClientOnly>
    </div>
</template>

<style module>
.chartWrap {
    flex: 1;
    display: flex;
    min-height: 0;
}
</style>
