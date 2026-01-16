# CM2607 Advanced Mathematics Coursework

This repository contains a Jupyter notebook for the **CM2607 Advanced Mathematics Coursework**, completed as part of the curriculum at **Informatics Institute of Technology**. The project analyzes transportation optimization in Colombo, Sri Lanka using mathematical modeling techniques.


## 📁 Project Structure

- `CM2607_Coursework.ipynb` – Main Jupyter notebook with all mathematical analyses and visualizations
- `CM2607_Advanced_Mathematics_Coursework/` – Automatically generated output folder containing:
  - `Q1_Differentiation/` – Gradient analysis of travel time functions
  - `Q2_Integration/` – Fare function integration and comparison
  - `Q3_Series/` – Passenger volume modeling using series approximation
  - `Q4_Fourier/` – Frequency analysis of boarding patterns
  - `Q5_DCT/` – *(Referenced in the code structure)*

Each question folder contains:
- `interpretation.txt` – Detailed explanation of mathematical insights
- Generated plots (PNG format) for visual analysis

---

## 📚 Mathematical Topics Explored

### 1. **Differential Calculus**
- Gradient computation for bus and taxi travel time functions:
  - Bus: \( T_b = a x^2 + b y^2 \)
  - Taxi: \( T_t = \sqrt{c (x^2 + y^2)} \)
- Interpretation of how travel time changes with distance and traffic congestion

### 2. **Integral Calculus**
- Integration of fare rate functions:
  - Bus fare: \( \int (2t + 1) dt = x^2 + x \)
  - Taxi fare: \( \int (3t + 2) dt = \frac{3x^2}{2} + 2x \)
- Cost comparison for Fort to Borella route (4.5 km)

### 3. **Series Approximation**
- Modeling passenger volume over 24 hours:
  - \( P(t) \approx 5 + 4\sin(\pi t) - 1.5t^2 + 0.25t^4 \)
- Identification of peak passenger times
- Analysis of model limitations for long-term predictions

### 4. **Fourier Analysis**
- Application of Fast Fourier Transform (FFT) to synthetic boarding data
- Identification of dominant frequencies representing rush hour patterns
- Comparative analysis of bus vs. taxi usage patterns

### 5. **Discrete Cosine Transform (DCT)**
*(Infrastructure prepared but analysis not shown in provided excerpt)*

---

## 🛠️ Technical Implementation

### Programming Environment
- **Python 3** with Jupyter Notebook interface
- **Key Libraries**:
  - `numpy` – Numerical computations
  - `matplotlib` – Data visualization
  - `sympy` – Symbolic mathematics
  - `scipy` – Scientific computing (FFT, DCT)
  - `opencv-python` – Image processing
  - `PIL` – Image manipulation

### Code Features
- Modular function design for saving interpretations and plots
- Automated folder structure generation
- Numerical evaluation at specific points (x=4.5, y=1)
- Clear visualization of mathematical relationships

---

## 🚀 How to Execute

1. **Clone the repository:**
   ```bash
   git clone https://github.com/[username]/CM2607-Mathematics-Coursework.git
   cd CM2607-Mathematics-Coursework
   ```

2. **Install dependencies:**
   ```bash
   pip install numpy matplotlib sympy scipy opencv-python pillow
   ```

3. **Launch Jupyter:**
   ```bash
   jupyter notebook CM2607_Coursework.ipynb
   ```

4. **Run sequentially:** Execute all cells to generate:
   - Mathematical computations
   - Visual plots
   - Interpretation text files in organized folders

---

## 📊 Key Findings

### Transportation Insights
- **Taxis** show more balanced gradients, making them preferable during congestion
- **Buses** are 63% more economical for the 4.5 km Fort-Borella route
- Morning (7-9 AM) and evening (5-7 PM) rush hours clearly identifiable in Fourier analysis

### Mathematical Observations
- The \( t^4 \) term dominates long-term predictions in the series model
- FFT reveals stronger periodic patterns in bus usage vs. taxi usage
- Gradient analysis provides quantitative basis for mode choice recommendations

---

## 🏛️ Academic Context

This project demonstrates the application of advanced mathematical concepts to real-world urban transportation problems. It was developed as part of:

**Course:** CM2607 – Advanced Mathematics  
**Institution:** Informatics Institute of Technology  
**Affiliation:** University of Moratuwa  
**Academic Level:** Undergraduate Engineering/Computing Program

The work showcases:
- Mathematical modeling of real systems
- Computational implementation of theoretical concepts
- Professional documentation and visualization
- Critical analysis of model limitations

---

## 📝 Notes for Reviewers

1. The notebook is structured to be self-contained and reproducible
2. All interpretations are saved as text files for easy reference
3. The DCT section infrastructure is prepared but requires additional implementation
4. Numerical values assume specific parameter choices (a=1, b=2, c=1)

---

## 🔗 Contact
**Amika Alankara**  
Informatics Institute of Technology  
Colombo, Sri Lanka

For academic collaboration or questions regarding this implementation, please open an issue in the repository.

---

*This project represents the intersection of mathematical theory, computational implementation, and practical urban planning applications.*
