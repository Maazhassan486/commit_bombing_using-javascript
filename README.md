
# Git Commits Bomber

**Disclaimer:**  
This tool is provided for experimental and educational purposes only. It is designed to create dummy contributions on your own GitHub profile for testing or demonstration purposes. **Do not use this tool for any malicious intent.** You are solely responsible for the effects of using this tool.

---

## Overview

The **Git Commits Bomber** is a Bash script that automates mass commits in any Git repository. It allows you to simulate a high volume of commits by modifying a file repeatedly. The script offers several modes of operation:

1. **Default Mass Commits Bombing:**  
   Appends changes to a default file (`test.txt`) and commits.
2. **Fixed File Mass Commits Bombing:**  
   Modifies a user-specified file and commits.
3. **Resetting File Mode:**  
   Overwrites a file with new content for each commit.
4. **Empty Commits:**  
   Creates empty commits using `--allow-empty`.

The resulting experiment will reflect on your GitHub profile as a history of dummy contributions.

---

## Dependencies

- **Git:** Ensure Git is installed and properly configured on your system.
- **Bash:** The script is written in Bash and should be run in an environment like Git Bash (on Windows) or any Unix-like terminal.

---

## Git Configuration

Before running the script, make sure your Git configuration is set up correctly to use your GitHub credentials:

```bash
git config --global user.email "your.email@example.com"
git config --global user.name "Your Name"
```

Replace the email and name with your actual GitHub account details.

---

## Setup & Installation

1. **Clone Your Repository (if not already cloned):**

   ```bash
   git clone https://github.com/YourUsername/YourRepository.git
   cd YourRepository
   ```

2. **Place the Script:**

   Save the `coms.sh` file (the Git Commits Bomber script) in the repository folder where you want to experiment.

3. **Make the Script Executable:**

   Open Git Bash and navigate to the directory containing `coms.sh`, then run:

   ```bash
   chmod +x coms.sh
   ```

---

## Running the Script

1. **Open Git Bash:**

   Navigate to your repository directory (for example):

   ```bash
   cd /c/Users/maazg/Desktop/github/Leetcode
   ```

2. **Execute the Script:**

   Run the script by typing:

   ```bash
   ./coms.sh
   ```

3. **Follow On-Screen Prompts:**

   - The script will display a menu with several options.
   - Enter the option number corresponding to your desired mode.
   - Follow further prompts (e.g., number of commits, filename if applicable).

4. **Push the Changes:**

   After the script finishes committing, ensure you push the changes to your remote repository:

   ```bash
   git push origin main
   ```

   **Note:** The script itself may remind you to push the changes. If not, use the above command.

---

## Important Warnings

- **Experimental Use:**  
  This tool creates a large number of commits (dummy contributions). The result of this experiment is visible on your GitHub profile.
  
- **Rewriting History:**  
  If you use this tool on a shared repository, you might disrupt the commit history. It is recommended to use it only on a personal/test repository.

- **System Impact:**  
  Running mass commits for an extended period may affect your local system performance and Git history. Use caution and consider cleaning up afterward if needed.

- **Legal & Ethical Use:**  
  The tool is for educational and testing purposes only. Do not use it to misrepresent your work or for any fraudulent activity.

---

## Contributing

Contributions to improve the script or its documentation are welcome. If you have ideas or improvements, please fork the repository and submit a pull request.

**Original Author:**  
Maaz Hassan([GitHub](https://github.com/Maazhassan486?tab=overview&from=2025-03-01&to=2025-03-27), maazhassan486@gmail.com)

---

## License

This project is distributed under the MIT License. See the [LICENSE](LICENSE) file for details.

