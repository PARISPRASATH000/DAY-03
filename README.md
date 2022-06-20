# DAY-03
QUE 1:For the given JSON iterate over all for loops (for, for in, for of, forEach)
ANS:There may be times where you feel you need to make a loop through the array of JSON objects in JavaScript. However, you no longer need to worry about this, as it can be done using an array of numbers, strings, or objects. There are numerous ways of looping in JavaScript and throughout this article we’ll help you grasp them.

There are a few types of ways to categorize the loops in JavaScript. These are essential to know as they play a significant role in understanding the concept.

QUE 2:Create your own resume data in JSON format
ANS: let resume= 

    {
        name:"Prasath S",
        EmailId: "parisprasath000@gmail.com",
        Mobile : 8122693099,
         educationalqualification:{
            BachelorOfCommerce :"B.com 65%",
           
         },
        
         PERSONALTRAITS : 
          {   
            a :'Self Motivated and Self Learner',
            b :'Effective Time Management and Punctual',
            c :'Flexible Person',
               },
         personalinfo:{
            personaladdress:{
                       street:"18th subramanian street",
                        doorn:'326/1-a 1st floor', 
                         area:'g k m colony', 
                         city:'chennai' , 
                     district:'chennai',
                     Pincode :600082
                    },
                         Dob : "27/04/1997",
                 FathersName : 'Mr.N.Saravanan',
                      Gender : 'Male',
                 Nationality : 'Indian',
          LinguisticAbility :'Tamil  English Telugu ',   
                     Hobbies : 'riding travelling and Listening Music',

         }
         }
                                       
{
    let resumeJSON = JSON.stringify(resume);// object to JSON CONVERSION 
    console.log(resumeJSON);

//let resumeobj  =JSON.parse(resumeJSON);
//console.log(resumeobj);
 
};
    QUE 3:Read about the difference between window, screen and document in javascript
    ANS:window is the execution context and global object for that context's JavaScript,
        document contains the DOM, initialized by parsing HTML,
        screen describes the physical display's full screen.
