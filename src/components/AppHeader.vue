<template>
    <header class="app-header">
        <div class="container flex space-between align-center">
            <div class="logo"></div>
            <nav>
                <div class="menu-icon">☰</div>
                <ul class="flex space-between">
                    <li v-for="idx in 4" :key="idx"></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

