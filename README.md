# Fluorophore-classification-using-photobleaching-steps-and-photoncount

Fluorophore classification based on their spectral properties and behavior is useful for analysing microscopy images expecially when fluorophores with overlapping emission spectra (e.g., GFP & YFP) are used together.

For example, subunit counting using photobleaching of fluorophores is a robust single-molecule imaging method to count the number of subunits of a protein in the native environment. The photostabilities of the blue and red fluorescent proteins are low. Most of the photostable fluorescent proteins lie in the green and yellow spectral range. The emission spectra of the green/yellow fluorescent proteins significantly overlap with each other. Also, we want to accommodate as many fluorophores as possible orthogonally to decipher multimeric protein complexes. If we use two fluorophores with overlapping spectra, we can achieve more space to include multiple fluorophores for bleaching step counting. Therefore, a principle to unmix GFP and YFP emission spectra for subunit counting method has to be established.

## **Principle of dual-view single-molecule imaging using GFP & YFP** ##
![gfpyfpsubunitcounting](https://github.com/antaramukhopadhyay/Fluorophore-classification-using-photobleaching-steps-and-photoncount/assets/160405848/e951a381-1259-4131-abe1-123e64706cdf)

## **Representative example of fluorophore step-ratios and photoncount distribution** ##
![gfpyfpstepratiophotoncount classification](https://github.com/antaramukhopadhyay/Fluorophore-classification-using-photobleaching-steps-and-photoncount/assets/160405848/c1e6c572-2866-413c-a36e-511d2dc0e709)



Here the program contains a classification analysis based on three distinct experiments with the same set of fluorophores (e.g., mEGFP, mGold) based on their two properties i.e. i) photobleaching steps and ii) photoncount
