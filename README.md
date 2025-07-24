# Email-ID-Validation
This project is a simple Python-based email validation tool that checks whether a given email ID is valid or not, based on commonly accepted email format rules. It uses basic string operations (for, if, input) without any external libraries or regular expressions — making it beginner-friendly and educational.

#✨ Features
Here are the key features of the project:

✅ Minimum Length Check: Ensures the email is at least 6 characters long.

🔠 Starting Character Validation: Checks that the email starts with a letter (not a digit or symbol).

🐵 Single '@' Symbol: Validates that exactly one @ symbol is present in the email.

🟣 Dot (.) Position Validation: Confirms that a dot (.) exists either 3rd or 4th character from the end (e.g., .com, .in).

🚫 No Spaces Allowed: The email must not contain any blank spaces.

🔐 Allowed Characters Only: The script allows only: Alphabets (a–z or A–Z), Digits (0–9), Symbols: _, ., and @

⚠️ Invalid Character Handling: Flags any unexpected characters and marks the email as invalid.

💡 Beginner-Friendly Logic: Uses simple if, for, and string methods like .isalpha(), .isdigit(), .isspace() to keep it easy to understand.

🖥️ Terminal-Based Interface: Fully functional in any command-line or terminal window.

🧪 Interactive Testing: Prompts user for input and instantly gives feedback on email validity.
