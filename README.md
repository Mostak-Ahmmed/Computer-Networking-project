# Operating System Algorithm Simulator Using Shell Script

This project simulates various Operating System services through a shell script, allowing users to explore and understand fundamental algorithms in OS concepts. It features simulations of CPU Scheduling Algorithms, Page Replacement Algorithms, and Contiguous Memory Allocation Algorithms.

## Authors
- **Md. Rabby Khan** (ID: 213902037)
- **Mostak Ahmmed** (ID: 213902126)

## Features
The shell script provides the following options:

### Main Menu:
1. **CPU Scheduling Algorithms**
2. **Page Replacement Algorithms**
3. **Contiguous Memory Allocation Algorithms**
4. **Exit**

### CPU Scheduling Algorithms
This module offers simulations for popular CPU scheduling algorithms:
1. **Priority Scheduling**
2. **Shortest Job First (SJF) Scheduling**
3. **First-Come, First-Served (FCFS) Scheduling**
4. **Show Best Algorithm** - Compares the algorithms based on average waiting time and turnaround time to determine the most efficient one.
5. **Exit**

### Usage Instructions
1. Clone the repository or download the script.
2. Run the script in a Unix-based terminal using:
   ```bash
   chmod +x script_name.sh
   ./script_name.sh
   ```
3. Navigate through the menu options by entering the corresponding number for the desired feature.

### Requirements
- A Unix-based operating system (Linux, macOS, etc.)
- Basic knowledge of shell scripting to modify or extend the script as needed.

### Example Commands
- To start simulating CPU scheduling, select option **1** from the main menu and follow the subsequent prompts.
- To explore memory allocation techniques, choose option **3**.

### Notes
- The "Show Best Algorithm" feature uses metrics such as average waiting time and average turnaround time to rank the scheduling algorithms.
- Ensure all necessary permissions are granted to execute the script.

### Future Enhancements
- Add more CPU scheduling algorithms (e.g., Round Robin Scheduling).
- Implement visual representations of simulations.
- Include more memory allocation strategies.

### ClientFormController in Java Chat Application
This Java class, `ClientFormController`, is part of a chat application built using JavaFX. The code manages the client-side user interface and interaction with the server. Below is a breakdown of its components and functionality:

#### Components
1. **JavaFX Components:**
   - **AnchorPane (pane):** A layout container.
   - **ScrollPane (scrollPain):** A scrollable area that contains the chat messages.
   - **VBox (vBox):** A vertical box layout to hold chat messages.
   - **JFXTextField (txtMsg):** A text field for the user to input messages.
   - **Text (txtLabel):** A label to display the client’s name.
   - **JFXButton (emojiButton):** A button to open the emoji picker.

2. **Networking Components:**
   - **Socket (socket):** For connecting to the server.
   - **DataInputStream (dataInputStream):** For reading data from the server.
   - **DataOutputStream (dataOutputStream):** For sending data to the server.

Feel free to explore the functionality or expand it further as per your project requirements.

### License
This project is open-source. Feel free to modify and enhance the script as per your requirements.
