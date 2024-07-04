{\rtf1\ansi\ansicpg1252\cocoartf2759
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;\f1\fnil\fcharset0 HelveticaNeue;\f2\fnil\fcharset0 HelveticaNeue-Bold;
}
{\colortbl;\red255\green255\blue255;\red34\green41\blue56;\red255\green255\blue255;}
{\*\expandedcolortbl;;\cssrgb\c17647\c21569\c28235;\cssrgb\c100000\c100000\c100000;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid1\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid1}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}}
\paperw11900\paperh16840\margl1440\margr1440\vieww29200\viewh17260\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 \
\
\pard\pardeftab720\li1820\fi-7\sa320\partightenfactor0

\f1\fs32 \cf2 \cb3 \expnd0\expndtw0\kerning0
1-) Sort the data in the title and description columns in the movie table.\
\pard\pardeftab720\li2245\fi6\sa320\partightenfactor0
\cf2 SELECT title, description FROM movie;\
\
\pard\pardeftab720\li1822\fi6\sa320\partightenfactor0
\cf2 2-) Sort the data in all columns of the movie table by movie length greater than 60 AND less than 75\
\pard\tx2343\pardeftab720\li1822\fi537\sa320\partightenfactor0
\cf2 SELECT * FROM movie WHERE length > 60 AND length <75;\
\
\pard\tx2343\pardeftab720\li1822\fi25\sa320\partightenfactor0
\cf2 3-) Sort the data in all columns in the movie table with the conditions rental_rate 0.99 AND replacement_cost 12.99 OR 28.99.\
      SELECT * FROM movie WHERE rental_rate= 0.99 AND (replacement_cost= 12.99 OR \cf2 replacement_cost= 28.99);\
\
\cf2 4-) What is the value in the last_name column of the customer whose value in the first_name column in the customer table is 'Mary'?\
     SELECT last_name FROM customer WHERE first_name = \'91Mary\'92;\
\
5-) Sort the data in the movie table that does NOT have a length greater than 50 and does NOT have a rental_rate of 2.99 or 4.99.\
     SELECT * FROM movie WHERE length<=50 AND (rental_rate <> 2.99 AND rental_rate <> 4.99);\
\
\
\
\pard\tx2343\pardeftab720\li1822\fi537\sa320\partightenfactor0
\cf2 \
\pard\pardeftab720\sa320\partightenfactor0
\cf2 \
\
\
\
\
\
\pard\pardeftab720\li2251\fi48\sa320\partightenfactor0
\cf2 \cb1 \
\pard\pardeftab720\li2251\fi48\sa160\partightenfactor0
\ls1\ilvl0\cf2 \
\ls1\ilvl0
\f2\b \cb3 \kerning1\expnd0\expndtw0 {\listtext	5	}\expnd0\expndtw0\kerning0
film
\f1\b0  tablosundaki uzunlu\uc0\u287 u(length) 50 ten b\'fcy\'fck OLMAYIP ayn\u305  zamanda rental_rate de\u287 eri 2.99 veya 4.99 OLMAYAN verileri s\u305 ralay\u305 n\u305 z.\cb1 \
\pard\pardeftab720\li2251\fi48\sa320\partightenfactor0
\cf2 \cb3 Kolay Gelsin.}