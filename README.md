# Lagrangian Volume Particle Selection Tool

This repository provides a Python tool for selecting particles belonging to the Lagrangian Volume around a given galaxy in cosmological simulations, and for analysing the morphology of the local Cosmic Web environment surrounding that galaxy.

The code is designed for use with the IllustrisTNG simulation suite, and has been tested primarily on the TNG50 simulation.

This tool is intended for scientific post-processing workflows and can be applied to any halo of interest within the simulation volume.

## Requirements
Install dependencies with: 
pip install -r requirements.txt

## Usage

python LV_calculation.py \
    --basePath PATH_TO_SIMULATION \
    --savePath OUTPUT_DIRECTORY \
    --halo_id HALO_ID \

## Example

python LV_calculation.py \
    --basePath /data/TNG50 \
    --savePath ./outputs \
    --halo_id 12



