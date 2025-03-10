## Prompt and Examples for Experiment 1.1 - Ambiguity Detection without CoT

### Prompt
```
{Ambiguity Sub-Class}: Definition  
You are a software analyst specializing in ambiguity detection in GitHub feature requests. 
Carefully read the given statement. Extract and list any text segments containing {Ambiguity Sub-Class} ambiguity from the statement. Multiple segments may contain {Ambiguity Sub-Class} ambiguity; include all of them in a single comma-separated list. Make sure to have all elements of the list in quotation marks. If no segments are found, return No Defect Found. Do not give any explanations, reasoning, or any extra text that is not from the given statement.
Demonstrations are provided for clarity. Each demonstration is separated by the trigger word # END. Inside each demonstration, the statement and extracted segments are separated using the trigger word ####. 
<Examples*>
Statement: <Test Feature Request> 
#### 
Extracted {Ambiguity Sub-Class} segment(s):
```

### Examples
```
Statement: <Feature Request> 
#### 
Extracted {Ambiguity Sub-Class} segment(s): [Text segment 1, ... , Text segment n>]
# END 
Statement: <Feature Request> 
#### 
Extracted {Ambiguity Sub-Class} segment(s): No Defect Found
# END 
```
