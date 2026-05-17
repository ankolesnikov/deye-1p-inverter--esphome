# Deye 1-Phase ESPHome Config

This repository contains a merged ESPHome configuration for a Deye 1-phase inverter based on:

- `Lewa-Reka/esphome-deye-inverter` as the base
- additional helper features inspired by `slipx06/Sunsynk-Home-Assistant-Dash`

## Included

- 1-phase package selection
- generator features and controls
- battery/grid helper entities
- raw register helpers
- inverter time sync
- adaptive polling helpers

## Files

- `pv-inverter.yaml` - top-level ESPHome config
- `pv_inverter/deye_hybrid_1p_lv.yaml` - 1P package entrypoint
- `pv_inverter/packages/deye_hybrid_1p/extras.yaml` - added helper features

## Notes

Review GPIO pins, Wi-Fi secrets, API keys, and inverter settings before flashing.
