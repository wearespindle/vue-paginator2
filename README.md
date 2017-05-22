# vue-paginator2
A paginator component for Vue2 using hardcoded styles from [Bulma](http://bulma.io/).

# Usage
This module depends on npm and commonjs. Just install in your project with:

    npm i vue-paginator2 --save

Then include the two components with:

    const {Paginator} = require('vue-paginator2')
    Vue.component('Paginator', Paginator)

Then in the template where you want pagination, use something like:

    <Paginator
        :count=items.count
        :next=items.next
        :previous=items.previous
        resource_action="items/readItems"
        resource_url="/items">
    </Paginator>

That's it! Have fun paginating. Please [file an issue](https://github.com/wearespindle/vue-paginator2/issues)
if you have feature requests or bug reports.
