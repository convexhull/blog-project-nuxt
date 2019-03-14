<template>
    <section class="post-list">
        <PostPreview
            id = "1"
            thumbnail = "https://images.techhive.com/images/article/2016/11/computerworld_tech_forecast_2017_hottest-tech-skills-for-2017-100692085-large.jpg"
            title = "Hello"
            previewText = "This is my first post"
        />
        <PostPreview
            id = "2"
            thumbnail = "https://images.techhive.com/images/article/2016/11/computerworld_tech_forecast_2017_hottest-tech-skills-for-2017-100692085-large.jpg"
            title = "Hello there"
            previewText = "This is my second post"
        />
        <PostPreview
            id = "3"
            thumbnail = "https://images.techhive.com/images/article/2016/11/computerworld_tech_forecast_2017_hottest-tech-skills-for-2017-100692085-large.jpg"
            title = "Hello there again"
            previewText = "This is my third post"
        />
    </section>
</template>


<script>

import PostPreview from '~/components/Posts/PostPreview';

export default {
   components : {
       PostPreview
   }     
}
</script>

<style scoped>

.post-list {
  display: flex;
  padding: 20px;
  box-sizing: border-box;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}

</style>

