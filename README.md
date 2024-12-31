

def alphabets(s):
    # Create a set of all alphabet letters
    alphabet_set = set('abcdefghijklmnopqrstuvwxyz')

    # Convert the input string to lowercase and create a set of its characters
    input_set = set(s.lower())

    # Check if all alphabet letters are in the input set
    return alphabet_set.issubset(input_set)

#Test Case 1
input_string = "Two driven jocks help fax my big quiz @123"
result = alphabets(input_string)
print(result)   - True 

#Test Case 2
input_string = "Hello World!"
result = alphabets(input_string)
print(result)  - false

@mallika2807 ➜ /workspaces/skills-copilot-codespaces-vscode (mallika) $  /usr/bin/env /home/codespace/.python/current/bin/python /home/codespace/.vscode-remote/extensions/ms-python.debugpy-2024.14.0-linux-x64/bundled/libs/debugpy/adapter/../../debugpy/launcher 54617 -- /workspaces/skills-copilot-codespaces-vscode/mallika/Assignment 
True
False
@mallika2807 ➜ /workspaces/skills-copilot-codespaces-vscode (mallika) $ 
