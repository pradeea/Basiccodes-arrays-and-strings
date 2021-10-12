# Basiccodes-arrays-and-strings
//finding factor
  var answer = 1;
  for(var i = num; i >= 1; i--){  //4
    answer = answer * i; //
  }
  console.log(answer);
------------------------------
  //reverse an string
  var data="Pradeep kumar"
  let res ="";
  for(var i=data.length-1; i>=0;i--)
  {
    res +=data[i]
  }
  console.log(res);
  ------------------------------
  // prime
 var n = 4;
  var count=0;
  for(let i=1;i<=n ; i++)
  {
    if(n%i == 0)
    {
      count=count+1;
    }
  }
  if(count==2)
  {
    console.log("it is prime");
  }
  else
  {
    console.log("it is not a prime");
  }
