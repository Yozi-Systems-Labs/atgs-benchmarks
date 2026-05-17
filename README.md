# ATGS Benchmarks

Public benchmark suites and reproducibility scaffolds for ATGS.

## Purpose

This repository contains benchmark definitions, reproducibility scaffolds, and comparative evaluation materials for ATGS.

## Related Repositories

- `Yozi-Systems-Labs/atgs-foundation`
- `Yozi-Systems-Labs/atgs-validator`

## Current Benchmark Coverage

### Exact Reference Cases

- two-state absorbing CTMC
- three-state absorbing CTMC chain
- reversible two-state CTMC
- bidirectional three-state ring
- unidirectional three-state ring

### Adversarial Boundary Cases

- disconnected graph
- isolated node
- missing reverse transitions

## Manifest

See:

- `manifests/benchmark_manifest_v1.json`

## Boundary

This repository is for public benchmark definitions and reproducibility materials.

It does not contain the proprietary ATGS exact CTMC commercial core.

## Validation Principle

Benchmarks should prove software behavior, not overclaim domain truth.

ATGS can validate computations over a model.

ATGS does not automatically validate that the model is a perfect representation of the real system.
