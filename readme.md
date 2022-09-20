# PAL-1 Sprite Colour Graphics Adapter

The PAL-1 Sprite Colour Graphics Adapter is an expansion board for the PAL-1 system<sup>1</sup>, 
based on the Texas Instruments TMS9918A Video Display Processor (VDP)<sup>2</sup> and was inspired 
by a Ciarcia's Circuit Cellar project<sup>3</sup>. 

The TMS9918A VDP was used in video systems to provide data display on raster scanned colour
television sets or monitors. The IC generates all necessary video, control, and synchronisation
signals and also controls the storage and retrieval of display data in its own dedicated screen 
memory. 

> **Note**  
> The TMS9918A VDP generates a 525-line NTSC encoded colour video signal. While the TMS9928A
> VDP, which is intended for use with PAL video systems, is functionally compatible with the
> TMS9918A, it is not pin-for-pin compatible. Thus it is **not possible** to use the TMS9928A 
> VDP in the PAL-1 Sprite Colour Graphics Adapter. Instead, users who do not have access to an 
> NTSC TV or monitor are recommended to use AV to HDMI or AV to VGA converters as appropriate.
> Such converters are widely available from the usual e-commerce and auction web sites. 

## Acknowledgements
The SRAM circuitry is based on work by Tom LeMense and Dan Werner<sup>4,5</sup>.  
PAL-1 and the PAL-1 logo used with kind permission of Liu Ganning.

## References
1. Liu Ganning, ‘PAL-1 Microcomputer User Manual’, 2020 <http://pal.aibs.ws/assets/PAL_en.pdf> [accessed 21 July 2022].
2. ‘9900 TMS9918A/TMS9928A/TMS9929A Video Display Processors’ (Texas Instruments Incorporated, 1982) <https://web.archive.org/web/20180717212934/https://emu-docs.org/VDP%20TMS9918/Datasheets/TMS9918.pdf> [accessed 17 September 2022].
3. Steve Ciarcia, ‘High-Resolution Sprite-Oriented Color Graphics’, Byte, 7.8 (1982), 57–80.
4. Tom LeMense, ‘SRAM Replacement for TMS99x8 VRAM’, 2010 <https://retrobrewcomputers.org/n8vem-pbwiki-archive/0/35845334/48860720/33053543/SRAM%20Replacement%20for%20TMS99x8%20VRAM.pdf> [accessed 17 September 2022].
5. Tom LeMense and Dan Werner, ‘Video Display Interface Board’, RetroBrew Computers Wiki, 2021 <https://www.retrobrewcomputers.org/doku.php?id=boards:ecb:scg:start> [accessed 17 September 2022].
