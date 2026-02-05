Phase 1: Environment Setup
Creating the workspace: Use mkdir Question1 to generate a dedicated folder for this task.

Navigating to the folder: Use cd Question1 to move inside the newly created directory.

Phase 2: Script Development & Preparation
Writing the script: Launch the nano editor with nano analyze.sh to write the logic for your file and directory analyzer.

Enabling execution: Run chmod +x analyze.sh to modify the file permissions, allowing the system to run the script as a program.

Generating test data: Create a dummy file named sample.txt using nano to provide the script with initial data to process.

Phase 3: Execution & Testing
Testing file analysis: Execute ./analyze.sh sample.txt. The script identifies the input as a file and utilizes the wc utility to report line, word, and character counts.

Preparing directory tests: * Build a new folder called testdir via mkdir.

Use the touch command to populate that folder with a mix of items (e.g., a.txt, b.txt, and image.png) to test the script's filtering capabilities.

Testing directory analysis: Run ./analyze.sh testdir. The script recognizes the input is a directory and outputs the total file count alongside the specific count of .txt files.

Validation of error handling: Run ./analyze.sh without any parameters. This confirms the script correctly identifies missing inputs and triggers an "invalid argument" warning.
