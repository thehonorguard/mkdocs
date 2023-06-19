# My Two-Column Page

this bit can be done in **markdown**. 



<div class="md-html">
  <div class="column-left">
    <h2>Left Column</h2>
    <p>While this is done in HTML</p>
  </div>
  
  <div class="column-right">
    <h2>Right Column</h2>
    <p>This is the content for the right column.</p>
  </div>
</div>

<style>
.column-left {
  width: 50%;
  float: left;
  padding-right: 10px;
  box-sizing: border-box;
}

.column-right {
  width: 50%;
  float: right;
  padding-left: 10px;
  box-sizing: border-box;
}

.md-html::after {
  content: "";
  display: table;
  clear: both;
}
</style>

and this bit is in **markdown** again. :-)