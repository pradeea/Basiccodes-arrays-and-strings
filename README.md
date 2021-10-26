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
  
  --------------------------------------
  Sorting array based on repetetion
  
   const arr=[1,1,2,2,2,3];

  function sortByFrequency(arr) {
    const frequency = {};
    arr.forEach(item => {
        frequency[item] = (frequency[item] || 0) + 1;
    });
    const sortable = arr.map(item => [item, frequency[item]]);
    console.log(`sort check ${sortable}`);
    sortable.sort((a,b) => {
      if (a[1] === b[1]) return a[0] - b[0];
      else return a[1] - b[1];
    });
    return sortable.map(s => s[0]);
    
}
  
  console.log(sortByFrequency(arr));![sortarray frequency](https://user-images.githubusercontent.com/48400035/138892673-b101a189-e8b9-4d5a-beec-b2e457b0b515.png)

