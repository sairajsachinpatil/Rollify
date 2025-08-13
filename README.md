# Rollify
Rollify is a data-driven, AI/ML-inspired offline automation tool for colleges to fairly distribute students into roll calls, divisions, and batches — balancing marks, branch, and gender ratio with a 94%+ fairness score, transforming weeks of manual work into seconds, while keeping all data 100% private.

🚀 **Simplifying Student Roll Call Distribution for Colleges**

---

## Overview

During my time observing college administrative processes, I noticed a common challenge: **distributing students into roll calls and divisions fairly and efficiently** — especially in first-year engineering, where students from multiple branches mix together. 

Traditional manual methods or Excel-based approaches often take **weeks** and fail to ensure balanced batches. This can lead to:

- Batches dominated by toppers or boys, which affects student motivation  
- Stigma around “topper” vs “weaker” batches  
- Unintentional bias by professors toward certain batches  
- Overall imbalance impacting learning opportunities and morale  

To solve this, I developed **Rollify**, a Flutter-based offline app that automates and simplifies this entire process — from **weeks of work to just seconds** — while keeping all data completely private.

---

## What is Rollify?

Rollify is designed specifically for college authorities to:

- **Equally distribute students** based on marks/percentile, branch, gender ratio, and alphabetical order  
- **Assign unique roll numbers, practical batches, and divisions** in seconds, even for large batches of 2000+ students  
- **Securely process input files** (CSV or Excel) locally, with **zero cloud upload or data sharing**, ensuring full data privacy  

Rollify currently supports:

- **Android APK** for mobile use  
- **Windows EXE desktop application** for faster processing in large colleges  

---

## How Rollify Works (Backend Logic)

When you upload student data files, Rollify:

- Parses and validates the input carefully to catch errors or missing info  
- Applies statistical methods like **quartiles and binning**, inspired by IIT Madras Data Science courses  
- Uses a combination of distribution algorithms — **Rule of Thumb, Round Robin, Snake, and Zigzag** — to allocate students fairly across divisions  
- Handles edge cases like duplicate names and missing data to maintain accuracy  
- Prepares final data for quick preview, editing, and roll number generation  

This combination ensures students are evenly balanced across performance, gender, and branch — avoiding clustering and boosting fairness.

---

## Impact and Benefits

- **Average allocation fairness around 94% +**, making student batches truly balanced  
- Drastically reduces the manual distribution time from weeks to seconds  
- Keeps all sensitive student data **offline and secure** with no cloud exposure  
- Helps improve student motivation and equal opportunity by preventing biased batch grouping  

---

## Development Notes

- The core logic and algorithms are built on research and data science principles.  
- AI tools like **ChatGPT, Perplexity, and Claude** were used during development for coding assistance, debugging, and research, but the final design and integration are fully by me.  
- Rollify is open for further enhancements and is designed with modular code to allow future updates easily.  

---

## Getting Started

(Include instructions here if you want users or colleges to try your app, install APK or Windows EXE, and upload student files.)

---

## License

Rollify is proprietary software. Please contact me for licensing or collaboration opportunities.

---

## Apps Download

You can download Rollify for your preferred platform here:

- **Android APK:** [Download Rollify Android APK](https://drive.google.com/file/d/1ST81HMyEzFbWYz90Hg0b3tNKqU3MTKhk/view?usp=sharing)  
- **Windows EXE:** [Download Rollify Windows App](https://drive.google.com/file/d/1oZxvoodO2UT2EGSXedpOZRLnbNQm7oUQ/view?usp=sharing)  

*Note: Please ensure you have the necessary permissions to install apps from unknown sources on your device.*

---

## Contact

Sairaj Sachin Patil  
gmail:sairajsachinpatil3066@gmail.com
mobile number: 99604 74559


---

*Thank you for checking out Rollify — transforming stude
