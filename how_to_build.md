## This page describes how a FRAM model is built, and how it can be used for either event analysis or risk asssessment

### Method-sine-model
The FRAM is a method-sine-model rather than a model-cum-method. The use of the FRAM therefore involves two stages. The first is using the FRAM to develop a model of the activity (process or performance) that is the focus of the analysis. The second is to use the model to create instantiations of the activity (or performance) and then to analyse these.

### Breadth first
In developing the model or representation of the activity (process or performance) that is the focus of the analysis, the guiding principle is breadth-first – or breadth-before-depth. This means that it is more important to develop a representation and an understanding of the situation as a whole, than to search for detailed causes.

The ‘breadth-first’ principle is consistent with the philosophy of the FRAM, namely that the understanding of the everyday functioning of a system (the breadth) is the necessary basis for understanding a specific development – actual or hypothetical (the depth). In the case of an event investigation, the purpose of the FRAM is not to determine what went wrong, but to understand what did not go right. The starting point must therefore be a description and understanding of what happens in everyday situaitons, when nothing goes wrong. In the case of a risk assessment, the purpose of the FRAM is to understand how combinations of everyday performance variability may lead to unexpected (and usually unwanted) outcomes, rather than to trace the possible propagation of a failure or a malfunction.

In consequence of the 'breadth-first' principle, the purpose of the first iteration of the model development is to identify all the functions that are part of the activity, rather than to go into - or get lost in - a description of details.

The 'logic' of the analysis is as follows:
1. Describe the event, using either an existing description (for instance an event report), a future scenario (for instance a safety case), a proposed change (design specifications, functional specifications) or any other available material.
2. Try to describe what should happen (meaning work-as-done, not work-as-imagined). This will require data from the daily work place, from people who have expert knowledge about the activity, rather than (post mortem) data from an accident investigation. The description is basically the set of functions that are required for everyday performance to succeed. (See more under 'Finding what goes right'.)
3. The outcome of Step 2 is the FRAM model. This is the basis for characterising the expected (potential) variability of the activity as carried out in the everyday work environment. (Notice the desparate attempts to avoid the word 'normal'.) The characterisation of this variability also provides the basis for describing the potential couplings.
4. Use more specific information (e.g., an event or accident analysis, or a safety case scenario) to propose one or more instantiations of the model.
5. Analyse these instantiations, either to find an explanation why something happened, or a plausible scenario of what may happen (as in risk assessment).

Step 2 is where the FRAM differs from a traditional accident investigation. The purpose of using the FRAM is to develop an understanding of the everyday situation and its variability, as a basis for understanding what went wrong (if it did), rather than to go directly for the 'root' cause.

### Developing a FRAM model: Identifying the functions
The first step is to identify the functions that are required for everyday performance to succeed, i.e., the functions without which the system could not fulfill its purpose. The breadth-first principle means that it is more important to identify all the functions than to describe some – or all – of them in great detail. Details can always be added – or removed – later.

It is in principle possible to begin by any function, since the method ensures that all relevant functions will be found – as long as the method is used consistently. Having said that, it may often be useful to begin by a function – or a small set of functions – that is seen as essential for the purpose of the analysis.

**A useful way of doing that is to consider how the activity usually is carried out, i.e., everyday performance. For any existing activity there is usually plenty of information about that, which can be obtained either by noticing what happens or by interviewing the people who do the work. For a non-existing activity, i.e., a future scenario or work situation, the information can be found in the design specifications.**

The next step is for every function to describe the aspects that are essential for the function to be carried out. The simplest way to do that is to start with the Input(s) and the Output(s). This is where it is important to remember the breadth-first principle. Do not attempt to describe every aspect, and do not attempt to account for everything that may relate to an aspect. Limit the description to aspects that the analysis team agrees are important. It may be practical to introduce the power of a veto, in the sense that any member of the team can veto a proposal for an aspect. This also helps to maintain the focus on breadth, and avoids the temptation to go into too much detail at the start.

**This description can be made using the FRAM Model Visualiser (FMV), which combines a textual and graphical representation of FRAM functions.**

In order for a FRAM model to be complete, each aspect that has been described must have a relation to another function. Thus if a function has an Output (as is usually the case), then this Output must exist as an aspect of another function – as either Input, Precondition, Resource, Control, or Time. Conversely, if a functions has an aspect described for either Input, Precondition, Resource, Control, or Time, then this aspect must be the Output of another function. The basic rule is that aspects do not appear out of nowhere and do not disappear into nowhere.

**This check is built into the FMV, and performed automatically. Aspects that are incompletely defined are marked with a red ring in the graphical representation, and with a red highlighting in the text editor.**

This rule ensures that all the necessary functions will be defined. In keeping with the breadth-first principle it may be sufficient at first to introduce these derived functions as ‘dummy’ functions, i.e., as placeholders for aspects that are part of the description of other functions. This could either be as the receiver (or sink) of an Output, but without describing any other aspects of this ‘receiver’ function. Such a ‘dummy’ function in practice defines where the analysis stops, i.e., it marks the boundary of the analysis. In case a function is needed as a source, i.e., to generate an Output that is used as an Input, Precondition, Resource, Control, or Time of another function, this ‘source’ may also initially be described as a ‘dummy’ function without any further details.

In the FRAM terminology, such 'dummy' functions are typically background functions (q.v.).

**This check rule ensures that the resulting FRAM model is complete, in the sense that all aspects are accounted for. The check rule enforces the breadth-first principle and avoids the analysis from getting lost in depth. The resulting model is, of course, not the final description of the activity (or performance), but merely a first iteration.**

### Developing a FRAM model: Describing the potential variability
A number of iterations may be necessary to develop an acceptable FRAM model of an activity. But in the end a model will have been produced which accounts for the everyday functioning or performance that is the necessary basis for understanding a specific development. The analysis of this development constitutes the second part of the method. This analysis can either refer to something that has happened, or a hypothetical future situation. In either case the purpose of the analysis is to characterise the potential variability of each functions.

It is not strictly necessary to characterise the potential variabillity for designated background functions, since these - by definition - do not vary for the type of work being considered.

### The following steps
Although the basic procedure is the same regardless of whether the analysis is retrospective or prospective, it nevertheless makes sense to describe the second part of the method for each purpose separately. There are three main purposes for which a FRAM model can be used:
- Using a FRAM model for retrospective analysis
- Using a FRAM model for prospective analysis
- Using a FRAM model as the basis for system design/redesign

A more extensive discussion of its use is set out in the manual available here