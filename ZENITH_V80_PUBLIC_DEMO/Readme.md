Honestly, if you are here looking for a copy paste AI trading script, you can close this tab right now. This is the Proof of Concept for Zenith V80. A real world Deep Reinforcement Learning orchestrator that I built specifically to dominate the Exness market.

The actual system is incredibly heavy. I trained it for months using my Lenovo LOQ i5 12450HX and RTX 3050 6GB VRAM. Because data sovereignty is everything, I absolutely refuse to share the main model weights or the raw data. Giving away the secret sauce will only create a real world maintenance nightmare for me.

Instead, I am providing this black box simulation for you to test drive.

Hardware Reality Check
Look, different silicon means different execution speeds. I built this to be a snappy predator, but if you run this on a potato laptop, it is going to be a memory hog and lag heavily. Multiprocessing and PyTorch tensors demand real world power.

The Architect Rig (My Setup): Intel Core i5 12450HX with an NVIDIA RTX 3050 6GB VRAM. This is the baseline for smooth real time execution.

Minimum Survival Specs: You need at least a dedicated GPU with 4GB VRAM. Think GTX 1650 or a basic RTX 2050. Your CPU must have decent multi core performance because Sector 1 and Sector 3 run concurrently in separate processes.

The Recommended Beast: If you want zero latency and maximum throughput, throw an RTX 4060 or any GPU with 8GB VRAM at it. Pair it with an i7 or Ryzen 7. More cores and more VRAM mean the LSTM brain can process the binary stream without breaking a sweat.

What is Inside This Demo Package?

Multiprocessing Executor
This is the main engine. I encrypted the code using high level obfuscation. Why? So you can see the performance but you cannot steal the logic behind my Sector 1 and Sector 3 architecture.

Cloaked Core Intelligence
My original LSTM neural network architecture is still here, but tightly wrapped. You can use your VRAM to run the brain, but you cannot unpack the logic.

Golden Sample Ammunition
I do not use random data. The zenith v80 golden sample.bin.npy file contains 4986 rows of real EURUSDc data from the Exness broker. I strictly filtered it using MACD True and ATR Survival. I intentionally wrapped it into a binary file so nobody can open it with a spreadsheet.

How to Run the Simulation:

1. Make sure Python is ready on your machine and PyTorch is configured for CUDA if you have an NVIDIA card.
2. lone this repository and do not delete the pyarmor runtime 000000 folder. That is the encryption engine.
3. Open your terminal in this folder and execute: python simulasi demo v80.py
4. Enjoy the show. Watch how two CPU processes work concurrently to read the ghost data and spit out profit predictions in real time.

Think of this as me lending you the cockpit of a fighter jet. Step on the gas and see how snappy this system makes decisions. But remember, do not ask for the original pth file or the raw data. The vault key stays safe in my Laptop.
