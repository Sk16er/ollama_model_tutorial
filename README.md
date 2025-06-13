# To use Any [ollama](https://ollama.com) model locally or in [github codespace](https://github.com/features/codespaces)[!](https://ollama.com/shushank)
## So First see how to use ollama model using the github codespaace.
## STEPS
- Fist make you account on [github](https://github.com).
- and then go to this [repposotry](https://github.com/Sk16er/ollama_model_tutorial)
- Then fork this reppoby clicking on this ![image](https://github.com/user-attachments/assets/69e8d287-850d-4651-8baa-fb7cb3fb2780)

- Then name this anything you wanted.![image](https://github.com/user-attachments/assets/f5cc5540-432b-47d7-bba9-4bbd598e0912)
- Then create fork
- Then create a Codespace there ![image](https://github.com/user-attachments/assets/4b0f0dc1-6415-4b07-be12-da712d942969)
-  - by clicking on code (That green button)
   - Then on codespace
   - Then create codespace at main.
 
-  It will took a while but wait, then in the bash in the bottom. enter these comand's. (If that is not active press `ctrl + Shift + ~ ` )
-  Then it will show there
-   - in that enter this command
``` bash
curl -fsSL https://ollama.com/install.sh | sh
```
- then it will download ollama.
- in that same enter
``` bash
ollama serve
```
- Then open a another bash by a + button on the top of that terminal And enter.
``` bash
ollama run shushank/vero
```
- This will pull that model and then wait a minute and you are ready to go. 


