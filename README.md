# Freshworks-
Assignment : Merge Json objects and Movie Wiki Application


<-----> THE MERGE JSON FILE WAS BUILT USING THE NETBEANS IDE <----->

TO EXECUTE THE PROJECT :
  The main function is in the folder "src/com/freshworks/Client/Test.java"
  
ALOGITHM :
  LOGIC : TO RETREIVE THE INPUT FILES FROM THE FOLDER AND MERGE
          
          //INITIAL SETUP 
                
                STEP1 : CREATE A OUTPUT FILE
                STEP2 : COPY THE FIRST FILE CONTENT TO THE OUTPUT FILE
                STEP3 : INCREMENT THE INPUTSUFFIX
        
           //LOOPING 
                WHILE ( THE NO OF INPUT FILES IN THE FOLDER)
                    DO
                        IF (INPUT_FILE_SIZE + OUTPUT_FILE_SIZE  <  MAX_FILE_SIZE) 
                           MERGE(INPUT_FILE,OUTPUT_FILE)
                        ELSE
                            INCREMENT THE OUTPUT SUFFIX
                            GENERATE THE NEW OUTPUT FILE 
                            COPY THE CURRENT INPUT_FILE TO NEWLY CREATED OUTPUT FILE
                            INCREMENT THE INPUT SUFFIX
                            MERGE(INPUT_FILE,OUTPUT_FILE)
                    INCREMENT THE INPUTSUFFIX
                END WHILE
  
  
  LOGIC : MERGE JSON OBJECTS
             
             STEP1 : CREATE A NEW JSON OBJECT TO STORE THE RESULT OF MERGE
             STEP2 : COPY JSON1 TO MERGED JSON
             STEP3 : LOOPING 
     
                    LOOP (UNTIL THERE ARE ANY KEY IN THE JSON2 OBJECT)
                    COPY THE KEY VALUES TO THE STRING
                    CONVERT THE STRING TO JSONARRAY OBJECT
                          LOOP(UNTIL THERE ARE ANY OBJECTS IN THE JSONARRAY)
                                APPEND THE OBJECT THE MERGED_JSON OBJECT
                          END LOOP
                    END LOOP
  
  
  
  ALGORITHM COMPLEXITY : 
  
  BEST CASE : O(n2)
  AVERAGE CASE : O(n2)
  WORST CASE : O(n2)
  
