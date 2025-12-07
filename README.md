# 🌌 Hello Quantum World — Cirq Quantum Demos  
**Bell State (Hello, Quantum World) + Grover’s Algorithm (Quantum Advantage)**  
Built and simulated in **Google Colab** using **Google’s Cirq library**.

---

## 🚀 Why This Project Exists
When Google announced its new **“Willow” quantum chip**, I wanted to do more than just read the news — I wanted to *build something real*.

So I opened a Colab notebook and coded my **first quantum programs**:

1. **The Bell State** — the “Hello World” of quantum computing  
2. **Grover’s Algorithm** — a quantum search that shows true quantum advantage  

This repository contains both implementations, fully working and beginner-friendly.

---

## 🔮 1. Bell State — *Hello, Quantum World!*
The Bell State is often the first quantum circuit developers learn.  
It proves one of the most surprising ideas in physics:

> Two qubits can become **entangled**, sharing a state even when separated.

### 🧠 What this code does:
- Creates two qubits  
- Applies a Hadamard gate  
- Applies a CNOT gate  
- Measures both qubits  
- Shows correlated outcomes (00 or 11)

### 📸 Example Output:
```
Hello, Quantum World!
Circuit:
0: ───H───────@────M('result')───
              │
1: ───────────X────M('result')───

Results:
result=0000000000...1111111111...
```

This is the quantum “Hello World” — not a printed string, but a **physical phenomenon**.

---

## 🔍 2. Grover’s Algorithm — *Quantum Advantage in Action*
Grover’s Algorithm is a quantum method for searching an unsorted list.  
It turns:

- **1,000,000 guesses → 500,000 (classical)**  
into  
- **1,000 guesses → √N (quantum)**  

One of the clearest demonstrations of why quantum computers matter.

### 🧠 What this implementation does:
- Uses two qubits to represent four items  
- “Marks” the state **|11⟩** using an oracle  
- Amplifies its probability using the diffuser  
- Measures the qubits to reveal the target state  

### 📸 Example Output:
```
Grover Circuit:
0: ───H────@─────────────@────────M('result')───
           │             │
1: ───H────Z────H────────X────────M('result')───

Results:
result=11  (dominant)
```

Grover’s algorithm finds the target **faster than any classical method**.  
This is exactly the kind of algorithm next-gen chips like **Google’s Willow** aim to accelerate.

---

## 🛠️ Running the Notebook
Clone this repo:

```bash
git clone https://github.com/<your-username>/hello-quantum-world-cirq.git
```

Or open the notebook directly in Google Colab:

```
Quantum_Demo.ipynb
```

Inside the notebook you can:

- Install Cirq  
- Run the Bell State  
- Run Grover’s Algorithm  
- Explore quantum simulation output  

---

## 🎥 Demo Video (Optional)

Here’s a short clip showing both the Bell State and Grover’s Algorithm running live in Google Colab:

https://github.com/user-attachments/assets/0aecaa6d-07fe-4b8d-bd31-79a83ee1d3ac

---

## 🧰 Tools Used
- **Google Colab** — interactive environment  
- **Cirq** — Google’s quantum programming library  
- **Python**  
- **GitHub**  

---

## ❤️ Why This Project Matters (Human Version)
This project is my first step into quantum computing.  
I’m an electronics student — not a quantum physicist — but I wanted to understand what quantum code *feels like*.

Running these circuits made the field go from:

**“someday…” → “okay, this is real.”**

If you’re curious about quantum computing, this repo is your invitation to start.

---

## 📬 Connect With Me
If you’re into quantum computing, Cirq, Google Research, or emerging tech —  
let’s connect and learn together.

---

## ⭐ If you found this project useful…
A star ⭐ on the repo would mean a lot!
