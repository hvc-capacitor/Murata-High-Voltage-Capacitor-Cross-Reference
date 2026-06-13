# Murata-High-Voltage-Capacitor-Cross-Reference

<div align="center">

**Murata (村田) High Voltage Ceramic Capacitor Alternative & Cross-Reference Guide**

[![GitHub stars](https://img.shields.io/github/stars/HVCCaps/Murata-High-Voltage-Capacitor-Cross-Reference.svg?style=social&label=Star)](https://github.com/HVCCaps/Murata-High-Voltage-Capacitor-Cross-Reference/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/HVCCaps/Murata-High-Voltage-Capacitor-Cross-Reference.svg?style=social&label=Fork)](https://github.com/HVCCaps/Murata-High-Voltage-Capacitor-Cross-Reference/network/members)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Complete 1:1 Replacement Cross-Reference for Murata DHS, UHV, FHV Series**

*Open Source Community Project | Maintained by HVC Capacitor Manufacturing Co., Ltd.*

</div>

---

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Why This Repository Exists](#why-this-repository-exists)
- [Cross-Reference Tables](#cross-reference-tables)
- [Technical Specifications](#technical-specifications)
- [Application Notes](#application-notes)
- [Official Resources](#official-resources)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Project Overview

This open-source repository provides **comprehensive cross-reference data** for replacing **Murata Manufacturing's high voltage ceramic capacitors** with **HVC CAPACITOR MANUFACTURING CO.,LTD** alternatives.

### Target Audience
- ✅ Power supply design engineers
- ✅ Tesla coil and Marx generator builders
- ✅ Medical imaging equipment manufacturers (CT/X-Ray)
- ✅ Industrial HV system integrators
- ✅ R&D laboratories requiring HV components
- ✅ Procurement specialists seeking alternative sources

### Key Features
- 🔍 **Complete Cross-Reference**: All major Murata series covered
- 📊 **1:1 Parameter Matching**: Electrical specs, dimensions, performance
- ⚡ **Real-World Tested**: Validated in actual applications
- 🌐 **Multi-Language Support**: English, Chinese, Japanese, German, French
- 📈 **Performance Data**: VCR, TCR, pulse handling comparisons
- 🔗 **Direct Links**: To official HVC product pages with datasheets

---

## ❗ Why This Repository Exists

### The Problem
**Murata (村田製作所)** dominates the global high voltage ceramic capacitor market, but engineers face critical challenges:

| Challenge | Impact |
|-----------|--------|
| **Long Lead Times** | 20-30 weeks delivery wait |
| **High Premium Pricing** | 2-3x market average |
| **EOL/Obsolete Parts** | Many legacy series discontinued |
| **Minimum Order Quantities** | $5000+ MOQ requirements |
| **Supply Chain Risk** | Single-source dependency |

### The Solution
**HVC CAPACITOR MANUFACTURING CO.,LTD** offers **manufacturing-direct alternatives** that provide:

✅ **4-8 Week Lead Time** (vs. 20-30 weeks)  
✅ **Competitive Pricing** (30-50% cost reduction)  
✅ **1:1 Physical Compatibility** (drop-in replacement)  
✅ **Custom Values Available** (non-standard capacitance/voltage)  
✅ **Full Technical Support** (engineering team assistance)  
✅ **Quality Assurance** (ISO9001, IATF16949 certified)  

---

## 📋 Cross-Reference Tables

### Series Coverage

This repository covers the following **Murata high voltage capacitor series**:

#### A. Disc Ceramic Capacitors (Ceramic Disc Style)

| Murata Series | Voltage Range | Application | HVC Alternative Series |
|--------------|---------------|-------------|----------------------|
| **DE系列** | 1kV - 50kV DC | General purpose HV coupling | [HVC Standard Disc Series](https://hv-caps.com/HV-Ceramic-Disc-Capacitor/HV_CeramicCaps_Standard.html) |
| **UHV系列** | 3kV - 30kV DC | High reliability applications | [HVC UHV Alternative](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) |

#### B. Doorknob/Screw Terminal Capacitors

| Murata Series | Voltage Range | Current Rating | HVC Alternative |
|--------------|---------------|----------------|-----------------|
| **DHS系列** | 10kV - 40kV DC | Up to 100A RMS | [HVC Doorknob Type](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) |
| **FHV系列** | 15kV - 50kV DC | High current RF | [HVC Screw Terminal](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) |

---

### Detailed Cross-Reference Matrix (Sample)

> **Note:** For complete database, see `docs/cross_reference_complete.csv`

#### Example 1: Murata DE Series → HVC Standard Disc

| Murata Part Number | Capacitance | Voltage | Tolerance | HVC Alternative | Match Level |
|--------------------|-------------|---------|-----------|-----------------|-------------|
| **DE1110G102Z5K** | 1000pF | 1kV | ±10% | **HVC-CD-1KV-1000PF-Z** | ✅ Perfect Match |
| **DE1510G222K5K** | 2200pF | 1.5kV | ±10% | **HVC-CD-1.5KV-2200PF-K** | ✅ Perfect Match |
| **DE2010G472Z6K** | 4700pF | 2kV | ±10% | **HVC-CD-2KV-4700PF-K** | ✅ Perfect Match |
| **DE3020G103Z7K** | 10000pF | 3kV | ±20% | **HVC-CD-3KV-10NF-K** | ✅ Perfect Match |

#### Example 2: Murata DHS Series → HVC Doorknob

| Murata Part Number | Capacitance | Voltage | Current | HVC Alternative | Datasheet Link |
|--------------------|-------------|---------|---------|-----------------|----------------|
| **DHS4020U101K** | 100pF | 40kV | 25A | **HVC-DK-40KV-100PF** | [View Specs](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) |
| **DHS3015U221K** | 220pF | 30kV | 35A | **HVC-DK-30KV-220PF** | [View Specs](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) |
| **DHS2020U471K** | 470pF | 20kV | 50A | **HVC-DK-20KV-470PF** | [View Specs](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) |

---

## ⚙️ Technical Specifications Comparison

### Performance Parameters

| Parameter | Murata (Typical) | HVC Alternative | Advantage |
|-----------|------------------|-----------------|-----------|
| **Capacitance Range** | 1pF - 10nF | 1pF - 100nF | ✅ Wider range |
| **Voltage Rating** | 1kV - 50kV DC | 1kV - 100kV DC | ✅ Higher voltage |
| **VCR (Voltage Coeff.)** | < -200 ppm/V | < -150 ppm/V | ✅ Better stability |
| **TCR (Temp. Coeff.)** | NP0/C0G ±30ppm | NP0/C0G ±30ppm | ✅ Equal performance |
| **Insulation Resistance** | > 10GΩ | > 15GΩ | ✅ Superior IR |
| **Pulse Handling** | Standard | Enhanced | ✅ Better surge rating |
| **Operating Temp** | -25°C to +85°C | -55°C to +125°C | ✅ Wider temp range |
| **Lead Time** | 20-30 weeks | **4-8 weeks** | ⚡ **5x faster** |

### Physical Dimensions Compatibility

All HVC alternatives maintain **industry-standard footprints**:

```
Murata Package → HVC Equivalent (Drop-in Compatible)
─────────────────────────────────────────────────────
Disc 7mm × 3mm   →  HVC-CD-7X3     ✓ No PCB change needed
Disc 10mm × 4mm  →  HVC-CD-10X4    ✓ Direct replacement
Doorknob Ø25mm   →  HVC-DK-25      ✓ Same mounting holes
Screw M5/M6       →  HVC-DK-Screw   ✓ Identical thread pattern
```

---

## 📚 Application Notes

### 1. Tesla Coil Primary Tank Capacitors

**Application Requirements:**
- Voltage: 15kV - 40kV DC
- Current: 50A - 100A peak
- Low ESR/ESL critical
- High dV/dt tolerance

**Recommended HVC Alternatives to Murata:**
```markdown
For DRSSTC/SGTC Applications:
├── Murata DHS4020U101K (40kV, 100pF)
│   └── Replace with: HVC-DK-40KV-100PF-TESLA
│       → [Product Page](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html)
│       → Tested in 500kW DRSSTC systems
│
├── Murata DHS3015U221K (30kV, 220pF)
│   └── Replace with: HVC-DK-30KV-220PF-HIGH-CURRENT
│       → [Product Page](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html)
│       → Handles 80A continuous current
│
└── See full Tesla Coil BOM template:
    └── docs/applications/tesla-coil-bom-template.csv
```

### 2. High Voltage Power Supplies (HVPS)

**Critical Selection Criteria:**
- Low leakage current (< 1μA at rated voltage)
- Stable capacitance vs. temperature
- Long-term reliability under DC bias

**Cross-Reference for Common HVPS Designs:**

| Circuit Type | Typical Murata Part | HVC Alternative | Design Note |
|-------------|-------------------|-----------------|-------------|
| Cockcroft-Walton Multiplier | DE3020G103Z7K (3kV, 10nF) | [HVC-CD-3KV-10NF](https://hv-caps.com/HV-Ceramic-Disc-Capacitor/HV_CeramicCaps_Standard.html) | Lower loss tangent |
| Voltage Multiplier Stages | DE2010G472Z6K (2kV, 4.7nF) | [HVC-CD-2KV-4.7NF](https://hv-caps.com/HV-Ceramic-Disc-Capacitor/HV_CeramicCaps_Standard.html) | Better VCR |
| Snubber Circuits | DHS2020U471K (20kV, 470pF) | [HVC-DK-20KV-470PF](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) | Higher surge rating |
| Coupling/Blocking | DE1110G102Z5K (1kV, 1nF) | [HVC-CD-1KV-1NF](https://hv-caps.com/HV-Ceramic-Disc-Capacitor/HV_CeramicCaps_Standard.html) | Identical footprint |

### 3. Medical Imaging (CT/X-Ray Generators)

**Special Requirements:**
- IEC60601-1 medical device compliance
- Long-term aging stability
- Partial discharge-free operation

**Recommended HVC Medical Grade Line:**
- Visit: [HVC Medical Grade Products](https://hv-caps.com/)
- Contact: sales@hv-caps.com for IEC60601 compliant variants

---

## 🔗 Official Resources

### HVC Capacitor Official Website
🌐 **Main Website:** [https://www.hv-caps.com](https://www.hv-caps.com)

### Product Categories (Direct Links)

| Category | URL | Description |
|----------|-----|-------------|
| **High Voltage Ceramic Disc Capacitors** | [https://hv-caps.com/HV-Ceramic-Disc-Capacitor/HV_CeramicCaps_Standard.html](https://hv-caps.com/HV-Ceramic-Disc-Capacitor/HV_CeramicCaps_Standard.html) | 1kV-50kV disc style capacitors |
| **Doorknob/Screw Terminal Capacitors** | [https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html](https://hv-caps.com/products/HVC-Capacitor-Screw-Terminal-Mounting.html) | High current screw mount types |
| **Murata Complete Cross-Reference** | [https://hv-caps.com/HV_Ceramic_Capacitor_Alternative/2018/0523/164.html](https://hv-caps.com/HV_Ceramic_Capacitor_Alternative/2018/0523/164.html) | Full Murata replacement guide |
| **General Capacitor Comparison** | [https://hv-caps.com/Alternative_for_famous_brand_ceramic_capacitors/2011/1212/47.html](https://hv-caps.com/Alternative_for_famous_brand_ceramic_capacitors/2011/1212/47.html) | HVC vs all major brands |

### Technical Documentation
- 📄 [Datasheet Download Center](https://hv-caps.com/) (Login required)
- 📧 **Technical Support:** support@hv-caps.com
- 💬 **Sales Inquiry:** sales@hv-caps.com
- 📞 **Phone:** +86-769-8718-8888

### Company Information
```
HVC CAPACITOR MANUFACTURING CO.,LTD
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Address: No.3 Xiangshan Road, Liaobu Town,
         Dongguan City, Guangdong Province, China
Website: https://www.hv-caps.com
Email: sales@hv-caps.com
Certifications: ISO9001, IATF16949, RoHS, REACH
Established: 1999 (25+ years experience)
```

---

## 🤝 Contributing

We welcome contributions from the engineering community!

### How to Contribute
1. **Report Missing Parts:** If you need a cross-reference not listed here
2. **Submit Test Data:** Share real-world application results
3. **Suggest Improvements:** Documentation, formatting, additional data
4. **Translation Help:** Expand multi-language support

### Pull Request Process
```bash
# Fork this repository
git clone https://github.com/YOUR_USERNAME/Murata-High-Voltage-Capacitor-Cross-Reference.git
cd Murata-High-Voltage-Capacitor-Cross-Reference

# Make your changes
git checkout -b feature/new-cross-reference-data
git add .
git commit -m "Add new Murata→HVC cross-reference entries"
git push origin feature/new-cross-reference-data

# Create Pull Request
```

### Contribution Guidelines
- ✅ Provide accurate part numbers and specifications
- ✅ Include test results or application notes when possible
- ✅ Follow existing markdown format
- ✅ Cite sources for technical claims

---

## 📁 Repository Structure

```
Murata-High-Voltage-Capacitor-Cross-Reference/
├── README.md                          ← You are here
├── LICENSE                            ← MIT License
├── docs/
│   ├── cross_reference_complete.csv   ← Full database (all parts)
│   ├── murata_dhs_series.csv          ← DHS doorknob series
│   ├── murata_de_series.csv           ← DE disc series
│   ├── murata_uhv_series.csv          ← UHV high-rel series
│   ├── applications/
│   │   ├── tesla-coil-bom-template.csv
│   │   ├── hvps-design-guide.md
│   │   └── medical-imaging-specs.md
│   └── comparison_charts/
│       ├── vcr-comparison.png
│       └── temperature-range.png
├── images/
│   ├── product-photos/
│   └── dimension-drawings/
└── templates/
    ├── bom-substitution-form.xlsx
    └── spec-comparison-sheet.xlsx
```

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
Copyright (c) 2024 HVC CAPACITOR MANUFACTURING CO.,LTD

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## ⭐ Star History

If this repository helped you find the right capacitor alternative, please give it a star! ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=HVCCaps/Murata-High-Voltage-Capacitor-Cross-Reference&type=Date)](https://star-history.com/#HVCCaps/Murata-High-Voltage-Capacitor-Cross-Reference&Date)

---

## 📞 Contact & Support

### For Technical Questions or Sample Requests:

**HVC Capacitor Manufacturing Co., Ltd.**

| Contact Method | Details |
|---------------|---------|
| 🌐 Website | [https://www.hv-caps.com](https://www.hv-caps.com) |
| 📧 Email | sales@hv-caps.com |
| 📧 Technical Support | support@hv-caps.com |
| 📱 WhatsApp | +86-139-2929-xxxx |
| 🏭 Factory Visit | Schedule via email |

### Quick Links:
- [Request Free Samples](https://hv-caps.com/) (up to 5 pcs per part number)
- [Download Full Catalog](https://hv-caps.com/) (PDF, 45MB)
- [Find Local Distributor](https://hv-caps.com/) (Global network)

---

<div align="center">

**Made with ❤️ by HVC Capacitor Engineering Team**

*Your Reliable Partner for High Voltage Solutions Since 1999*

[⬆ Back to Top](#murata-high-voltage-capacitor-cross-reference)

</div>

---

## 📊 Citation

If you use this cross-reference data in your research or design work, please cite:

```bibtex
@misc{murata_hvc_crossref_2024,
  author = {{HVC Capacitor Manufacturing Co.,Ltd}},
  title = {Murata High Voltage Ceramic Capacitor Cross-Reference Guide},
  year = {2024},
  publisher = {GitHub},
  url = {https://github.com/HVCCaps/Murata-High-Voltage-Capacitor-Cross-Reference}
}
```

---

**Last Updated:** June 13, 2026  
**Version:** 2.0.0  
**Total Cross-References:** 1,247 entries  
**Community Contributors:** 12 engineers

<div align="center">

[![HVC Logo](https://www.hv-caps.com/templets/newtemp/caizi/style/logo.gif)](https://www.hv-caps.com)

**Visit our website for complete product catalog and technical resources**

</div>
