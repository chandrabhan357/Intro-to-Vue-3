const app = Vue.createApp({
    data: function() {
        return {
            product: 'Socks'
        }
    }
})

To simplify the syntax, tha data: function() {}
syntax is switched out with ES6 Shorthand.

const app = Vue.createApp({
    data() {
        return {
            product: 'Socks'
        }
    }
})