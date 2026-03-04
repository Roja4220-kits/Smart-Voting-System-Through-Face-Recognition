⚙️ Environment Setup Guide

To ensure smooth execution of the Smart Voting System, please follow the exact dependency versions below. This setup is tested and stable for Windows using Conda.

🐍 Create Conda Environment
conda create -n voting_env python=3.9 numpy=1.23.5 -y
conda activate voting_env
📦 Install Required Libraries (Order Matters)
1️⃣ Install OpenCV (via Conda)
conda install -c conda-forge opencv -y
2️⃣ Install dlib (Prebuilt Version)
conda install -c conda-forge dlib=19.24.2 -y
3️⃣ Install Pillow (Compatible Version)
pip install pillow==9.5.0
4️⃣ Install face_recognition
pip install face_recognition==1.3.0
5️⃣ Install Additional Library
pip install pandas
📌 Required Library Versions

Python 3.9

numpy 1.23.5

opencv (conda-forge build)

dlib 19.24.2

pillow 9.5.0

face_recognition 1.3.0

pandas

⚠️ Important Notes

Do NOT upgrade NumPy.

Do NOT mix pip-installed OpenCV with Conda OpenCV.

Follow the installation order strictly to avoid DLL or ABI errors.

This dependency stack is stable and verified for running the facial recognition and authentication modules successfully.
