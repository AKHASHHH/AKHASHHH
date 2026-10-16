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

My work includes **UVM testbench development, SystemVerilog Assertions, constrained-random verification, functional coverage, register abstraction, formal verification, CDC, mutation testing, and regression automation**.

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
![VC Formal](https://img.shields.io/badge/Synopsys-VC%20Formal-red?style=flat-square)
![VC Static](https://img.shields.io/badge/Synopsys-VC%20Static%20%2F%20SpyGlass%20CDC-red?style=flat-square)
![URG](https://img.shields.io/badge/Synopsys-URG%20Coverage-red?style=flat-square)
![Bash](https://img.shields.io/badge/Bash-Scripting-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

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
- **Mutation Testing:** Controlled RTL fault injection, checker sensitivity analysis, assertion coverage, and waveform-based root-cause debugging
- **Automation:** Python and Bash-based compilation, regression, seed management, and coverage collection

---

## 🚀 Featured Projects

### 🔷 [AXI-Lite Register Block Verification](https://github.com/AKHASHHH/AXI4-Lite-Register-Block-Verification-using-SystemVerilog-UVM)

> SystemVerilog · UVM · RAL · SVA · Synopsys VCS/URG

- Built a reusable UVM environment for a 32-bit AXI4-Lite register block with a scoreboard, functional coverage, RAL model, and monitor-driven prediction
- Verified independent address/data ordering, backpressure, byte-write strobes, error responses, reset recovery, and front-door/back-door register access
- Closed **100% of modeled functional coverage bins** and achieved **100% DUT line coverage** and **93.94% DUT branch coverage**
- Completed the automated regression with **12/12 directed tests passing**, **0 UVM or RAL errors/fatals**, and **0 SVA failures**


---

### 🔷 [LLM-Generated SVA Mutation-Based Verification](https://github.com/AKHASHHH/LLM-Generated-SVA-Mutation-Based-Verification)

> SystemVerilog · SVA · APB · Mutation Testing · Synopsys VCS / URG / Verdi

- Evaluated **GPT- and Claude-generated assertion suites** against a frozen APB programmable timer specification using **10 deliberately injected RTL defects** and **8,348 simulation cycles**
- Compared internal-state-aware and port-only checker contracts: both white-box suites detected **10/10 activated mutants**, while black-box GPT and Claude detected **1/9** and **2/9 port-observable mutants**, respectively
- Analyzed assertion exercise using **VCS/URG**, audited mutation detection and reproducibility using **SHA-256**, and debugged prescaler, pending-flag, and IRQ-timing defects in **Verdi**
- Validated two separate **AI-assisted, port-only supplemental assertions** targeting previously missed M07/M09 defects, with **zero reference-run failures** and **6/14 mutant assertion failures** respectively

---

### 🔷 [Formal Verification of Round-Robin Arbiter](https://github.com/AKHASHHH/Round-Robin-Arbiter-Formal-Verification-using-SystemVerilog-SVA)

> SystemVerilog · SVA · Synopsys VC Formal · Safety · Bounded Fairness

- Designed and formally verified a four-requester round-robin arbiter with rotating priority and starvation-prevention guarantees
- Developed **28 assertions** covering mutual exclusion, grant validity, priority selection, pointer transitions, and bounded fairness; proved **28/28** with **0 falsified**
- Confirmed **26/26 implication-based properties were non-vacuous** and reached both formal cover scenarios
- Injected a priority-order defect, used counterexamples to connect the immediate selection error to a fairness violation, then restored the RTL and re-proved the full suite


---

### 🔷 [Asynchronous FIFO for Clock Domain Crossing](https://github.com/AKHASHHH/Async-FIFO-CDC-Verification)

> CDC · Gray-Code Synchronization · SVA · Synopsys VCS · VC Static · Verdi

- Designed a parameterized asynchronous FIFO using Gray-coded pointers, two-flop synchronizers, and independent write/read clock domains
- Verified ordering, overflow/underflow protection, pointer wraparound, and full/empty behavior with directed and concurrent randomized traffic plus **12 SVA properties**
- Achieved **99 passing checks with 0 errors**, **0 assertion failures**, and **100% of defined write- and read-domain functional coverage bins**
- Passed **100/100 random seeds** and **4/4 clock-ratio configurations**; proved both pointer data-loss checks and both Gray-reconvergence checks in VC Static, and debugged an injected full-detection defect in Verdi


---

### 🔷 [Five-Stage Pipelined RISC-V Simulator](https://github.com/AKHASHHH/RISC-V-Simulator)

> C++ · RISC-V · Five-Stage Pipeline · Hazard Handling

- Built a cycle-accurate simulator for the IF, ID, EX, MEM, and WB pipeline stages
- Implemented forwarding, load-use stalls, and branch and jump control-hazard handling
- Added cycle-by-cycle pipeline state, register-file, and data-memory output logs


---

## 🧰 Technical Skills

<div align="center">

### Languages

`C` · `C++` · `Python` · `Tcl` · `Bash` · `Verilog` · `SystemVerilog`

### Verification

`UVM` · `Constrained-Random Verification` · `SVA` · `Functional Coverage` · `Assertion Coverage` · `RAL` · `Scoreboards` · `Mutation Testing` · `Regression`

### Protocols

`AXI4-Lite` · `APB` · `SPI` · `I²C` · `UART`

### Formal / CDC

`VC Formal` · `VC Static / SpyGlass CDC` · `SymbiYosys` · `Yosys` · `Clock Domain Crossing` · `Gray-Code Synchronization` · `Counterexample Debugging`

### Tools

`Synopsys VCS` · `Synopsys URG` · `Verdi` · `VC Formal` · `VC Static / SpyGlass CDC` · `Cadence Xcelium` · `Design Compiler` · `Genus` · `Innovus` · `Xilinx Vivado` · `Git` · `Linux`

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
- 🧪 Applying **UVM, SVA, Formal Verification, CDC, mutation testing, and constrained-random verification** across hardware projects
- 🐍 Using **Python and Bash** to automate simulations, regressions, results analysis, and coverage collection
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
