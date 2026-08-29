# SE-Workflow
Project Name: PC Build Management System (FixMyRig)	Test Designed by: Tahmina Akhter
Test Case ID: TC_HELP_01	Test Designed date:  7/6/2026
Test Priority (Low, Medium, High): Medium	Test Executed by:ESHTIAK FERDOUS MAHI
Module Name:  Help & Support	Test Execution date: 27/8/2026
Test Title: Verify Browse Help navigation and topic selection	 
Description: Test whether the user can open Browse Help and access a PC-building help topic.	 
Precondition: The FixMyRig website and Help & Support page are available.
Dependencies: Help & Support and Browse Help pages must be properly connected in the prototype/website.
Test Steps	Test Data	Expected Results	Actual Results	Status (Pass/Fail)
·  Open the FixMyRig website. 
·  Navigate to HELP & SUPPORT. 
·  Click the BROWSE HELP button. 
·  Verify that the Browse Help page opens. 
·  Select a help category such as Compatibility. 
·  Observe the corresponding help information.
	Button:
BROWSE HELP

Selected Topic:
Compatibility	The Browse Help page should open successfully, and selecting Compatibility should take the user to the relevant compatibility help information.	The Browse Help page opens and the selected help topic is displayed.	Pass


Figma Design:
https://www.figma.com/design/qq77IMwKCI26GfBs0PSMh9/Help-Desk?m=auto&t=Ozv78XmyMKWJREQC-1

Test Case ID: TC_CHATBOT_01	Test Designed date: 7/6/2026
Test Priority (Low, Medium, High):  High	Test Executed by: ESHTIAK FERDOUS MAHI
Module Name: AI Chatbot	Test Execution date: 27/8/2026
Test Title: Verify chat-bot provides PC-building assistance	 
 Description:Test whether the AI chat-bot accepts a user's PC-building question and provides a relevant response.
Precondition:The FixMyRig website is open and the AI Assistant/chat-bot is available.
Dependencies: AI service/Google AI connection must be available.
Test Steps	Test Data	Expected Results	Actual Results	Status (Pass/Fail)
·  Open the FixMyRig website. 
·  Click the Help/AI Assistant icon. 
·  Open the chatbot interface. 
·  Enter a PC-building question. 
·  Click Send. 
·  Observe the chatbot response.
	User Question:
"What GPU is suitable for a gaming PC?"	The chat-bot should receive the question and provide a relevant response related to selecting a GPU for a gaming PC.	The chatbot provides a response to the user's question.
	Pass.

Figma Design:
  https://www.figma.com/design/FdnrrkZPAMtbo0atc3DqI0/FixMyRig-AI-Chatbot?node-id=0-1&t=TCcWET3MnPB9u05J-1

