# BASH SCRIPT ASSIGNMENT

# question 1
1 process

# question 2
    ````
     
    #this script shows the  date time
    # logged in users
    # sytmem uptime
    # usage

      date > logfile.txt
    users >> logfile.txt
    uptime -p>> logfile.txt

    cat logfile.txt
    
        
  
    
    
# question 3
touch empty.txt
# question 4
 mkdir -p Work mini-project RNA-Seq
 # question 5
mv seqs.txt sequences.fasta - no effect
# question 6
 echo hello world > universal_greetings.txt
 # question 7
 echo hello world > "universal greetings.txt"
 # question 8
 done
 # question 9
 10281 lines

grep ">" test.fa | wc -l  100sequences
# question 10

 grep ">" test.fa > identifiers.txt
 # question 11
 sed s/A/a/g test.fa
 # question 12
setterm -linewrap off
# question 13
     grep -v PREDICTED: identifiers.txt > notpredicted.txt
        grep  PREDICTED: identifiers.txt > predicted.txt
        cut -d ' ' -f 2,3 notpredicted.txt > species.txt
        cut -d ' ' -f 3,4 predicted.txt >> species.txt
        cut -d ' ' -f 2 species.txt > sname.txt

          
# question 14
sort | uniq -c sname.txt

# question 15 

    #this scripts count intergers from 1 to 30 in different lines

    n=1
    while [ $n -le 30 ]
    do
    echo "$n"
     n=$((n+1))

    done
    

    
    
    
 # question16
 $ touch trial{1..20}.data
 # question 17
  it throws an error saying- expr: division by zero because any number divided by 0 is undefined
  # question 18
 command 2> error.txt 1> output.txt


    

 # question 19
    # this script ask the user to input their name
    # greets the user
    # tells the user what day and time it is.

    echo " what is your name?"
     
    read  varname
    
    echo Good evening? $varname

    echo it is now
    date +%T
    echo on this lovely  day of
    date +%e
    date +%B
    date +%Y  
    

# question 20
cd ../../Fun_stuff/


