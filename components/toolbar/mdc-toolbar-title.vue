<template>
    <a class="mdc-toolbar-title mdc-toolbar__title" @click="dispatchEvent">
        <slot></slot>
    </a>
</template>

<script>
import {DispatchEventMixin} from '../util'

export default {
  name: 'mdc-toolbar-title',
  mixins: [DispatchEventMixin]
}
</script>
