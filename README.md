# ePAWP Calculator

## Quantitative estimation of pulmonary artery wedge pressure using echocardiography

A web-based clinical calculator for non-invasive estimation of pulmonary artery wedge pressure (PAWP) using standard echocardiographic parameters.

## Overview

This calculator implements the validated formula from recent research published in the European Heart Journal - Imaging Methods and Practice, allowing clinicians to estimate PAWP without invasive catheterization or left atrial volume measurements.

### Required Parameters

1. **Mitral E-wave velocity** (cm/s) - Peak early diastolic mitral inflow velocity
2. **Pulmonary vein systolic velocity (S)** (cm/s) - Peak systolic flow velocity in pulmonary veins
3. **Pulmonary vein diastolic velocity (D)** (cm/s) - Peak diastolic flow velocity in pulmonary veins

### Formula

```
ePAWP (mmHg) = 2.4 + E/S × 2.76 + D [cm/s] × 0.106
```

## Important Clinical Limitations

⚠️ **Not applicable in:**
- Non-sinus rhythms (atrial fibrillation, atrial flutter, etc.)
- At least moderate mitral valvular lesions (stenosis or regurgitation)


## Usage

1. Open the HTML file in any web browser
2. Enter the three required echocardiographic measurements
3. Click "Calculate ePAWP" to get the estimated PAWP value
4. Interpret results using the provided reference ranges

## Installation & Deployment

### Local Usage
1. Download the HTML file
2. Open in any web browser
3. No installation required

### Web Deployment
The calculator can be deployed on any web hosting service:
- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting

## Scientific Validation

This calculator is based on peer-reviewed research demonstrating high diagnostic and prognostic accuracy for PAWP estimation without requiring left atrial volume measurements.

### Citation

Thomas Lindow, Aristomenis Manouras, Geoff Strange, Per Lindqvist, David Playford, Odd Bech-Hanssen, Martin Ugander, Echocardiography can accurately estimate pulmonary artery wedge pressure without left atrial volume information – diagnostic and prognostic performance, *European Heart Journal - Imaging Methods and Practice*, 2025;, qyaf082

**DOI**: [https://doi.org/10.1093/ehjimp/qyaf082](https://doi.org/10.1093/ehjimp/qyaf082)

## License

This calculator is provided for educational and clinical use. Please cite the original research when using this tool in research.

## Disclaimer

This tool is intended for use by qualified healthcare professionals. Clinical decisions should always incorporate multiple factors and professional medical judgment. The authors and developers assume no responsibility for clinical decisions made using this calculator.

## Contributing

This is a single-file HTML application. Suggestions for improvements can be made by:
- Creating issues for bug reports or feature requests
- Submitting pull requests with improvements
- Providing feedback on clinical usability

## Version History

- **v1.0** - Initial release with core calculation functionality
- Clean, responsive design optimized for clinical use
- Mobile-friendly interface
- Comprehensive input validation

## Support

For technical issues or clinical questions about the underlying research, please refer to the original publication or contact the research authors through the journal.
