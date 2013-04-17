PLANCK CMB Cube Maps
===========================================================================

This repository contains cube maps of the Cosmic Microwave Background (CMB) fluctations. The original data was taken from the Planck Legacy Archive (http://pla.esac.esa.int/pla/aio/planckProducts.html). The cube maps were generated from the smica dataset (COM_CompMap_CMB-smica_2048_R1.20.fits) using a slightly modified version of CMBView (http://code.google.com/p/cmbview/). Then, a python script was used to converted the raw images to a color scheme which approximately matches that used by the Planck team. The color scale ranges from -300uK to 300uK.

These cubemaps should be very easy to use with OpenGL. 

There are two versions of the map. 
1) The original dataset which includes artifacts due to the mask used in the galactic plane.
2) An inpainted map which fill the masked area with artifical, CMB-like noise. This version is used for most outreach projects. In this repository, it is labled 'inp' for inpainted.

