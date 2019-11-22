<template>
    <div>
        <SearchBar @termChange="onTermChange"></SearchBar>
    </div>
</template>

<script>
    import SearchBar from './components/SearchBar'

    export default {
        name: 'App',
        components: {
            SearchBar
        },
        methods: {
            onTermChange(searchTerm) {
                /* eslint-disable no-console */
                console.log(searchTerm)
                /* eslint-enable no-console */
            }
        }
    }
</script>