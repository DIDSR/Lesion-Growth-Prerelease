# Lesion-Growth-Prerelease
##########################################################################################################################################################
#
# ****Disclaimer****
#  This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in
#  the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection
#  and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software
#  without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the
#  Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other
#  parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality,
#  reliability, or any other characteristic. Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory
#  decisions. Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are
#
#	@file    README.txt
#       @author  Aunnasha Sengupta (Aunnasha.Sengupta@fda.hhs.gov)
#       @date    Apr 1,5 2021
#
##########################################################################################################################################################


*************
INTRODUCTION
*************
To replicate a longitudinal study like TMIST, there was a need for an in silico approach for modeling the growth of tumors specifically for breast cancer. To develop a 
biologically relevant growth model, we used an extension to Turing's model that simulates avascular and vascular growth of cancerous tumors using the advection-reaction-diffusion 
equations. Building on this previously reported model, we coupled the growth dynamics with local tissue mechanics with the goal of generating anisotropic and realistic breast 
lesions. The model accounts for the stiffness of surrounding anatomical structures such as ducts, fat, ligaments and glandular tissues, by allowing tumor cells to preferentially
proliferate in the more elastic regions of the breast (fat and ducts), while constraining growth through stiffer structures like ligaments. Depending on the breast local anatomical
structures, a range of unique lesion morphology can be realized. 

