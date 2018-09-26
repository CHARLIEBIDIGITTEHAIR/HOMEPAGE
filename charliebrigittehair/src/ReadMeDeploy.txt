To Build website run the following commands 1 and 2. 
The commands numbered > 2 are there to assist with managing the deployments. 

1. now 
2. now alias xxxxxx charliebrigittehair.com
3. now ls - this will display all the instances currently running.
4. now rm "instance_name" 

Notes On Command Functionality
    1. the now command builds the production package and deployes a unique version of the code. AkA an istance.  
    2. the first now command generates a unique https: that looks something like this https://charliebrigittehair-vbhmyvplwd.now.sh .. Every time you run the now command it generates a new unqiue https link. You
    now need to alias this link to our custom domain which is charliebrigittehair.com 

Notes:
    There can only be 3 instances of the site running at 1 particular time. To view how many instances are running use command 3
    To make room for a new instance you will need to remove an old instance to do this use command 4. 
