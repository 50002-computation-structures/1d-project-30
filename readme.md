[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/5YTzVbxp)
## 50.002 1D Project Group (TEAM-NAME)

Brandon Ng Joon Hoe 1007090
Kyaw Zin Htoo 1007064
Lim Wei Ren Marcus 1006855
Teo Xu Kai 1007226
Teo You Xiang 1007220
Phua Jia Jing Elliot 1006967
Yang Si Jun 1006904

### The Project

ALU 13 Functionality Test Case
Add details about your prototype here, perhaps a few photos and how-to-use would be great.

ADD (0x00)
- c{b1, 14xb0, b1} + c{b0, 15xb1} = 16xb0 Z:b1 V:b0 N:b0 
SUB (0x01)
- c{b1, 15xb0} - c{b0, 15xb1} = 16xb1 Z:b0 V:b0 N:b1 
MUL (0x02)
- 4xb1 * c{b1,0} = c{5xb1, 0} 


AND (0x18)
- c{4xb0, 4xb0, 4xb1, 4xb1} AND c{4xb0, 4xb1, 4xb0, 4xb1} = c{4xb0, 4xb0, 4xb0, 4xb1}
OR (0x1E)
- c{4xb0, 4xb0, 4xb1, 4xb1} AND c{4xb0, 4xb1, 4xb0, 4xb1} = c{4xb0, 4xb1, 4xb1, 4xb1}
XOR (0x16)
- c{4xb0, 4xb0, 4xb1, 4xb1} AND c{4xb0, 4xb1, 4xb0, 4xb1} = c{4xb0, 4xb1, 4xb1, 4xb0}
“A” (LDR) (0x1A)
- c{4xb0, 4xb0, 4xb1, 4xb1} AND c{4xb0, 4xb1, 4xb0, 4xb1} = c{4xb0, 4xb0, 4xb1, 4xb1}


SHL (0x20)
- 16xb1 shift 4 {b1, 2xb0} = c{12xb1, 4xb0}
SHR (0x21)
- c{b1, 15xb0} shift 4 {b1, 2xb0} = c{4xb0, b1, 11xb0}
SRA (0x23)
- c{b1, 15xb0} shift 4 {b1, 2xb0} = c{5xb1, 11xb0}


CMPEQ (0x33)
- 16xb1 and 16xb1 = c{15xb0, b1}
CMPLT (0x35)
- b1 and 16xb1 = c{15xb0, b1}
CMPLE (0x37)
- 16xb1 and b1 = c{15xb0, b0}

### Other Details

Any other details
