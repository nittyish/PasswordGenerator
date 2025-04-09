🔐 Password Generator & Strength Checker

A simple yet powerful Java console-based tool designed to create secure, randomized passwords and evaluate their strength with intelligent criteria.

⸻

💡 Project Overview

This project was born out of a spark during my winter break in the second year of university, shortly after completing a course on Object-Oriented Programming with Java. Eager to apply what I’d learned, I was on the hunt for a fun and practical idea. One evening, while chatting with my dad about the importance of strong passwords for his social accounts, the concept hit me—why not build a random password generator?

Within a week, the initial version was functional. As development progressed, I added a password strength evaluation system to help users understand how secure their passwords really are. Though it worked well, I realized that the console interface might be intimidating for non-technical users. That led me to the next phase: creating a GUI version, which you can find in my Password-Services repository.

⸻

⚙️ Key Features

1. Password Generation
	•	Users are prompted with yes/no questions to include:
	•	Uppercase letters
	•	Lowercase letters
	•	Numbers
	•	Special characters
	•	Users then specify the desired length of their password.
	•	Based on the responses, a custom character pool is generated.
	•	The system randomly assembles a password from the selected pool and displays it.

2. Password Strength Evaluation
	•	The application checks for:
	•	Use of uppercase letters
	•	Use of lowercase letters
	•	Presence of digits
	•	Inclusion of symbols
	•	Minimum length of 8 characters
	•	Extended length of 16+ characters
	•	Based on these criteria, the tool assigns a strength rating (Weak, Medium, Good, Great) and gives helpful feedback.

3. Security Tips & Best Practices
	•	The console displays practical advice on creating secure passwords, such as:
	•	Avoiding reused passwords
	•	Steering clear of repetitive characters and patterns
	•	Not using common words or sequences
	•	Tips to resist brute-force and dictionary attacks
