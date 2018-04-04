<template>
    <div>
        <form class="jumbotron" v-on:submit.prevent="handleSubmit">
        <Editor v-model="content"/>
        <h3>Click to submit some content!</h3>

        <input type="submit" class="btn btn-lg btn-success"/>
        </form>

        <!-- <PostList content={this.state.content}/> -->

      <Postlist/>
      </div>
</template>


<script>
    import Editor from '@tinymce/tinymce-vue'
    import Postlist from './Postlist'

    var data = {
        content: ""
    }

    export default {
        name: "Input",
        components: {
            Editor,
            Postlist
        },
        methods: {
            handleSubmit: () => alert(data.content),
        },
        data: () => data
    }
</script>


