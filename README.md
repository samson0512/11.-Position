# 11.-Position

## program :
```
<!DOCTYPE html>
<html>
  <head>
    <title>position example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>position</h1>
    <h4>Static</h4>
    <div class="container-static">
    <p>It's default position.</p>
    </div>
    <h4>absolute</h4>
    <div class="container-absolute">
      <div class=item1>1</div>
      <div class=item2>2</div>
      <div class=item3>3</div>
      <div class=item4>4</div>
      <div class=item5>5</div>
    </div>
    <h4>Relative</h4>
    <div class="container-relative">
      <div class=item6>1</div>
      <div class=item7>2</div>
      <div class=item8>3</div>
      <div class=item9>4</div>
      <div class=item10>5</div>
    </div>
    <h4>Fixed</h4>
    <div class="container-fixed">
      <div class=item11>1</div>
      <div class=item12>2</div>
      <div class=item13>3</div>
      <div class=item14>4</div>
      <div class=item15>5</div>
    </div>
    <h4>Sticky</h4>
    <div class="container-sticky">
      <div class=item16>1</div>
      <div class=item17>2</div>
      <div class=item18>3</div>
      <div class=item19>4</div>
      <div class=item20>5</div>
    </div>
     </body>
</html>
.body{
  background-color:#f0f0f0;
  font-family: Arial;
  margin:0;
  padding:0;
}
h1{
  background-color:tomato;
  text-align:center;
  color:white;
  margin-top:0;
}
h4{
  color:#f34345;
}
.container-absolute,
.container-relative,
.container-fixed,
.container-sticky,
.container-static{
  background-color:#ccc;
  border-radius:4px;
  box-sizing:border-box;
  display:flex;
  margin:10px;
  
}
.container-absolute >div,
.container-relative >div,
.container-fixed >div,
.container-sticky >div{
  background-color:white;
  height: 50px;
  width: 50px;
  border-radius:5px;
  display:grid;
  place-items:center;
  background-color:yellow ;
  border:2px solid #ccc;
}
.item1{
  position:absolute;
}

.item7{
  position:relative;
  top:20px;
  right:20px;

}
.item6{
  position:absolute;
}
.item11{
  position:fixed;
}
.item20{
  position:sticky;
  right:50px;
  top:30px;
}

```
## output:
![WhatsApp Image 2024-07-14 at 22 42 06_3ab3dd5a](https://github.com/user-attachments/assets/c8ea4ef9-6851-461c-83c3-263fe608fc41)
