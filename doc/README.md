# Documentation resources:
1. Vendor or "outside" documentation goes into contrib:
    1. contrib/datasheet - vendor hardware or soft/firmware datasheets
    2. contrib/cad - vendor CAD files such as PCB component libraries
    3. contrib/publication - vendor documentation such as user guides
3. Docs created by the project go into the other subdirectories:
    1. minutes - main group and breakout group meeting notes
    2. whiteboards - graphics typically supporting minutes (often linked to from minutes or elsewhere)

Don't put vendor code under here: use the top level src/contrib/vendorname subdirectory. Our projects can go in top level dirs such as "programmer", "breakout", etc.