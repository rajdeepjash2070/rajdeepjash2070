 <!DOCTYPE html>
<html>
<head>
   <tittle>
</tittle>
<style>
#menu{
margin-top:40px;
}
.menuicon{
width: 35px;
  height: 3px;
  background-color: deeppink;
  margin: 6px 0;
border:1px solid deeppink;
border-radius:2px 2px 2px 2px;
}
    #d4{
transform:rotateZ(45deg);
        height:3px;
width:35px;
position:relative;
background-color:deepskyblue;
display:none;
}
#d5{
transform:rotateZ(135deg);
height:3px;
width:35px;
background-color:deepskyblue;
margin-top:-2px;
display:none;
}
#menu:hover #d1{
        transform:rotateZ(45deg);
transition:.6s;
} 
#menu:hover #d2{
transform:rotateZ(-45deg);
transition:.6s;
margin-top:-10px;
}
#menu:hover #d3{
display:none;
}
</style>
</head>
<body>
<div id="menu">
<div id="d1" class="menuicon">
</div>
     <div id="d2" class="menuicon">
</div>
 <div id="d3" class="menuicon">
</div>
<div id="d4" class="crossicon">
</div>
 <div id="d5" class="crossicon">
</div>
</div>

</body>
</html>
