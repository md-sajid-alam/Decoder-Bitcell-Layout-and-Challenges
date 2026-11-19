# Decoder-Bitcell-Layout-and-Challenges

Design of 7nm Decoder and Bit cell Layout block

## Layout Screenshot of Decoder + Bitcell
<img width="897" height="662" alt="image" src="https://github.com/user-attachments/assets/ca9fce97-6643-4ae2-a5f6-f1b34aee7f3d" />



## Schematic of Decoder + Bitcell 
<img width="2171" height="724" alt="Symmetric Butterfly Decoder with Bitcells" src="https://github.com/user-attachments/assets/42027072-81a8-4645-a6c4-a10e9b18f6b5" />

Layout challenges kept in mind while making Decoder + Bitcell block

    ► Width of decoder should be in 2 Bitcell pitch 
    ► A chunk of 4 decoder can follow butterfly architecture such that connection should be like 4 bitcell on top and 4 bitcell on bottom of decoder
    ► To accomodate configuration of 256x16x4, capacity of Bitcell array: 32x32 on both top and bottom of decoder because of butterfly architecture
    ► Decoder orientation is R0+MX+MY and similarly Bitcell orientation would be R0+MY+R0+MY
