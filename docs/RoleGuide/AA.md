# My Two-Column Page

<div class="md-html">
  <div class="column-left">
    <h2>Left Column</h2>
    <p>This is the content for the left column.</p>
    <ul>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ul>
  </div>
  
  <div class="column-right">
    <h2>Right Column</h2>
    <p>This is the content for the right column.</p>
    <ol>
      <li>Step 1</li>
      <li>Step 2</li>
      <li>Step 3</li>
    </ol>
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
