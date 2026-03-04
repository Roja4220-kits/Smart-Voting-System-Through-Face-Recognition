🗳️ AI-Powered Smart Voting System

Liveness-Aware Facial Biometrics & Multi-Level OTP Authentication

📌 Overview

This project implements a secure and intelligent digital voting system using facial recognition, liveness detection, and multi-level OTP authentication.

The system is designed to prevent impersonation, duplicate voting, and spoofing attacks while ensuring that only eligible voters (18+) can cast their vote.

It follows a strict one-person-one-vote policy and includes an admin monitoring panel for voter approval and activity tracking.

🚀 Key Features

✅ AI-Based Facial Recognition

✅ Liveness Detection (Anti-Spoofing)

✅ Multi-Level OTP Authentication

✅ Age Eligibility Verification (18+)

✅ Duplicate Vote Prevention

✅ Admin Dashboard

✅ Real-Time Authentication Logs

🛠️ Tech Stack

Python

Flask

OpenCV

dlib

face_recognition

SQLite / PostgreSQL

HTML, CSS, JavaScript

⚙️ Environment Setup Guide

This setup is tested and stable on Windows (Conda environment).

🐍 Create Conda Environment

conda create -n voting_env python=3.9 numpy=1.23.5 -y

conda activate voting_env
📦 Install Required Libraries (Order Matters)

1️⃣ OpenCV

conda install -c conda-forge opencv -y

2️⃣ dlib

conda install -c conda-forge dlib=19.24.2 -y

3️⃣ Pillow

pip install pillow==9.5.0

4️⃣ face_recognition

pip install face_recognition==1.3.0

5️⃣ Additional Library

pip install pandas

📌 Required Versions

Python 3.9

numpy 1.23.5

opencv (conda-forge build)

dlib 19.24.2

pillow 9.5.0

face_recognition 1.3.0

pandas

▶️ Run the Application

python app.py

(Or run specific modules like phase1_authentication.py)

⚠️ Important Notes

Do NOT upgrade NumPy

Do NOT mix pip-installed OpenCV with Conda OpenCV

Follow installation order strictly to avoid DLL/ABI errors

This dependency stack is stable and verified for running the biometric authentication modules successfully.
