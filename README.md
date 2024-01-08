<!DOCTYPE html>
<html>
<head> 
    <title>Painting by Pier Mondrian</title>
    <style> 
    .wrapper{
        display:grid;
        background-color: black;
        grid-template-columns: 1fr 3fr;
        grid-column-gap: 0.5em;
        grid-row-gap: 1em;
        height: 600px;
        width: 350px;
        justify-items:stretch;
        align-items:stretch;

    }
 
    
    
.box1 {
  background-color: rgb(217, 215, 215);
  grid-column-start: 1;
  grid-column-end: span 1;
  grid-row-start: 1;
  grid-row-end: 1;

}
.box2 {
  grid-column-start: 2;
  grid-column-end: span 10;
  grid-row-start: 1;
  grid-row-end: span 2;
  background-color: red;

}

.box3 {
  grid-row-start: 3;
  grid-row-end: span 2;
  grid-column-start: 1;
  grid-column-end: span 1;
  background-color:#2F539B;
  height: 80px;
 
  
}
.box4 {
  grid-row-start: 2;
  grid-row-end: span 1;
  background-color: #e0e0dc;
 
}
.box5{
  background-color: #e0e0dc;
  grid-row-start: 3;
  grid-row-end: span 1;
  
 height: 30px;
}

.box6{
  background-color: #e1e1df;
  grid-row-start: 3;
  grid-column-start: 2;
  grid-column-end: span 3;
  grid-row-end: span 2;
  height: 80px;
 
}

.box7{
  background-color: #d8d84d;
  grid-row-start: 3;
  grid-row-end: span 1;
  grid-column-start: 3;
  grid-column-end: span 1; 
  height: 30px;
}
    </style>
</head>
<body> 
    <div class="wrapper">
        <div class="box box1">box1</div>
        <div class="box box2">box2</div>
        <div class="box box3">box3</div>
        <div class="box box4">box4</div>
        <div class="box box5">box5</div>
        <div class="box box6">box6</div>
        <div class="box box7">box7</div>
    </div>
</body>
</body>
</html>
        
