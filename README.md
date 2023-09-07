# UiPath_OpenAI_Integration
Integrating OpenAI with UiPath Automation Robot that works on Custom DataSet.

This is to integrate Generative AI capabalities to a Automation Robot developed using UiPath. This Automation makes a call to a function: AnalyzeDataset in a external Python Script file and returns the response back to the UiPath Workflow.

This code was initially developed in a transitional way when there was no in-built activity available in UiPath. The latest versions of UiPath do have a activity for this however this has it's own limitations. If you need to run the OpenAI APIs in UiPath on your own dataset i.e. Custom Dataset you can achive this by integrating Python Script in UiPath Workflows.

In UiPath Workflow: I have created a Attend Bot with simple interface to demonstrate & to enter user queries and capture the response and display the same. The same can also be implemented as a Unattened Bot as well depending on your requirements.

Before executing this Workflow, you need to install Python and all the libs required and update the Path accordingly. Calling the Python Script is done with UiPath's Python Scope Activity in this example however there are other ways to execute the same.

By integrating Python Scripts we can build automation that works on LLMs, NLP Models etc... in a bit accelerated development time line and can achive faster search/query time on quering a large data volumns.

If you have any queries or suggestion please write to me and I would be much more happier to colabarate with you on any other projects or activities.
