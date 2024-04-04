# Augmented Reality Tool
https://augmented-reality-tool.incisive.iti.gr/

# Requirements
POSIX Shell & Utilities
Git
Docker

# Download
git clone https://github.com/XaralampidisBasilis/augmented-reality-tool.git $HOME/github.com/XaralampidisBasilis/augmented-reality-tool
cd $HOME/github.com/XaralampidisBasilis/augmented-reality-tool/

# Development
cd docs/ && make clean check all && cd ..

# Staging
cd docs/ && make STAGING=1

# Usage
augmented-reality-tool README