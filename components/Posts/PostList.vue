<template>
  <section class="post-list">
    <PostPreview
      id='1'
      thumbnail='https://cdn.techinasia.com/wp-content/uploads/2017/06/47724337_l.jpg'
      title='Hi there'
      previewText= 'some text'
    ></PostPreview>
    <PostPreview
      id='2'
      thumbnail='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR44nlmb5vuFyADTwjw99ivVXRFmEZB1hd8eGts9YLVDYZEYh62'
      title='Hi there again'
      previewText= 'some other text'
    ></PostPreview>
    <PostPreview
      id='3'
      thumbnail='https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8etIH7cqT-sCHJH_EX41XSWaSzGVDB78wnmzmGlqvLaJXqeRJ'
      title='Hi there one more time'
      previewText= 'some more text'
    ></PostPreview>
  </section>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'
export default {
  name: 'PostList',
  components: {
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