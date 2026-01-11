Mitigating Adversarial Machine Learning Threats in Formula 1 Telemetry Systems
Project Overview

This research project investigates the vulnerability of machine learning models used in Formula 1 (F1) telemetry-driven decision systems to adversarial manipulation, and evaluates robust training techniques as a mitigation strategy.

Using public Formula 1 race telemetry data accessed via the FastF1 library, the study focuses on a realistic operational task:
predicting whether a car will pit within the next N laps, and assessing how small, malicious perturbations in telemetry data can affect model confidence and decision-making.

The project demonstrates:

How small telemetry tampering (±2%) can degrade ML model confidence

How adversarially augmented training improves robustness

Why probability stability is more important than raw accuracy in safety-critical systems

Research Objectives

Model pit-stop likelihood using race telemetry features

Simulate adversarial telemetry manipulation

Evaluate the impact of attacks on model confidence and predictions

Implement and assess robust training as a defensive strategy

Frame findings in the context of cybersecurity risks in F1 racing systems

Dataset

Source: Public Formula 1 telemetry via the fastf1 Python library

Season: 2023

Granularity: Lap-level telemetry

Target Variable:
PitWithinNextNLaps (binary classification)

No proprietary or restricted data is used.