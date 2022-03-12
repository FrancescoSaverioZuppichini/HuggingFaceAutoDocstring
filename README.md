# HuggingFaceAutoDocstring 🤗💅

[mustache](https://github.com/janl/mustache.js/) file to use [vscode autodocstring extension](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) with [hugging face docstyle](https://github.com/huggingface/transformers/tree/master/docs#writing-documentation---specification)

## Usage

1. Install [autodocstring]((https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)) in vscode.

2. Download [`hugginface.mustache`](https://raw.githubusercontent.com/FrancescoSaverioZuppichini/HuggingFaceAutoDocstring/main/hugginface.mustache)

  ```
  wget https://raw.githubusercontent.com/FrancescoSaverioZuppichini/HuggingFaceAutoDocstring/main/hugginface.mustache
  ```
3. Update vscode settings
  1. go to vscode settings
  2. search for `autodocstring`
  3. copy the path `hugginface.mustache` to in the *Auto Docstring: Custom Template Path* input bar
  ![img][1.png]
  
