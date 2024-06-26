<template>
    <div>
        <a href="/" class="row" style="padding: 20px;">
            <img src="/icon.png" style="height: 80px;" />
        </a>
        <slot />
        <div class="row" style="padding: 20px;border-top: solid 1px lightgray;justify-content: space-between;">
            <div class="row" style="gap: 20px;">
                <a href="/privacy-policy">プライバシーポリシー</a>
                <a href="/term-of-use">利用規約</a>
            </div>
            <p class="gray_text">
                ©2024 Crewto, Inc. All rights reserved.
            </p>
        </div>
    </div>
</template>

<style>
@import url("~/assets/default.css");
</style>