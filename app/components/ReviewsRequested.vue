<template>
    <div class="hello">
        <h1>{{ title }}</h1>
        <p>
            This will be where your requested reviews show....
        </p>
    </div>
</template>

<script>
    export default {
        data () {
            return {
                title: 'Requested Reviews'
            };
        },
        methods () {
            return {
                getData () {
                }
            };
        }
    };
</script>
