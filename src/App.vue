<template>
    <section>
        <h2>My Friends</h2>
        <ul>
            <li></li>
        </ul>
    </section>
</template>

<script>
    export default {
        data () {
            return {
                friends: [
                    {
                        id: 'jk',
                        name: 'John',
                        email: 'john@localhost.com',
                        phone: '000 000 0000'
                    },
                    {
                        id: 'tk',
                        name: 'Travis',
                        email: 'travis@localhost.com',
                        phone: '111 111 1111'
                    }
                ]
            }
        }
    }
</script>