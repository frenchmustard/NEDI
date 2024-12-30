# NEDI

**NEDI** (Nim EDI) is a library for parsing and generating EDIFACT and X12 messages in the Nim programming language. This project initially started for me to get some knowledge in about the Nim language and is more a proof-of-concept library, use at your own discretion essentially.

---

## Table of Contents
1. [Features](#features)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
   - [Parsing an EDIFACT Message](#parsing-an-edifact-message)
   - [Writing an EDIFACT Message](#writing-an-edifact-message)
   - [Parsing an X12 Message](#parsing-an-x12-message)
   - [Writing an X12 Message](#writing-an-x12-message)
5. [Contributing](#contributing)
6. [License](#license)

---

## Features

- **EDIFACT & X12 Parsing**: Turn EDI text into structured Nim objects.  
- **EDIFACT & X12 Writing**: Convert structured Nim objects back into valid EDI strings.  
- **Strict or Lenient Parsing** (future feature ideas): Configure how strictly you interpret invalid segments.  
- **Lightweight**: Focused on core EDI parsing/writing (no built-in AS2 transport, etc.).

---

## Installation

First, make sure you have Nim installed. Then clone the [frenchmustard/NEDI](https://github.com/frenchmustard/NEDI) repo and install via Nimble:

```bash
git clone https://github.com/frenchmustard/NEDI.git
cd NEDI
nimble install
