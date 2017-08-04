<template>
  <div id="app">
    <div class="container">
      <div class="card-columns">
        <div class="card p-3">
          <blockquote class="card-blockquote">
            <footer>
              <small>
                <a target="_blank">
                  Read more on
                </a>
              </small>
            </footer>
          </blockquote>
        </div>
      </div>
    </div>
    <div class="text-center">
      Loading...
    </div>
  </div>
</template>

<script>
import axios from 'axios'
export default {
  created() {
    this.getPosts()
  },
  data() {
    return {
      posts: [],
      postsLoading: false,
      nextPage: null
    }
  },
  methods: {
    getPosts(page) {

    }
  }
}
</script>
