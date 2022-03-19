<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
.abc{
 padding-top: 35px;
}
img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
  border-radius: 50%;
}
</style>
</head>
<body>

<h2>Two Equal Columns</h2>

<div class="row">
  <div class="column">
   <ul>
   <li>👋 Hi, I’m Touqeer Hussain</li>
   <li>👀 I’m interested in Javascript</li>
   <li>🌱 I’m currently working Javascript.</li>
   <li>💞️ I’m looking to collaborate on IT Company.</li>
   <li>📫 How to reach me: { <br/>
             &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Phone: (+923011321938)<br/>
             &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Email: (htouqeer938@gmail.com)<br/>
             &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Web: (www.touqeerhussain.me)<br/>
              }
        </li>
   </ul>
  </div>
  <div class="column">
    <div class="abc">
    <img src="https://1.bp.blogspot.com/-sYHpxw9DbFo/YVGnMuhxu1I/AAAAAAAAAOc/lCP9xHLzPA0Gq63a2JrN2bvykbspD-EUQCLcBGAsYHQ/s0/me.jpg" width="128"/>

    </div>
  </div>
</div>

</body>
</html>
