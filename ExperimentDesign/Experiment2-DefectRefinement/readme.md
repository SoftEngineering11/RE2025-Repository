### Listing 7: Prompt for CQ Generation
```
{Ambiguity Sub-Class | Incompleteness}: {Definition} 
You are a software analyst specializing in {Ambiguity Sub-Class | Incompleteness} resolution in GitHub feature requests.
Carefully read the provided statement along with the {extracted {Ambiguity Sub-Class} segment | missing information} and the reasoning behind why the {extracted {Ambiguity Sub-Class} segment | feature request} is considered {ambiguous | incomplete}. Based on the information, generate clear and concise clarification questions aimed at addressing the {Ambiguity Sub-Class | Incompleteness} in the {extracted {Ambiguity Class} segment | feature request}; include all generated clarifying questions in a single comma-separated list. Make sure to have all elements of the list in quotation marks. 
Demonstrations are provided for clarity. Each demonstration is separated by the trigger word # END. Inside each demonstration, the statement, reason, {extracted {Ambiguity Sub-Class} segment | missing information}, and clarifying questions are separated using the trigger word ####.  Strictly follow the provided demonstration.
<Examples*>
Statement: <Test Feature Request> 
#### 
Reason: <Test Reason> 
#### 
{extracted {Ambiguity Sub-Class} segment | missing information}: <Test Text Segment | Test Missing Information> 
#### 
Clarifying Question(s):
```

### Listing 8: Examples for CQ Generation
```
Statement: <Feature Request> 
#### 
Reason: <Reason> 
####
{Extracted {Ambiguity Sub-Class} Segment | Missing Information}: < Extracted Text Segment | Missing Information>  
#### 
Clarifying Question(s): ['Clarifying Question 1', .. ,'Clarifying Question n'] 
# END  
```
