# VSCode Utilities
1. **White background when using Julia plots in VSCode.**
    - Install [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css).
    - Add the following to your `settings.json` file:
     ```json
     "vscode_custom_css.imports": [
         "https://raw.githubusercontent.com/mossr/vscode-utils/main/plots.css"
      ],
     ```
     ![image](https://user-images.githubusercontent.com/1592413/172889608-375a76e2-92ce-4f5f-bc9b-efe31d204ce0.png)
