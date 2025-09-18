# 📈 FPGA Stock Market Analyzer  

An **FPGA-based stock market dashboard** built on the **DE1-SoC board** to visualize and analyze 10 years of FAANG stock data.  
The system integrates **real-time rendering, user interaction via PS2 keyboard/mouse, dynamic scaling, and text-to-speech output**, providing a fully interactive financial analytics platform on custom hardware.  

---

## 🎯 Overview  
- **Timeline:** Jan 2025 – Apr 2025  
- **Tech Stack:** DE1-SoC, FPGA, C, Assembly, VGA, Git  
- **Impact:** Delivered a responsive stock analysis system with seamless rendering and advanced user interactivity.  

---

## 🧠 Technical Highlights  
- **Stock Data Integration:**  
  - Imported **10 years (2014–2024) of FAANG stock data**.  
  - Converted data into optimized C arrays for efficient FPGA use.  

- **Dynamic Scaling Algorithms:**  
  - Implemented real-time **X/Y axis scaling and indexing** for seamless VGA rendering.  
  - Supported multiple sampling intervals (daily, weekly, monthly).  

- **Interactive User Control:**  
  - **PS2 Keyboard & Mouse support** for:  
    - Switching stocks (keys 1–5)  
    - Timeframe selection (+/- keys for year range)  
    - Cursor traversal (<, > keys & mouse drag)  
  - Cursor-tracked statistics (price, date, opening/closing values).  

- **Enhanced Analytics:**  
  - **Statistics sidebar** updates continuously with dynamic calculations.  
  - **Text-to-speech output** for auditory feedback on stock selection.  

---

## 📊 Features Showcase  

### Main Dashboard View  
- Smooth stock display rendering on VGA.  
- Sidebar with real-time statistics.  
- User-controlled zooming & indexing.  

### User Interaction Flow  
1. **Intro Screen** → spacebar to start.  
2. **Instructions Screen** → shows all control keys (toggle with `H`).  
3. **Main Display** → press 1–5 to choose FAANG stock.  
4. **Indexing** → arrow keys adjust timeframe, sampling intervals.  
5. **Cursor Tracking** → locate precise stock values with keyboard or mouse.  

---

## 📽️ Demo  

🎥 **Video Walkthrough:** [Google Drive Link](https://drive.google.com/file/d/17qfD2idL0ijc8XOCcW2xP4rC3k5U3Mgw/view?usp=sharing)  

📸 *Add screenshots of your VGA display, sidebar, and cursor tracking here.*  

---

## 🧩 System Design  

### Block Diagram  
![Block Diagram](./assets/block-diagram.png)  

### Example Screens  
- **Intro Screen**  
- **Instructions Screen**  
- **Stock Graph Display with Sidebar**  
*(Upload these images into `/assets/` and embed them here.)*  

---
