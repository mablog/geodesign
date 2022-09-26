1- Iinit npm folder : 

    ==> npm init -y 
    
    the -y is added to answer yes for all the questions given on terminal

2- Install Parcel as dev dependecy :

    ==> npm i -D parcel@2.7.0

3- Install Bootstrap 

    ==> npm i bootstrap@5.2.1

4- Overwrite Bootstrap scss variables
    
    create scss folder in the fronted folder 
    create abstract folder in the new scss folder 
    in the abstract folder, create a variables file
    Overwrite the target variable
    create a main.scss file in the scss folder 
    import this main.scss in the index.html file 
    import bootstrap as javascript module in the index.js file
    parcel will do the job by compiling the scss on css and
    include it automaticly on the html file to be served

