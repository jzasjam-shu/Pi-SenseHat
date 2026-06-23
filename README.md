# Raspberry Pi Sense HAT

## Jupyter Notebooks for SHU Summer School 2026

---

**Description:** Example code and guides for using the Raspberry Pi Sense HAT.

**Introductory Slides:** [Google Slides](https://docs.google.com/presentation/d/11kjfUA7y1wN6u6KTTDqKMyE-SACJ7qHDdcWYVI_QLaA/edit?usp=sharing)

## Setup Instructions

### 1. Open a new **Terminal** window on the Raspberry Pi.

<img width="511" height="607" alt="image" src="https://github.com/user-attachments/assets/8098fcb5-dc91-4fbf-b3c0-a5e34d9b2050" />

---

### 2. If you are currently using a virtual environment, deactivate it using:

   ```bash
   deactivate
   ```

   <img width="656" height="120" alt="image" src="https://github.com/user-attachments/assets/00964a4c-aacf-47f2-aed0-cf6e26f7bc18" />

---

### 3. Update the package list and install Jupyter Notebook:

   ```bash
   sudo apt update
   sudo apt install jupyter-notebook
   ```
---

### 4. Clone this repository to your Raspberry Pi:

   ```bash
   git clone https://github.com/jzasjam-shu/Pi-SenseHat.git
   ```

   <img width="656" height="196" alt="image" src="https://github.com/user-attachments/assets/b4d1e4ec-efc5-4094-a7fd-160e04a8d553" />

---

### 5. Enter the repository directory:

   ```bash
   cd Pi-SenseHat
   ```

   <img width="657" height="36" alt="image" src="https://github.com/user-attachments/assets/2c2ecb33-fd21-42b0-b7af-17edca1605cd" />

---

### 6. Start Jupyter Notebook:

   ```bash
   jupyter-notebook
   ```

   <img width="653" height="106" alt="image" src="https://github.com/user-attachments/assets/61bd6237-dc53-4d64-a75f-78555cb69001" />

   <img width="655" height="200" alt="image" src="https://github.com/user-attachments/assets/c6d5718e-9847-487f-ac67-db60169f7245" />

---

### 7. Open your browser and navigate to:

   ```
   http://localhost:8888
   ```

   <img width="1062" height="416" alt="image" src="https://github.com/user-attachments/assets/28ae26b9-2e29-41d5-bf7d-f69511845431" />

   You should now see the notebook files contained in this repository (the .ipynb files).

---

### 8. Click on one of these to open the notebook and run the code examples.

   <img width="1065" height="531" alt="image" src="https://github.com/user-attachments/assets/d4ce2f58-1383-45ca-a271-a99c27932282" />

---

### Additional Resources
- [SenseHAT Docs](https://sense-hat.readthedocs.io)
- [Sense HAT Guide](https://projects.raspberrypi.org/en/projects/getting-started-with-the-sense-hat)
- [GPIO Recipies/Guides](https://gpiozero.readthedocs.io/en/latest/recipes.html#)

---
