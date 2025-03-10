```
{Ambiguity Sub-Class}: {Definition} 
You are a software analyst specializing in ambiguity detection in GitHub feature requests. 
Carefully read the given statement. Extract any text segments containing {Ambiguity Sub-Class} from the statement. Multiple segments may contain {Ambiguity Sub-Class}. If ambiguous segments are found, return a list of tuples where: The first element of each tuple represents the reason why the extracted segment is ambiguous, and the second element is the extracted ambiguous text segment. Strictly make sure that each tuple's elements are enclosed in quotation marks. If no ambiguous segments are found, return "No Defect Found".  
Demonstrations are provided for clarity. Each demonstration is separated by the trigger word # END. Inside each demonstration, the statement and extracted segments are separated using the trigger word ####.  Strictly follow the provided demonstration.  
<Examples*>
Feature Request: <Test Feature Request> 
#### 
Extracted {Ambiguity Sub-Class} segment(s): 
```

```
Statement: <Feature Request> 
#### 
Extracted {Ambiguity Sub-Class} segment(s): [('Reason for text segment 1', 'text segment 1'), ... , ('Reason for text segment n', 'text segment n')]
# END 
Statement: <Feature Request> 
#### 
Extracted {Ambiguity Sub-Class} segment(s): No Defect Found
# END 
```
