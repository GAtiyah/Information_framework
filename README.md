# Information-Theoretic Generative Modeling Notes

This repository contains research notes for an ongoing project on building a mathematically grounded training framework for generative modeling from an information-theoretic perspective.

## Overview

The project starts from the discrete rate–distortion problem and studies how latent representations, Markov structure, and semigroup dynamics can be used to derive principled training objectives for generative models. 
The most recent notes reformulate latent-channel rate–distortion optimization as a KL-projection problem over the semigroup image of the simplex, yielding an exact-inversion regime and a projection regime. This perspective is intended as a theoretical foundation for diffusion-style models derived from optimization principles rather than prescribed noise schedules. 

## Contents
- `information_notes_1.pdf`: intro to rate-distortion function, example given of Gaussian source with MSE distortion.
- `information_notes_2.pdf`: discrete rate–distortion with Hamming distortion, closed-form solution, threshold truncation, and Markov kernel construction.
- `information_notes_3.pdf`: arbitrary distortion, degradation kernels, small-step generators, and failure of Markov compatibility in general. 
- `information_notes_4.pdf`: semigroup-based reformulation, KL-projection interpretation, exact inversion criterion, and convex optimization characterization.

## Status

This is ongoing theoretical work. The current focus is on mathematical derivation and structural analysis, with experiments planned in future work.
