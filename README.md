# Vue Snippets StandardJS

## Description

These snippets are based on Sarah Drasner snippets (can be found [here](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)) with minor adaptations to StandardJS standards and for my personal use.

## Snippets

### Vue

Snippet | Purpose
------- | --------------------------
`vbase` | Single file component base

### Template

Snippet           | Purpose
----------------- | ----------------------------------
`vfor`            | v-for directive
`vmodel`          | Semantic v-model directive
`vmodel-num`      | Semantic v-model number directive
`von`             | v-on click handler with arguments
`vel-props`       | Component element with props
`vsrc`            | Image src binding
`vstyle`          | Inline style binding
`vclass`          | Class binding
`vanim`           | Transition component with JS hooks
`vroutename`      | router-link Named Routing
`vroutenameparam` | router-link Named with Parameters
`vroutepath`      | router-link Path Routing Link

### Script

Snippet          | Purpose
---------------- | ---------------------------------------------------------------------
`vdata`          | Component data as a function
`vmethod`        | Vue method
`vcomputed`      | Vue computed property
`vwatch`         | Vue watcher with new and old value args
`vwatch-option`  | Vue watcher with options"
`vprops`         | Props with type and default
`vbeforecreate`  | beforeCreate lifecycle method
`vcreated`       | created lifecycle method
`vbeforemount`   | beforeMount lifecycle method
`vmounted`       | vmounted lifecycle method
`vbeforeupdate`  | beforeUpdate lifecycle method
`vupdated`       | updated lifecycle method
`vbeforedestroy` | beforeDestroy lifecycle method
`vdestroyed`     | destroyed lifecycle method
`vimport`        | Import one component into another
`vcomponents`    | Import one component into another within the export statement
`vfilter`        | Vue filter
`vmixin`         | Create a Vue Mixin
`vmixin-use`     | Bring a mixin into a component to use
`vc-direct`      | Vue create a custom directive
`vimport-lib`    | Import a library
`vanimhook-js`   | Using the Transition component JS hooks in methods
`vcommit`        | Commit to Vuex store in methods for mutation
`vdispatch`      | Dispatch to Vuex store in methods for action
`vshallowtest`   | A simple unit testing component with Vue test utils and shallow mount
`vmountest`      | A simple unit testing component with Vue test utils and mount

### Vuex

Snippet         | Purpose
--------------- | ------------------------------
`vstore`        | Base for Vuex store.js
`vgetter`       | Vuex Getter
`vmutation`     | Vuex Mutation
`vaction`       | Vuex Action
`vstore-import` | Import vuex store into main.js

## Contributing

This is an open source project. Contributions are welcome [github](https://github.com/andersonmfjr/vue-snippets-standardjs).
