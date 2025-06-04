## 📝 Go CLI Todo App

A simple command-line todo list written in Go — beginner-friendly and file-based using JSON for storage.

> 🎯 Part of the `die <= learn Go => master` journey

---

### 📦 Features

- ✅ Add tasks  
- 📋 List all tasks  
- ✔️ Mark tasks as done  
- 🗑️ Delete tasks  
- 💾 Persistent with `tasks.json`

---

### 🚀 Getting Started

#### 1. Clone the repo

```bash
git clone https://github.com/shayanghad0/go-task1
cd go-cli-todo
```

#### 2. Run it

```bash
go run main.go <command> [args...]
```

#### 3. Build it

```bash
go build -o todo main.go
./todo list
```

---

### 🛠️ Usage

```bash
todo add "Learn Go"         # Add a new task
todo list                   # Show all tasks
todo done 1                 # Mark task #1 as done
todo delete 1               # Delete task #1
```

---

### 💡 Example

```bash
$ todo add "Write README"
Added: Write README

$ todo list
[1] ❌ Write README

$ todo done 1
Marked done: Write README

$ todo list
[1] ✅ Write README
```

---

### 📁 Storage

All tasks are saved in `tasks.json` in the project directory.

---

### 📚 Learning Goals

- Go CLI apps  
- JSON file handling  
- Structs, slices, loops  
- `os.Args` parsing  
- Basic terminal UX

---

### 🔮 Next Steps

- [ ] Use `flag` package  
- [ ] Sort by status/date  
- [ ] Export to `.csv` or `.txt`  
- [ ] Add a TUI (Text UI)

---

## 🧠 Part of...
>📘 die <= learn Go => master

## 📜 License
> MIT — free to use, learn, remix.