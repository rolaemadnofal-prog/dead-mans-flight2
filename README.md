# Dead Man’s Flight

**Category:** Digital Forensics / Cryptography
**Difficulty:** Hard
**Flag Format:** `DMF{...}`

## Scenario

During an autonomous flight, a drone unexpectedly aborted its mission and entered an abnormal descent.

The investigation team recovered several artifacts from the flight:

* `flight.pcap` — Captured network traffic during the flight.
* `blackbox.bin` — Flight controller blackbox log.
* `telemetry.log` — Encrypted and fragmented telemetry export.

Your task is to analyze the recovered evidence, correlate the suspicious events, and recover the hidden flag.

## Objectives

1. Analyze the network capture and identify the suspicious command.
2. Correlate the event with the flight controller's blackbox log.
3. Recover the cryptographic parameters from the available evidence.
4. Reconstruct and decrypt the telemetry to obtain the flag.

## Rules

* All artifacts are provided for authorized CTF analysis.
* The challenge is self-contained.
* Submit the flag in the format `DMF{...}`.

Good luck!
