# ArchField – Architecture Project Tool

ArchField is a comprehensive web-based architecture project management and compliance checking tool. It streamlines architectural planning, SANS 10400 compliance verification, material calculations, and energy efficiency analysis.

## Features

- **Drawing Tool** - Canvas-based architectural sketching
- **Plan Analyzer** - Upload and analyze PDF and Revit files
- **Floor Area Calculator** - Quick area calculations for spaces
- **Material Calculator** - Track and calculate material quantities
- **SANS 10400 Compliance** - South African building standards compliance checker
- **XA Energy Check** - Building energy efficiency analysis
- **Live Bill of Quantities (BoQ)** - Real-time project material tracking

## Project Structure

Organized into modular JavaScript components with comprehensive documentation.

## Installation

1. Clone the repository:
git clone https://github.com/aidonandrew/Archfield-.git
cd Archfield-

2. Install dependencies:
npm install

3. Start development server:
npm run dev

## Technology Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Build Tool**: Webpack
- **Testing**: Jest
- **PDF Support**: PDF.js
- **Node.js**: v14+

## Usage

### Floor Area Calculator
- Input length and width
- Click "Calculate" to get total area in m²

### Material Calculator
- Automatically tracks quantities for bricks, concrete, and plaster
- Updates dynamically as you input values

### SANS 10400 Compliance
- Reference all 22 parts of South African building standards
- Check specific compliance requirements for your project

### XA Energy Check
- Input window area and floor area
- Get glazing ratio analysis for energy efficiency

## License

This project is licensed under the MIT License.

## Author

**Aidan Andrew** - [@aidonandrew](https://github.com/aidonandrew)