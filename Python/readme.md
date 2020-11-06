PYTHON DETAILS:
  ->Python Keyword
  ->Identifier
  ->Comment:
         #Single comment
         '''Multi sentence comment '''
   ->Dcstring -document to the function class and number using multi comment for check---rint(functionname._doc_)
               (Press shift+tab to see the docstring)
  ->Python Indentation: logical continous of previous column check
  ->Python statement:
         #Single line statement
         #Multiline statement - after finish one statement just add slash '\' then it means for contious line
  ->Variable- Give u alise loc and memory that is used to store some data
            - python internally handle type of variable
            - Variable assignment
            -Multiple  assignments 
            -Sorage location-id(variablename)
  ->DataType- Variable store in datatype -Every value in python as a datatype
            - Commonly used Datatype: int,float ,complex -for check datatype -type(varaiblename)
            
  ->Pythong string-It is sequence of unicode character
   
  ->Python List-order sequence of item
   ex: mylist=['asdf',12,'grape',89]
       print(mylist)
       mylist[0]-first word of list
       *we can replace the list value mention
       mylist[0]='tyu'
       new list will be ['tyu',12,'grape',89]
       *if we remove particular list we use pop
         mylist.pop(2)
         
  ->Python Tuple-tuple as unorder sequence of item same as list
                 the only difference between tuple and list tuple are immutable
                 
          Ex: mytuple=('qwe',78,12,34)
              print(mytuple[2])
              * we can not edit tuple
              
  ->Python set: Unorder list of unique id
           ex:myset={10,20,20,30}
            print(myset)
            * Set doesn't allow indexing
            
  ->Python Dictionary : unorder collection of key and value pair
           ex: mydict={key1':'value1','key2':'value2'}
               mydict['key2']=value2
             changeing key values
               mydict['key1]='alue100'
               mydict (after chnage dictionary value new dictionary value comes
               {key1':'value100','key2':'value2'}
             add new key also 
               mydict['key3']='value
               mydict (after adding new key new dictionary comes
               {key1':'value100','key2':'value2','key3':'value3'}
             for del value in dictionary
              del mydict['key']
              
   ->Conversion between Datatype
           int-float
           float-int
       -Convert list to set
          mylist=['a','b','c,'d']
          myset=set(mylist)
          print(myset)
          {'a','b','c,'d'}  -set not allow duplicate value
        -Convert string to list
           mystr="My name is mukesh swain"
           strtolist=list(mystr)
           print(strtolist)
           {'m','y','','n',....}
   
   ->Python Output
   ->Output format
            ex: myint1=20
                myint2=30
                print("my int1:{}is half of myint32 :{}",format(myint1,myint2))
   ->Python input
   
          ex: userinput =input["please enter some data:"]
                print('you type in:',userinput)
               we can type of input int bydefault input type is string
               
               classstrength=int(userinput)
               
               
           
          
          
           
          
    
   
                
               
               
  
               
               
               
             
  
  
          
        
         
  
  
