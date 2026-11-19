# Decoder-Bitcell-Layout-and-Challenges

Design of 7nm Decoder and Bit cell Layout block

## Layout Screenshot of Decoder + Bitcell
<img width="1861" height="1042" alt="image" src="https://github.com/user-attachments/assets/4e724201-797c-46e6-805f-92e4632b3e60" />


## Schematic of Decoder + Bitcell 
<img width="2171" height="724" alt="Symmetric Butterfly Decoder with Bitcells" src="https://github.com/user-attachments/assets/42027072-81a8-4645-a6c4-a10e9b18f6b5" />

Layout challenges kept in mind while making Decoder + Bitcell block

    ► Width of decoder should be in 2 Bitcell pitch 
    ► A chunk of 4 decoder can follow butterfly architecture such that connection should be like 4 bitcell on top and 4 bitcell on bottom of decoder
    ► To accomodate configuration of 256x16x4, capacity of Bitcell array: 32x32 on both top and bottom of decoder because of butterfly architecture
    ► Decoder orientation is R0+MX+MY and similarly Bitcell orientation would be R0+MY+R0+MY
