# oscal-tools
Work with the NIST 800-53 OSCAL Documents

This needs to have functions to read in the NIST 800-53 rev5 templates from here (https://github.com/usnistgov/oscal-content)
I'm going to start with the JSON format only since I know prefer JSON.

Then it needs to walk the user through providing the exter information that the Organization must specify. I think these values should both be saved in a version of the complete control set as well as a seperate document (I want a seperate document so I can apply them to updated versions of the 800-53 and so that I can apply the to the different levels (Low, Moderate and High).

Next it needs to take a complete control set and allow you to go through and fill out implementation details. It might only be selected implementation details. As a sub-component SSP might only implement a small subset of the controls. Heck it might not even completely implement them. The you need to be able to save the sub-component SSP document (this might just be a file included with a library)

Finally for this project you need to be able to merge a list of sub-component SSP documents into a single SSP document.
