--- Machine Learning (ML) ---

Statistics (Many friendly packages exist aka no Linear Algebra required)

	--- Type(s) ---
	
	Classification - Who is Jane? (0/1, True/False, Yes/No); Discrete {[0], 1, 2, 3,..}
	Regression - What will Jane do next? Non-Linear(non-discrete); {0.1, 2.3, 19.7,..}
	
	--- Classification (Example) ---
	
	[J][A][E][N] - 1
	[s][A][E][N] - 0
	[M][A][R][Y] - 0
	
	--- Over-fitting (Problem) ---
	
	What? : [J][A][N][E] - 1
	
	When? : When the data points themselves are the match, and not the pattern (derived characteristics (of "JANE") ie. all caps, english, mostly straight,..)
	
	How? : Caused by biased data and/or combined with a lower availability of data to collect.
		
	Solution : Can be solved by simply diversifying the data (selecting all the subgroups from a group (rather than only observing the group itself),
		and collecting more data (including more groups).
		
		(Example): Where is Waldo?
			Continents (group) <- Countries (subgroups) <- states/provinces (sub-subgroups) <-- (collect data from these)
	
	Python packages (scikit-learn, numpy, pandas)
		
--- Artificial Intelligence (AI) ---

Statistics, Linear Algebra (the _[E-word]_-vector obsession)

	--- Neural Network ---
	
	What? : Modeled after the human eye in its processing of what it sees, where layers of probabilities are stacked for a final determination, 
	  	also where each data point is a probability (like in Quantum Theory where "every thing is a probability.")
	
	When? : Use when you want to make predictions, or when you want to determine something that is very hard to determine/distinguish (amongst the rest..)
	
		(Example): 
			- When will it rain next?
			- Reading doctor's handwriting.
	
	How? : Same applies here to AI as does with ML on the data collection side. 
		AI tools like Tensorflow, used with a cloud-based infrastructure (Google GCP, Microsoft Azure, Amazon AWS)
	

--- Programming Languages ---

	--- Popular Types ---
	
	- Object Oriented Programming (OOP) - 
 		- Class (blueprint)
   		- Object (house)
   		- Attributes (address, shade, sqft)
     		- Behavior (smart house (functions))
       		- Constructor (the builder)

  		*The three "pillars" of OOP [code] - 
    			- Inheritance (recycle, reduce, reuse)
       			- Encapsulation (need to know basis)
	  			- Polymorphism (versatility))
	
		Java, Scala, Python
	
	- Functional - Called "stateless", where no information is stored (as opposed to info. being stored as "states" that are snapshots of data in memory).
	
		Java 8+, Scala (Lambda style ""functional"" programming, but in style only, else recursion would not be possible.); Lisp
		
		Con(s) : Recursion is not possible.
		
		(Example): 
			# info. is stored into 'x' and 'y'.
			x = 3
			y = f(x+1)
			
			# info. is passed down from function [to function].
			f(x+1)
			
			# or with a function 'g()' standing in for f(x+1).
			f(g(3))
	
	--- Languages ---
	
	The Python programming language is very easy to learn (intuitive to the learner), and has an enormous number & variety of packages to choose from (the "swiss army knife").
		Con(s) : No true parallelism. Only fine-tuning towards asynchronous can help make faster.
		
	**Scala** - Like Java but less/more wordy (for an example of wordy - org.apache.."RefreshAuthorizationPolicyProtocolServerSideTranslatorPB").
 		An even High(er) level language); Programmability is simplified(towards) / abstracted(away)
		Con(s) : Lesser amount of user documentation; mainly just the Scala API documents itself.
		
	**Java** - Like Scala but with all the documentation user and official. Best way to learn OOP or Map Reduce (a programming model used in ML).
		Con(s) : Not as exciting as Scala.
		
	**Go** - No true parallelism?
		Con(s) : Relatively new language on the scene. Not exactly a recommended language for those who just want to learn.
