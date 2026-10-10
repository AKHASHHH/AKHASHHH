<div align="center">

<!-- Animated typing header -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=32&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&width=700&lines=Hi+there%2C+I'm+Akhash+%F0%9F%91%8B;Design+Verification+Engineer" alt="Typing SVG" />

<br/>

<!-- Animated wave banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:00d9ff,100:7c3aed&height=120&section=header&text=&animation=fadeIn"/>

</div>

---

<div align="center">

### `D. Akhash Krishna` · MS Computer Engineering @ NYU · Graduating Dec 2026

> *"My trust issues have 100% functional coverage."*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Akhash%20Krishna-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/akhash-krishna-d)
[![GitHub](https://img.shields.io/badge/GitHub-akhashhh-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akhashhh)
[![Email](https://img.shields.io/badge/Email-NYU%20Mail-57069e?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ad7252@nyu.edu)

**Seeking Full-Time Design Verification Engineer Opportunities**

</div>

---

## 🧠 About Me

```systemverilog
class Akhash extends VerificationEngineer;

  string university = "New York University";
  string degree     = "MS Computer Engineering";
  string location   = "Brooklyn, NY";
  string graduating = "December 2026";
  string seeking    = "Full-Time Design Verification Engineer";

  task run_phase();
    forever begin
      build_testbenches();
      verify_designs();
      debug_failures();
      close_coverage();
    end
  endtask

endclass
```

I'm a Computer Engineering graduate student at **New York University** focused on **digital design and verification**.

My work includes **UVM testbench development, SystemVerilog Assertions, constrained-random verification, functional coverage, register abstraction, formal verification, CDC, and regression automation**.

I'm currently looking for **full-time Design Verification Engineer opportunities** beginning around my **December 2026 graduation**.

---

## ⚙️ Verification Stack

<div align="center">

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-RTL%20%26%20Verification-00d9ff?style=flat-square)
![Verilog](https://img.shields.io/badge/Verilog-RTL-00d9ff?style=flat-square)
![UVM](https://img.shields.io/badge/UVM-Verification%20Methodology-7c3aed?style=flat-square)
![SVA](https://img.shields.io/badge/SVA-Assertions-7c3aed?style=flat-square)
![RAL](https://img.shields.io/badge/RAL-Register%20Verification-7c3aed?style=flat-square)
![Python](https://img.shields.io/badge/Python-Automation-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-Programming-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Tcl](https://img.shields.io/badge/Tcl-Scripting-e34c26?style=flat-square)

<br/>

![Synopsys VCS](https://img.shields.io/badge/Synopsys-VCS-red?style=flat-square)
![Cadence Xcelium](https://img.shields.io/badge/Cadence-Xcelium-blue?style=flat-square)
![Verdi](https://img.shields.io/badge/Synopsys-Verdi-red?style=flat-square)
![SymbiYosys](https://img.shields.io/badge/Formal-SymbiYosys-555555?style=flat-square)
![Yosys](https://img.shields.io/badge/Formal-Yosys-555555?style=flat-square)
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🔬 Verification Experience

- **UVM:** Drivers, monitors, sequences, scoreboards, and register models
- **SystemVerilog Assertions:** Protocol, handshake, and functional property checking
- **Constrained-Random Verification:** Randomized stimulus, corner-case testing, and regression
- **Functional Coverage:** Coverage-driven verification and coverage analysis
- **RAL:** Front-door and back-door register access
- **Formal Verification:** Safety properties, bounded liveness, counterexample analysis, and k-induction
- **CDC:** Gray-coded pointers, synchronizers, and independent clock-domain verification
- **Automation:** Python-based compilation, regression, seed management, and coverage collection

---

## 🚀 Featured Projects

### 🔷 AXI-Lite Register Block Verification

> UVM · RAL · SVA · Python Regression · Synopsys VCS

- Built a UVM environment with drivers, monitors, sequences, a scoreboard, and a RAL model supporting front-door and back-door register access
- Wrote SVA assertions checking VALID/READY handshakes, protocol legality, and register read/write consistency
- Automated VCS regression in Python for compilation, seed management, and coverage collection
- Reached **94.6% functional coverage across 4,730 randomized transactions**

---

### 🔷 Formal Verification of Round-Robin Arbiter

> SystemVerilog · SymbiYosys · Yosys · Safety · Liveness · k-Induction

- Designed a four-requester round-robin arbiter with rotating priority and fairness-preserving grant logic
- Verified mutual-exclusion safety and bounded-liveness properties
- Checked that asserted requests receive a grant within a **4-cycle bound**
- Used formal counterexamples to debug grant-priority issues
- Applied **k-induction** to extend safety verification beyond bounded model checking

---

### 🔷 Asynchronous FIFO for Clock Domain Crossing

> CDC · Gray-Code Synchronization · Constrained Random · Scoreboard · VCS

- Designed an asynchronous FIFO using Gray-coded read/write pointers and dual-flop synchronizers
- Verified operation across independent and randomized read/write clock frequencies
- Built a self-checking scoreboard using a reference queue to verify FIFO ordering
- Reached **93.8% functional coverage across 73 randomized seeds**

---

### 🔷 UART Controller with UVM Register Abstraction Layer

> SystemVerilog · UVM · RAL · Error Injection

- Designed a UART transmit/receive controller with memory-mapped baud-rate, parity, and control/status registers
- Developed a UVM environment with a RAL model supporting front-door and back-door register access
- Injected parity and framing errors to verify error detection and corresponding status-register behavior
- Executed **347 directed and randomized test cases**

---

## 🧰 Technical Skills

<div align="center">

### Languages

`C` · `C++` · `Python` · `Tcl` · `Verilog` · `SystemVerilog`

### Verification

`UVM` · `Constrained-Random Verification` · `SVA` · `Functional Coverage` · `RAL` · `Scoreboards` · `Regression`

### Protocols

`AXI4-Lite` · `APB` · `SPI` · `I²C` · `UART`

### Formal / CDC

`SymbiYosys` · `Yosys` · `Clock Domain Crossing` · `Gray-Code Synchronization`

### Tools

`Synopsys VCS` · `Cadence Xcelium` · `Verdi` · `Design Compiler` · `Genus` · `Innovus` · `Xilinx Vivado` · `Git`

</div>

---

## 💼 Experience

### Product Developer Intern — Microtek Power Controls Pvt. Ltd.

`Chennai, India` · `Jun 2023 – Aug 2023`

- Validated UPS functional behavior across normal and fault operating conditions using oscilloscopes, multimeters, and serial monitoring
- Analyzed captured waveforms and logs to investigate test failures
- Developed Python scripts to automate serial-data logging, measurement capture, and pass/fail checking
- Helped streamline repetitive test-reporting workflows through automation

---

## 🎓 Education

### New York University
**Master of Science in Computer Engineering**  
Expected **December 2026**

Relevant areas:
- VLSI System Design
- VLSI Systems and Architecture
- SoC Design
- Computing Systems Architecture

### Sri Ramachandra Institute of Higher Education and Research
**B.Tech. Computer Science — Artificial Intelligence & Machine Learning**  
Graduated **April 2024**

---

## 🎯 Currently

- 🔍 Seeking **Full-Time Design Verification Engineer** opportunities
- 🎓 Completing my **MS in Computer Engineering at NYU**
- 🧪 Building verification projects across **UVM, SVA, Formal Verification, CDC, and constrained-random testing**
- 🐍 Using **Python** to automate verification and regression workflows
- 📚 Continuing to strengthen digital design, computer architecture, and verification fundamentals

---

## 📫 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Akhash%20Krishna-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/akhash-krishna-d)
[![GitHub](https://img.shields.io/badge/GitHub-akhashhh-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/akhashhh)
[![Email](https://img.shields.io/badge/Email-ad7252%40nyu.edu-57069e?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ad7252@nyu.edu)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c3aed,50:00d9ff,100:0a0a0a&height=100&section=footer"/>

*"The bug existed before I found it. I just made it undeniable."*

</div>
