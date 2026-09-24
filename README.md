# Ninja-One-Inventor-Pro-2025-uninstall
Can be put into the Ninja One automation library to then be used to uninstall Inventor Pro 2025 with safety checks to not uninstall any other present Autodesk installations, or shared components. 

In the NinjaOne automation library, add automation, set category to "software", language to "Powershell", operating system to "Windows", architecture to "x64 (64-bit)", run as "system".

Script will follow checks in order to ONLY uninstall Inventor Pro 2025, stops if any other Autodesk applications is detected as target uninstall, also checks over any possible hared components between products in order to not uninstall those. 


