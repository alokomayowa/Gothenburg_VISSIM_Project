# Project Report: Ullevigatan–Skånegatan VISSIM Model

**Author:** [Your Full Name]  
**Date:** September 2026  
**Software:** PTV VISSIM 2026 (Student Version)

---

## 1. Introduction

Traffic congestion at urban signalised intersections is a common problem in many European cities. Microsimulation tools such as PTV VISSIM allow engineers to test different signal timing strategies before implementing them in the real world.

This project focuses on the intersection of Ullevigatan and Skånegatan in Gothenburg, Sweden. The objectives were:

- To build a realistic microscopic simulation model
- To evaluate the performance of a fixed-time signal plan (Base Case)
- To test an alternative signal timing (Scenario A)
- To compare the results in terms of queue length and travel time

---

## 2. Study Area and Data

The study intersection is located in central Gothenburg and carries significant traffic volumes, especially on Ullevigatan.

**Traffic Data (2025):**
- Ullevigatan: approximately 21,800 vehicles per day (ÅMVD)
- Skånegatan: approximately 4,500–6,700 vehicles per day

Peak-hour volumes used in the model:
- Ullevigatan West: 1,100 veh/h
- Ullevigatan East: 1,000 veh/h
- Skånegatan South: 400 veh/h
- Skånegatan South-East: 600 veh/h

---

## 3. Model Building Process

The model was developed step by step in PTV VISSIM:

1. Network geometry (Links and Connectors)
2. Conflict Areas
3. Desired Speed Decisions and Speed Distributions
4. Vehicle Composition and Vehicle Inputs
5. Static Vehicle Routes
6. Fixed-time Signal Controller and Signal Heads
7. Queue Counters and Travel Time Measurements

The student version of VISSIM limited the simulation time to 600 seconds.

---

## 4. Base Case Results

**Signal Timing (Base Case):**
- Ullevigatan E-W: 48 s green
- Skånegatan N-S: 26 s green
- Turnings: 16 s green

**Maximum Queue Lengths:**
- Ullevigatan West: 66 m
- Ullevigatan East: 35 m
- Skånegatan South: 33 m
- Skånegatan South-East: 18 m

**Average Travel Times:**
- Ullevigatan East: 57 s
- Ullevigatan West: 62 s
- Skånegatan South: 41 s
- Skånegatan South-East: 58 s

---

## 5. Scenario A Results

**Signal Timing (Scenario A):**
- Ullevigatan E-W: 54 s green
- Skånegatan N-S: 22 s green
- Turnings: 14 s green

**Maximum Queue Lengths:**
- Ullevigatan West: 69 m
- Ullevigatan East: 36 m
- Skånegatan South: 32 m
- Skånegatan South-East: 37 m

**Average Travel Times:**
- Ullevigatan East: 58 s
- Ullevigatan West: 68 s
- Skånegatan South: 47 s
- Skånegatan South-East: 56 s

---

## 6. Comparison and Discussion

Giving additional green time to Ullevigatan in Scenario A did not produce a clear improvement.  

- Queues on Ullevigatan West remained similar (slightly higher)
- Some travel times increased
- Skånegatan South-East experienced longer queues

This suggests that simply allocating more green time to the main road is not always effective. A more balanced or actuated signal control may perform better.

---

## 7. Conclusions and Future Work

A complete microsimulation model of a real urban intersection was successfully developed and tested. The project demonstrated practical skills in:

- Network coding in VISSIM
- Use of real traffic data
- Signal timing design
- Performance evaluation (queues and travel times)

**Future improvements could include:**
- Vehicle-actuated signal control
- Public transport priority for trams
- More detailed turning movement data
- Longer simulation periods (commercial VISSIM licence)

---

## 8. References

- Göteborgs Stad – Trafikmängdskatalogen (2025)
- PTV Group – VISSIM User Manual
- OpenStreetMap / Bing Maps (background imagery)