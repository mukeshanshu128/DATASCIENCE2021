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
    ->Python operator
            var1=10
            var2=20
            print(var1+var2)
            print(var1-var2)
            print(var1/var2)
            print(var1*var2)
            print(var1%var2)  //Modular division
            print(var1//var2) //floor division
            print(var1**var2)  //exponenet
            
        ->Comparision operator : <,> ,==, != ,>=,<=
        
              var1,var2=2,5
               print(var1 < var2)
               print(var1 > var2)
               print(var1 == var2)
               print(var1 != var2)
               print(var1 >= var2)
               print(var1 <= var2)
          ->Logical operator
                -Logical opertor only operate TRUE & FALSE  or //boolean value
              ex: var1,var2=True,false
                print(var1 and var2)
           ->Bitwise operator:
                    Bitwise operation act on operands as they were string of binary digit.It operate bit by bit
                    var1 ,var2 = 3,7             -->3 -0000 0011 4- 0000 0111
                    
                    print(var1 & var2)
                    print(var1 | var2)
                    print(~var2)            //inverse
                    print(var1 ^ var2)      //xor
                    print(var1 >>2)         //left shift 
                    print(var1 <<2)         //right shift
                    
              ->Assignment operator
              
                     age=12
                     age+=12
                     age-=12
                     age/=12
                     age%=12
                     age//=12   floor divison
                     age**=12    exponenet
                     
        ->Special operator
                -Identity operator & Member operator
              *Identity operator
                  list is not identitcal operator
                  list is created unique memory for every time we created new list
              *Membership operator (In not)
                  In dictionary value search the key
       ->Control Flow
              -Python if else statement
               ex1:  if test expresssion:
                        body of if
                     else:
                        body of else
                ex2:  if test expresssion:
                        body of if
                      elseif
                         body of else if
                      else:
                        body of else
               ->while loop
               ->for loop
               ->break
               ->continue
         ->List:
               ->Create List
               ->Finding lenghth of list
               ->Add element in the list
               ->Insert element at particular position
               ->Append the list
               ->List in list (Append vs extend)
               ->delete an element in list -del vs pop vs remove
               ->Reversing the list (list.revese)
               ->Sorting a list (mynewlist=sorted(mylist),mylist.sort())
               ->Split a string to create list (mysplitlist=mystr.split(',')
               ->Indexing the lsit
               ->List slicing (listofitem[0:3])
               ->skip th eitem in a list(listofitem[::2])
               ->Extend a list using '+'
               
                        
                        
                         
              
               
              
                   
                  
           
                     

                     
                    
                    
                    
            
               
            
               
               
               
           
          
          
           
          
    
   
                
               
               
  
               
               
               
             
  
  
          
        
         
  
  
