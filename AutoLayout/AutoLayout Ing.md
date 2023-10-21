{\rtf1\ansi\ansicpg1252\cocoartf2757
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red14\green14\blue14;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c6667\c6667\c6667;\cssrgb\c100000\c100000\c100000\c70196;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid301\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}
{\list\listtemplateid5\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid401\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid5}
{\list\listtemplateid6\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid501\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid6}
{\list\listtemplateid7\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid601\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid7}
{\list\listtemplateid8\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid701\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid8}
{\list\listtemplateid9\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid801\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid9}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}{\listoverride\listid5\listoverridecount0\ls5}{\listoverride\listid6\listoverridecount0\ls6}{\listoverride\listid7\listoverridecount0\ls7}{\listoverride\listid8\listoverridecount0\ls8}{\listoverride\listid9\listoverridecount0\ls9}}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs32 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 AutoLayout\
\
When we create a View in a certain screen size, when emulating on other devices, we will see that our elements will be out of order, and this is because smartphones have different screen sizes. AutoLayout is precisely to avoid this problem. By building a screen in a specific size, we can maintain proportionality in different screen sizes. It works using Constraints, which are \'93rules\'94 that help maintain the proportionality of the elements.\
\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0\cf2 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 In the lower right corner, still in the development area, is where we define the \
Constraints of the element. After selecting the desired element, the first item \
from left to right, updates the element to the original location where it will be \
arranged, and the second item we can define Alignment Constraints, which \
serve to \'91fix\'92 an element vertically or horizontally.\
\ls1\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 The Constraints only appear for the selected Elements, and each form of \
Constraints are the opposite of the position they define.\
\ls2\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 To delete a Constraint, select it with the mouse (wait for it to appear clearer \
and then click) and press BackSpace, which works as the delete button.\
\ls3\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls4\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 The third item from left to right in the lower right area of the development \
environment, it is where we can create our Constraints. When selecting an \
element, we open the environment to create Constraints and, when \
selecting the line of the desired Constraint, it will turn red and then we can add \
the value and add it to the element.\
\ls4\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls5\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 In the development environment, it is not recommended to use the entire \
device screen, we have an upper and lower margin to start developing, this \
margin is called \'91Safe Area\'92, which is where the device displays time, internet \
connection, battery and etc\'85\
\ls5\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls6\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 By clicking on an element and clicking on a Constraint, in the properties area \
on the right, we can change its values.\
\ls6\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls7\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 If we do not use Constraints, the View document will warn that it is missing to \
place Constraints on the specific element, and will present an error.\
\ls7\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls8\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 - \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 Lines - If the Element has a very large text, you can change its property from \
lines to show more text, and a very important point is that if you put the \
number of lines as \'910\'92, the software itself will make arrangements to define how\
 many lines are needed to show all text.\
\ls8\ilvl0\cb1 \
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls9\ilvl0\cf2 \cb3 \kerning1\expnd0\expndtw0 \outl0\strokewidth0 -\expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 To copy an element, we can use both command(cntrl) + C and \
command(cntrl) + V or hold down the optional(Alt) button click on the element\
 and drag.\
\ls9\ilvl0\cb1 \
\pard\pardeftab720\partightenfactor0
\cf2 \cb3 Tips: During simulator use do not close it to return to development minimize and press pause button next to build button on left. Another tip is to use shortcut: Command + R to start emulation.\
\
We can conclude that in order to keep an element in a certain position we can mix both size constraints as well as alignment constraints making it easier to build our view.\
}