# SharpTokenFinder
A C# implementation of [TokenFinder](https://github.com/doredry/TokenFinder/blob/main/TokenFinder.py). Enumerates M365 Desktop Office applications for plain text authentication tokens. Parses and prints out any interesting tokens that can be leveraged to compromise the user's M365 identity.  

![image](https://github.com/HuskyHacks/SharpTokenFinder/assets/57866415/bc52695a-e1c6-418e-abf9-3d98a3c9fa43)

## Usage
Run this as a reflective assembly or compile and run the executable. Ensure your payload architecture matches the process architecture for the apps that you are trying to mine.

## Contributing
I included a set of M365 app processes and interesting token audiences for the checks, but if you have any battle-tested insights about other M365 app processes/token audiences that are exploitable, feel free to open a PR!

## More info about this technique
[![More info about this technique](https://img.youtube.com/vi/y4Ue_Es5cGA/0.jpg)](https://www.youtube.com/watch?v=y4Ue_Es5cGA)
