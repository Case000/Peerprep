# Peerprep
Technical interview preparation platform and peer  matching system

User Story
A student who is keen to prepare for their technical interviews visits the site. They create
an account and then log in. After logging in, the student selects the question difficulty level
(easy, medium, or hard) and a topic they wants to attempt today. The student then waits 
until they are matched with another online student who has selected the same difficulty 
level as them. If they are not successfully matched after a specific duration, they time out. 
If they are successfully matched, the student is provided with the question and a 
collaborative space to develop their solution in real-time, allowing both the student and 
their matched peer to collaborate on the provided question. The application should allow 
the users to terminate the collaborative session gracefully.

The following are the must-have features (labeled Mx) of PeerPrep.
• M1: User Service – responsible for user profile management.
• M2: Matching Service – responsible for matching users based on some criteria (e.g., difficulty level 
of questions, topics, proficiency level of the users, etc.) This service can potentially be developed 
by offering multiple matching criteria.
• M3: Question service – responsible for maintaining a question repository indexed by difficulty 
level (and any other indexing criteria – e.g., specific topics).
• M4: Collaboration service – provides the mechanism for real-time collaboration (e.g., concurrent 
code editing) between the authenticated and matched users in the collaborative space.
• M5: Basic UI for user interaction – to access the app that you develop.
• M6: Deploying the application on your local machine (e.g., laptop) using a native technology stack.
• M7: Perform basic unit/integration testing (automated) demonstrating the effective use of CI in 
the development process
The following are the nice-to-have features (labeled Nx) of PeerPrep
• N1: Communication: Implement a mechanism to facilitate communication among the participants
in the collaborative space (other than the shared workspace) e.g., text-based chat service and/or
video (+voice) calling service.
• N2: History: Maintain a record of the questions attempted by the user e.g., maintain a list of
questions attempted along with the date-time of attempt, the attempt itself and/or suggested
solutions.
• N3: Code execution: Implement a mechanism to execute attempted solution/code in a sandboxed
environment, and retrieve+present the results in the collaborative workspace.
• N4: Enhance collaboration service by providing an improved code editor with code formatting,
syntax highlighting for one language, syntax highlighting for multiple languages.
• N5: Enhance collaboration service by providing code translation from one language to another
(e.g., JS to Python) depending on the preference of the users. (I.e., user 1 prefers python, user 2
prefers JS, provide a mechanism to translate code to the preferred language of each of the users)
• N6: Incorporate generative AI to assist during the preparation. For example, users can seek help
from ChatGPT, Copilot (or such other services) to seek explanation of code written by the other
participant. Users can seek help from gen AI to solve the puzzle by providing prompts from within
the interface.
• N7: Deploy the app on a (local) staging environment (e.g., Docker-based, Docker + Kubernetes).
• N8: Scalability – the deployed application should demonstrate easy scalability of some form. An
example would be using a Kubernetes horizontal pod auto-scaler to scale up the number of
application pods when there is a high load.
