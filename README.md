# Linket — QR-Based Ticket Generation & Verification System

An automated event ticketing system built with Python to generate personalized QR-enabled tickets and verify ticket validity through a web-based interface.

## Overview

Linket automates the ticketing workflow from participant registration to QR-based verification.

The system processes participant data, assigns unique ticket identifiers, generates personalized event tickets with embedded QR codes, and provides a web-based interface for validating scanned tickets and tracking their scan status.

## Workflow

**Registration → QR Ticket → QR Scan → Verified**

![Linket Workflow](Linket%20Flow.png)

## Key Features

- Automated generation of personalized event tickets
- Unique ticket identification for each participant
- QR-code generation and embedding into ticket designs
- Automated ticket image generation using predefined templates
- Web-based QR ticket verification
- Ticket validation and verification status display
- Duplicate scan detection and scan-status tracking
- Batch processing of participant registration data

## Technology Stack

- **Python** — core application logic and automation
- **Pandas** — participant data processing
- **Flask** — web-based ticket verification
- **Pillow (PIL)** — ticket image generation and processing
- **QR Code Generation** — unique QR creation and encoding
- **HTML/CSS** — verification interface

## Implementation Flow

1. Participant registration data is processed from a structured dataset.
2. A unique ticket identifier is assigned to each participant.
3. The identifier is encoded into a unique QR code.
4. The QR code and participant information are incorporated into a personalized ticket template.
5. The generated QR ticket is scanned at the event.
6. The verification system validates the ticket and displays its status.
7. Scan status is recorded to prevent repeated use of the same ticket.

## Results

The system was successfully used to generate **90 personalized QR-enabled event tickets** for an event.

Each ticket contained a unique QR code linked to the verification workflow, enabling digital validation at the point of entry.

## Project Showcase

### Ticket Template

![Ticket Template](Ticket%20Templet.png)

### Generated QR Ticket

![Generated Ticket](Generated%20Ticket.png)

### QR Verification

![Verification Interface](Verification%20Server%20Screen.png)

## Project Contribution

Developed the automated ticket generation and QR-based verification workflow, including participant data processing, unique ticket identification, QR generation, ticket image composition, and web-based validation.

## Repository Note

This repository is a **project showcase** containing selected visuals and documentation.

The complete implementation source code and participant data are not publicly distributed.
