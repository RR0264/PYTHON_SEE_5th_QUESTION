# PYTHON_SEE_5th_QUESTION
Program is given in debug_exam.py and Instructions are given in ReadMe file.
# Fork the repository and commit the changes.
# Answers should be given for all three questions here.
5a
if k in data1:
            v1 = data1[k]
        if v1 != v2:
            dupKeys[k] = [v1, v2]
            del data1[k]
        else:
            data1[k] = v2
    return dupKeys
    
 5b
 def uniqueUpdate(data1, data2):
  dupKeys = {}
        for [k, v2] in data2:
         if k in data1:
            v1 = data1[k] 
            if v1 != v2:           
                dupKeys[k] = [v1, v2] 
                del data1[k]
        else:  
            data1[k] = v
    return dupKeys
    
    
    5c
    test case 1:
    4
    1 2
    3 3
    3 8
    4 9
    
    2
    3 3
    4 4
    
    test case 2:
    the test case written in 5a, which breaks the initially written code can be written.
    
