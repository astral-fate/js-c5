# js-c5

we learned so for, three methods of flow control:

if statments
switch statments
conditional operators



below is an example for conditional operators, if we have the follwing senario, and we want to plot it from if statments, to conditional operators: 


    

                          if (30<bill<=300){
                              console.log(`${bill}, ${bill * 0.15}`);
                             }
                              else if (bill<300) {
                              console.log(`${bill}, ${tip*0.20`});
                             }




now if we want to transfer it into conditional operators:  



                            let bill = 275;
                         const tip = bill <= 300 && bill >=50 ?  console.log(`${bill}, ${bill*0.20}`) :  console.log(`${bill}, ${bill*0.15}`);
 


notice that if we want to inculde statments that generates values in the console, we have to write them inside ${};
    
    
    

   

