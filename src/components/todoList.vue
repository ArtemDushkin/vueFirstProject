<template>
    <div>
        <ul>
            <TodoItem />
        </ul>

    </div>
</template>

<script>
import TodoItem from './todoItem.vue';
export default {
    props: ['todos'],
    components: {
        TodoItem
    }
}
</script>