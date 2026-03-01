# Reshma's Ansible Automation Lab 🚀

Welcome to my learning journey! I am documenting my progress as I learn **Ansible** from scratch. I tackle practical tasks whenever I'm free and feel like learning, recording my process and uploading the code here.

## 📺 YouTube Series
I'm sharing my "learning-by-doing" process to help other beginners. 
[https://youtu.be/7DDnzB1DwAA?si=30IhCSBmV1dSwHQG]

## 📂 Repository Structure
* **`inventory.ini`**: This is the "address book." It tells Ansible to talk to my local machine (`localhost`).
* **`test_ping.yml`**: This is the "instruction manual" (Playbook). It checks the connection and prints a custom message to the screen.

## 🚀 How to Execute
To run this specific task, open your WSL terminal and use this command:

```bash
ansible-playbook -i inventory.ini test_ping.yml
