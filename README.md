
# 🧠 Street Fighter II AI Bot

This project integrates a trained AI model with the **Street Fighter II UMC** ROM using the **EmuHawk** emulator. The AI autonomously plays the game by simulating keyboard inputs through a custom controller.

## ✅ Requirements

Before running the project, make sure you have Python installed and the following libraries:

```bash
pip install numpy tensorflow pandas keyboard
```

---

## 🚀 How to Run the Project
Firstly merge the files in single-player and single-player_2 into single single-player folder
### 1. Launch the Emulator
- goto aiprojectwo->AI Project->gamebot-competition-master

- Go to the `Single Player` folder.
- Run the file: `emuhawk.exe`.
-the extra work folder contains all the work that wos done to trainn and test the model

### 2. Load the Game ROM

- In EmuHawk, open the `File` dropdown.
- Click `Open ROM`.
- Select the ROM file: `Street Fighter II UMC.smc`.

### 3. Open the Toolbox

- Go to the `Tools` dropdown in EmuHawk.
- Select `Toolbox`.
- Leave the toolbox window open.

### 4. Start the AI Controller

- Open Command Prompt (CMD) in the `Python API` folder.
- Run the following command:

```bash
python controller.py 1
```

> ⚠️ Leave this terminal open and running.

### 5. Start the Game

- Return to EmuHawk.
- Select `Normal` mode.
- Choose **any character**.

### 6. Activate the AI Bot

- Once the match begins:
  - In the Toolbox window, click the **second icon in the first row** (labelled **Gyroscope Bot**).
  
✅ Your AI bot will now take over and play the game.



## 🔁 Repeating the Process

After each round or match:

1. Close EmuHawk.
2. Repeat steps from **Step 1** to restart the game and re-enable the bot.



## 🤖 About the AI

The AI model was trained using TensorFlow and simulates inputs through the emulator using keyboard events. The bot analyzes the game state and responds in real time.



## 📌 Notes

- The ROM and emulator should remain unchanged.
- Make sure no other program is blocking keyboard events.
- Works best with stable frame rates in the emulator.
