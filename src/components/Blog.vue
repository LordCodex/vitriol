<template>
  <div v-bind:class="'blog-box'">
    <div class="blogs">
      <div class="blog-text">
        <h1 class="news">Our Articles And Blog</h1> 
    <p style="text-align:center; color: rgb(99, 107, 131)">  Quisque velit nisi, pretium ut lacinia in, elementum id enim.
              Curabitur aliquet quam id dui posuere blandit. </p>
    <br>
       
      </div>
      <div class="articles">
        <div class="article-box">
          <img src="../assets/images/post1.png" width="100%" />
          <div class="article-details">
            <div class="cat"><b>Opportunity</b></div>
            <h1 class="lorem">Lorem Ipsum Dolor ....</h1>
            <p style="color: rgb(99, 107, 131)" >
              Quisque velit nisi, pretium ut lacinia in, elementum id enim.
              Curabitur aliquet quam id dui posuere blandit.
            </p>
            <br />
            <p class="art">
              <i class="fa-solid fa-user"></i> Codex Ui &nbsp;
              <i class="fa-solid fa-calendar"></i> 24 Mins ago&nbsp;
              <i class="fa-solid fa-eye"></i> 12,947 views&nbsp;
            </p>
          </div>
          <br />
          <button class="btns">Read More</button>
        </div>


        <div class="article-box">
          <img src="../assets/images/post1.png" width="100%" />
          <div class="article-details">
            <div class="cat"><b>Opportunity</b></div>
            <h1 class="lorem">Lorem Ipsum Dolor ....</h1>
            <p style="color: rgb(99, 107, 131)" class="caption">
              Quisque velit nisi, pretium ut lacinia in, elementum id enim.
              Curabitur aliquet quam id dui posuere blandit.
            </p>
            <br />
            <p>
              <i class="fa-solid fa-user"></i> Codex Ui &nbsp;
              <i class="fa-solid fa-calendar"></i> 24 Mins ago&nbsp;
              <i class="fa-solid fa-eye"></i> 12,947 views&nbsp;
            </p>
          </div>
          <br />
          <button class="btns">Read More</button>
        </div>

        <div class="article-box">
          <img src="../assets/images/post1.png" width="100%" />
          <div class="article-details">
            <div class="cat"><b>Opportunity</b></div>
            <h1 class="lorem">Lorem Ipsum Dolor ....</h1>
            <p style="color: rgb(99, 107, 131)" class="caption">
              Quisque velit nisi, pretium ut lacinia in, elementum id enim.
              Curabitur aliquet quam id dui posuere blandit.
            </p>
            <br />
            <p>
              <i class="fa-solid fa-user"></i> Codex Ui &nbsp;
              <i class="fa-solid fa-calendar"></i> 24 Mins ago&nbsp;
              <i class="fa-solid fa-eye"></i> 12,947 views&nbsp;
            </p>
          </div>
          <br />
          <button class="btns">Read More</button>
        </div>
      </div>
    </div>
  </div>
  <br />
  <br />
</template>

<script>
export default {
  name: "BlOgs,",
};
</script>

<style scoped>
@import "../assets/css/Blog.css";
</style>