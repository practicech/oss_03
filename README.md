# oss_03분반

**Hello, I'm seongchan kang, my English name is Arthur**

# 🐧 Linux Process Commands Investigation (Assignment #2)

---

## 1. 🍋 Command Summary Table

| Command | Key Feature ✨ | Note 📝 |
| :--- | :--- | :--- |
| **top** | Real-time system & process monitoring ⚡ | Similar to Windows Task Manager |
| **ps** | Check current process status (Snapshot) 📸 | Often used with `ps -ef` |
| **jobs** | List background jobs 💼 | Check tasks running behind |
| **kill** | Terminate a specific process 🛑 | Needs PID (Process ID) |

---

## 2. 🔍 Detailed Explanation

### ① top (Table Of Processes) 🚀
* **What is it?:** Shows CPU, Memory usage, and process rankings in **Real-time**! It updates live like magic! ✨
* **How to use:** Just type `top` in your terminal.
* **Screenshot:**
> *(Please insert your 'top' screenshot here!)*

### ② ps (Process Status) 📸
* **What is it?:** Takes a **snapshot** of processes at this exact moment. Unlike `top`, it stays static.
* **Useful Options:**
  * `-e`: Show **E**verything (all processes).
  * `-f`: **F**ull format (shows more details).
* **Screenshot:**
> *(Please insert your 'ps -ef' screenshot here!)*

### ③ jobs 💼
* **What is it?:** Checks what work is running in the background of your current shell.
  * `Running`: Working hard! 🏃‍♂️
  * `Stopped`: Taking a break. ⏸️
  * `Terminated`: All done! ✅

### ④ kill 🔫
* **What is it?:** Sends a signal to a process to say "Stop right now!".
* **Caution:** If a program is frozen, use the `-9` option to **force kill** it! (e.g., `kill -9 1234`) 🔥

---

## 3. 💭 Conclusion & Thoughts

* Through this assignment, I learned how to monitor and control processes in Linux! 😎
* It was super useful to learn how to stop a frozen program using the `kill` command.
* I will make sure to check the **PID** carefully before killing any process! 💖
