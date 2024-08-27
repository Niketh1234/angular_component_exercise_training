# Angular Assignment - Keep	Level 1
	
## Objective:	
	
The Objective of this application is to understand the fundamentals of Angular.	
	
## Expected Outcome:	
	
By the end of the assignment you should be able to understand	
	
1.  Modules  
2.  Components	
4.  Data Binding	
5.  Dependency Injection	
6.  Services  

## Prerequisites

1. Fork this boilerplate repository  
2. Clone the boilerplate repository and cd into it  
	
## Assignment:	
	
Create a Angular Application similar to Google Keep with the following specs.	
 
## Instructions:

1. You are expected to use `Note` class for Note model  
2. `AppModule` shall be the root module  
3. `HeaderComponent` to use Material Toolbar with text content `Keep`  
4. `AppComponent` as the bootstrapping component  
	4.1 To have a Bootstrap Accordion compoent with header title `Take a note`  
	4.2 Accordion to include an `input` Form Control with name attribute `title` for taking `title` for the note   
	4.3 Accordion to include a `textarea` Form Control with name attribute `text` for taking `text` for the note  
	4.4 Accordion to include a button with text `Done` to add and persist the note in the Notes Array.   
5. `NotesService` stores the Notes To Array<Note>   -  
	5.1 `getNotes()` to fetch the notes collection  
	5.2 `addNote()` to persist a note to Notes Array  
6. In case you have implemented this -> `json-server should host and serve angular application and notes api `, please add the necessary steps to run the application in this same file.  


## Submitting your solution for preliminary  review  
1. Push the code to gitlab repository. 

## MENTORS TO BEGIN REVIEW YOUR WORK ONLY AFTER ->

- You add the respective Mentor as a Reporter/Master into your Assignment Repository
 

- Intimate your Mentor on Slack  - with your Git URL - Once you are done working and are ready for final submission.



## References:	
	
1.  Google Keep	
2.  [Angular Architecture](https://angular.io/guide/architecture)
3.  [Angular CLI](https://cli.angular.io/)	
4.  [Angular Templates](https://angular.io/guide/architecture#templates)	
5.  [Angular Data Binding](https://angular.io/guide/architecture#data-binding)	

