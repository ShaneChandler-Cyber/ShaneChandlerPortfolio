---
layout: default
---


#  [About me](./aboutme.html) | [Home](./index.html) | [Contact](./contactinfo.html) | [Resources](./resources.html) | [Projects](./projects.html) | [Blog](./blog.html)


document.getElementById('post-container').addEventListener('scroll', function() {
  if (this.scrollTop + this.clientHeight >= this.scrollHeight) {
    loadMorePosts();
  }
});
function loadMorePosts() {
  // Logic for fetching and displaying posts
}


<div id="post-container">
  # This is a post! 
</div>

