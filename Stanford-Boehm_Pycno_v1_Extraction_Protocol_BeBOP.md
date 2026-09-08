<style>
ol ul, ol ol, ul ul, ul ol {
  margin-top: 0;
  margin-bottom: 0;
}
</style>

---
title: Stanford-Boehm_Pycno_v1_Extraction_Protocol_BeBOP

---

---
# MIOP terms

methodology_category: sample extraction and purification
project: Boehm Lab, Stanford University, eDNA Protocols
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: Pacific Ocean [GAZ:00000360], Monterey Bay [GAZ:00002509]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine benthic biome[ENVO:01000024]
local_environmental_context: marine biome [ENVO:00000447], marine benthic biome[ENVO:01000024], aquarium [ENVO:00002196]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator: Meghan M. Shea
materials_required: vortexer [OBI:0400118], centrifuge [OBI:0400106], incubator [OBI:0000136]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 1800
personnel_required: 1
language: en
issued: 2026-09-08
audience: scientists
publisher: Stanford University, Boehm Laboratory
hasVersion: 1.0.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms

samp_vol_we_dna_ext: 1000
samp_vol_we_dna_ext_unit: mL
nucl_acid_ext_lysis: physical | enzymatic | thermal
nucl_acid_ext_sep: column-based
nucl_acid_ext: XXX [add link to this protocol]
nucl_acid_ext_kit: QIAGEN DNeasy Blood and Tissue Kit, 250
nucl_acid_ext_modify: Modified for sterivex, reagent volume altered
dna_cleanup_0_1: 0
dna_cleanup_method: not applicable
concentration: not applicable
concentration_unit: ng/µl
concentration_method: Qubit Fluorometer v.4 dsDNA high sensitivity kit
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable

---

# Stanford-Boehm_Pycno_v1_Extraction_Protocol_BeBOP



## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY   | AFFILIATION   | ORCID         | DATE          |
| ------------- | ------------- | ------------- | ------------- |
| Meghan M. Shea  | Stanford University  |[0000-0002-7419-6654](https://orcid.org/0000-0002-7419-6654) | 2026-09-03    |
| Alexandria B. Boehm | Stanford University  |[0000-0002-8162-5090](https://orcid.org/0000-0002-8162-5090) | 2026-09-08|


### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protcols from manufacturers or other groups.


| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| Coastal Environmental DNA Sampling & Gravity Filtration Protocol  | https://dx.doi.org/10.17504/protocols.io.bp2l69y7klqe/v2 | 2.0 | 2023-7-27   | Internal      |
| DNA Extraction Protocol from Sterivex Filters  | https://dx.doi.org/10.17504/protocols.io.ewov1qyyygr2/v1 | 1.0 | 2023-08-01   | Internal      |
| Extraction Protocol for Sterivex Using a Centrifuge (NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group)  | https://doi.org/10.5281/zenodo.11398154| 1.1.4 | 2025-11-14   | External      |
| Spens et al. 2017 |https://doi.org/10.1111/2041-210X.12683 | 1.0  | 2016-11-15  | External |
| Qiagen DNeasy Blood & Tissue Kit Handbook |https://www.qiagen.com/en-US/resources/download/kitHandbookAndProtocol/hb-2061-004-hb-dny-blood-tissue-0623-ww | 1.0  | June 2023  | External |


### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2026-09-08 | Initial release |


### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|BSC	|Biosafety cabinet |
|DNA	|Deoxyribonucleic acid|
|eDNA	|environmental DNA|
|EtOH| Ethanol|
|NOAA|National Oceanic and Atmospheric Administration|
|PCR| Polymerase chain reaction |
|PPE    | Personal protective equipment |
|PVDF | Polyvinylidene fluoride |
|UV| Ultraviolet|


### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Extraction blank  | Extraction negative control. Typically, nuclease-free water or an empty filter is run through the DNA extraction process to control for contamination in the DNA extraction step.  |
| Field blank  | Sampling negative control. Typically, distilled or reverse osmosis water is run through a filter like a seawater eDNA sample to control for contamination in the field sampling step.  |
| No template control | PCR negative control. Typically, nuclease-free water is loaded in place of a sample on a PCR to control for contamination in the PCR step. |
| Positive control  | PCR positive control. Typically, a synthetic DNA strand, non-indigenous DNA extract, or intentionally designed mock community is loaded in place of a sample on a PCR to control for contamination and index hopping in the PCR step. |


## BACKGROUND

This document describes the required protocol to extract DNA from a 0.22 µm PVDF sterivex filter.

This protocol was modified and adapted from our previously published [DNA Extraction Protocol from Sterivex Filters](https://dx.doi.org/10.17504/protocols.io.ewov1qyyygr2/v1); we also utilized the NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group [Extraction Protocol for Sterivex Using a Centrifuge](https://doi.org/10.5281/zenodo.11398154) as a guide for proper BeBOP formatting. 


### Summary

This protocol describes the steps for extracting DNA from 0.22 µm PVDF sterivex filters, as generated through, e.g.,  [this sampling protocol](https://dx.doi.org/10.17504/protocols.io.bp2l69y7klqe/v2). Nucleic acid extraction from the sterivex filters utilizes the Qiagen DNeasy Blood & Tissue Kit with some modifications to [the manufacturer's protocol](https://www.qiagen.com/en-US/resources/download/kitHandbookAndProtocol/hb-2061-004-hb-dny-blood-tissue-0623-ww). These modifications were first detailed in [Spens et al. 2017](https://doi.org/10.1111/2041-210X.12683)


### Method Description and Rationale

The [Spens et al 2017](https://doi.org/10.1111/2041-210X.12683) protocol is a widely used, highly reproducible, and easily executable DNA extraction protocol from sterivex filters. Sterivex filters are a commonly used filter for seawater and freshwater sampling, including by the [PMEL Ocean Molecular Ecology Program](https://www.pmel.noaa.gov/ocean-molecular-ecology/) and the [NOAA CalCOFI Ocean Genomics](https://calcofi.com/index.php?option=com_content&view=category&layout=blog&id=234&Itemid=1142) group. This extraction protocol from sterivex samples has been demonstrated to generate sufficient DNA yields while minimizing contamination ([Spens et al 2017](https://doi.org/10.1111/2041-210X.12683), [Shea et al. 2024](https://doi.org/10.1002/edn3.521)).

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to extract DNA from filtered seawater samples from intertidal and coastal environments in California, including Monterey Bay, CA and Half Moon Bay, CA. Samples collected range in depth from surface ocean (epipelagic biome) to just off bottom (benthic biome). 

## Personnel Required

One person with molecular biology experience. 

### Safety

Buffer AW1 from the DNeasy Blood & Tissue Kit contains guanidine hydrochloride and is classified as category 4 for acute toxicity [(Safety Data Sheet)](https://www.qiagen.com/binary/resource/sds/800000000214-en-GB-IE--1/214-BufferAW1-en-GB-IE--1.00000.pdf). Additional care should be taken when working with this buffer. This protocol also uses bleach and ethanol, both of which are classified as hazardous chemicals. Appropriate PPE must be worn, and standard safety procedures should be followed to avoid skin and eye exposure.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and previous DNA/RNA extraction experience) is required to conduct this protocol.

### Time Needed to Execute the Procedure

Extracting DNA from 23 sterivex samples, including an extraction blank, takes approximately 30 hours (1800 minutes), including a 24 hour incubation period. This involves about 2 hours of active laboratory time on Day 1 and 5 hours of of active laboratory time on Day 2.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

For a full extraction set, including 22 eDNA samples and an extraction blank: 

**Durable equipment**

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
|Biosafety Cabinet | Purifier Class II Biosafety Cabinet [36205 DS]| LABCONCO | 1 | Can be substituted with generic - internal UV light required |
|Incubator | Incubator [1525]| VWR | 1-2 | Can be substituted with generic; just needs to reach 56°C, have an internal outlet, and fit roller shaker (below). Thermo Fisher Heratherm™ Advanced Protocol Microbiological Incubators also work well |
|Tube Roller | Southwest Horizonal Tube Roller [STL100]| Southwest Science | 1-2 | Can be substituted with generic; just needs to be rated to at least 56°C and fit in incubator (above) |
| Centrifuge | Benchtop Microcentrofuge [5424] | Eppendorf | 1 | Can be substituted with generic - needs to fit 1.5 mL tubes. |
| Vortex | Mini Vortex Mixer Advanced [EF25348] | LabGenius | 1 | Can be substituted with generic. |
| Freezer | Freezer capable of reaching and maintaining -20°C | Generic | 1 | Used to store DNA aliquots | 
|-80°C freezer| Freezer capable of reaching and maintaining -80°C | Generic |1|Used to store DNA aliquots|
| Pipetter: 20 - 200 μL | Various | Various | 1 | Can be substituted with any accurate pipettor |
| Pipetter: 100-1000 μL | Various | Various | 1 | Can be substituted with any accurate pipettor |
| Heat Block | Fisher Scientific Dry Bath Incubator [11-718-2] | Fisher Scientific | 1 | Can be substituted with generic |
| Spray bottle | Spray bottles for 10% bleach solution, 70% ethanol solution, and RNase Away | Generic | 3 | |
| Small ice bin | Various | Various | 1 |  |
| Tip waste container | Pipette tip waste container | Generic | 1 |Sterilizable container (such as a plastic cup or graduated 1L beaker) capable of holding waste pipette tips. |
| Liquid waste container | Liquid waste container | Generic | 1 |Sterilizable container (such as a small beaker) capable of holding liquid waste in the biosafety cabinet before transferring to ultimate liquid waste disposal system. |
|Cryoboxes|81-place Polypropylene Microtube/Cryotube Storage Box|VWR [89085-514] |2|Can be substituted with generic; ensure they fit in -80°C freezer racks |
| Label printer | DYMO® LabelWriter® 550 Printer | GA International | 1 | Can be subsituted with other strategies for generating cryo labels |
| Rack for sterivex | Any rack that can hold Sterivex tubes upright (often similar to a 50 mL tube rack) | Various | 1 |  |
| Rack for 5 mL tubes | Any rack that can hold 5 mL LoBind tubes | Various | 1 |  |
| Rack for 1.5 mL tubes | 	80 Well Microtube Rack [e.g. 22-313630] | Fisher Scientific | 4 | Can be substituted with generic |
| Rack for 0.5 mL tubes | 	96-Well Flipper™ Microtube Racks [21-402-18]| Thermo Scientific | 1 | Can be substituted with generic |


**Consumable equipment**

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 200 μL pipette tips  | Rainin pipettes with LTS™ LiteTouch™, Sterilized, filter| Rainin | Approximately 140 | Can be subsituted with generic. Must be sterile and filtered. |
| 1000 μL pipette tips  | ART™ Barrier Extended Length Pipette Tips [2079-05-HR] | Thermo Scientific | Approximately 230 | Can be subsituted with generic. Must be sterile, filtered, and narrow enough to fit in Sterivex inlet. |
| 5 mL LoBind Tubes | Eppendorf DNA LoBind Tubes (5 mL) [14-282-305] |Fisher Scientific | 23 | Can be substituted with generic, must be sterile/PCR clean |
| 1.5 mL LoBind Tubes | Eppendorf DNA LoBind Tubes (1.5 mL) [13-698-791] |Fisher Scientific | 25 | Can be substituted with generic, must be sterile/PCR clean |
| 0.5 mL LoBind Tubes | Eppendorf DNA LoBind Tubes (0.5 mL) [13-698-790] |Fisher Scientific | 46 | Can be substituted with generic, must be sterile/PCR clean |
| Lab notebook | Durable, hardcover lab notebook | Generic | 1 | Dedicated to the lab space. |
| Writing utensils | Sharpies and pens | Generic | 2 | Dedicated to the lab extraction space. Not made of wood - must be able to be wiped down with bleach/EtOH |
| Kimwipes | Delicate task wipes | Kimtech | 5 | Can be substituted with generic. Must be lint-free. |
| Nitrile gloves | Various | Various | Many |  |
| 50 mL falcon tubes | Falcon 50 mL high clarity conical centrifuge tube | Corning Falcon | 1 | Can be substituted with generic. Must be sterile. |
| 3 mL luer lock syringes | 	
BD Disposable Syringes with Luer-Lok™ Tips [14-823-435] | Fisher Scientific | 22 | Can be subsituted with generic. Must be sterile and luer lock. |
| Cryo labels | 	
DYMO® LabelWriter™ 5-Series Cryogenic Labels for Frozen Surfaces – 23.9 mm x 12.7 mm + 9.5 mm [LWCS-506-WH] | GA International | 22 | Can be subsituted with other cryo label types |
| **QIAGEN Extraction Kit** | QIAGEN DNeasy Blood and Tissue Kit - 250 extractions [69506] | QIAGEN | 1 | For this protocol at scale (i.e., 250 samples), additional volumes of some buffers need to be purchased.|



**QIAGEN Kit Contents**

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| Spin columns | Mini spin column | **Included in kit** | 23 | Kit contains 250 columns - sufficient for 250 extractions using this protocol. |
| Collection tubes | 2 mL collection tube | **Included in kit**| 46 | Kit contains 500 tubes - sufficient for 250 extractions using this protocol. |
| Buffer ATL | QIAGEN Buffer ATL | **Included in kit, may need to purchase additional** | 16.56 mL | Kit contains 50 mL  - sufficient for 69 extractions using this protocol; requires 200 mL total for 250 extractions. |
| Proteinase K | QIAGEN Proteinase K | **Included in kit, may need to purchase additional** | 1840  μL  | Kit contains 6 mL - sufficient for 75 extractions using this protocol; requires 20 mL total for 250 extractions. |
| Buffer AL | QIAGEN Buffer AL | **Included in kit, may need to purchase additional** | 20.7 mL* | Kit contains 66 mL - sufficient for ~73 extractions using this protocol; requires ~225 mL total for 250 extractions. [Variable amount depending on how much liquid is recovered from each sterivex]|
| Buffer AW1 | QIAGEN Buffer AW1 | **Included in kit** | 11.5 mL | Kit contains 98 mL concentrate - sufficient for 250 extractions using this protocol. **Mix with 100% molecular grade EtOH before use, instructions on bottle** |
| Buffer AW2 | QIAGEN Buffer AW2| **Included in kit** | 11.5 mL| Kit contains 66 mL concentrate - sufficient for 250 extractions using this protocol. **Mix with 100% molecular grade EtOH before use, instructions on bottle** |
| Buffer AE | QIAGEN Buffer AE | **Included in kit** | 2300 μL | Kit contains 120 mL - sufficient for 1200 extractions using this protocol. |

**Chemicals**

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| 100% molecular grade EtOH | Ethanol, Absolute (200 Proof), Molecular Biology Grade, Fisher BioReagents™ [BP2818500] | Fisher Scientific | 20.7 mL*|Can be substituted with generic, must be 200 proof and molecular biology grade; also need additional EtOH for adding to Buffer AW1 and AW2 when first using DNeasy kit. [Variable amount depending on how much liquid is recovered from each sterivex] |
| 70% EtOH | Molecular grade ethanol | Generic | Various; depends on cleaning frequency |  |
| 10% Bleach | Hypochlorite Bleach | Clorox | Various; depends on cleaning frequency | Remake frequently as bleach decomposes quickly at 10% concentration |
| RNase Away | Thermo Scientific™ RNase AWAY™ Surface Decontaminant [14-375-35] | Fisher Scientific | Various; depends on cleaning frequency | Can be substituted with generic |
| Molecular-grade water | Water, DNA Grade, DNASE, Protease free, Fisher BioReagents [BP24701] | Fisher Scientific | 1000 µl | Can substitute with generic  |


## STANDARD OPERATING PROCEDURE


### Laboratory Set-Up

To minimize contamination, we utilize one specific biosafety cabinet for conducting DNA extractions that is separate from where we add DNA products to PCR plates or handle any high-concentration gBlocks. 


### Sample Management

When thinking about how many samples to process at once, it's important to consider how to optimize across the extraction protocol and any subsequent processing.

When doing ddPCR, we often [quantify samples](https://doi.org/10.5281/zenodo.20057580) on the same day that we generate our DNA extracts, to avoid the impact of freezing and thawing on our extracts. In this case, we conduct our extractions in batches of 22 samples (and 1 extraction blank), and then run our ddPCR assays as half plates (22 samples and extraction blank in duplicate, 1 positive control, and 1 NTC; 48 total reactions). We do this, in part, because our ddPCR automatic droplet generator needs a given 96-well plate to have full columns of samples, so our total reactions is best as a multiple of 8. However, this requires us to use multiple roller shakers and incubators, as our roller shaker only fits 15 sterivex filters at once. The remainder of this protocol will be tailored to this approach, but can be adjusted if you are running less or more samples at once.

When doing metabarcoding, and not quantifying samples via ddPCR, we typically conduct our extractions in batches of 15 samples (and 1 extraction blank), as this is the maximum number of samples that fit on a single roller shaker and is easy to balance in the centrifuge. In this case, only one incubator and roller shaker is needed. 

### Day 0 - Preparation

1. Clean biosafety cabinet with bleach, ethanol, and RNase away
2. Turn on incubator(s) and set to 56°C; set up tube roller in incubator
3. Soak all tube racks needed for both days of extraction protocol in a 10% bleach solution, followed by 3 rinses with DI water. Leave in biosafety cabinet to dry.

>**Note:**
>For extracting 22 Sterivex filters, recommend:
>
- 1 rack that can hold 22 Sterivex
- 1 rack that can hold 23 5 mL tubes
- 1 rack that can hold 46 .5 mL tubes
- ~4 racks that can hold 1.5/2 mL tubes

<ol start="4">
<li>

Inventory supplies and ensure that all tubes, reagents, and other supplies are ready
<ul>
<li>Make sure that 1000 µL pipette tips (that fit in the inlet of the Sterivex) and 200 µL pipette tips are placed in biosafety cabinet in preparation for Day 1</li>
<li>Ensure 100% molecular grade EtOH has been added to Buffer AW1 and AW2 according to the QIAGEN DNeasy Blood and Tissue Kit manufacturer's instructions</li>
</ul>
</li>
</ol>

### Day 1 - DNA Lysing and Preparation for Day 2

<ol start="5">
<li>Clean biosafety cabinet surfaces with bleach, ethanol, and RNase Away</li>

<li>Wipe down 1000 µL and 200 µL pipettes with RNase Away; place in biosafety cabinet if not already stored there</li>

<li>Turn on UV light in biosafety cabinet for at least 15 minutes</li>

<li>Assemble reagents needed:
<ul>
<li>Proteinase K (from Qiagen DNeasy Blood & Tissue Kit)</li>
<li>ATL Buffer (from Qiagen DNeasy Blood & Tissue Kit)</li>
</ul>
</li>
</ol>

>**Note:** Check Buffer ATL for precipitate; if present, put in incubator (56°C) for ~5 minutes to fully dissolve

</li>
</ol>

<ol start="9">
<li>Remove sterivex filters from -20°C freezer</li>

<li>For each filter:
<ul>
<li>Remove Sterivex from Whirl-Pak bag and remove cap from inlet end of Sterivex filter</li>
<li>Slowly pipette 80 µL of Proteinase K directly on top of the filter through the inlet, avoiding backsplash by expelling slowly</li>
<li>Slowly pipette 720 µL of ATL buffer directly on top of the filter through the inlet, again avoiding backsplash</li>
<li>Secure Sterivex with same luer cap</li>
<li>Handshake vigorously for several seconds</li>
</ul>

<li>Place all filters onto roller shaker in incubator</li>
<li>Incubate at 56°C for ~24 hours (minimum of 12 hours; try to incubate for the same amount of time for all filters for a particular project) while rotating at approximately 6 rpm</li>
<li>Prepare in advance for Day 2
<ul>
<li>Clean biosafety cabinet surfaces with bleach, ethanol, and RNase Away</li>
<li>Set up tubes needed for Day 2 in tube racks in biosafety cabinet
<ul>
<li>1.5/2 mL LoBind: # of samples + extraction blank</li>
<li>.5 mL LoBind: (# of samples + extraction blank) * 2 </li>
<li>5 mL LoBind: # of samples + extraction blank</li>
<li>Enough tubes (any type, does not need to be LoBind, to hold AE Buffer that fit in heat block; see Step 23)</li>
</ul>
<li>Turn on UV light in biosafety cabinet for at least 15 minutes</li>
<li>Make cryo-labels for storage tubes (.5 mL LoBind tubes)</li>
<li>Close tubes and label with sample numbers (1.5/2 mL LoBind, 5 mL LoBind) or cryo-labels (.5 mL LoBind tubes)</li>
<li>Add sterile 3 mL syringes (one per sample) to biosafety cabinet</li>
</ul>
</li>
</ol>


### Day 2 - DNA Extraction

<ol start="14">
<li>Clean biosafety cabinet and bench area (with vortex and centrifuge) with bleach, ethanol, and RNase away. 
<li>Wipe down 1000 µl pipette and 200 µl pipette RNase Away; place in biosafety cabinet if not already stored there
<li>Remove two tube racks and place on cleaned bench area 
<li>Turn on UV light in biosafety cabinet for at least 15 minutes
<li>Open and label additional tubes needed from Qiagen DNeasy Blood & Tissue Kit and place in removed tube rack: 
<ul>
<li>Packaged spin columns: # of samples + extraction blank
<li>Additional collection tubes: (# of samples + extraction blank) * 2
</ul>
<li>Place 50 mL tube of molecular-grade ethanol on ice to chill for later use
<li>Tape list of samples to biosafety cabinet so you can easily refer to it and record volumes of liquid removed
<li>Assemble other reagents needed and stage outside of biosafety cabinet:
<ul>
<li>AL Buffer (from Qiagen DNeasy Blood & Tissue Kit)
<li>Buffer AW1 (from Qiagen DNeasy Blood & Tissue Kit)
<li>Buffer AW2 (from Qiagen DNeasy Blood & Tissue Kit)

</ol>

>**Note:** Check Buffer AL for precipitate; if present, put in incubator (56°C) for ~5 minutes to fully dissolve

<ol start="22">
<li>Heat aliquot (volume calculation below) of AE buffer (from Qiagen DNeasy Blood & Tissue Kit) on heating block at 70°C 
<ul>

<i>Volume: (# of samples including blank * 100 µl) * 1.1</i>

</ul>
<li>Remove Sterivex filters from incubator and transfer to biosafety cabinet
<li>Remove liquid from each filter:
<ul>
<li>Handshake vigorously for several seconds
<li>Remove caps from filter
<li>Using a sterile 3 mL syringe attached to the inlet end of the Sterivex, remove all liquid from filter, record the volume, and transfer into a 5 mL LoBind tube
</ul>

<li> Create an extraction blank by adding 1000 uL nuclease free water subbed in for extracted liquid to a 5 mL LoBind tube
<li> For each sample and extraction blank, add AL buffer and 0°C ethanol to the extracted liquid in a 1:1:1 ratio and vortex vigorously for 10 seconds
<li> For each sample and extraction blank, filter the mixture through a spin column:
<ul>
<li>Pipet the mixture (650 µl at a time) into a DNeasy Mini Spin column placed in a collection tube
<li>Spin in micro-centrifuge for 1 minute at 6000 x g (8000 rpm)
<li>Discard flow throw, and dab the rim of the spin column dry on a Kimwipe
<li>Repeat sub-steps of 27 until all sample is filtered through spin column
</ul>

<li>Place the spin column in a new collection tube, add 500 µl Buffer AW1
<li>Centrifuge for 1 minute at 6000 x g (8000 rpm). Discard flow through and collection tube.
<li>Place in new collection tube and add 500 µl Buffer AW2
<li>Centrifuge for 3 min at 20,000 x g (14000 rpm) to dry the membrane
<li>Discard flow through and dab rim of spin column on a clean Kimwipe
<li>Place the spin column back in collection tube and centrifuge for 1 min at 20,000 x g (14000 rpm)
<li>Transfer spin column to new 1.5/2 mL LoBind tube with cap left open
<li>Place samples in 70°C heat block
<li>Add 100 µl Buffer AE (4 samples at a time) directly over membrane
<li>Immediately transfer tubes to room temperature
<li>Incubate at room temperature for 10 minutes
<li><i>[If immediately doing PCR, begin set-up now]</i>
<li>Centrifuge for 1 min at 6000 x g (8000 rpm)
<li>Re-elute DNA from DNA LoBind tube (apply eluate back on spin column while tubes are in heat block)
<li>Incubate at room temperature for 10 minutes
<li><i>[If immediately doing PCR, continue set-up now]</i>
<li>Centrifuge for 1 min at 6000 x g (8000 rpm)
<li>Discard the spin column

</ol>

>**Note:** Sample tubes should now contain a final volume of 100 µl of DNA extract

<ol start="46">
<li>Transfer ~50 µl of remaining DNA extract to 2 pre-marked .5 mL DNA LoBind tubes:
<ul>
<li>1 archive tube to store at -80°C
<li>1 working tube to store at -15°C
</ul>
</ol>

>**Note:** Aliquot to archive tube first, so that archive volumes are consistently 50 µl. Working tube volumes may be slightly less than 50 µl due to Qubit aliquot, etc.

### Quality Control

An extraction blank is included in every extraction batch; field blanks are also collected during sampling campaigns. Samples are PCR amplified alongside no template and positive controls. 

**Recommended (not required):** We split all DNA extracts into two aliquots: a working stock for immediate use at -20°C (~50 µl) in a 1.5 mL tube and an archival stock in a 1.5 mL tube and frozen at -80°C indefinitely (~50 µl). All are stored in labeled cryoboxes.

### Basic Troubleshooting Guide

**Issue 1:** Column clogging when pipetting the sample/Buffer AL/EtOH mixture to the spin columns

**Solution 1:** If a sample is turbid, solids may survive the digestion and lysis steps. These solids can clog the spin column and trap liquid above the filter. If repeating the spin-down step does not fully drain liquid from the column, use a second fresh column for the remainder of the sample. Both spin columns are then run through the protocol, and the eluted DNA is combined.

**Issue 2:** Bubbling of ATL out of sterivex upon addition

**Solution 2:** If the pipette tip is improperly seated in the inlet of the sterivex when adding buffer ATL, the buffer can spray upwards out of the inlet, introducing potential contamination to other samples. Ensure that the pipette tip is fully seated inside the inlet, and add buffer slowly to avoid overpressuring the sterivex. Suggest tilting the sterivex slightly to ensure the seal isn't too tight.

**Issue 3:** Liquid on sides of collection tube after centrifuge step following Buffer AW2 addition

**Solution 3:** Re-run the spin-down step in a fresh spin column. No additional buffer AW2 is added. If the issue persists, move to a new collection tube and respin.


## REFERENCES

Brown, S., Weinrich, J. (Han), & Gold, Z. (2025). marinednadude/NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge: V1.1.4. [https://doi.org/10.5281/zenodo.17655148](https://doi.org/10.5281/zenodo.17655148)

Shea, M. M., & Boehm, A. B. (2023a) Coastal Environmental DNA Sampling & Gravity Filtration Protocol. [https://doi.org/10.17504/protocols.io.bp2l69y7klqe/v2](https://doi.org/10.17504/protocols.io.bp2l69y7klqe/v2)

Shea, M. M., & Boehm, A. B. (2023b). DNA Extraction Protocol from Sterivex Filters. [https://doi.org/10.17504/protocols.io.ewov1qyyygr2/v1](https://doi.org/10.17504/protocols.io.ewov1qyyygr2/v1)

Shea, M. M., & Boehm, A. B. (2024). Environmental DNA metabarcoding differentiates between micro-habitats within the rocky intertidal. Environmental DNA, 6(2), e521. [https://doi.org/10.1002/edn3.521](https://doi.org/10.1002/edn3.521)

Spens, J., Evans, A. R., Halfmaerten, D., Knudsen, S. W., Sengupta, M. E., Mak, S. S. T., Sigsgaard, E. E., & Hellström, M. (2017). Comparison of capture and storage methods for aqueous macrobial eDNA using an optimized extraction protocol: the advantage of an enclosed filter. Methods in Ecology and Evolution, 8 (5), 635-645. [https://doi.org/10.1111/2041-210X.12683](https://doi.org/10.1111/2041-210X.12683)