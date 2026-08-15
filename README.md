# Linket — QR-Based Ticket Generation & Verification System

An automated event ticketing system built with **Python** for personalized QR-enabled ticket generation and web-based ticket verification.

## Overview

**Linket** automates the workflow from participant registration to verified event entry.

Participant data is processed to generate unique ticket identifiers, which are encoded into QR codes and embedded into personalized event tickets. At the event, the QR code can be scanned to validate the ticket through a web-based verification interface.

## Workflow

**Registration → QR Ticket → QR Scan → Verified**

<p align="center">
  <img src="Linket%20Flow.png" alt="Linket workflow" width="850">
</p>

## Key Features

- Automated personalized ticket generation
- Unique ticket identification
- QR-code generation and embedding
- Template-based ticket image composition
- Web-based QR ticket verification
- Ticket validity and verification status display
- Duplicate scan detection and scan-status tracking
- Batch processing of participant registration data

## Technology Stack

| Technology | Purpose |
|---|---|
| **Python** | Core automation and application logic |
| **Pandas** | Participant data processing |
| **Flask** | Web-based verification interface |
| **Pillow (PIL)** | Ticket image generation and composition |
| **QR Code Generation** | Unique QR creation and encoding |
| **HTML/CSS** | Verification interface |

## Implementation Flow

1. **Registration** — Participant information is collected in a structured dataset.
2. **Identification** — A unique ticket identifier is assigned to each participant.
3. **QR Generation** — The identifier is encoded into a unique QR code.
4. **Ticket Generation** — Participant details and the QR code are incorporated into a predefined ticket template.
5. **QR Scan** — The generated ticket is scanned at the event.
6. **Verification** — The verification system validates the ticket and displays its status.
7. **Status Tracking** — The scan status is recorded to support duplicate-scan detection.

## Results

The system was successfully used to generate **90 personalized QR-enabled event tickets** for an event.

Each ticket contained a unique QR code connected to the verification workflow, enabling digital ticket validation at the point of entry.

## Project Showcase

<table>
<tr>
<td align="center">
<strong>Ticket Template</strong><br><br>
<img src="Ticket%20Templet.png" width="180">
</td>

<td align="center" valign="middle">
<h2>→</h2>
</td>

<td align="center">
<strong>Generated QR Ticket</strong><br><br>
<img src="Generated%20Ticket.png" width="180">
</td>

<td align="center" valign="middle">
<h2>→</h2>
</td>

<td align="center">
<strong>QR Verification</strong><br><br>
<img src="Verification%20Server%20Screen.png" width="180">
</td>

</tr>
</table>

## Project Contribution

Developed the automated ticket generation and QR-based verification workflow, including:

- Participant data processing
- Unique ticket identification
- QR code generation
- Template-based ticket composition
- Automated ticket image generation
- Web-based ticket validation
- Scan-status handling

## Repository Note

This repository is a **project showcase** containing selected visuals and documentation.

The complete implementation source code and participant data are **not publicly distributed**.
