# shell_scripting_project

**Step-by-Step Solution:**

Create the Script File:

Open a terminal on your Linux system.
Create a new file named "processrunning.sh" using a text editor like vi or nano

```bash
vim processrunning.sh
```

![Screenshot 2025-04-02 115037](https://github.com/user-attachments/assets/6acc5699-8c53-4e62-8120-182fa564ade9)

**Write the Script:**

Add the following lines to the file:

```bash
#!/bin/bash
echo "Displaying all running processes:"
ps aux
echo "Total processes running: $(ps aux | wc -l)"
```

**Make the Script Executable:**

Change the permissions of the script to make it executable:

```bash
chmod +x processrunning.sh
```
![Screenshot 2025-04-02 115328](https://github.com/user-attachments/assets/2ce6a48c-b85d-42aa-b5b3-28faf6241f01)


**Execute the Script:**

Run the script on your system:

```bash
./processrunning.sh
```
The script will display a list of all running processes, followed by the total number of processes.
Review the Output:

![Screenshot 2025-04-02 115436](https://github.com/user-attachments/assets/1512b73a-78c4-4b6e-8dc2-304e45d32804)



