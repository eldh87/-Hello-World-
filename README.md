# -Hello-World-
A simple Hello World Python script.
# Navigate to your working directory
cd path/to/your/folder

# Create a new repository folder
mkdir hello-world && cd hello-world

# Initialize Git
git init

# Create the hello.py script
echo 'print("Hello, World!")' > hello.py

# Add the script to Git
git add hello.py

# Commit the changes
git commit -m "Added basic Hello World script"

# Connect to the GitHub repository (replace with your repo URL)
git remote add origin https://github.com/your-username/hello-world.git

# Set the default branch to main
git branch -M main

# Push the code to GitHub
git push -u origin main
