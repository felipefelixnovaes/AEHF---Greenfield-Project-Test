# Task Depth Policy

This pilot uses AEHF depth classification.

## Initial default

Use **Standard** for the first MVP slice because the project is small but still benefits from explicit scope, plan, and validation.

## Use Fast when
- the change is tiny and local
- no meaningful architecture or domain understanding changes

## Use Standard when
- adding or changing a normal feature
- creating a new flow in the MVP
- the work touches more than one file or requires documentation updates

## Use Deep when
- risk becomes materially higher than expected
- architecture or contracts broaden significantly

## Use Reverse when
- the system becomes unclear enough that current behavior must be reconstructed before safe change

## Pilot guidance

For now, prefer Standard unless a task is obviously tiny.
