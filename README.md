# problemsolving
# problemsolvingtask1
<!DOCTYPE html>
<html lang="en">
<head>


    <title>arthimetic progreesiion</title>
</head>
<body>
    <script>



//print a square or not a squae based on length and bredth

var a=prompt("enter n length")
 var b=prompt("enter n breadth")
 if(a==b){
     alert("it is square")
 }
 else{
    alert("it a not a square")
 }

// print a rectangular or not a rectangular based on length and bredth

 var a=prompt("enter n length")
 var b=prompt("enter n breadth")

 if(a>b||a<b){
     alert("it is a recctangular")
 }
else{
    alert("it is a  not recctangular")
 }

// athemetic progression

 var a=prompt("enter a ")
 var b=prompt("enter b")
 var c=prompt("enter c")
 var d=prompt("enter d")

 if(b-a==c-b&&d-c==b-a){

    alert("it is arthemtic progression")
}
else{alert("it is not a arthemetic progression")}


// 4thquation


var a=prompt("enter a ")
var b=prompt("enter b")
var c=prompt("enter c")
 var d=prompt("enter d")

 if(( a%2==0&&b%2==0) && (c%2==0&&d%2==0) )
 {
     alert(" 1")
     }

else{alert("-1")}
//5th quation

 x=20;
 y=87;
z=56;
e=34;

var a=+prompt("enter a ")
var b=+prompt("enter b")
var c=+prompt("enter c")
 var d=+prompt("enter d")
 var x=a+b+c+d
 bal=220
if(x==bal){
    alert("paid")
}
else if ( bal>x) {
    alert(bal-x+"take change")
} else if(x>bal){
    alert(x-bal+"pay amount")
}
\else{
     alert("enter valudess")
 }




    </script>
</body>
</html>
