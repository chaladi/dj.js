# dj.js
dj.js is a javascript library (jquery like) based on ES6  for createing small- or large-scale web applications, and is particularly useful in creating interactive websites.

Sample code,
```
<script src="dj.js" charset="utf-8"></script>


 <div class="class1" id="id1">This is id1</div>
  <div class="class1" id="id2">This is id2 with class1</div>
  <button type="button" name="button" id="bt">Click</button>

  <script type="text/javascript">
    // var djj=new djs();
    dj("#id1").html("This is changed by dj");

    dj(".class1").append("This string is appended to class1");

    dj("#bt").on("click", function(){  // event handling
      if(dj().isArray([1,2,3])){
        alert("Tharray is 3")
      }
    })
  </script>

```
