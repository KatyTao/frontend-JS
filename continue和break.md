## 案例
求整数50~200的第一个能被7整除的数
    
    for(var i=50; i<=200; i++){
        if(i%7 === 0){
          console.log(i);
          break;
        }
     }

求整数1~100的累加值，但要求跳过所有个位为3的数

    var sum = 0;
    for(var i=1; i<=100; i++){
      if(i%10 === 3){
        continue;
      }else{
      sum+=i;
      }
    }
