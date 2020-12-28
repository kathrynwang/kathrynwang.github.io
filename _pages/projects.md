---
layout: noimg_page
title: projects
permalink: /projects/
---

# Projects
<html>
<style>
* {
  box-sizing: border-box;
}
/* Float 2 columns side by side */
.column {
  float: left;
  width: 50%;
  padding: 10px 10px 10px 10px;
}
/* Remove extra left and right margins, due to padding in columns */
.row {margin: 0 -5px;}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
/* Style the counter cards */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2); /* this adds the "card" effect */
  padding: 16px;
  text-align: center;
  background-color: #f1f1f1;
}
/* Responsive columns - one column layout (vertical) on small screens */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
    display: block;
    margin-bottom: 20px;
  }
img {
    float: left;
    width:  450px;
    height: 350px;
    object-fit: cover;
}
}
</style>
<body>
<div class="row">
  <div class="column">
    <div class="card">
      <img src="/img/regood.png">
      <p><h3>Regood</h3></p>
      <p>Regood is a lifestyle brand with a mission to close the loop on fast fashion. We rescue usable textiles destined for the landfill and upcycle them into lifestyle products.</p>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="/img/padt2.jpg">
      <p><h3>Pan-Asian Dance Troupe</h3></p>
      <p>President, Artistic Director, and Choreographer of 11 show pieces for Penn's premiere Asian fusion dance group.</p>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="/img/ninja.png">
    </div>
  </div>
</div>
</body>
</html>
